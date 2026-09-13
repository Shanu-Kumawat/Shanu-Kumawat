<div align="center">
  
# Shanu Kumawat

Systems & Product Engineer · Open Source Builder · Dart SDK Contributor

<a href="https://linkedin.com/in/shanukumawat"><img src="https://img.shields.io/badge/LinkedIn-d5d5d5?style=for-the-badge&logo=linkedin&logoColor=0A0209" alt="LinkedIn" /></a>
<a href="https://x.com/shanu_builds"><img src="https://img.shields.io/badge/Twitter-d5d5d5?style=for-the-badge&logo=x&logoColor=0A0209" alt="Twitter" /></a>
<a href="mailto:shanu.kumawat.dev@gmail.com"><img src="https://img.shields.io/badge/Email-d5d5d5?style=for-the-badge&logo=gmail&logoColor=0A0209" alt="Email" /></a>

</div>

---

## About

Software builder and undergraduate at **MNNIT Allahabad** (Engineering & Computational Mechanics, 2023–2027) focused on **systems software, desktop architecture, and verified agentic systems**.

I build tools to eliminate real-world friction—from Linux desktop utilities used by hundreds of daily users, to C++ patches in the Google Dart SDK compiler, to multi-agent harnesses with deterministic hallucination verification.

- **Languages:** C++, Python, Dart, C, Bash, SQL
- **Systems & Architecture:** Linux Internals, Memory Management, Wayland Compositing, Compilers & ASTs, TUN/TAP Routing, Sandboxing
- **AI & Agentic Systems:** Multi-Agent Orchestration, Human-in-the-Loop Controls, Deterministic Output Verification
- **Campus Leadership:** Representative at the Computer Coding Club (MNNIT); maintain the institute's SAC production server ([sac.mnnit.ac.in](https://sac.mnnit.ac.in/)).

---

## Flagship Builds & Projects

### [Quickshell Overview](https://github.com/Shanu-Kumawat/quickshell-overview)
*Standalone Linux workspace overview module for Hyprland compositors · Arch Linux AUR*
- **Traction:** **480+ GitHub stars**, packaged on **Arch Linux AUR** (`quickshell-overview-git`), actively directing development and PR reviews from 10+ open-source contributors.
- **Engineering:** Implemented live Wayland window previews, drag-and-drop workspace migration, and multi-monitor scaling using Qt6/QML; optimized shared memory buffers and event-driven IPC sockets to sustain fluid 60+ FPS under heavy compositing loads.

### [TrueStrike](https://github.com/Shanu-Kumawat/truestrike)
*Autonomous web security agent with sandboxed tooling and deterministic verification*
- **Architecture:** Orchestrates role-aware subagents inside isolated Daytona cloud sandboxes, governed by an exploit-approval gateway requiring audited operator authorization for intrusive payloads.
- **Verification Engine:** Built an independent verification engine and automated CI test pipeline that **audits and recalculates AI arithmetic hallucinations on CVSS 3.1 scores**; discovered and documented critical upstream harness vulnerabilities, including silent host execution when sandboxes are unconfigured.

### [RentKhata](https://github.com/Shanu-Kumawat/RentKhata)
*Production-grade, offline-first rental management system (~90K LOC) · Play Store Beta*
- **Architecture:** Conceived, designed, and built a complete offline-first ledger (~90K LOC across 220+ files) using Flutter, Riverpod, and Drift (SQLite) to eliminate landlord bookkeeping friction.
- **Domain Engine:** Engineered a custom anniversary billing engine with 31st month-end clamping and leap-year edge cases (verified via comprehensive unit test suites), dynamic PDF invoice generation, biometric lock, and structured offline data schemas.

### [mnnit-proxy](https://github.com/CC-MNNIT/mnnit-proxy)
*Automated TUN-mode campus proxy router for Linux distributions · CC-MNNIT*
- **Adoption:** Actively used by campus Linux developers across Arch, Debian, and Fedora to eliminate manual per-app proxy configuration.
- **Reliability:** Automated room-wise static IP resolution with NetworkManager dispatchers; built Dockerized multi-distro integration tests (Ubuntu/Fedora) in GitHub Actions CI to guarantee zero-touch network auto-switching.

---

## Open Source & Compiler Contributions

### [Google Dart SDK Compiler](https://github.com/dart-lang/sdk)
*Core contributor to the official Dart programming language frontend and runtime:*
- **[Check @Native on extension members](https://dart-review.googlesource.com/c/sdk/+/482160):** Contributed C++ patches to resolve a Foreign Function Interface (FFI) diagnostic discrepancy, enforcing strict diagnostic parity between the Analyzer and Common Front End (CFE).
- **[Issue #62716](https://github.com/dart-lang/sdk/issues/62716):** Discovered, triaged, and documented a core compiler crash caused by an invalid Abstract Syntax Tree (AST) type cast (`ExtensionElementImpl` to `InterfaceElement`) during static analysis.
- **Test Infrastructure:** Modernized 9 legacy VM static-check test suites to a contemporary expectation framework, safeguarding compiler test integrity.

---

## Contact

- **Email:** [shanu.kumawat.dev@gmail.com](mailto:shanu.kumawat.dev@gmail.com)
- **LinkedIn:** [linkedin.com/in/shanukumawat](https://linkedin.com/in/shanukumawat)
- **Twitter / X:** [@shanu_builds](https://x.com/shanu_builds)
