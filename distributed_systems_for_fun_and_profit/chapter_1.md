# Chapter 1: Basics
* Two tasks
  - storage
  - computation
* The need
  - the problem no longer fits on a single computer

* Scalability: is the ability of a system, network, or process, to handle a growing amount of work in a capable manner or its ability to be enlarged to accommodate that growth, mainly
  - Size scalability: adding more nodes should make the system linearly faster; growing the dataset should not increase latency.
  - Geographic scalability: it should be possible to use multiple data centers; cross data center latency is sensible
  - Administrative scalability: adding more nodes should not increase the administrative costs of the system
* Performance: is characterized by the amount of useful work accomplished by a computer system compared to the time and resources used.
  - low latency
  - high throughput
  - low utilization of resources
* Availability (and fault tolerance): the proportion of time a system is in a functioning condition. If a user cannot access the system, it is said to be unavailable.

* Abstractions and models
  - trade of between abstraction (distributed systems presented as a single system) and reality (where performance is needed)
  - programmer needs (clean semantics) vs business needs (availability/consistency/performance)

* Two basic design technique:
  - partitioning
    - improves performance by reducing data size per node and improving locality
    - improves availability by allowing independent failure
  - replication
    - improved performance by increasing bandwidth (working on the exatra copy), and caching
    - improved availability by increasing the #nodes that need to fail before availability is sacrificed
    - consistency model needed
      - only strong consistency allows treating the data as not replicated
      - weaker consistency expose replication internals but provide better latency/availability
