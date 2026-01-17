# CM Mongo

![Role](https://img.shields.io/badge/Role-Systems_Engineer-blue?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Edge_Computing_%7C_Distributed_Systems-black?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-Rust_%E2%86%92_WASM-blueviolet?style=for-the-badge)

**Systems Engineer | Edge Computing & Distributed Systems**

I build secure, distributed systems from bare metal to cloud edge. My focus: WASM sandboxing (WASI, Workers), industrial IoT, and fault-tolerant architectures. Currently exploring capability-based security for edge computing.

> **[🖥️ Launch Interactive Terminal Portfolio →](https://gammahazard.github.io/Vanguard-Portfolio/)**  
> *Built with Rust & WebAssembly*

---

## 🎯 Featured Projects

### Guardian One — The Flagship Demo

> **[Guardian One Web Demo](https://github.com/gammahazard/guardian-one-web-demo)** | [Live Demo →](https://guardian-one-web-demo.vercel.app)

Story-driven demonstration of industrial edge security—Python/Docker vs WASM side-by-side.

- **Concept:** Industrial edge security with IEC 62443 zones, 2oo3 TMR voting, live attack simulations
- **Stack:** Leptos, Pyodide (real Python execution), WASI 0.2
- **Features:** Real CVE citations, guided learning flow (Problem → Hardware → Demo → Proof)
- **Hardware Preview:** Browser simulation of upcoming physical demo with Siemens S7-1200 PLC + 3-node Raspberry Pi Raft cluster

---

### Edge Protocol Demo — Production Cloudflare Workers

> **[Edge Protocol Demo](https://github.com/gammahazard/edge-protocol-demo)** | [Live Demo →](https://edge-protocol-demo.pages.dev)

Production-style Cloudflare Workers + Leptos dashboard demonstrating real-world edge patterns.

- **Features:** URL shortener (Workers KV), edge rate limiter (10M+ req/day capable), capability sandbox
- **Stack:** Rust → WASM (Workers), Leptos 0.7 (Pages), CI/CD via GitHub Actions
- **Architecture:** Shows same capability security principles as WASI, but at cloud edge
- **Highlight:** Complete production setup—rate limiting, CORS, health checks, standard headers

---

### Edge WASI Runtime — Hardware Proof

> **[Edge WASI Runtime](https://github.com/gammahazard/edge-wasi-runtime)** | [Live on Raspberry Pi](https://github.com/gammahazard/edge-wasi-runtime#demo)

Secure, hot-swappable IoT runtime executing sandboxed Python plugins on Raspberry Pi.

- **Concept:** Running untrusted Python scripts on bare metal without risk
- **Stack:** Rust (host), WASI Component Model, Python (guest), Wasmtime, Tokio
- **Innovation:** Hybrid architecture—Rust for safety, Python for velocity
- **Highlight:** Hot-swap a running sensor driver in <10ms without dropping connections (demonstrated live on hardware)

---

### Raft Consensus Cluster — Distributed Systems

> **[Raft Consensus](https://github.com/gammahazard/Raft-Consensus)** | [Live Demo →](https://raft-consensus.vercel.app)

Distributed consensus in the browser—same Rust binary runs in browser AND on Raspberry Pi.

- **Concept:** Leader election, log replication, network partitions—all visualized live
- **Stack:** Rust, WASI 0.2, Leptos, IndexedDB, BroadcastChannel
- **Advanced:** PreVote protocol (Raft Thesis §9.6) prevents disruptive servers
- **Highlight:** 120+ tests, chaos controls to kill nodes and watch self-healing

---

## 🔧 More Projects

- **[ICS Guardian](https://github.com/gammahazard/vanguard-ics-guardian)** — Capability-based security for industrial sensors (14.7KB WASM vs 500MB Docker)
- **[Protocol Gateway Sandbox](https://github.com/gammahazard/protocol-gateway-sandbox)** — Safe Modbus/MQTT translation with crash containment
- **[The Kennel Platform](https://github.com/gammahazard/Vanguard-kennel-frontend)** — Production booking system with FIDO2 biometric auth

---

## 🛠️ Tech Stack

| **Core Systems** | **Web & Edge** | **Security & Data** |
|:-----------------|:---------------|:--------------------|
| Rust, WASI 0.2, Wasmtime | Next.js 14, React, TypeScript | FIDO2, IEC 62443, Zero Trust |
| Leptos, Component Model | Cloudflare Workers/Pages | Capability Security, 2oo3 TMR |
| nom Parser, Axum | Node.js, Tokio | PostgreSQL, MongoDB, KV |

---

## 🧠 Engineering Philosophy

**Deep Runtime Knowledge:** I understand WASM runtimes (Wasmtime, browser), JavaScript internals (Event Loop, ESM/CJS), and hardware constraints (Raspberry Pi, PLCs).

**Capability-Based Security:** Deny-by-default sandboxing. Untrusted code gets only explicitly granted permissions—whether WASI plugins or Cloudflare Workers.

**Crash Containment:** Malformed parsers run in WASM sandboxes. Buffer overflow kills the sandbox, not the host. Sub-millisecond recovery, zero data loss.

**Hybrid Architecture:** WASM + Docker coexist—Docker ships infrastructure (Rust host), WASM ships business logic (plugins). O(n) tenants in O(1) container.

**Evidence Over Assertions:** When I claim "<0.1ms rebuild," I provide `performance.now()` timings (5-sample averaged) in live demos.

---

## 📫 Connect

- **Portfolio Terminal:** [gammahazard.github.io/Vanguard-Portfolio](https://gammahazard.github.io/Vanguard-Portfolio)
- **GitHub:** [@gammahazard](https://github.com/gammahazard)
- **Projects:** Edge computing, WASM runtimes, industrial IoT, distributed systems

---

**Engineering high-assurance systems—from industrial edge devices to enterprise web.** 🚀
