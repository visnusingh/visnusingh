<h1 align="center">Visnu Singh</h1>

<p align="center">
  <b>Full Stack Engineer</b> · Node.js, backend-leaning · London, UK · Right to work in the UK · Open to relocation
</p>

<p align="center">
  <a href="https://visnusingh.com"><img src="https://img.shields.io/badge/Portfolio-visnusingh.com-0B6E62?style=for-the-badge" alt="Portfolio" /></a>
  <a href="https://visnusingh.com/resume"><img src="https://img.shields.io/badge/CV-read%20or%20download-0B6E62?style=for-the-badge" alt="CV" /></a>
  <a href="https://www.linkedin.com/in/visnusingh"><img src="https://img.shields.io/badge/LinkedIn-visnusingh-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="mailto:contact@visnusingh.com"><img src="https://img.shields.io/badge/Email-contact%40visnusingh.com-111111?style=for-the-badge" alt="Email" /></a>
</p>

Full stack engineer, backend-leaning. I built and run two booking systems in production for UK businesses as the sole engineer, from first commit to live customers to day-to-day operation. Node.js and Express REST APIs, Redis caching, authentication (OAuth 2.0, JWT, role-based access), email automation, Docker and GitHub Actions CI. AI-native workflow with Claude Code: spec first, every diff reviewed, CI gates on every push. Looking for a backend or full stack role in a product team.

## In production

| Status | Platform | What it does | Role | When |
| --- | --- | --- | --- | --- |
| 🟢 Live | [greggmaurice.co.uk](https://greggmaurice.co.uk) | Airport parking bookings for Heathrow & Gatwick | Full Stack Engineer, sole engineer | Nov 2025 – now |
| 🟢 Live | [teknifyltd.com](https://teknifyltd.com) | Store discovery & bookings for a retail business | Freelance Full Stack Engineer | Aug – Oct 2025 |

## Experience

### Full Stack Engineer · [Gregg Maurice Parking](https://greggmaurice.co.uk), London · Nov 2025 – present

Independent airport parking operator for Heathrow and Gatwick · sole engineer.

- Built the customer booking site and admin system end to end and run it in production. Node.js, Express, React, Tailwind CSS, Redis, GitHub Actions.
- Booking flow: search by terminal and dates, quote, book, amend and extend, confirmation emails; per-terminal SEO landing pages for Heathrow T2–T5 and Gatwick North and South.
- Admin panel with role-based access, protected routes and inactivity logout: booking management, promo codes, supplier commission reports with per-supplier email dispatch, CSV export.
- Replaced manual data entry with automated pipelines: IMAP parsing of supplier emails into a booking import queue, Nodemailer notifications on booking events.
- Redis caching on repeated supplier and booking lookups, taking the hot admin queries off the database.
- GitHub Actions CI on every push: lint, build validation and deployment checks before anything reaches production.

### Freelance Full Stack Engineer · [TEKNIFY LTD](https://teknifyltd.com) · Aug 2025 – Oct 2025

Store discovery and booking site for a retail business, delivered solo from backend to deployment in three months.

- Designed and shipped the REST API (Node.js, Express) and admin for store discovery, bookings and dynamic site configuration; SQLite and Firebase for data, Dockerised deployment.
- Nearest-store search: browser geolocation, Haversine distance, ETA logic and the Google Maps API.
- Booking confirmations with branded SMTP templates, retry-safe states and delivery logging, so failed sends are visible and retried.
- Google OAuth and protected routes for admin operations; Redis caching on repeated requests.

## Projects

- **[visnusingh.com](https://visnusingh.com)** · hand-built site on Firebase Hosting behind Cloudflare; Cloud Functions contact form with Turnstile, Firestore-backed rate limiting and SMTP delivery, under a strict Content Security Policy.
- **[Smart Security Camera](https://github.com/visnusingh/Smart-Security-Camera)** · university project (Python, Flask, OpenCV, SQLite, AWS EC2): motion detection by frame differencing, live stream and incident log, deployed on EC2.
- **[Online Learning Platform](https://github.com/visnusingh/Online-Learning-Platform)** · university project (Node.js, Express, MySQL, JWT, Multer, Cloudflare Turnstile): role-based sign-up and login for students and professors, video upload, course search; MySQL schema built by hand.
- **IBM × Barclays Cyber Security Hackathon, Oct 2024** · top 10 of 50 teams; four-person team building a real-time intrusion-detection prototype in Python.

## Stack

**Backend**<br>
<img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white" alt="Express.js" />
<img src="https://img.shields.io/badge/REST%20API%20design-0B6E62" alt="REST API design" />
<img src="https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white" alt="JWT" />
<img src="https://img.shields.io/badge/OAuth%202.0%20(Google)-0B6E62" alt="OAuth 2.0 (Google)" />
<img src="https://img.shields.io/badge/Role--based%20access%20control-0B6E62" alt="Role-based access control" />
<img src="https://img.shields.io/badge/Nodemailer%20%26%20SMTP-0B6E62" alt="Nodemailer and SMTP" />
<img src="https://img.shields.io/badge/IMAP%20processing-0B6E62" alt="IMAP processing" />
<img src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white" alt="Flask" />

**Data**<br>
<img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white" alt="Redis" />
<img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white" alt="MySQL" />
<img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white" alt="SQLite" />
<img src="https://img.shields.io/badge/Firestore-FFCA28?logo=firebase&logoColor=black" alt="Firestore" />

**Infrastructure**<br>
<img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white" alt="GitHub Actions" />
<img src="https://img.shields.io/badge/AWS%20EC2-232F3E" alt="AWS EC2" />
<img src="https://img.shields.io/badge/Firebase%20Hosting%20%26%20Cloud%20Functions-FFCA28?logo=firebase&logoColor=black" alt="Firebase Hosting and Cloud Functions" />
<img src="https://img.shields.io/badge/Cloudflare%20(Turnstile%2C%20CSP)-F38020?logo=cloudflare&logoColor=white" alt="Cloudflare (Turnstile, CSP)" />
<img src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black" alt="Linux" />

**Frontend**<br>
<img src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
<img src="https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white" alt="Vite" />
<img src="https://img.shields.io/badge/HTML-E34F26?logo=html5&logoColor=white" alt="HTML" />
<img src="https://img.shields.io/badge/CSS-663399?logo=css&logoColor=white" alt="CSS" />

**Languages**<br>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/SQL-4479A1" alt="SQL" />

**Ways of working**<br>
<img src="https://img.shields.io/badge/AI--native%20development%20with%20Claude%20Code-D97757?logo=claude&logoColor=white" alt="AI-native development with Claude Code" />
<img src="https://img.shields.io/badge/Spec%20first-0B6E62" alt="Spec first" />
<img src="https://img.shields.io/badge/Reviewed%20diffs-0B6E62" alt="Reviewed diffs" />
<img src="https://img.shields.io/badge/CI%20gates-0B6E62" alt="CI gates" />
<img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" alt="Git" />

## Education & certifications

- **BSc Computer Science** · University of Northampton, UK · 2024 – 2025. Final-year top-up as a transfer student; years 1–2 at Assumption University, Thailand (2021 – 2024).
- **Microsoft Certified: Azure Fundamentals** · Microsoft · Jun 2026 · [Verify on Credly](https://www.credly.com/badges/981500f7-20e6-4ba4-9d6b-5440d5379fee)
- **AWS Academy Cloud Foundations** · Amazon Web Services · Feb 2024 · [Verify on Credly](https://www.credly.com/badges/66a67ad5-75c8-4ea5-a4c8-fcbbd377084d)

Languages: English, Hindi, Thai.

## Contributions

<p align="center">
  <img src="https://ghchart.rshah.org/0B6E62/visnusingh" alt="GitHub contribution calendar for visnusingh" />
</p>

<p align="center">
  Open to a backend or full-stack role in a product team, UK · <a href="mailto:contact@visnusingh.com">contact@visnusingh.com</a> · <a href="https://visnusingh.com/lets-talk">send a message</a>
</p>
