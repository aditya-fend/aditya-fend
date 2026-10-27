<div align="center">

![Aditya Fend](https://readme-typing-svg.demolab.com?font=Inter&weight=700&size=32&pause=1000&center=true&vCenter=true&width=500&lines=Hi%2C+I'm+Aditya+Fend+%F0%9F%91%8B;Full+Stack+Web+Developer;Backend+%26+System+Architecture)

**I build web applications from start to finish — database, API, frontend, and deployment.**

Computer Science student & Fullstack Software Engineer based in Grobogan, Central Java.

[![Portfolio](https://img.shields.io/badge/Portfolio-aditya--fend.vercel.app-black?style=for-the-badge&logo=vercel)](https://aditya-fend.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-aditya--fend-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/aditya-fend)
[![GitHub](https://img.shields.io/badge/GitHub-aditya--fend-181717?style=for-the-badge&logo=github)](https://github.com/aditya-fend)
[![Email](https://img.shields.io/badge/Email-adityafend@gmail.com-D14836?style=for-the-badge&logo=gmail)](mailto:adityafend@gmail.com)

🟢 **Open to Opportunities** — Full-Time

</div>

---

### 🧑‍💻 About Me

- 🎓 Computer Science student who enjoys building web apps end-to-end
- 💻 Strongest on the backend side — building REST APIs with **Golang**, **Python (FastAPI)**, and **Node.js**, and designing PostgreSQL / MySQL databases
- 🧠 My latest project is **Nalar**, an AI analytics workspace for F&B distributor operations teams. Gemini only plans the query; PostgreSQL does the math, so the model never writes SQL. Built with Python, FastAPI, PostgreSQL, and Next.js.
- 💳 **NilaiKita** is a paid learning platform for investment education. I designed and built it from scratch: the backend API in Golang, the database structure, the subscription payment flow, and the frontend. The part I enjoyed most was making payments reliable — every payment confirmation is verified with a digital signature, and a payment that arrives twice can never activate a subscription twice.
- 🔐 In another project I worked on encrypted patient records for a hospital system, where every change is recorded in an audit log that cannot be edited
- 🤖 I use AI coding tools every day to help me write code, track down bugs, and find solutions
- 📝 Writing technical articles on Medium

---

### 🛠️ Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,go,python,fastapi,postgres,mysql,solidity,tailwind,prisma,supabase,git,vercel,docker&perline=13" alt="Tech Stack" />
</div>

| Category | Skills |
|---|---|
| **Fullstack & Core** | Golang, Python, TypeScript, JavaScript, React & Next.js, Node.js, FastAPI, Tailwind CSS, REST API Design, Figma Slicing, OOP |
| **Database & Backend** | PostgreSQL, MySQL, Prisma, SQLAlchemy, Database Structure Design, Query Optimization & Indexing, Data Migration, Raw SQL (tanpa ORM) |
| **Security & Auth** | Password Hashing, Webhook Signature Verification, Data Encryption, Role-Based Access Control, Input Validation, Audit Logging |
| **Payments & Reliability** | Idempotency Keys, Row Locking, Signed Webhooks, Subscription State Machines, Rate Limiting |
| **Quality & Workflow** | Unit & Integration Testing, End-to-End Browser Testing, Docker & CI/CD, Agile/Scrum, Git/GitHub, Vercel & Google Cloud Run |
| **AI & Web3** | Gemini / OpenAI API, Prompt Engineering, AI Coding Agents, Solidity, wagmi + viem, Supabase |

---

### 🚀 Featured Projects

#### 1. Nalar — AI Analytics Workspace for F&B Distributors
> An analytics workspace for operations teams at F&B distributors. You ask a business question in plain language; Gemini only turns it into a structured query plan, PostgreSQL calculates the numbers, and the screen shows the answer, a chart, and a calculation trail you can inspect. The model never writes SQL — the plan is validated and compiled into parameterized queries. Login uses Argon2id with server-side sessions, permissions are checked on every request, and every question is recorded in an audit history.

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `Next.js` `TypeScript` `Tailwind CSS` `Google Gemini API` `Argon2id` `Docker` `Railway` `Neon` `Vercel`

[🔴 Live Demo](https://nalar-aditya-fend.vercel.app) · `2026` · *AI Full-Stack Engineer*

---

#### 2. NilaiKita — Platform Belajar Investasi Berlangganan
> A paid platform for learning about investing, with three kinds of users: members, coaches, and admins. The interesting part was the payment flow — a subscription moves through statuses (trial, active, expired, cancelled) that are only confirmed through signed webhooks. Because a webhook can arrive more than once, I added an idempotency key and row locking inside a single transaction, so a duplicate delivery can never activate a subscription twice. Prices are decided on the server, never by the browser. The frontend talks to a small server layer, so the Go API and its secrets are never exposed to the browser.

`Go` `chi` `pgx` `PostgreSQL` `Next.js` `TypeScript` `Tailwind CSS` `Vitest` `Playwright` `Docker` `Railway` `Neon` `Vercel`

[🔴 Live Demo](https://nilai-kita-aditya-fend.vercel.app) · `2026` · *Fullstack & Backend Engineer*

---

#### 3. KlinikForm SIMRS — Rekam Medis Elektronik
> A hospital information system for a regulated healthcare domain. Form templates are versioned, so publishing a new form never changes records that were already collected. Patient details are encrypted, and every change is written to an audit log that cannot be edited, to meet Indonesia's health data regulation (Permenkes No. 24/2022). Connects to the national health system (SatuSehat FHIR R4) and BPJS VClaim.

`PHP` `Laravel` `PostgreSQL` `Encryption` `Tailwind CSS` `Docker`

[💻 GitHub](https://github.com/aditya-fend/sim-rs) · `2026` · *Full Stack & Systems Engineer*

---

#### 4. WorkSpace Pro — Task & Workflow Management System
> A Kanban board that turns written requirements into developer subtasks with AI. Includes role-based access control for admins and developers, a relational database design, and a responsive interface.

`Next.js` `TypeScript` `Prisma` `MySQL` `Tailwind CSS` `Gemini API`

[🔴 Live Demo](https://workspace-pro-aditya-fend.vercel.app) · `2026` · *Fullstack Software Engineer*

---

#### 5. War Room AI — Analitik Keuangan UMKM
> Helps small businesses see their cash situation clearly through financial analytics, document reading (OCR/CSV), and AI-based recommendations for business decisions.

`Next.js` `React` `TypeScript` `Tailwind CSS` `OCR / CSV` `Gemini API`

[🔴 Live Demo](https://ai-war-room-aditya-fend.vercel.app) · `2026` · *AI Full-Stack Developer*

---

### ✍️ Technical Writings

- 📄 [How We Built War Room AI: Helping MSMEs See Their Cash Situation](https://medium.com/@adityaportfolio3/how-we-built-war-room-ai-eliminating-the-msme-cash-flow-blind-spot-using-gemini-multi-agent-ca932870361e) — `AI` `Finance` · 4 min

---

### 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=aditya-fend&show_icons=true&theme=gotham&hide_border=true&count_private=true" height="150" alt="stats" />
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=aditya-fend&layout=compact&theme=gotham&hide_border=true" height="150" alt="langs" />
</div>

---

### 📬 Contact

<div align="center">

**Let's build something useful together.**

[![Email](https://img.shields.io/badge/adityafend@gmail.com-D14836?style=flat-square&logo=gmail)](mailto:adityafend@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/aditya-fend)
[![Instagram](https://img.shields.io/badge/@adtyathree-E4405F?style=flat-square&logo=instagram)](https://www.instagram.com/adtyathree)
[![Medium](https://img.shields.io/badge/@adityaportfolio3-000000?style=flat-square&logo=medium)](https://medium.com/@adityaportfolio3)

*Usually responds within 24 hours.*

</div>
