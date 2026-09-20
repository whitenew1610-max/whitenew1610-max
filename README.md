# Hi there, I'm Triis 👋

<p align="left">
  <a href="https://kiemseo.site"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=34D399&background=05070600&vCenter=true&width=620&lines=Full-Stack+Engineer+%7C+Next.js+16+%7C+Golang;Application+Security+%26+Anti-Tamper+Architect;Anti-Cheat+%26+Fraud+Detection+Systems+(16+Layers);Reverse+Engineering+%26+TLS+Fingerprinting+(JA3%2FJA4);High-Performance+Web+%26+Automation+Since+2025" alt="Typing SVG" /></a>
</p>

```json
{
  "name": "Triis",
  "role": "Full-Stack Engineer & Systems Security Researcher",
  "experience": "Architecting production platforms, high-concurrency systems & security engines since 2025",
  "specialties": [
    "High-Performance Web (Next.js 14-16, React 19, Core Web Vitals 100/100)",
    "Anti-Cheat & Fraud Detection Architecture (16-Layer Defense Pipeline)",
    "Application Security & Anti-Tamper (5-Layer Shield, AST Hardening, Memory Zero-Trace)",
    "High-Concurrency & Automation (Golang Goroutines, CDP / Chromedp, Proxy Rotation)",
    "Reverse Engineering (WebAssembly, ECDH/AES-GCM Handshakes, TLS JA3/JA4)"
  ],
  "location": "Vietnam"
}
```

---

### 🚀 Giới thiệu (About Me)
- 👨‍💻 **Kỹ sư Full-Stack & Nghiên cứu Bảo mật (AppSec)** với kinh nghiệm thực chiến chuyên sâu trong việc thiết kế các hệ thống SaaS quy mô, công cụ tự động hóa tải cao bằng **Golang** và các giải pháp bảo vệ mã nguồn/chống gian lận đa tầng từ năm **2025**.
- ⚡ **Thế mạnh kỹ thuật nổi bật:**
  - **Tối ưu hóa hiệu năng đỉnh cao:** Tối ưu hóa website đạt điểm tuyệt đối **100/100 Google Lighthouse** (Mobile & Desktop), tối ưu LCP/FCP/CLS, tối ưu font variable, WebP/AVIF và cấu hình bộ nhớ đệm đa tầng.
  - **Kiến trúc Anti-Cheat & Chống Gian Lận (16 Layers):** Thiết kế hệ thống phòng thủ toàn diện từ Pre-Start Gate, URL Vault, HMAC tokens, phân tích quỹ đạo chuột Bézier, đo độ lệch chuẩn thời gian (StdDev) đến chấm điểm rủi ro ngầm (Silent Risk Scoring 0–100).
  - **Bảo mật ứng dụng & Chống dịch ngược (Anti-Tamper):** Xây dựng lá chắn 5 lớp bảo vệ mã nguồn (Cloudflare Worker token isolation, AST Control-Flow Flattening, RC4 encryption, DevTools docking traps, Silent Failure và Memory Zero-Trace trong RAM).
  - **Hệ thống tải cao & Tự động hóa (High Concurrency):** Xử lý luồng mạng phân tán bằng **Golang** (Goroutines/Channels, `chromedp`), kỹ thuật Split-Routing vượt qua cơ chế đối chiếu IP, giả lập phần cứng điện thoại 100% (Samsung S24 Ultra, W3C TouchEvent).
  - **Nghiên cứu Mạng & Reverse Engineering:** Bóc tách WebAssembly (`.wasm`), cơ chế mật mã học ECDH P-256 / AES-GCM, tùy biến TLS ClientHello giả lập vân tay **JA3/JA4** vượt qua Cloudflare/WAF.
  - **DevOps & Vận hành:** Quản trị Linux VPS, Nginx Reverse Proxy, SSL Certbot, quy trình **Zero-Downtime Deployment** với PM2 / Docker và cơ chế tự phục hồi (Health Check Rollback).

---

### 🏆 Các Dự Án & Giải Pháp Kỹ Thuật Nổi Bật (Featured Projects)

#### 1. 🌐 Kiếm Seo — High-Performance Traffic & SEO Platform
> Nền tảng SaaS tăng trưởng traffic thật và tối ưu hóa thứ hạng SEO chuẩn Google Analytics 4.
- **Tech Stack:** Next.js 14, TypeScript, Tailwind CSS, PostgreSQL, Prisma ORM, Linux VPS, Nginx, PM2.
- **Điểm nhấn kiến trúc:**
  - Đạt điểm chuẩn hiệu năng tuyệt đối **100/100 Google Lighthouse** trên cả thiết bị di động và máy tính.
  - Hệ thống lọc bot ảo & click fraud thông minh đạt độ chính xác **99.82%**.
  - Pipeline tự động hóa triển khai **Zero-Downtime Deployment** với cơ chế Atomic Swap và tự phục hồi (Health Check Rollback).

#### 2. 🛡️ Distributed Anti-Cheat & Anti-Fraud Engine (16-Layer Defense)
> Hệ thống phòng thủ toàn diện ngăn chặn tự động hóa trái phép, click ảo và gian lận phần thưởng.
- **Tech Stack:** TypeScript, Next.js, Web Crypto API, HMAC, Hardware Fingerprinting.
- **Điểm nhấn kiến trúc:**
  - **Pre-Start Gate:** Chặn cứng script click giả qua `isTrusted`, kiểm tra tương tác thực (`clickX/Y`, `windowWidth/Height`), PageToken động hạn 10 phút và thử thách toán học ngẫu nhiên.
  - **URL Vault:** Niêm phong link đích phía server, client chỉ có thể lấy qua `/api/task/reveal` sau debounce 200ms, sử dụng 1 lần và tự hủy sau 5 phút.
  - **13+ Lớp Callback Verification:** Xác thực chữ ký số HMAC, IP Consistency, IP Intelligence (phát hiện VPN, Proxy, Tor qua `proxycheck.io`/`ip-api.com`), vân tay thiết bị (Canvas 2D, WebGL GPU, AudioContext, Math precision), cờ Marathon (cày 4h-14h liên tục), quỹ đạo chuột Bézier và phân tích độ lệch chuẩn thời gian callback (StdDev < 3s = timer bot).
  - **Triết lý "Flag, not block":** Gắn cờ ngầm tích lũy điểm `Risk Score` (0-100) để quản trị viên duyệt lúc rút tiền, ngăn đối tượng tấn công nhận biết cơ chế phát hiện.

#### 3. ⚡ High-Concurrency Automation & Anti-Bot Bypass Core
> Bộ công cụ tự động hóa tải cao bằng Golang, nghiên cứu cơ chế phòng thủ và giả lập môi trường thực tế.
- **Tech Stack:** Golang, Goroutines, Channels, `chromedp` (Chrome DevTools Protocol), Python, Reverse Engineering.
- **Điểm nhấn kiến trúc:**
  - **Bóc tách Reverse Engineering:** Giải mã module bảo vệ JavaScript obfuscated và WebAssembly (`.wasm`), phân tích cơ chế bắt tay mật mã ECDH P-256, dẫn xuất khóa HKDF-SHA256 và gói tin mã hóa AES-GCM (`X-AC-Token`).
  - **Giả lập điện thoại 100% (Mobile Spoofing):** Giả lập hoàn hảo thiết bị Samsung Galaxy S24 Ultra (`SM-S928B`), Android 14, GPU Adreno 750, đồng bộ `navigator.platform` (`Linux armv8l`) với `userAgentData`, màn hình `412x915 portrait-primary`, `maxTouchPoints: 5` và phát sinh sự kiện cảm ứng chuẩn W3C `TouchEvent` (`touchstart`, `touchend`, `pressure: 1.0`).
  - **Kiến trúc Split-Routing:** Tách biệt luồng xử lý shortlink qua pool Proxy xoay dân cư trong nhân Go, đồng thời chuyển tiếp link đích về trình duyệt thật để nộp bằng IP gốc $\rightarrow$ Triệt tiêu 100% lỗi lệch IP.

#### 4. 🔒 Multi-Layer Application Hardening & Anti-Tamper Shield (5-Layer Defense)
> Hệ thống lá chắn 5 tầng bảo vệ runtime logic, chống dịch ngược và ngăn chặn can thiệp mã nguồn.
- **Tech Stack:** JavaScript, TypeScript, WebAssembly (WASM), Cloudflare Workers, Cryptography.
- **Điểm nhấn kiến trúc:**
  - **Layer 1 - Token Isolation:** Toàn bộ API token nhạy cảm được đưa lên Cloudflare Worker Gateway; client chỉ chứa mã phân mảnh bit-shift byte shards tái tạo động theo session.
  - **Layer 2 - AST Hardening:** Tự động hóa Control-Flow Flattening, mã hóa toàn bộ chuỗi ký tự bằng RC4, cơ chế tự hủy (Self-Defending - code tự hỏng nếu bị format) và chèn dead code.
  - **Layer 3 - Runtime Integrity & Anti-Debug:** Đo lường độ trễ thực thi `performance.now()`, bẫy DevTools docking, bẫy getter console, kiểm tra hash tính toàn vẹn của hàm. Kích hoạt **Silent Failure** (làm sai lệch kết quả ngầm mà không báo lỗi) khi bị can thiệp.
  - **Layer 4 - Memory Zero-Trace:** Dữ liệu nhị phân xử lý qua `Uint8Array` cô lập trong RAM, hủy ngay lập tức sau khi dùng xong để chống dump bộ nhớ.
  - **Layer 5 - Context & Domain Lock:** Giới hạn chặt chẽ domain thực thi, từ chối chạy trên sandbox lạ.

#### 5. 🛰️ TLS Fingerprinting & Network Traffic Lab
> Công cụ nghiên cứu giao thức mạng, tùy biến tầng TLS và kiểm thử sức chịu tải hệ thống.
- **Tech Stack:** Node.js, TLS/SSL, HTTP/2 Multiplexing, Network Socket Programming.
- **Điểm nhấn kiến trúc:**
  - Tùy biến mã nguồn TLS ClientHello, giả lập vân tay **JA3/JA4** nhằm vượt qua các bộ lọc WAF và Cloudflare Bot Management.
  - Hệ thống tự động thu thập, kiểm tra độ trễ và phân loại chất lượng proxy xoay dân cư/datacenter.
  - Kỹ thuật ghép kênh HTTP/2 Multiplexing phục vụ kiểm thử sức chịu tải hệ thống ở quy mô lớn.

#### 6. 📚 Modern E-Learning & Course Platform
> Nền tảng học trực tuyến và quản lý bản quyền phần mềm hiện đại.
- **Tech Stack:** Next.js 16, React 19, Tailwind CSS v4, Prisma ORM, SQLite / PostgreSQL, Python Automation.
- **Điểm nhấn kiến trúc:**
  - Hệ thống xác thực và quản lý bản quyền thông qua cơ chế mã kích hoạt (Redeem Code Licensing Engine).
  - Giao diện người dùng hiện đại, tương tác mượt mà với Framer Motion, Radix UI và Phosphor Icons.
  - Tự động hóa quy trình đóng gói và triển khai lên máy chủ Linux VPS (`deploy.py`, `restart_vps.py`).

---

### 🛠️ Kỹ năng & Công nghệ (Tech Stack)

#### Ngôn ngữ lập trình (Languages)
<p align="left">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Golang" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=for-the-badge&logo=webassembly&logoColor=white" alt="WebAssembly" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
</p>

#### Frontend & Hiệu năng Web (Web Performance)
<p align="left">
  <img src="https://img.shields.io/badge/Next.js_14--16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Core_Web_Vitals-00C49F?style=for-the-badge&logo=google&logoColor=white" alt="Core Web Vitals" />
  <img src="https://img.shields.io/badge/Lighthouse_100-008080?style=for-the-badge&logo=lighthouse&logoColor=white" alt="Lighthouse 100" />
</p>

#### Backend, Cơ sở dữ liệu & Tải cao (Backend & Concurrency)
<p align="left">
  <img src="https://img.shields.io/badge/Golang_Goroutines-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Goroutines" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Prisma_ORM-3982CE?style=for-the-badge&logo=Prisma&logoColor=white" alt="Prisma" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Chromedp_CDP-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Chromedp" />
</p>

#### Bảo mật, Mạng & DevOps (Security, Network & Infrastructure)
<p align="left">
  <img src="https://img.shields.io/badge/Anti--Cheat_%26_Fraud_Detection-8B0000?style=for-the-badge&logo=shield&logoColor=white" alt="Anti-Cheat" />
  <img src="https://img.shields.io/badge/AppSec_%26_Anti--Tamper-DC143C?style=for-the-badge&logo=securityscorecard&logoColor=white" alt="AppSec" />
  <img src="https://img.shields.io/badge/TLS_JA3%2FJA4-4A154B?style=for-the-badge&logo=wireshark&logoColor=white" alt="TLS" />
  <img src="https://img.shields.io/badge/Linux_VPS-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/PM2_Zero--Downtime-2B037A?style=for-the-badge&logo=pm2&logoColor=white" alt="PM2" />
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=portswigger&logoColor=white" alt="Burp Suite" />
</p>

---

### 📊 Thống kê GitHub (GitHub Stats)
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=whitenew1610-max&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
  <br />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=whitenew1610-max&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

