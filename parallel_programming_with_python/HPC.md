## Why use parallel programming?
1. Run independent pieces of a specific program in parallel with one another, thus enhancing the response and the general performance.
2. Computer are equipped with more processors and these with plenty of more cores.


### Concurrent programming

a program dispatches several workers and these workers dispute to use the CPU to run a task, the stage at which the dispute takes place is controlled by the CPU scheduler.
### parallel programming
a program data creates workers to run specific tasks simultaneously in a **multicore environment** without need for concurrency among them to acess CPU

### distributed programming
the possibility of sharing the processing by exchanging data through messages between machines (nodes) of computing, which are physically separated.
* Fault-tolerance
* Horizontal scalability
* Cloud computing


### Communicating in parallel programming
* Share state
* message passing

### Parallel programming problems
* Deadlock: two or more workers keep indefinitely waiting for the freeing of a resource.
* Starvation: badly adjusted policies of process ranking
* Race conditions: 

### Design parallel algorithms
* Divide and conquer technique
* Using data decomposition
* Decomposing tasks with pipeline
* Processing and mapping
