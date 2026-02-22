# Inferno64: The Reclaimed Compute Grid

**Inferno64** is a modern, aspirational evolution of the classic distributed operating system. It provides a seamless, peer-to-peer compute grid designed to run on everything from modern desktops to reclaimed hardware. By networking together discarded phones, old laptops, and idle processors, Inferno64 creates a decentralized execution environment for distributed workloads and local AI hosting.

> **// SYSTEM STATUS: ALPHA //** > Inferno64 is an ongoing, highly aspirational research and development project. While core components like the Dis VM and basic networking are operational, features like the WASM-to-Dis bridge, the Owen labor exchange, and the Claw AI agent are in active, heavy development. Expect sharp edges, frequent core dumps, and rapid architectural shifts. Contributors and fellow silicon recyclers are welcome.

---

## ⚡ Core Features

* **Advanced Execution:** Runs the classic Dis VM upgraded with highly optimized **AMD64 and ARM64 JIT Compilers**.
* **WASM-to-Dis Bridge:** Compiles WebAssembly directly to Dis, enabling modern web payloads to run natively on the retro grid.
* **LLM Fileserver:** A native Styx/9P fileserver interfacing directly with `llama.cpp`. Grid nodes can read/write to large language models as standard text files.
* **Built-in SQLite:** Lightweight, reliable database functionality integrated seamlessly into the core environment.
* **Modernized Infrastructure:** Updated cryptography and compression algorithms for secure, fast peer-to-peer communication.
* **Revamped Audio:** Deep integration with PulseAudio on Linux for high-fidelity sound management.
* **Cross-Platform Host:** Runs on Windows 11, macOS, Android (via Termux), and modern Linux distributions.

---

## 🌐 The Compute Grid & The Owen Labor Exchange

Millions of capable processors sit idle in drawers across the globe. Inferno64 utilizes a peer-to-peer compute model to harness this wasted potential. 



At the heart of the cluster lies the **Owen labor exchange**, serving as the dedicated control plane. Owen intelligently manages resource discovery across the network, schedules distributed workloads, and facilitates a token-based compute economy. Whether it is routing WASM payloads or distributing LLM inference tasks, the Owen exchange ensures processes are allocated to the most capable idle nodes efficiently.

---

## 🤖 The Claw: Sandboxed AI Agent

Inferno64 hosts a built-in AI agent capable of interacting directly with the distributed OS via the **Claw**—an autonomous AI agent framework designed to run on personal hardware and execute tasks across a user's digital life. It smoothly traverses filesystems, operates command-line tools, and orchestrates complex operations across the grid.



Security is handled natively through Inferno's fundamental architecture. Every process in Inferno constructs its own configurable namespace, meaning the AI agent operates within a strictly defined reality. By omitting directories, network interfaces, or sensitive files from the agent's unique namespace, it remains perfectly sandboxed. It can only see, touch, and use the exact resources it has been explicitly granted.

---

## 🛠️ Building and Installation

To join the grid, pull the repository and build the host environment. You will need standard C build tools (gcc/clang) installed on your host system.

```bash
# 1. Clone the repository
$git clone [https://github.com/caerwynj/inferno64.git$](https://github.com/caerwynj/inferno64.git$) cd inferno64

# 2. Configure the build environment
$ ./makemk.sh

# 3. Build and install the system
$ mk install