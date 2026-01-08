# CM Mongo

![Role](https://img.shields.io/badge/Role-Principal_Systems_Architect-blue?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Security_%7C_Reliability_%7C_Scale-black?style=for-the-badge)
![Status](https://img.shields.io/badge/System-Operational-green?style=for-the-badge)

### Principal Systems Architect
*Engineering high-assurance systems—from industrial edge devices to enterprise web.*

---

## 🖥️ Interactive Terminal Portfolio

> **[Launch Terminal System >>](https://gammahazard.github.io/Vanguard-Portfolio/)**
> *Built with Rust & WebAssembly.* 

---

I don't just build frontends; I engineer complete systems.
My focus is on **Reliability Engineering**—creating applications that look great on the client side (Next.js/React) while remaining bulletproof on the server side. Whether it's high-frequency blockchain forensics, cross-platform desktop apps, or business-critical booking platforms, I build software that **does not fail**.

---

## 🛡️ The Reliability Triad

My flagship portfolio demonstrates **systems engineering** across three pillars of reliability:

| Project | Domain | Reliability Story |
|---------|--------|-------------------|
| **ICS Guardian** | Security | "I ensure the connection is safe." |
| **Protocol Gateway** | Edge | "I ensure the parser is crash-proof." |
| **Raft Cluster** | Distributed | "I ensure the system state is consistent." |

---

### 🔭 Featured Implementations

> **[Project: ICS Guardian](https://github.com/gammahazard/vanguard-ics-guardian)**
> Capability-based security demo: WASI 0.2 data diode for industrial control systems.
> * **Live Demo:** [vanguard-ics-guardian.vercel.app](https://vanguard-ics-guardian.vercel.app)
> * **Concept:** Sandbox untrusted sensor drivers—allow reads, block exfiltration.
> * **Stack:** Rust (cargo-component), Leptos, WASI 0.2, JavaScript host (JCO).
> * **Reliability:** 2oo3 TMR voting demo—WASM hot-swap (<0.1ms measured) vs Python restart (3+ sec).
> * **Security:** 17 integration tests verifying all 4 security states.
> * **Highlight:** 14.7KB WASM component vs 500MB+ Docker containers.



> **[Project: Protocol Gateway Sandbox](https://github.com/gammahazard/protocol-gateway-sandbox)** ⭐ FLAGSHIP
> Safe legacy protocol translation via WASM sandboxing—Modbus TCP → MQTT with crash containment.
> * **Live Demo:** [protocol-gateway-sandbox.vercel.app](https://protocol-gateway-sandbox.vercel.app)
> * **Concept:** Malformed Modbus crashes the sandbox, not the gateway. ~7ms recovery (measured).
> * **Stack:** Rust (nom parser), Leptos, WASI 0.2, JavaScript host (JCO).
> * **Reliability:** 2oo3 TMR voting with real WASM measurements—SIL 3 patterns.
> * **Security:** Dual-terminal demo with 4 attack vectors + "Run All" chaos mode.
> * **Highlight:** IEC 62443 attack surface minimization—only 2 of 40+ function codes implemented.



> **[Project: Raft Consensus Cluster](https://github.com/gammahazard/Raft-Consensus))** 🚧 IN DEVELOPMENT
> Distributed consensus in the browser via WASI 0.2—backend Rust runs unchanged in browser.
> * **Concept:** Leader election, log replication, network partitions—all visualized live.
> * **Stack:** Rust (no_std compatible), WASI 0.2, Leptos, IndexedDB, BroadcastChannel.
> * **Reliability:** Chaos controls to kill nodes and watch the cluster self-heal.
> * **Highlight:** Same Raft algorithm runs on server AND in browser via WASI capability mapping.

---

### 🏢 Production Applications

> **[Project: The Kennel Platform](https://github.com/gammahazard/Vanguard-kennel-frontend)**
> A Zero-Liability booking and guest management platform for luxury pet facilities.
> * **Concept:** Digital Identity ("Pawsports") & Biometric Access Control.
> * **Stack:** Next.js 14, Rust (Axum), FIDO2/WebAuthn, SQLite.
> * **Scale:** ~20,000 lines frontend + ~3,500 lines Rust backend.
> * **Security:** 10/10 integration tests passing, IDOR protection, rate limiting.

---

### 🏛️ Ventures & Engagements

> **[Metafrontier](https://metafrontier.xyz) (Technical Operations Lead)**
> *Current Engagement.*
> * **Role:** Ecosystem Security & Technical Support.
> * **Focus:** Managing operational security for a high-value user base, triaging technical incidents, and mitigating social engineering threats.

> **[CyberVerse](https://cyberversegame.io/) (Co-Founder & Lead Engineer)**
> *Legacy Project - Active Ecosystem.*
> * **Role:** Co-Founder / Core Developer.
> * **Achievement:** Built the platform from the ground up (0 to 1), scaling it to a live, self-sustaining ecosystem.
> * **Tech:** MongoDB, Vanilla JS, Web3 Integration.

---

### 🛠️ The Full Stack Arsenal

I operate across the entire stack, from pixel-perfect UI to system-level desktop control.

| **Core Systems** | **Web & Backend** | **Data & Security** |
| :--- | :--- | :--- |
| ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) | ![Next JS](https://img.shields.io/badge/Next.js_14-black?style=flat-square&logo=next.js&logoColor=white) | ![FIDO](https://img.shields.io/badge/Biometrics_(FIDO2)-green?style=flat-square) |
| ![WASI](https://img.shields.io/badge/WASM_%2F_WASI-orange?style=flat-square) | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) | ![Postgres](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) |
| ![Leptos](https://img.shields.io/badge/Leptos-EF3939?style=flat-square&logo=rust&logoColor=white) | ![Node](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white) | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) |
| ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | ![Zero Trust](https://img.shields.io/badge/Zero_Trust_Arch-blueviolet?style=flat-square) |
| ![Desktop](https://img.shields.io/badge/Tauri_%2F_Electron-critical?style=flat-square) | ![Component Model](https://img.shields.io/badge/Component_Model-blueviolet?style=flat-square) | ![ICS Security](https://img.shields.io/badge/ICS_Security-darkgreen?style=flat-square) |
| ![nom](https://img.shields.io/badge/nom_Parser-FF6B6B?style=flat-square) | ![Axum](https://img.shields.io/badge/Axum-000000?style=flat-square&logo=rust&logoColor=white) | ![IEC 62443](https://img.shields.io/badge/IEC_62443-critical?style=flat-square) |

---

### 🧠 Engineering Philosophy

* **Deep Runtime Knowledge:** I understand the JavaScript runtime at a low level (ESM vs CJS, Event Loop, Bundling). I specialize in making legacy modules work within modern, strict frameworks like Next.js.

* **Zero-Liability Design:** I prioritize **risk reduction**. I leverage hardware security (FIDO2) and architectural air-gaps to ensure that toxic data (Credit Cards/PII) never touches the application database.

* **Capability-Based Security:** I design systems where untrusted code runs in sandboxes that can only access explicitly granted capabilities. Deny by default, grant by exception.

* **Crash Containment:** Untrusted parsers run in WASM sandboxes. A buffer overflow kills the sandbox—not the host. Sub-millisecond recovery, zero data loss.

* **Hitless Failover:** 2oo3 TMR voting ensures continuous operation during faults. WASM's microsecond instantiation enables software failover without frame loss.

* **Real Measurements, Not Marketing:** When I claim "<0.1ms rebuild," I provide `performance.now()` timings (5-sample averaged) in the live demo. Evidence over assertions.

---

### 🕵️ On-Chain Forensics & Research
* **Incident Response:** Mitigating live threats and phishing vectors in the Metafrontier ecosystem and associated Solana protocols.
* **Transaction Analysis:** Specialized in tracing diverted funds and analyzing smart contract interactions on Solana/EVM.

---

[👉 **Explore Full Portfolio (Terminal Mode)**](https://gammahazard.github.io/Vanguard-Portfolio/)
