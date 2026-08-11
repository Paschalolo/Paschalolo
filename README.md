# Paschal Ahanmisi

> **Systems Engineer** · Low-Level Software, Microarchitecture, & High-Performance Infrastructure

I build deterministic, high-throughput systems from first principles. My focus lies at the intersection of raw hardware and software execution: squeezing out maximum performance, eliminating operating system friction, and understanding the true cost of every cycle, cache miss, and instruction.

---

## 🛠️ Core Competencies & Technical Stack

* **Languages:** C (C11/C23), C++ (Modern/Systems), Assembly (`x86_64`, `ARM64`)
* **SIMD & Data-Parallelism:** AVX-512, AVX2, NEON
* **Kernel-Bypass & Networking:** AF_XDP, User-Space PCIe Drivers
* **Memory & Concurrency:** Lock-free/wait-free data structures, custom NUMA-aware memory allocators, cache-line optimization, memory ordering
* **Systems Architecture:** Microarchitecture profiling, TLB/cache efficiency, profile-guided optimization (PGO), binary rewriting, custom ELF parsers/loaders

---

## 🚀 Projects & Engineering Artifacts

Rather than a traditional list of repositories, my complete body of work, technical write-ups, and systems projects are hosted and documented in a minimalist, self-contained format.

👉 **[Explore My Complete Project Archive & Portfolio](https://paschalolo.github.io/)**

Highlights of systems built from scratch (available on the archive above) include:
* **Custom Dynamic Linker & ELF Parser:** Engineered entirely in C to resolve symbols, handle relocations, and load binaries from first principles.
* **Production-Grade Slab Allocator:** A custom, thread-local cached, NUMA-aware memory allocation engine designed to bypass standard allocator lock contention.
* **Profile-Guided Binary Layout Optimizer:** A optimization engine that restructures execution paths and basic blocks to yield massive performance gains.
* **Kernel-Bypass Storage Engine:** Zero-copy storage architecture built to eliminate OS friction and maximize I/O throughput.

---

## 🔬 Engineering Philosophy

* **Measure, Don't Guess:** Optimization without profiling is just superstition. Microarchitectural bottlenecks—cache misses, branch mispredictions, pipeline stalls—dictate the design.
* **Zero-Cost Abstractions (When Possible):** If an abstraction introduces runtime overhead or hides the underlying hardware cost, discard it.
* **First Principles:** Relying on the standard library or OS primitives is a choice, not a requirement. True understanding comes from building the stack from the metal up.
