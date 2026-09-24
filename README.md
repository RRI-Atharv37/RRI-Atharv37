<h1 align="center">ATHARV DEWANGAN</h1>

<h2>
    <p align="center">
        <strong>Full Stack Developer & Computer Science Student</strong><br />
        Passionate about software engineering, cybersecurity and developing projects that work
    </p>
</h2>

<p align="center">
  <a href="mailto:dewangan.atharv@gmail.com">
   <img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white">
   </a>
  <a href="https://www.linkedin.com/in/dewanganatharv/">
   <img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
   </a>
  <a href="https://instagram.com/itsatharv.lol">
   <img src="https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
   </a>
  <a href="https://discord.gg/yyjEg9wTFa">
   <img src="https://img.shields.io/badge/-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
   </a>

</p>

---

## Currently Building

### [Corvale](https://github.com/RRI-Atharv37/corvale) - an offline-first personal finance tracker with a native desktop app, built and shipped solo.

- full-stack TypeScript: Express 5 / MongoDB API, React 19 / Vite / Tailwind 4 web app, plus a separate internal admin app and a VitePress docs site. A multi-package monorepo that shares its money, balance, budget and forecast math between the server and the client
- offline-first: local SQLite (WASM/OPFS in the browser, SQLCipher on desktop) with an outbox-based bidirectional sync engine, checkpointed pull and conflict handling. The desktop app signs in once and then runs offline
- native desktop app via Tauri v2 (Rust) from the same codebase, plus an installable PWA. Auto-updates run through signed GitHub releases
- multi-tenant workspaces with owner/editor/viewer roles. Row-level security is enforced in the query layer, so any unscoped Mongoose query throws
- 1,900+ automated tests at the last full-suite gate (1,179 backend, 744 frontend). Three full-project security audits produced 69 findings: all fixed
- **v1.0.4 is live**, and all four launch gates through production/GA are closed. It's in a private field test ahead of a wider public release. Subscription billing (entitlements, trial/downgrade rules, provider webhooks) and an internal admin console are built behind feature flags and aren't live
- licensed AGPL-3.0, open to feedback or collab contributions

**Upcoming (planned, not shipped):** two-factor auth (TOTP) for user accounts · Google sign-in · paid plans and a paid beta · later: automatic bank sync, native mobile apps, investment tracking


**Languages & Runtime**:
![TypeScript](https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logo=typescript)
![Rust](https://img.shields.io/badge/-Rust-black?style=for-the-badge&logo=rust)
![Node.js](https://img.shields.io/badge/-Node.js-black?style=for-the-badge&logo=node.js)

**Backend**:
![Express](https://img.shields.io/badge/-Express-black?style=for-the-badge&logo=express)
![MongoDB](https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logo=mongodb)
![Mongoose](https://img.shields.io/badge/-Mongoose-black?style=for-the-badge&logo=mongoose)
![JWT](https://img.shields.io/badge/-JWT-black?style=for-the-badge&logo=jsonwebtokens)
![AWS S3](https://img.shields.io/badge/-AWS_S3-black?style=for-the-badge&logo=amazonaws)
![Sentry](https://img.shields.io/badge/-Sentry-black?style=for-the-badge&logo=sentry)

**Frontend**:
![React](https://img.shields.io/badge/-React-black?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/-Vite-black?style=for-the-badge&logo=vite)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logo=tailwind-css)
![React Router](https://img.shields.io/badge/-React_Router-black?style=for-the-badge&logo=reactrouter)
![Recharts](https://img.shields.io/badge/-Recharts-black?style=for-the-badge&logo=recharts)

**Offline, Sync & Desktop**:
![SQLite](https://img.shields.io/badge/-SQLite-black?style=for-the-badge&logo=sqlite)
![Tauri](https://img.shields.io/badge/-Tauri-black?style=for-the-badge&logo=tauri)
![PWA](https://img.shields.io/badge/-PWA-black?style=for-the-badge&logo=pwa)

**Testing & Tooling**:
![Vitest](https://img.shields.io/badge/-Vitest-black?style=for-the-badge&logo=vitest)
![Testing Library](https://img.shields.io/badge/-Testing_Library-black?style=for-the-badge&logo=testing-library)
![ESLint](https://img.shields.io/badge/-ESLint-black?style=for-the-badge&logo=eslint)
![Docker](https://img.shields.io/badge/-Docker-black?style=for-the-badge&logo=docker)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-black?style=for-the-badge&logo=githubactions)
![VitePress](https://img.shields.io/badge/-VitePress-black?style=for-the-badge&logo=vitepress)
![Caddy](https://img.shields.io/badge/-Caddy-black?style=for-the-badge&logo=caddy)

**Architecture & Practices:** REST API design · modular backend with import-boundary rules enforced by an architecture test · JWT auth with rotating refresh tokens and token-version invalidation · role-based access control (RBAC) & multi-tenant workspaces · custom row-level security (RLS) plugin at the query layer · centralized error handling (typed `CustomError` + single error middleware) · offline-first sync (outbox pattern, checkpoint pagination, conflict resolution) · encryption at rest (PBKDF2 + AES-GCM in the browser / SQLCipher on desktop) · strict CSP, rate limiting and upload virus scanning · shared domain logic between server and client · test-driven development · CI/CD with dependency-audit gates (npm audit / cargo audit) and automated cross-platform desktop releases · VitePress documentation site

---

## 🛠 Skills

**Languages** </br>
![C](https://img.shields.io/badge/-C-black?style=for-the-badge&logo=c)
![C++](https://img.shields.io/badge/-C%2B%2B-black?style=for-the-badge&logo=cplusplus)
![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=for-the-badge&logo=javascript)
![TypeScript](https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logo=typescript)
![Python](https://img.shields.io/badge/-Python-black?style=for-the-badge&logo=python)
![Java](https://img.shields.io/badge/-Java-black?style=for-the-badge&logo=java)
![Rust](https://img.shields.io/badge/-Rust-black?style=for-the-badge&logo=rust)
![HTML5](https://img.shields.io/badge/-HTML5-black?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/-CSS3-black?style=for-the-badge&logo=css3)

**Frontend** </br>
![React](https://img.shields.io/badge/-React-black?style=for-the-badge&logo=react)
![Next.js](https://img.shields.io/badge/-Next.js-black?style=for-the-badge&logo=next.js)
![Vite](https://img.shields.io/badge/-Vite-black?style=for-the-badge&logo=vite)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logo=tailwind-css)

**Backend & Data** </br>
![Node.js](https://img.shields.io/badge/-Node.js-black?style=for-the-badge&logo=node.js)
![Express](https://img.shields.io/badge/-Express-black?style=for-the-badge&logo=express)
![MongoDB](https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logo=mongodb)
![SQLite](https://img.shields.io/badge/-SQLite-black?style=for-the-badge&logo=sqlite)

**Desktop & Tooling** </br>
![Tauri](https://img.shields.io/badge/-Tauri-black?style=for-the-badge&logo=tauri)
![Docker](https://img.shields.io/badge/-Docker-black?style=for-the-badge&logo=docker)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-black?style=for-the-badge&logo=githubactions)
![AWS](https://img.shields.io/badge/-AWS-black?style=for-the-badge&logo=amazonaws)

<!-- --- -->

<!-- ## 📊 GitHub Stats -->

<!-- ![](https://komarev.com/ghpvc/?username=RRI-Atharv37&color=blueviolet) -->
<!-- ![GitHub followers](https://img.shields.io/github/followers/RRI-Atharv37) -->

<!-- ![Atharv's GitHub stats](https://github-readme-stats.vercel.app/api?username=RRI-Atharv37&theme=neon&show_icons=true) -->

<!-- ![](https://github-readme-streak-stats.herokuapp.com/?user=RRI-Atharv37&theme=neon&hide_border=false) -->

<!-- ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=RRI-Atharv37&theme=neon&show_icons=true) -->

<!-- [![Atharv's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=RRI-Atharv37&theme=react-dark)](https://github.com/Ashutosh00710/github-readme-activity-graph) -->
