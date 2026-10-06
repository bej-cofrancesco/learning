# Learning

Repo with all my learnings and materials + my work (potential different repos depending on scopes)

# 1. ALGORITHMIC THINKING

## Books

- _Grokking Algorithms, 2nd Edition_
- _The Algorithm Design Manual, 3rd Edition_

## Learn

- Big O
- Big Theta
- Big Omega
- Arrays
- Strings
- Hash tables
- Stacks
- Queues
- Linked lists
- Trees
- Binary search
- Sorting
- Recursion
- Divide and conquer
- Heaps
- Graphs
- Breadth-first search
- Depth-first search
- Greedy algorithms
- Dynamic programming
- Backtracking
- Memoisation
- Correctness
- Complexity analysis

## Practice

- LeetCode
- Codeforces
- Timed problem solving
- Reimplement algorithms from memory

## Completion standard

- Solve unfamiliar problems without AI
- Explain why the algorithm works
- Explain complexity
- Identify alternative solutions
- Identify edge cases

---

# 2. COMPUTER SYSTEMS

## Book

- _Computer Systems: A Programmer’s Perspective, 3rd Edition_

## Binary and data representation

- Bits
- Bytes
- Binary
- Hexadecimal
- Decimal conversion
- Bitwise AND
- Bitwise OR
- XOR
- NOT
- Bit shifts
- Bit masks
- Flags
- Unsigned integers
- Signed integers
- Two’s complement
- Integer overflow
- Floating point
- IEEE 754
- NaN
- Infinity
- Precision
- Character encoding
- ASCII
- Unicode
- Endianness

## Memory

- Memory addresses
- Pointers
- Stack
- Heap
- Static memory
- Dynamic allocation
- Alignment
- Padding
- Object representation
- Memory layout
- Virtual memory
- Pages
- Page faults
- Page tables
- TLBs
- Memory-mapped files

## CPU

- Registers
- Instructions
- Instruction execution
- Arithmetic
- Branches
- Function calls
- Stack frames
- Calling conventions
- Assembly
- Machine code
- CPU cycles

## Compilation

- Source code
- Preprocessing
- Compilation
- Assembly
- Object files
- Linking
- Static libraries
- Dynamic libraries
- Loading
- Runtime

## Performance

- Latency
- Throughput
- Cache locality
- Memory bandwidth
- Branch behaviour
- Cache misses
- CPU versus memory bottlenecks

---

# 3. C AND LOW LEVEL PROGRAMMING

## Book

- _The C Programming Language, 2nd Edition_

## Learn

- Variables
- Types
- Arrays
- Strings
- Pointers
- Pointer arithmetic
- Function pointers
- Structs
- Unions
- Enums
- Manual memory management
- `malloc`
- `calloc`
- `realloc`
- `free`
- Headers
- Preprocessor
- Compilation units
- Linking
- Undefined behaviour
- Lifetime
- Aliasing
- Data representation

## Build

- Dynamic array
- Linked list
- Hash table
- String library
- Memory allocator
- Command-line utility
- Unix-style utility
- Small network program

## Completion standard

- Explain exactly what happens in memory
- Debug pointer bugs without AI
- Find memory leaks
- Explain undefined behaviour
- Read C code confidently

---

# 4. C++ FOUNDATIONS

## Books

- _A Tour of C++, 3rd Edition_
- _Programming: Principles and Practice Using C++, 3rd Edition_

## Language

- Types
- References
- Pointers
- Classes
- Structs
- Constructors
- Destructors
- Inheritance
- Polymorphism
- Virtual functions
- Operator overloading
- Namespaces
- Templates
- STL
- Containers
- Iterators
- Algorithms
- Exceptions
- Lambdas
- Ranges

## Core mental models

- Value semantics
- Reference semantics
- Object lifetime
- Ownership
- Resource management
- RAII
- Copy semantics
- Move semantics
- Rule of zero
- Rule of five
- Undefined behaviour
- ABI basics

## Build

- Vector
- String
- Smart pointer
- Hash map
- Tree
- Logger
- Configuration system
- CLI application

---

# 5. MODERN C++

## Books

- _Effective Modern C++_
- _C++ Templates: The Complete Guide, 3rd Edition_
- _C++ Core Guidelines_

## Learn

- `auto`
- `decltype`
- Type deduction
- `const`
- `constexpr`
- `consteval`
- Rvalue references
- Move semantics
- Perfect forwarding
- Universal references
- Lambdas
- `std::function`
- `unique_ptr`
- `shared_ptr`
- `weak_ptr`
- Custom deleters
- Smart pointer ownership
- Reference cycles
- Exception safety
- Generic programming
- Type traits
- Concepts
- Constraints
- Fold expressions
- Template specialisation
- Variadic templates
- Compile-time programming
- Ranges

## Deep theory

- Value categories
- Object lifetime
- Ownership
- Aliasing
- Copy elision
- ABI
- Undefined behaviour
- Strict aliasing
- Memory layout
- Resource lifetime

---

# 6. OPERATING SYSTEMS

## Book

- _Operating Systems: Three Easy Pieces_

## Processes

- Processes
- Threads
- System calls
- Context switching
- Scheduling
- Process states
- Signals
- Inter-process communication

## Memory

- Address spaces
- Virtual memory
- Paging
- Page tables
- TLBs
- Memory allocation
- Page faults
- Copy-on-write
- Memory protection

## Concurrency

- Threads
- Race conditions
- Critical sections
- Mutexes
- Semaphores
- Condition variables
- Deadlocks
- Starvation
- Scheduling

## Storage

- File systems
- Files
- Directories
- Inodes
- Persistence
- Journaling
- Storage devices
- I/O

---

# 7. COMPUTER ARCHITECTURE

## Book

- _Computer Organization and Design: The Hardware/Software Interface, RISC-V Edition_

## Learn

- ISA
- Machine instructions
- Registers
- Arithmetic and logic
- Control flow
- Function calls
- Stack frames
- Instruction encoding
- Pipelining
- Pipeline hazards
- Branch prediction
- Instruction-level parallelism
- SIMD
- Vectorisation

## Memory hierarchy

- Registers
- L1 cache
- L2 cache
- L3 cache
- Cache lines
- Cache associativity
- Cache misses
- DRAM
- Memory bandwidth
- Locality
- False sharing

## Performance

- CPU cycles
- Instructions per cycle
- Branch misprediction
- Cache misses
- Memory stalls
- SIMD
- Instruction throughput
- Memory latency

---

# 8. C++ CONCURRENCY

## Book

- _C++ Concurrency in Action, 2nd Edition_

## Learn

- Threads
- Mutexes
- Locks
- Condition variables
- Futures
- Promises
- Atomics
- Memory ordering
- Sequential consistency
- Acquire
- Release
- Relaxed ordering
- Data races
- Deadlocks
- Lock-free programming
- Wait-free concepts
- Concurrent data structures
- Thread pools

## Build

- Thread pool
- Concurrent queue
- Producer-consumer system
- Parallel map/reduce
- Work-stealing queue
- Concurrent cache

---

# 9. ADVANCED ALGORITHMS

## Book

- _Introduction to Algorithms, 4th Edition_

## Learn

- Formal complexity
- Recurrences
- Advanced sorting
- Hashing
- Binary search trees
- Red-black trees
- Heaps
- Disjoint sets
- Graph algorithms
- Minimum spanning trees
- Shortest paths
- Network flow
- Dynamic programming
- Greedy algorithms
- Amortised analysis
- Advanced data structures
- Correctness proofs

## Goal

Move from:

> “I know this algorithm.”

to:

> “I can derive an appropriate algorithm for this problem.”

---

# 10. PERFORMANCE ENGINEERING

## Learn

- Compiler optimisation
- Inlining
- Allocation costs
- Object layout
- Cache-aware programming
- Data-oriented design
- Branch prediction
- SIMD
- Vectorisation
- Memory layout
- False sharing
- Lock contention
- Latency
- Throughput
- Profiling
- Benchmarking
- Flame graphs
- Assembly inspection

## Tools

- Linux
- CMake
- Ninja
- GDB
- LLDB
- AddressSanitizer
- UndefinedBehaviorSanitizer
- ThreadSanitizer
- Valgrind
- `perf`
- Compiler Explorer
- Git
- Docker
- CI/CD

## Completion standard

- Profile before optimising
- Identify the actual bottleneck
- Explain why it is slow
- Optimise it
- Benchmark the result
- Explain the generated assembly where relevant

---

# 11. RUST

## Books

- _The Rust Programming Language_
- _Rust for Rustaceans_
- _Rust for C++ Developers_

## Fundamentals

- Ownership
- Borrowing
- References
- Lifetimes
- Structs
- Enums
- Pattern matching
- Traits
- Generics
- Iterators
- Closures
- Error handling
- Modules
- Crates
- Macros

## Memory and safety

- Ownership models
- Borrow checker
- Smart pointers
- Interior mutability
- `Box`
- `Rc`
- `Arc`
- `Mutex`
- `RefCell`
- Unsafe Rust
- FFI

## Advanced Rust

- Concurrency
- Async
- Futures
- Pinning
- `Send`
- `Sync`
- Zero-cost abstractions
- API design
- Performance
- C interoperability
- C++ interoperability

## Build

- CLI
- HTTP server
- Async service
- Concurrent system
- Rust/C++ FFI project
- High-performance data processing system

---

# 12. MATHEMATICS

## Books

- _Mathematics for Machine Learning_
- _A First Course in Probability_
- _Statistical Inference_
- _Numerical Recipes_

## Linear algebra

- Vectors
- Matrices
- Matrix multiplication
- Linear transformations
- Eigenvalues
- Eigenvectors
- Orthogonality
- Decompositions

## Calculus

- Functions
- Limits
- Derivatives
- Integrals
- Partial derivatives
- Gradients
- Optimisation
- Multivariable calculus

## Probability

- Sample spaces
- Conditional probability
- Bayes’ theorem
- Random variables
- Distributions
- Expectation
- Variance
- Covariance
- Conditional expectation
- Law of large numbers
- Central limit theorem

## Statistics

- Estimation
- Maximum likelihood
- Confidence intervals
- Hypothesis testing
- Regression
- Correlation
- Statistical significance

## Numerical methods

- Numerical stability
- Root finding
- Optimisation
- Numerical integration
- Monte Carlo
- Floating-point error

---

# 13. QUANTITATIVE FINANCE

## Books

- _Options, Futures, and Other Derivatives_
- _Paul Wilmott Introduces Quantitative Finance_

## Learn

- Financial markets
- Equities
- Bonds
- Derivatives
- Forwards
- Futures
- Options
- Payoffs
- Arbitrage
- No-arbitrage pricing
- Volatility
- Implied volatility
- Black-Scholes
- Greeks
- Binomial models
- Monte Carlo pricing
- Interest rates
- Stochastic processes
- Risk
- Portfolio theory

## Implement

- Black-Scholes calculator
- Greeks calculator
- Binomial option pricer
- Monte Carlo option pricer
- Implied volatility solver
- Yield curve calculations
- Portfolio risk calculator

---

# 14. QUANT DEVELOPMENT

## Engineering

- High-performance C++
- Rust
- Python for research
- Numerical computing
- Parallel computing
- Multithreading
- Networking
- Serialization
- Memory pools
- Lock-free structures
- Market data
- Market data ingestion
- Market data replay
- Time synchronisation
- Logging
- Monitoring
- Latency measurement

## Systems

- TCP
- UDP
- Binary protocols
- Network buffers
- Zero-copy techniques
- Ring buffers
- Object pools
- Memory allocators
- CPU affinity
- NUMA
- Cache-aware design

## Projects

1. Limit order book
2. Matching engine
3. Market data parser
4. Market data replay engine
5. Backtesting engine
6. Black-Scholes engine
7. Implied volatility solver
8. Monte Carlo pricing engine
9. Portfolio risk engine
10. Statistical arbitrage research system
11. End-to-end trading simulator

---

# 15. SENIOR ENGINEERING

## Architecture

- API design
- Modularity
- Abstraction
- Coupling
- Cohesion
- Dependency management
- Error handling
- Testing
- Observability
- Documentation
- Security
- Networking
- Databases
- Distributed systems

## Engineering judgement

- Choose the simplest design that meets requirements
- Understand trade-offs
- Understand operational failure modes
- Understand abstraction costs
- Measure before optimising
- Know when not to optimise
- Design for observability
- Read unfamiliar code
- Read source code
- Read technical documentation
- Debug independently
- Communicate technical decisions

---

# 16. CAPSTONE PROJECT LADDER

## Level 1

- Algorithms library
- Dynamic array
- Linked list
- Hash table
- Binary tree
- Heap

## Level 2

- Memory allocator
- String library
- CLI utility
- Mini shell
- File system utility

## Level 3

- HTTP server
- Multithreaded server
- Thread pool
- Concurrent queue
- Concurrent cache

## Level 4

- Cache-aware data structure
- SIMD implementation
- Custom allocator
- Lock-free queue
- Parallel processing system

## Level 5

- Interpreter
- Compiler
- Virtual machine
- Rust systems application
- C++/Rust FFI system

## Level 6

- Limit order book
- Matching engine
- Market data parser
- Market data replay engine
- Backtesting engine

## Level 7

- Monte Carlo pricing engine
- Implied volatility engine
- Portfolio risk engine
- Statistical arbitrage system
- End-to-end quant trading simulator

---

# 17. WEEKLY STRUCTURE

## Every week

- 3 textbook sessions
- 2 implementation sessions
- 2 algorithm sessions
- 1 project session
- 1 review session

## Every day

- 15 to 30 minutes active recall
- One small problem
- Review previous mistakes

## Every week

- Re-solve failed problems
- Write summary from memory
- Update error log
- Review previous concepts

## Every month

- Complete one project milestone
- Complete a no-AI problem set
- Revisit weak areas
- Benchmark one implementation
- Explain one difficult concept from memory

---

# 18. HOW TO STUDY EACH BOOK

## Before reading

- Identify the chapter objectives
- Write what you already know
- Write questions you expect the chapter to answer

## While reading

- Do not passively highlight
- Work through examples
- Predict outcomes before reading explanations
- Complete exercises

## After reading

- Close the book
- Reconstruct the concepts
- Explain them without notes
- Implement them
- Break the implementation
- Debug it
- Benchmark it where relevant

## Chapter completion

You should be able to:

- Explain the concept
- Implement the concept
- Explain its complexity
- Explain its memory behaviour
- Explain its trade-offs
- Identify failure cases
- Debug an implementation
- Teach it to another developer

---

# 19. AI RESET PROGRAM

## Stage 1: Dependency break

- No AI for LeetCode attempts
- No AI for textbook exercises
- No AI for debugging for the first 30 minutes
- No AI-generated project architecture
- No copying solutions

## Stage 2: Controlled AI

- Ask for hints
- Ask questions
- Ask for counterexamples
- Ask for critique
- Ask why your approach fails

## Stage 3: AI as reviewer

- Build independently
- Give AI your solution
- Ask it to identify weaknesses
- Verify everything yourself
- Rewrite anything you do not understand

## Stage 4: Independent engineer

- Design independently
- Implement independently
- Debug independently
- Benchmark independently
- Use AI only as another engineering opinion

---

# 20. FINAL COMPLETION STANDARD

You are finished when you can:

- Solve unfamiliar algorithmic problems
- Reason about complexity
- Explain bits and bytes
- Explain how memory works
- Explain pointers
- Explain object lifetimes
- Explain smart pointers
- Explain RAII
- Explain move semantics
- Explain templates
- Explain compilation
- Read assembly
- Understand CPU caches
- Understand virtual memory
- Understand operating systems
- Understand concurrency
- Understand atomic memory ordering
- Profile C++ programs
- Optimise based on measurements
- Write production C++
- Write production Rust
- Explain ownership and lifetime
- Design concurrent systems
- Implement algorithms from scratch
- Debug without AI
- Read source code independently
- Read technical documentation independently
- Understand probability
- Understand statistics
- Understand numerical methods
- Understand derivatives and options
- Build pricing models
- Build market infrastructure
- Build a backtesting system
- Build a quant research system
- Explain every important engineering decision you make

## The end goal

> **Think like a computer scientist.**
> **Build like a systems engineer.**
> **Reason like a mathematician.**
> **Code like a senior C++/Rust engineer.**
> **Develop like a quant developer.**
> **Use AI as a tool, not as your brain.**
