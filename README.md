# Hi there, I'm Triis 👋

<p align="left">
  <a href="https://kiemseo.site"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=34D399&background=05070600&vCenter=true&width=620&lines=Full-Stack+Engineer+%7C+Next.js+16+%7C+Golang;Application+Security+%26+Anti-Tamper+Architect;Anti-Cheat+%26+Fraud+Detection+Systems;Reverse+Engineering+%26+TLS+Fingerprinting+(JA3%2FJA4);High-Performance+Web+%26+Automation+Since+2025" alt="Typing SVG" /></a>
</p>

```json
{
  "name": "Triis",
  "role": "Full-Stack Engineer & Systems Security Researcher",
  "experience_since": 2025,
  "focus": "Architecting high-performance SaaS, distributed concurrency engines & advanced AppSec systems",
  "capabilities": [
    "High-Performance Web Architecture (Next.js 14-16, React 19, Core Web Vitals 100/100)",
    "Anti-Cheat & Fraud Detection Systems (Behavioral Biometrics, Silent Risk Scoring)",
    "High-Concurrency & Protocol Emulation (Golang Goroutines, CDP / Chromedp)",
    "Application Hardening & Anti-Tamper Defense (AST Flattening, Memory Zero-Trace)",
    "Reverse Engineering & Cryptographic Network Protocols (WASM, ECDH/AES-GCM, TLS JA3/JA4)"
  ],
  "location": "Vietnam"
}
```

---

### 🚀 Năng Lực & Kinh Nghiệm Kỹ Thuật (Core Capabilities & Experience)

#### 1. 🌐 Kiến Trúc Full-Stack SaaS & Tối Ưu Hiệu Năng Đỉnh Cao (Web Performance)
- **Năng lực cốt lõi:** Thiết kế và xây dựng các hệ thống Web SaaS quy mô lớn với **Next.js (App Router), React 19, TypeScript, Tailwind CSS, PostgreSQL và Prisma ORM**.
- **Tối ưu hóa Core Web Vitals:** Đạt điểm chuẩn tuyệt đối **100/100 Google Lighthouse** trên cả Mobile và Desktop thông qua tối ưu hóa LCP/FCP/CLS, tối ưu font variable, nén asset chuẩn WebP/AVIF và cấu hình bộ nhớ đệm đa tầng.
- **DevOps & Vận hành:** Thiết lập quy trình tự động hóa triển khai **Zero-Downtime Deployment** trên Linux VPS (Nginx Reverse Proxy, PM2 / Docker, SSL Certbot) cùng cơ chế Health-Check và tự động Rollback khi có sự cố.

#### 2. 🛡️ Thiết Kế Hệ Thống Anti-Cheat & Phát Hiện Gian Lận (Fraud Detection & Behavioral Biometrics)
- **Kiến trúc phòng thủ phân tách:** Xây dựng hệ thống phòng thủ đa tầng tách biệt hoàn toàn giữa tầng thu thập dữ liệu phía Client (Telemetry) và Decision Engine phía Server.
- **Sinh trắc học hành vi (Behavioral Biometrics):** Phân tích quỹ đạo di chuyển chuột và cảm ứng theo đường cong Bézier, đo động lực học gia tốc, kiểm tra tính toàn vẹn sự kiện (`isTrusted`) và phân tích độ lệch chuẩn thời gian thực thi (Timing Variance / StdDev Analysis) để phân biệt chính xác giữa người dùng thật và bot.
- **Thu thập vân tay phần cứng chuyên sâu:** Khai thác dấu vân tay thiết bị đa chiều (Deep Hardware, Canvas 2D, WebGL GPU unmasked renderer, AudioContext oscillator, float precision) kết hợp xác thực chữ ký phiên làm việc bằng HMAC.
- **Triết lý "Flag, not block":** Ứng dụng mô hình **Silent Risk Scoring** (tích lũy điểm rủi ro ngầm từ 0–100), cho phép người quản trị kiểm soát gian lận mà không để lộ cơ chế phát hiện cho đối tượng tấn công.

#### 3. ⚡ Tự Động Hóa Tải Cao & Giả Lập Môi Trường (High-Concurrency & Device Emulation)
- **Lập trình đồng thời quy mô lớn:** Xây dựng hệ thống xử lý phân tán bằng **Golang** (Goroutines, Channels), quản lý hàng chục nghìn kết nối đồng thời với mức tiêu thụ tài nguyên phần cứng tối thiểu.
- **Điều khiển trình duyệt sâu (CDP):** Điều phối và tự động hóa trình duyệt headless thông qua **Chrome DevTools Protocol (`chromedp`)** ở cấp độ thấp.
- **Giả lập môi trường phần cứng 100%:** Mô phỏng hoàn chỉnh thông số phần cứng thiết bị di động (Platform, Screen dimensions, Pixel ratio, GPU Renderer) và chuẩn hóa sự kiện cảm ứng W3C `TouchEvent` (`touchstart`, `touchend`, `pressure`), triệt tiêu các cờ nhận diện bot tự động.
- **Kiến trúc mạng Split-Routing:** Tách biệt thông minh giữa luồng xử lý trung gian qua pool Proxy xoay dân cư và luồng nộp kết quả qua IP phiên làm việc, loại bỏ hoàn toàn hiện tượng lệch địa chỉ IP.

#### 4. 🔒 Bảo Mật Ứng Dụng & Chống Dịch Ngược (Application Security & Anti-Tamper)
- **Kiến trúc bảo vệ 5 tầng:** Thiết kế lá chắn mã nguồn phân tách hoàn toàn Secret Token lên Edge Gateway (Cloudflare Workers); mã nguồn client chỉ chứa phân mảnh bit-shift byte shards được tái tạo động tại runtime.
- **AST Hardening:** Tự động hóa kỹ thuật làm rối luồng điều khiển (Control-Flow Flattening), mã hóa toàn bộ chuỗi ký tự bằng RC4, chèn dead code và tích hợp cơ chế tự hủy (Self-Defending) nếu mã bị can thiệp hoặc định dạng lại.
- **Phòng thủ Runtime & Silent Failure:** Thiết lập bẫy DevTools docking, bẫy getter console, kiểm tra hash tính toàn vẹn của hàm và kích hoạt cơ chế **Silent Failure** (âm thầm làm sai lệch dữ liệu tính toán thay vì báo lỗi để đánh lạc hướng kẻ tấn công).
- **Memory Zero-Trace:** Xử lý luồng nhị phân nhạy cảm trên bộ nhớ đệm RAM (`Uint8Array`) cô lập và tự động giải phóng ngay lập tức sau khi dùng để chống dump bộ nhớ.

#### 5. 🔍 Nghiên Cứu Bảo Mật, Reverse Engineering & Giao Thức Mạng (Security & Protocol Research)
- **Dịch ngược & Bóc tách mã:** Phân tích mã nguồn nhị phân WebAssembly (`.wasm`) và JavaScript làm rối mức độ cao.
- **Phân tích giao thức mật mã học:** Nghiên cứu và phân tích các luồng bắt tay mã hóa quân sự (ECDH Curve P-256, dẫn xuất khóa HKDF-SHA256, mã hóa gói tin AES-GCM).
- **Tùy biến tầng TLS (JA3/JA4):** Tùy biến mã nguồn TLS ClientHello, giả lập vân tay **JA3/JA4** phục vụ kiểm thử và vượt qua các bộ lọc WAF và Cloudflare Bot Management.
- **Lập trình mạng hiệu năng cao:** Ứng dụng kỹ thuật ghép kênh **HTTP/2 Multiplexing** và điều phối pool Proxy xoay tự động phục vụ kiểm thử sức chịu tải hệ thống.

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
