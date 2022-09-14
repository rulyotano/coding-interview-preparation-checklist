# Coding interview preparation checklist
Preparing for a coding interview is difficult, but preparing for a coding interviw in one of the top companies like Google, Microsoft, Amazon, Meta, Booking, Linking, ... can be even harder.

Some frirend gave me some tips based on his experience entering one of this. After preparing for like 6 months this is what he suggested:
- Train by using [leetcode.com](https://leetcode.com/) (can be another like [hackerrank.com](https://www.hackerrank.com/)), you should be able to solve 1 medium problem in 20 minutes (usually you need to solve 2 in ~40 minutes)
- Learn System Design hard, and gave me some references
- - Read books System Design Interview by Alex Xu and System Design Interview Part 2 by Alex Xu and Shan Lam
- - I would add a book that it make take more time, and it is Designing Data Intensive Applications by Martin Kleppmann, I'm reading it and it is great and it is related to this topic
- - Pass the following course [Grokking Modern System Design Interview for Engineers & Managers](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers)
- And by last, he gave me the following the check list of topics that when you know all of them or almost most of them, you will be confident in your interviews. The list is taken [from here](https://global-uploads.webflow.com/5d0cef7a72ca1b074065dfda/6221f7158d6664975f41f43a_IK_Tech_Int_Checklist_3Mar22.pdf).

I wanted to take this check list into a github repo, because I can customize it. I can create a branch per company, or what ever I want. I can create directories with `README.md` files (to describe problems and algorithms) and containing problem solutions covering each topics. We can add links from here (each list point) to those repositories directories. We can customize and track the progress however we want.

I also think, that even if we finally don't make an application to one of this company, knowing all of this is great for a Software Engeenier.

## Must-Learn Topics for Coding Interviews

- [ ] **Basic math**
> Relevant parts of discrete math pertaining to combinatorics
- - [ ] Algebra (linear and quadratic equations, arithmetic, and geometric series)
- - [ ] Combinatorics
- - [ ] Recursive mathematical functions
- - [ ] Proofs by mathematical induction 
- - [ ] Decrease and conquer
- - [ ] Asymptotic analysis

- [ ] **Basic data structures**
> For storing collections of "n" like items
- - [ ] Arrays
- - [ ] Linked lists
- - [ ] Stacks
- - [ ] Queues and deques
- - [ ] Linear search
- - [ ] Binary search
- - [ ] Binary search trees
- - [ ] Hash tables

- [ ] **Bit manipulation**
- - [ ] Conversion from base 10 to base 2 and vice versa
- - [ ] Finite (32 bit) representation of an infinite number line
- - [ ] Representing negative numbers (using 2s complement, Boolean operators)
- - [ ] Multiplication and division
- - [ ] Other data types (floating point, character encodings)

- [ ] **Binary search variants**
- - [ ] Regular binary search
- - [ ] Bisection
- - [ ] Binary search for optimization

- [ ] **Sorting algorithms**
- - [ ] Quicksort
- - [ ] Merge sort
- - [ ] Heap sort
- - [ ] Bubble sort
- - [ ] Selection sort
- - [ ] Insertion sort
- - [ ] Counting sort
- - [ ] Radix sort
- - [ ] Bucket sort
- - [ ] Cycle sort

- [ ] **Extensions of merge sort**
> Two-pointer pass in two array

- [ ] **Extensions of quicksort**
- - [ ] Quicksort pattern
- - [ ] Tree-way partitioning pattern

- [ ] **Tow-sum pattern**
> Presorting vs. hash tables

- [ ] **Selection in a stram using heaps**

- [ ] **Interval line sweep**

- [ ] **Linked lists**
- - [ ] Floyd Cycle detection
- - [ ] Sorting and partitioning
- - [ ] List reversal

- [ ] **Generic decrease and conquer for array problems**

- [ ] **Prefix sum**

- [ ] **Sliding windows**
- - [ ] Fixed-length windows
- - [ ] Variable-length windows

- [ ] **Combinatorial enumeration**

- [ ] **Backtracking**

- [ ] **Tree travesal patterns**
- - [ ] BFS
- - [ ] DFS
- - [ ] Top-down
- - [ ] Bottom-up
- - [ ] Boundary walk
- - [ ] Iterative

- [ ] **Tree construction patterns**

- [ ] **Graph foundation**
- - [ ] BFS/DFS on undericted graphs
- - [ ] BFS/DFS on directed graphs
- - [ ] BFS/DFS on 2D grids

- [ ] **Dynamic programming (DP)**
- - [ ] DP on sequences
- - [ ] DP on sub-trees
- - [ ] DP on permutations
- - [ ] DP on subsets
- - [ ] DP on two-strings

- [ ] **Greedy algorithms foundations with interval problems**

- [ ] **Advanced graphs**
- - [ ] Bridges and articulation points
- - [ ] Strongly connected components (Tarjan, Kosaraju)
- - [ ] Union-find foundations and coding pattern
- - [ ] Eulerian path construction
- - [ ] Combinatorial optimization on graphs
- - [ ] Shortest-path problem
- - [ ] Minimum spanning trees
- - [ ] All-pairs shortest paths
- - [ ] State-space tree 
- - [ ] Graph search

- [ ] **Advanced trees**
- - [ ] AVL
- - [ ] Red-black
- - [ ] Segment
- - [ ] Binary-indexed
- - [ ] B-trees
- - [ ] Quad trees

- [ ] **Pattern matching**
- - [ ] KMP
- - [ ] Rabin Karp
- - [ ] Tries

- [ ] **Ad-hoc problems**
> Such as design skip lists

## Must-Learn Topics for Systems Design Interviews

- [ ] **Basics of system design**
- - [ ] Online Processing
- - [ ] Batch Processing
- - [ ] Stream Processing

- [ ] **Basic of networking**
- - [ ] Network protocols
- - [ ] Webserver
- - [ ] Cryptographic hash functions

- [ ] **Scaling distributed applications**
- - [ ] Reasons of scaling (data size, throughput, fault tolerance, geolocation and hotspots)
- - [ ] Horizontal scaling
- - [ ] Vertical scaling
- - [ ] Load balancing
- - [ ] Server proxy (reverse and forward)
- - [ ] CAP theorem
- - [ ] Content distribution networks

- [ ] **Sharding techniques**
- - [ ] Partitioning vs. replication
- - [ ] Partitioning of key value data
- - [ ] Partitioning and secondary indexes
- - [ ] Rebalancing partitions

- [ ] **Measuring the performance of scalable system**
- - [ ] Performance metrics of a scalable system
- - - [ ] Correctness
- - - [ ] Availability
- - - [ ] Throughput
- - - [ ] Response time
- - [ ] Service-level agreements

- [ ] **Cache**
- - [ ] Reads and writes
- - [ ] LRU cache
- - [ ] Strategies
- - [ ] Consistent hashing

- [ ] **Storage and retrieval**
- - [ ] Key-value stores
- - [ ] Relational database and tree index
- - [ ] SQL, normalization, and keys
- - [ ] ACID transactions
- - [ ] Big data
- - [ ] NoSQL

- [ ] **MapReduce and distributed file systems**
- - [ ] MapReduce Framework
- - [ ] Distributed file system

- [ ] **Searching in a corpus of documents**
- - [ ] Inverted index
- - [ ] External sort merge
- - [ ] K-way external sort-merge
- - [ ] Distributed sorting

- [ ] **Systems design case studies**
- - [ ] URL shortener
- - [ ] Streaming services
- - [ ] Chat messenger server
- - [ ] Recommendation system
- - [ ] Maps
- - [ ] Search Engine
- - [ ] Unique ID generator

- [ ] **Object modeling** (not required for all companies)
- - [ ] Basics of UML
- - [ ] Design patterns (I will let [this reference](https://refactoring.guru/design-patterns) here, it is the Refactoring Guru site, it explain easy a lot of design patterns
- - - [ ] Composite pattern
- - - [ ] Decorator pattern
- - - [ ] Facade pattern
- - - [ ] Visitor pattern
- - - [ ] Flyweight pattern
- - - [ ] Proxy pattern
- - - [ ] Command pattern
- - - [ ] Observer pattern
- - - [ ] Strategy pattern
- - - [ ] State pattern
- - - [ ] Factory pattern
- - - [ ] Singleton pattern

- [ ] Basics of API design
- - [ ] RESTful API design
- - [ ] SOLID principles

- [ ] Concurrency (Not required for all companies)
- - [ ] Parallelism vs. concurrency
- - [ ] Blocked vs. running
- - [ ] Mutex
- - [ ] Cross-process mutex
- - [ ] Condition variable
- - [ ] Semaphore
- - [ ] Atomic operations
- - [ ] Deadlock

