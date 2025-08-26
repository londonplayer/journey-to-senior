# My 16-Week Computer Science Fundamentals Journey

This repository documents a rigorous, 16-week self-study program to build a deep, first-principles understanding of computer science. The goal is to move beyond simply _using_ tools to fundamentally understanding _how they work_, from the physics of transistors up to distributed data systems.

This plan is a bottom-up journey with no shortcuts, emphasizing hands-on implementation, mathematical reasoning, and clear technical explanations.

## 🎯 Core Objectives

- **Explain systems from first principles:** From how a bit is stored to how a distributed transaction is committed.
- **Implement small systems:** Build components like a memory allocator, a compiler front-end, a bytecode VM, and an HTTP server.
- **Reason with mathematics:** Defend performance claims, analyze complexity, and prove correctness using logic, discrete math, and probability.
- **Master the toolchain:** Understand the path from C source code to a running process, including compilation, linking, loading, and virtual memory.

---

## 📚 Study Plan Overview

The curriculum is divided into 8 two-week modules. Each module integrates systems programming, computer architecture, and the relevant mathematical or physical principles.

### **Module 1: From Physics to a CPU**

_Core Resources: Harris & Harris DDCA, Nand2Tetris Part I_

- **### Week 1: From Bits to Logic Gates & The C Toolchain**

  - **Topics:** Voltage levels, noise margins, CMOS logic.
  - **Labs:** Build combinational logic circuits (adders, muxes, ALU slice) in Logisim. Trace a C program through the `preprocess -> compile -> assemble -> link` pipeline and inspect the resulting ELF file.
  - **Math:** Propositional logic and proofs by truth table.

- **### Week 2: Sequential Logic, Timing, and State**
  - **Topics:** Latches, D-Flip-Flops, registers, and the Program Counter (PC).
  - **Labs:** Construct sequential circuits in Logisim. Analyze timing diagrams for setup/hold violations. **Micro-Lab:** Simulate RC delay in Falstad to connect physical properties to clock speed.
  - **Math:** Predicates, sets, and proof by contradiction.

### **Module 2: The Journey of a Program**

_Core Resources: CS:APP, System V ABI (ELF Spec)_

- **### Week 3: Linking, Loading, and the C Ramp-Up**

  - **Topics:** Static vs. dynamic linking, symbol resolution, relocations, PLT/GOT.
  - **Labs:** Build a program with static and shared libraries, inspecting relocation entries with `readelf` and tracing runtime linking with `LD_DEBUG`.
  - **Math:** Proof by induction.

- **### Week 4: Virtual Memory and the Operating System**
  - **Topics:** Address spaces, page tables, Translation Lookaside Buffers (TLBs), page faults.
  - **Labs:** Use `strace` and `/proc/<pid>/maps` to inspect a process's memory layout and provoke page faults. **Micro-Lab:** Demonstrate metastability with a multi-clock circuit in Logisim.
  - **Math:** Asymptotics and solving simple recurrences (Master Method).

### **Module 3: Building a Language**

_Core Resources: Crafting Interpreters_

- **### Week 5: Lexing and Parsing**

  - **Topics:** Regular expressions, finite automata, recursive-descent parsing, Abstract Syntax Trees (ASTs).
  - **Labs:** Implement a lexer and parser for a simple expression language.
  - **Math:** Graphs, trees, and structural induction.

- **### Week 6: Bytecode and Virtual Machines**
  - **Topics:** Stack-based VMs, instruction sets, dispatch loops, stack frames.
  - **Labs:** Design a simple bytecode instruction set and implement the core VM loop to execute it.
  - **Math:** Combinatorics, counting, and binomial coefficients.

### **Module 4: Managing Memory**

_Core Resources: OSTEP, CS:APP_

- **### Week 7: Dynamic Memory Allocation**

  - **Topics:** Heap management, `brk`/`mmap`, explicit free lists, coalescing, fragmentation.
  - **Labs:** Implement a basic `malloc`, `free`, and `realloc` with an explicit free list and boundary tags.
  - **Math:** Recurrence relations (substitution method).

- **### Week 8: Caches and the Memory Hierarchy**
  - **Topics:** Spatial and temporal locality, cache lines, direct-mapped vs. associative caches.
  - **Labs:** Write microbenchmarks to experimentally determine the size and latency of your CPU's L1/L2/L3 caches.
  - **Math:** Invariants and their application in proofs.

### **Module 5: Concurrency and Numerical Computing**

_Core Resources: OSTEP, TLPI, Goldberg's FP Paper_

- **### Week 9: Threads, Locks, and Floating Point**

  - **Topics:** POSIX threads, mutexes, condition variables, deadlock.
  - **Labs:** Implement a thread pool with a bounded work queue. **Micro-Lab:** Demonstrate floating-point cancellation and implement Kahan summation to mitigate it.
  - **Math:** Probability basics, random variables, and expectation.

- **### Week 10: Advanced Concurrency Patterns**
  - **Topics:** Rate limiting, work-stealing, scheduling, backpressure.
  - **Labs:** Implement a token-bucket rate limiter or a simple work-stealing scheduler.
  - **Math:** Queueing theory (Little's Law) and tail bounds (Markov/Chernoff).

### **Module 6: The Internet**

_Core Resources: Kurose & Ross, relevant RFCs_

- **### Week 11: Sockets and Application Protocols**

  - **Topics:** TCP/IP, sockets API, HTTP/1.1 protocol.
  - **Labs:** Build a simple, concurrent HTTP/1.1 server that can serve static files.
  - **Math:** Conditional probability and Bayes' Rule.

- **### Week 12: Network Performance and Security**
  - **Topics:** RTT, bandwidth-delay product (BDP), TCP slow start, TLS 1.3 handshake (conceptual).
  - **Labs:** Use `tcpdump`/Wireshark to measure RTT and handshake latency. **Micro-Lab:** Compare measured latency to the theoretical speed-of-light lower bound.
  - **Math:** Variance and confidence intervals.

### **Module 7: Storing Data**

_Core Resources: DDIA, Mitzenmacher & Upfal_

- **### Week 13: Log-Structured Storage**

  - **Topics:** Log-Structured Merge-Trees (LSM), memtables, SSTables, compaction, write-ahead logs (WAL).
  - **Labs:** Implement a prototype log-structured key-value store with a WAL for crash recovery and optional Bloom filters for read optimization.
  - **Math:** Probabilistic data structures (Bloom filters).

- **### Week 14: Transactions and Consistency**
  - **Topics:** Durability (`fsync`), batching, snapshot isolation, CAP theorem.
  - **Labs:** Add snapshot read capabilities and configurable durability policies to the KV store.
  - **Math:** Applying queueing theory to batching and tail latency.

### **Module 8: Capstone and Synthesis**

_Core Resources: Serious Cryptography, project-specific RFCs/specs_

- **### Week 15: Capstone Project Kickoff**

  - **Topics:** Threat modeling, performance analysis planning, symmetric cryptography primitives (AEADs).
  - **Labs:** Design and begin implementation of the capstone project (Compiler+VM or TCP+HTTP Server).
  - **Math:** Applying performance models and reviewing numerical pitfalls.

- **### Week 16: Capstone Completion and Defense**
  - **Topics:** Final implementation, performance benchmarking, security review, technical writing.
  - **Labs:** Complete the capstone project, write a final report with data-backed claims, and prepare for an oral defense.
  - **Math:** Synthesizing models, proofs, and numerical analysis for the final report.

---

## 💻 Core Tools & Environment

- **OS:** Windows 11 with WSL2 (Ubuntu)
- **Compilers & Tooling:** GCC, Clang, GDB, Valgrind, `make`, `perf`, `strace`
- **Simulators:** Logisim-evolution (digital logic), Falstad (circuits)
- **Networking:** Wireshark, `tcpdump`
- **Scripting & Plotting:** Python with `numpy`/`matplotlib`, `gnuplot`
- **Version Control:** Git

## 📂 Repository Structure

This repository is organized by module. Each top-level directory corresponds to one of the 8 modules in the study plan.
