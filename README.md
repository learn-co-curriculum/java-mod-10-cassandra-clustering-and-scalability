# Cassandra Clustering and Scalability

## Learning Goals

- Understanding the Cassandra scaling model
- Understanding Cassandra data partitioning
- Adapting applications from Relational systems

## Introduction

Cassandra was designed from the ground up to be a distributed, and highly scalable NoSQL Database system. How we've been using it so far
is helpful to get quick test implementations, but you will not see something as simple in any serious production environments.
When it comes to multi-node Cassandra environments, things can be both more and less complicated when compared to equivalent Relational
clusters.

There is a great overview of the Cassandra scaling model you can read through.

- [Cassandra Cluster Basics](https://cassandra.apache.org/_/cassandra-basics.html)


While Cassandra queries look fairly similar to those from Relational Database systems, there are some important caveats. Read up on the differences between
data models in use.

- [Cassandra Data Model](https://cassandra.apache.org/doc/latest/cassandra/data_modeling/intro.html)
- [Differences To RDBMS](https://cassandra.apache.org/doc/latest/cassandra/data_modeling/data_modeling_rdbms.html)
