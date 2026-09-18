# Mark Gilbert

**Principal Systems Architect**  
*High-Concurrency Distributed Systems · Low-Latency C++20 Runtimes · Mechanical Sympathy*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/markgilbert1)
[![PyTorch RFC #110](https://img.shields.io/badge/PyTorch%20RFC-PR%20%23110-EE4C2C?style=flat&logo=pytorch)](https://github.com/pytorch/rfcs/pull/110)
[![Aegis Benchmark](https://img.shields.io/badge/Aegis%20Benchmark-0.649s%20%2F%201B%20Ops-22C55E?style=flat&logo=cplusplus)](https://github.com/markbgilbert/aegis-zero-gc-benchmark)

---

### 🚀 Active Architectural Initiatives

* **[PyTorch Core RFC-0036 (PR #110)](https://github.com/pytorch/rfcs/pull/110):** Proposing an optional zero-runtime-allocation, 64-byte cache-aligned (`alignas(64)`) C++20 flat arena memory pattern to eliminate host-side speculative decoding verification bottlenecks in PyTorch (`torch.compile` Inductor) and ExecuTorch (`pytorch/executorch`).
* **[Aegis Zero-GC Hardware Benchmark](https://github.com/markbgilbert/aegis-zero-gc-benchmark):** Standalone open-source reproduction harness executing 1,000,000,000 operations in **0.649 seconds (1.54B ops/sec)** in Node.js (V8) and **0.277 ns/op (< 1 cycle)** in compiled native C/AVX2 with zero allocator stalls.
* **Low-Latency Systems Research:** Exploring hardware-enforced memory isolation, flat arena batch ingestion, and lock-free SPSC ring buffers for high-throughput AI pipelines.

---

### 🛠️ Proven Technical Lineage

* **HBO (Game of Thrones):** Advised engineering leadership on streaming architecture resilience, scaling origin capacity by **10,000% (100x)** and orchestrating **10,000,000 Concurrent Virtual User (10M VU)** synthetic stress tests ahead of global premieres.
* **PyTorch Host Ingestion Acceleration (nanoGPT):** Engineered zero-allocation flat arena feeder kernel achieving **136.3x faster batch ingestion (7.32 µs vs. 997.70 µs)** and **82.5% host RAM reduction** on physical AMD Zen 5 hardware.
* **High-Concurrency Distributed Systems:** Decades of experience designing fault-tolerant distributed execution engines, high-frequency trading matching kernels, and zero-allocation memory architectures.

---

### 💻 Core Specializations

* **Languages & Runtimes:** C++20, ISO C, WebAssembly (WASM), TypeScript/Node.js, Python FFI (`pybind11`).
* **Mechanical Sympathy:** 64-byte CPU cache alignment (`alignas(64)`), AVX2 / AVX-512 vectorization, DRAM bus saturation, zero-copy lock-free SPSC ring buffers.
* **Systems Architecture:** Distributed load orchestration, edge caching architectures, socket buffer optimization, zero-allocation memory pools.

---

📫 **Connect:** [mbgilbert@gmail.com](mailto:mbgilbert@gmail.com) · [LinkedIn](https://linkedin.com/in/markgilbert1)
