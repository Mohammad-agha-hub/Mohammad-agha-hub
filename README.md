<h1 align="center">Hi, I'm Mohammad Agha 👋</h1>

<p align="center">
  <b>Backend-Focused Full-Stack Developer</b><br>
  I design and build production web apps end-to-end — with my depth in APIs, data models, and the systems underneath.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohammad-agha-349a56388/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/Mohammad-agha-hub">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

##  About me

I'm a full-stack developer who's honest about where the depth is: **backend and systems work is my home turf**. I like schema design more than most people like anything, and I treat an API as a user interface whose users happen to be developers.

I've shipped several complete products — each one with a frontend I built myself — because a product isn't done until someone can use it. Right now I'm focused on the hard server-side problems: **background processing, data modeling, auth, and scalability**.

---

##  Experience

- **Software Engineer** — *Quantum Kurv* · 2025–Present
  Build and maintain web applications and internal systems for a UK software consultancy, owning projects from planning through launch and ongoing improvement.
- **Software Engineer** — *Arctesia* · 2024–2025
  Build and ship client web applications end-to-end at a digital-solutions agency — designing APIs and data models and implementing the frontends on top.
- **Online Instructor & Freelance Developer** — *Self-Employed* · 2024–Present
  Teach web development through project-based lessons, and ship freelance software/website work for local clients and small businesses.

---

##  Tech stack

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat&logo=react-query&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-DD2C00?style=flat&logo=redis&logoColor=white)

**Databases & ORMs**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat&logo=drizzle&logoColor=black)

**Also work with**
REST API design · Background jobs & schedulers (BullMQ, node-cron) · Rate limiting · Bulk CSV/Excel ingestion · PDF generation (Puppeteer) · Webhooks · Cloudinary · Docker · Git

---

##  Featured projects

###  Dial Loom — Bulk Email Marketing Platform
A queue-driven email engine: upload a list, send in throttled batches, and **auto-pause before you burn your sender reputation** — resumable even if a worker dies mid-send.
- **BullMQ + Redis** worker pipeline with configurable per-send delay and Redis-tracked auto-pause
- Database as the single source of truth for reliable resume; CSV/Excel ingestion with DB-level dedup
- Domains, open-tracking, analytics, templates, and Svix webhooks behind role-based JWT auth
- **Stack:** TypeScript · Express · BullMQ/Redis · MySQL (Drizzle) · React · TanStack Query
- 🔗 [Backend](https://github.com/Mohammad-agha-hub/Email_management_backend) · [Frontend](https://github.com/Mohammad-agha-hub/Email_marketing_frontend)

###  School Management System
A full student-information system: admissions, classes, exams, results, fees, and year-to-year promotions.
- **Concurrent BullMQ import worker** turning bulk CSVs into users, students, and admissions — with race-safe roll-number assignment
- **PDF report cards & fee receipts** generated with Puppeteer, behind a dedicated rate limiter
- Term-based admissions & promotions modeled in PostgreSQL
- **Stack:** Next.js · Express · PostgreSQL · BullMQ/Redis · Puppeteer
- 🔗 [Backend](https://github.com/Mohammad-agha-hub/school_backend) · [Frontend](https://github.com/Mohammad-agha-hub/school_frontend)

###  Al-Qaym Aid — Blood Donor Network
A nonprofit platform connecting donors, hospitals, and patients, with a multilingual admin CMS.
- Donation cooldowns enforced in Postgres with an **hourly node-cron job** that auto-restores availability
- Site content editable per language (English / Urdu / Farsi) as JSONB — no redeploy needed
- First-run admin bootstrap with bcrypt + httpOnly-cookie JWT auth
- **Stack:** Next.js · Express · PostgreSQL · JWT · Cloudinary
- 🔗 [Backend](https://github.com/Mohammad-agha-hub/Al-Qaym-Backend) · [Frontend](https://github.com/Mohammad-agha-hub/Al-Qaym-Aid-Frontend)

###  Quantum Kurv — Live Client Site + Custom CMS
A production business website with a self-serve blog CMS behind a private admin panel.
- JWT-authenticated admin over a **Prisma + MySQL** blog (SEO fields, categories, tags)
- Cloudinary uploads, Resend email, and reCAPTCHA-guarded forms
- **Stack:** Next.js · Prisma/MySQL · JWT · Cloudinary · Resend
- 🔗 [Live site](https://quantumkurv.co.uk) · [GitHub](https://github.com/quantumkurv1/Quantum-Kurv)

> Also shipped and live: **[Algrey Cleaning Services](https://algreyscleaningservices.co.uk)** (Next.js + MongoDB + custom blog CMS) and **[NSK School](https://nsk-school.vercel.app)** (Next.js marketing site).

---

##  Education & certifications

- **CS50x — Introduction to Computer Science** · HarvardX *(in progress)* — algorithms, data structures, C, Python, SQL, and web development. *(CS50 AI with Python up next.)*
- **Intermediate in Computer Science (ICS)** · KB Science College — 983/1100 (89.36%).

---

##  GitHub

<p align="center">
  <a href="https://github.com/Mohammad-agha-hub?tab=followers">
    <img src="https://img.shields.io/github/followers/Mohammad-agha-hub?label=Followers&style=social" alt="GitHub followers" />
  </a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=Mohammad-agha-hub&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>

---

##  Let's connect

- **LinkedIn:** [mohammad-agha](https://www.linkedin.com/in/mohammad-agha-349a56388/)
- **GitHub:** [Mohammad-agha-hub](https://github.com/Mohammad-agha-hub)

<p align="center"><i> Always learning, building, and improving.</i></p>
