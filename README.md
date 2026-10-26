<h1 align="center">Atharv Dewangan</h1>

<p align="center">
  <strong>CSE @ PES University · Full-stack & systems developer · Cybersecurity & CTFs · Learning AI/ML</strong><br />
  I build software end to end and ship it: web, desktop and low-level tools, with security designed in from the start.
</p>

<p align="center">
  <a href="mailto:dewangan.atharv@gmail.com"><img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/dewanganatharv/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://instagram.com/itsatharv.lol"><img src="https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
  <a href="https://discord.gg/yyjEg9wTFa"><img src="https://img.shields.io/badge/-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
</p>

---

## Flagship projects

### [Corvale](https://github.com/RRI-Atharv37/corvale): offline-first personal finance tracker
`TypeScript` `React` `Node.js` `MongoDB` `SQLite` `Rust / Tauri` · **v1.0.4, in private field test** · AGPL-3.0

A finance tracker for students and young adults, built and shipped solo since April 2025. One codebase runs as a web app, an installable PWA and a native desktop app.

- **Full-stack TypeScript monorepo:** Express 5 + MongoDB API, React 19 + Vite + Tailwind 4 web app and a VitePress docs site, with money, budget and forecast logic shared between server and client
- **Offline-first sync:** local SQLite (WASM/OPFS in the browser, SQLCipher on desktop) with an outbox-based, bidirectional sync engine, checkpointed pulls and conflict handling. The desktop app signs in once, then works fully offline
- **Native desktop app** with Tauri v2, auto-updating through signed GitHub releases
- **Security:** multi-tenant workspaces with owner/editor/viewer roles, row-level security enforced in the query layer (an unscoped query throws instead of leaking data), rotating refresh tokens, encryption at rest, strict CSP and upload virus scanning
- **Quality:** 1,900+ automated tests and three full security audits, with all 69 findings fixed

**Next:** two-factor auth · Google sign-in · paid plans · later, bank sync and mobile apps

### [HeapScope](https://github.com/RRI-Atharv37/heapscope): heap profiler for native Windows programs
`Rust` `C++` `Windows internals` · **v0.1.0-beta** · GPL-3.0

Record every heap allocation of a 64-bit Windows program, find leaks and compare two runs, with no source changes.

- `heapscope run` launches a program, and `heapscope attach` hooks into one already running, by injecting a capture DLL that intercepts the C/C++ runtime and `HeapAlloc`
- Streams allocations into a custom `.hstrace` format, then builds a self-contained HTML report with a call tree, flame graph, timeline and run-to-run diff
- Sampling and lifetime filters keep overhead low; an optional MIT-licensed header covers custom allocators
- CI templates for GitHub Actions and Azure Pipelines that fail a build on memory regressions

---

## Cybersecurity

- 🏆 **7th place, Nimbus 2000 CTF** (cybersecurity, GenAI, data analytics, cloud), out of ~65–70 teams. Competed solo in an event built for teams of two
- Building my own Python CTF triage toolkit: file and stego analysis, encoding and classic-cipher chains, common RSA attacks, XOR, pcap and USB HID extraction, JWT and Flask-cookie tooling
- Security in my own projects: three full security audits on Corvale (69 findings, all fixed), row-level security at the query layer, encryption at rest, and `npm audit` / `cargo audit` gates in CI. HeapScope works at the level of DLL injection and API hooking on Windows

---

## Also working on

- **[MeshVault](https://github.com/RRI-Atharv37/meshvault)** (Rust): the open engine of a peer-to-peer file-sync app for teams with large video and 3D files. FastCDC + BLAKE3 chunking at ~590 MB/s on one thread, version vectors, signed updates and a contract test kit for sync backends
- **AI/ML from scratch** (Python, NumPy): logistic regression spam classifier with hand-written gradient descent and TF-IDF, k-NN and k-means++ on ~114k Spotify tracks, and linear regression on air-quality data
- **Fundamentals:** [CS50x](https://github.com/RRI-Atharv37/cs50x), [CS50P](https://github.com/RRI-Atharv37/cs50p), [C++](https://github.com/RRI-Atharv37/learncpp) and [data structures in C/C++](https://github.com/RRI-Atharv37/data-structures-c-cpp)

Earlier, I published [**commanding.js**](https://www.npmjs.com/package/commanding.js), an npm command-handler library for Discord bots.

---

## Tech stack

**Languages**<br />
![TypeScript](https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logo=typescript)
![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=for-the-badge&logo=javascript)
![Rust](https://img.shields.io/badge/-Rust-black?style=for-the-badge&logo=rust)
![Python](https://img.shields.io/badge/-Python-black?style=for-the-badge&logo=python)
![C](https://img.shields.io/badge/-C-black?style=for-the-badge&logo=c)
![C++](https://img.shields.io/badge/-C%2B%2B-black?style=for-the-badge&logo=cplusplus)
![Java](https://img.shields.io/badge/-Java-black?style=for-the-badge&logo=openjdk)

**Web**<br />
![React](https://img.shields.io/badge/-React-black?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/-Vite-black?style=for-the-badge&logo=vite)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logo=tailwind-css)
![Node.js](https://img.shields.io/badge/-Node.js-black?style=for-the-badge&logo=node.js)
![Express](https://img.shields.io/badge/-Express-black?style=for-the-badge&logo=express)

**Data, desktop & ML**<br />
![MongoDB](https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logo=mongodb)
![SQLite](https://img.shields.io/badge/-SQLite-black?style=for-the-badge&logo=sqlite)
![Tauri](https://img.shields.io/badge/-Tauri-black?style=for-the-badge&logo=tauri)
![NumPy](https://img.shields.io/badge/-NumPy-black?style=for-the-badge&logo=numpy)

**Tooling**<br />
![Git](https://img.shields.io/badge/-Git-black?style=for-the-badge&logo=git)
![Docker](https://img.shields.io/badge/-Docker-black?style=for-the-badge&logo=docker)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-black?style=for-the-badge&logo=githubactions)
![Vitest](https://img.shields.io/badge/-Vitest-black?style=for-the-badge&logo=vitest)
![AWS](https://img.shields.io/badge/-AWS-black?style=for-the-badge&logo=amazonaws)

---

<p align="center">Open to internships and collaborations. Feedback and contributions on Corvale and HeapScope are welcome.</p>
