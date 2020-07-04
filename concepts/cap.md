---
layout: default
title: CAP theorem
parent: Concepts
nav_order: 1
---
# CAP theorem
* It is impossible for a distributed system to simultaneously provide more than two out of the three guarantees
  - Consistency: Every read receives the most recent write or an error; all nodes see the same data at teh same time
  - Availability: Every request receives a (non-error) response; every request received by a non-failing node in the system must result in a response
  - Partition tolerance: The system continues to operate despite an arbitrary number of messages being dropped (or delayed) between nodes

* Examples
  - CA (consistency + availability). Examples include full strict quorum protocols, such as two-phase commit.
  - CP (consistency + partition tolerance). Examples include majority quorum protocols in which minority partitions are unavailable such as Paxos.
  - AP (availability + partition tolerance). Examples include protocols using conflict resolution, such as Dynamo, which uses a weaker consistency model


* In the real world network partition is inevitable, so during a partition we are essentially choosing between
  - cancelling the operation
  - proceeding and risking inconsistency
