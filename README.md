# Hi, I'm Eric 👋

I'm a Computer Science graduate from **Tsinghua University** (Class of 2026), with a focus on systems programming and storage infrastructure.

---

## 🔧 About Me

- 🎓 B.Eng. in Computer Science — Tsinghua University, June 2026
- 🛠️ Interested in operating systems, storage systems, and cloud infrastructure
- 🐧 Linux enthusiast; comfortable across Linux and Windows environments
- 🎨 Amateur digital artist in my spare time

---

## 🚀 Featured Project — LS-COW

> **Log-Structured Copy-on-Write Block Storage for Concurrent Lightweight VM Startup**

My undergraduate thesis project, built around [Firecracker](https://firecracker-microvm.github.io/) microVMs. LS-COW is a block storage backend designed to accelerate the cold-start problem when launching many lightweight VMs simultaneously, using a log-structured write path combined with copy-on-write semantics to minimize redundant I/O across instances.

**Key results:**
- 📈 **320+ MB/s** sequential write throughput
- ⚡ **3.5×–4.0× recovery speedup** over the baseline (71.5%–75.3% reduction in recovery time)

**Core ideas:**
- Log-structured writes eliminate random I/O during concurrent startup bursts
- COW layering lets multiple VM instances share read-only base images efficiently
- Crash recovery is optimized by replaying only the compact log tail

---

## 🛠️ Skills & Tools

**Languages:** C++ · Python · GDScript  
**Systems:** Linux kernel interfaces · block I/O stack · virtual machines  
**Tooling:** Git · GDB · perf · Firecracker · QEMU  
**Other:** LaTeX · Makefile-based build systems

---

## 📫 Get in Touch

- 📧 [angrytrappers@proton.me](angrytrappers@proton.me)

---

*Open to systems engineering and infrastructure roles — feel free to reach out!*
