---
layout: default
title: Home
nav_order: 0
---
## Guides
* [Distributed systems theory for the distributed systems engineer](https://www.the-paper-trail.org/post/2014-08-09-distributed-systems-theory-for-the-distributed-systems-engineer/)
* [How to Read Paper](https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf)
* [awesome-distributed-systems](https://github.com/theanalyst/awesome-distributed-systems)
( [read twice](https://michaelfeathers.silvrback.com/10-papers-every-developer-should-read-at-least-twice) (theoretical)
* [read twice](http://blog.fogus.me/2011/09/08/10-technical-papers-every-programmer-should-read-at-least-twice/) (practical)
* [a ds reading list](https://dancres.github.io/Pages/)
* [papers we love](https://github.com/papers-we-love/papers-we-love)

## Books
* [Distributed systems for fun and profit](http://book.mixu.net/distsys/intro.html)

## Papers & Articles
* [END-TO-END ARGUMENTS IN SYSTEM DESIGN](https://web.mit.edu/Saltzer/www/publications/endtoend/endtoend.pdf)
* [Notes on Distributed Systems for Young Bloods](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/)
* [Perspectives on the CAP Theorem](https://dspace.mit.edu/bitstream/handle/1721.1/79112/Brewer2.pdf)
* [CAP Twelve Years Later: How the "Rules" Have Changed](https://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed/)
* [Uniform consensus is harder than consensus](https://www.researchgate.net/profile/Andre_Schiper/publication/2362295_Uniform_Consensus_is_Harder_than_Consensus_Extended_Abstract/links/5481968e0cf20f081e728ba1.pdf)
* [Replicated Data Consistency Explained Through Baseball](http://pages.cs.wisc.edu/~remzi/Classes/739/Papers/Bart/ConsistencyAndBaseballReport.pdf)
* [Life beyond Distributed Transactions: an Apostate’s Opinion](https://www-db.cs.wisc.edu/cidr/cidr2007/papers/cidr07p15.pdf)
* [If you have too much data, then 'good enough' is good enough](https://dl.acm.org/doi/pdf/10.1145/1953122.1953140)
* [Building on Quicksand](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.195.6558&rep=rep1&type=pdf)


### Lamport clocks, vector clocks
* [time, clocks and the ordering of events](http://lamport.azurewebsites.net/pubs/time-clocks.pdf)

### Failure detection
* Unreliable failure detectors and reliable distributed systems - Chandra and Toueg
* Latency- and Bandwidth-Minimizing Optimal Failure Detectors - So & Sirer, 2007
* The failure detector abstraction, Freiling, Guerraoui & Kuznetsov, 2011

### Snapshots
* Consistent global states of distributed systems: Fundamental concepts and mechanisms, Ozalp Babaogly and Keith Marzullo, 1993
* Distributed snapshots: Determining global states of distributed systems, K. Mani Chandy and Leslie Lamport, 1985

### Causality
* Detecting Causal Relationships in Distributed Computations: In Search of the Holy Grail - Schwarz & Mattern, 1994
* Understanding the Limitations of Causally and Totally Ordered Communication - Cheriton & Skeen, 1993

### Primary-backup and 2PC
* Replication techniques for availability - Robbert van Renesse & Rachid Guerraoui, 2010
* Concurrency Control and Recovery in Database Systems

### Paxos
* The Part-Time Parliament - Leslie Lamport
* Paxos Made Simple - Leslie Lamport, 2001
* Paxos Made Live - An Engineering Perspective - Chandra et al
* Paxos Made Practical - Mazieres, 2007
* Revisiting the Paxos Algorithm - Lynch et al
* How to build a highly available system with consensus - Butler Lampson
* Reconfiguring a State Machine - Lamport et al - changing cluster membership
* Implementing Fault-Tolerant Services Using the State Machine Approach: a Tutorial - Fred Schneider

### Raft and ZAB
* In Search of an Understandable Consensus Algorithm, Diego Ongaro, John Ousterhout, 2013
* Raft Lecture - User Study
* A simple totally ordered broadcast protocol - Junqueira, Reed, 2008
* ZooKeeper Atomic Broadcast - Reed, 2011
