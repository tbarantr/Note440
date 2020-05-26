# CAP theorem
* It is impossible for a distributed data store to simultaneously provide more than two out of the three guarantees
  - Consistency: Every read receives the most recent write or an error
  - Availability: Every request receives a (non-error) response, without the guarantee that it contains the most recent write
  - Partition tolerance: The system continues to operate despite an arbitrary number of messages being dropped (or delayed) by the network between nodes
* Network partition is inevitable, so we are essentially choosing between
  - cancelling the operation
  - proceeding and risking inconsistency
