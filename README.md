# Paschal Ahanmisi
> **Systems Engineer** · Low-Level Software & Microarchitecture

I build deterministic, high-throughput systems from first principles—eliminating OS friction, optimizing for cache and instruction cost, and executing down to the metal.

🌐 **[Complete Project Archive](https://paschalolo.github.io/)**

---

### ⚙️ Core Technical Stack
* **Languages:** C (C11/C23), C++, Assembly (`x86_64`, `ARM64`)
* **SIMD:** AVX-512, AVX2, NEON
* **Systems & Networking:** Kernel-bypass (AF_XDP), User-Space PCIe Drivers, io_uring
* **Concurrency & Memory:** Lock-free/wait-free structures, NUMA-aware allocators, memory ordering

---

### 🚀 Highlights
* **Custom Dynamic Linker & ELF Parser:** Engineered in C to resolve symbols and load binaries from scratch.
* **NUMA-Aware Slab Allocator:** Thread-local cached memory allocator bypassing standard lock contention.
* **Profile-Guided Binary Optimizer:** Restructures execution paths to slash instruction cache misses.
* **Kernel-Bypass Storage Engine:** Zero-copy, lock-free architecture built to maximize I/O throughput.
