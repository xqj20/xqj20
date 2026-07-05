# Hey, I'm Eric Xu / 徐秋骏

I'm a fresh graduate from **Tsinghua University** (Class of June 2026) majoring in Computer Science.

---

## About

- Graduated with a degree (Bachelor's Degree of Engineering in Computer Science and Technology) from Tsinghua University in June of 2026
- Authored undergraduate capstone thesis on optimizing the efficiency of copy-on-write storage for the startup of concurrent virtual machines 
- Interned at MeiTuan (美团）over the summer of 2024
- Interested in operating systems, storage systems, and cloud infrastructure
- Interested in developing indie games, building a small home lab, and doing digital art for fun 
- I like Linux :)

---

## Featured Project : LS-COW

> **Log-Structured Copy-on-Write Block Storage for Concurrent Lightweight VM Startup**

My undergraduate thesis capstone project, built around [Firecracker](https://firecracker-microvm.github.io/) microVMs. LS-COW is a block storage backend designed to accelerate the cold-start problem when launching many lightweight VMs simultaneously, using a log-structured write path combined with copy-on-write semantics to minimize redundant I/O across instances.

**Key results:**
- **320+ MB/s** sequential write throughput
- **3.5×–4.0× recovery speedup** over the baseline (71.5%–75.3% reduction in recovery time)

**Core ideas:**
- Log-structured writes eliminate random I/O during concurrent startup bursts
- COW layering lets multiple VM instances share read-only base images efficiently
- Crash recovery is optimized by replaying only the compact log tail

---

## Skillset & Tools

**Programming Languages:** C++ · C# · Python · GDScript · Java · Rust  
**Languages:** English (Native; Canadian citizen, US permanent resident) · Mandarin Chinese (Very Fluent; HSK 5 certified)  
**Game Engines:** Godot  
**Systems:** Linux kernel interfaces · block I/O stack · virtual machines  
**Tooling:** Git · GDB · perf · Firecracker · QEMU  
**Other:** LaTeX · Makefile-based build systems

---

## Contact Information

- [angrytrappers@proton.me](angrytrappers@proton.me)

---
