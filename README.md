<h1 align="center">Hi, I'm Omar Aydah 👋</h1>
<p align="center">Software Development Engineer — backend, data & infrastructure</p>

<p align="center">
  <a href="https://bridge-eight-lemon.vercel.app"><img src="https://img.shields.io/badge/Live%20Demo-Bridge-000000?style=flat-square" /></a>
  <a href="https://www.linkedin.com/in/omar-aydah-"><img src="https://img.shields.io/badge/LinkedIn-Connect-000000?style=flat-square" /></a>
</p>

---

### About

I'm a CS student at Westfield State University and a backend engineer who likes building the parts of a system that have to be right — auth, data pipelines, and the integrations that quietly break everything if they're wrong. Right now that means shipping backend infrastructure for an AI research-integrity platform used by real researchers, and before that it meant untangling why a mentorship platform's OAuth flow was silently failing in production.

Outside of code: I'm a Residential Assistant overseeing a 280-student community, and a peer counselor/ambassador with my school's LEAD Scholars Program, mentoring incoming students through their transition to college. Bilingual in Arabic and English.

- 🔭 Currently building backend infrastructure for **RIGORA**, an AI-powered research integrity platform (Virginia Tech × Gates Foundation) — private/client repo
- 🧱 Shipped: **Bridge**, a mentorship marketplace — backend API, auth/session data layer, and OAuth/scheduling integration
- 🌱 Publishing more personal projects soon — see below
- ⚡ I like systems that are easy to trust: locked-down auth, server-verified payments, tests that catch real bugs

---

### Featured work

**RIGORA — Research Integrity Platform**
An AI-powered platform, built with Virginia Tech faculty and funded by the Gates Foundation, that flags questionable research practices in academic literature before they can shape funding decisions. I own the backend end-to-end: a search pipeline that translates a single query across 5 academic databases (PubMed, Crossref, OpenAlex, Semantic Scholar, Google Scholar) — each with its own query syntax — surfacing 900,000+ deduplicated candidate records that get narrowed to a targeted reference corpus, plus citation graph traversal and a 5-class misconduct classification pipeline powering automated report generation. Rebuilt the platform's statistical layer (bootstrap confidence intervals, power analysis) to fix a production accuracy bug, cutting query latency 43% and scaling test coverage 3.4x.
*Repo is private (client/company codebase) — no public link available.*
`Python` `FastAPI` `Pydantic` `scipy` `rapidfuzz`

**[Bridge](https://bridge-eight-lemon.vercel.app) — Mentorship Platform**
Paid mentorship marketplace connecting job seekers with vetted industry mentors: booking, Stripe payments, Calendly scheduling, AI-guided intake, and live video sessions. My contribution: backend API and integration layer — session/mentor data services, and resolving a blocking Google OAuth/Calendar authentication issue to enable reliable production scheduling. Built collaboratively with a teammate over two development sprints.
[Live demo →](https://bridge-eight-lemon.vercel.app)
`Next.js` `React` `Supabase` `Stripe` `Calendly`

---

### More on the way

Currently building out a few more projects to publish here — check back soon.

| Project | Status |
|---|---|
| 🔜 TBD | In progress |
| 🔜 TBD | Planned |

---

### Tech I work with

**Languages**
`Python` `SQL / MySQL` `R` `Java` `TypeScript` `JavaScript` `HTML/CSS`

**Frameworks & Libraries**
`FastAPI` `Pydantic` `React` `Next.js` `NumPy` `Pandas` `Tailwind CSS` `scipy` `rapidfuzz` `Axios` `BeautifulSoup` `Zod` `shadcn/ui`

**Tools & Platforms**
`Git` `GitHub` `Docker` `Supabase` `PostgreSQL` `REST APIs` `Vite` `pytest` `Postman` `Vercel` `CI/CD` `Linux/Bash`

---

<p align="center">
  <a href="https://bridge-eight-lemon.vercel.app">Bridge demo</a> · <a href="https://www.linkedin.com/in/omar-aydah-">LinkedIn</a>
</p>
