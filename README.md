# Hi there, I'm Triis 👋

<p align="left">
  <a href="https://kiemseo.site"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=34D399&background=05070600&vCenter=true&width=580&lines=Full-Stack+Web+Engineer+%7C+Next.js+%7C+Golang;Application+Security+%26+Anti-Fraud+Architect;Building+fast%2C+secure+systems+since+2025" alt="Typing SVG" /></a>
</p>

```
Full-Stack Engineer who builds high-performance web systems
and knows how attackers think — so I build defenses that actually work.
```

---

### 🌐 Live Production Projects

**[kiemseo.site](https://kiemseo.site)** — Full-stack SEO & Analytics Platform  
`Next.js 16` · `React 19` · `TypeScript` · `PostgreSQL` · `Prisma ORM` · `Tailwind CSS v4`  
⚡ **Lighthouse 100/100** (Mobile & Desktop) · Zero-downtime deployment · Edge security via Cloudflare Workers

**[khoahocne.xyz](https://khoahocne.xyz)** — Education Platform (Course Sharing for High School Students)  
`Next.js 16` · `React 19` · `Prisma` · `SQLite` · `Google Auth` · `Framer Motion`  
Full SSR/SEO optimization · Dark mode · Gamification (ranks, confetti, leaderboard)

---

### 💻 What I Build

#### Full-Stack Web Architecture
- Architect production-grade SaaS with **Next.js App Router, React 19, TypeScript**
- Optimize to **100/100 Lighthouse** — variable fonts, WebP/AVIF, multi-layer caching
- Full DevOps pipeline: Linux VPS, Nginx reverse proxy, PM2, Docker, SSL auto-renewal, health checks & auto-rollback

#### High-Concurrency Systems (Golang)
- Build distributed automation engines handling **tens of thousands of concurrent connections** (Goroutines, Channels)
- Deep browser orchestration via **Chrome DevTools Protocol** (`chromedp`) at the socket level
- Cross-platform compilation: single codebase → Windows x64 + Android ARM64/ARMv7 binaries
- Network-layer split-routing architecture for session integrity & load testing

---

### 🛡️ Competitive Edge: Application Security & Anti-Fraud

> _A developer who understands how systems get broken builds systems that don't._

#### Anti-Cheat & Fraud Detection Engine
- Designed and implemented a **13-layer server-side anti-cheat engine** (~37K lines) with complete client/server separation
- **Behavioral biometrics**: mouse trajectory analysis (Bézier curves), touch dynamics, timing variance (StdDev), `isTrusted` verification
- Deep hardware fingerprinting: Canvas 2D, WebGL GPU renderer, AudioContext oscillator, float precision — with HMAC session binding
- **Silent Risk Scoring** (0–100): flag threats invisibly, never reveal detection logic to attackers
- Pre-Start Gate with server-rendered page tokens, math challenges, interaction data validation

#### Application Hardening & Anti-Tamper
- **5-layer source code protection** pipeline: secrets isolated to Cloudflare Workers Edge Gateway → client receives only runtime-assembled byte shards
- Automated AST obfuscation build system: Control-Flow Flattening, RC4 string encryption, dead code injection, self-defending code
- Runtime integrity: FNV-1a hash verification of critical functions, DevTools getter traps, **silent failure** (corrupt calculations silently instead of throwing errors)
- Memory zero-trace: sensitive data processed in isolated `Uint8Array` buffers, immediately zeroed after use

#### Reverse Engineering & Protocol Security Research
- Reverse-engineered production WebAssembly (`.wasm`) anti-cheat modules and heavily obfuscated JavaScript
- Analyzed military-grade cryptographic handshakes: ECDH Curve P-256, HKDF-SHA256 key derivation, AES-GCM encrypted payloads
- Custom TLS ClientHello fingerprinting (JA3/JA4) — built from raw `net/tls` sockets with custom cipher suites, HPACK encoding, HTTP/2 frame-level control
- Anti-reverse-engineering for compiled Go binaries: VM detection, debugger traps, control-flow flattening, integrity checksums

---

### 🛠️ Tech Stack

#### Languages
<p align="left">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Golang" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
</p>

#### Frontend & Web Performance
<p align="left">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" alt="Framer Motion" />
  <img src="https://img.shields.io/badge/Lighthouse_100-008080?style=for-the-badge&logo=lighthouse&logoColor=white" alt="Lighthouse" />
</p>

#### Backend & Infrastructure
<p align="left">
  <img src="https://img.shields.io/badge/Golang-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white" alt="Prisma" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white" alt="Cloudflare" />
</p>

#### Security & Research
<p align="left">
  <img src="https://img.shields.io/badge/Anti--Fraud_Engine-8B0000?style=for-the-badge&logo=shield&logoColor=white" alt="Anti-Fraud" />
  <img src="https://img.shields.io/badge/AppSec_&_Hardening-DC143C?style=for-the-badge&logo=securityscorecard&logoColor=white" alt="AppSec" />
  <img src="https://img.shields.io/badge/TLS_JA3%2FJA4-4A154B?style=for-the-badge&logo=wireshark&logoColor=white" alt="TLS" />
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=portswigger&logoColor=white" alt="Burp Suite" />
  <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=for-the-badge&logo=webassembly&logoColor=white" alt="WASM" />
  <img src="https://img.shields.io/badge/Chromedp_CDP-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Chromedp" />
</p>
