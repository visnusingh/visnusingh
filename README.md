<h1 align="center">Visnu Singh</h1>

<p align="center">
  <b>Full Stack Engineer</b> · Node.js, backend-leaning · London, UK · English, Hindi, Thai
</p>

<p align="center">
  <a href="https://visnusingh.com"><img src="https://img.shields.io/badge/Portfolio-visnusingh.com-0B6E62?style=for-the-badge" alt="Portfolio" /></a>
  <a href="https://visnusingh.com/resume"><img src="https://img.shields.io/badge/CV-read%20or%20download-0B6E62?style=for-the-badge" alt="CV" /></a>
  <a href="https://www.linkedin.com/in/visnusingh"><img src="https://img.shields.io/badge/LinkedIn-visnusingh-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="mailto:contact@visnusingh.com"><img src="https://img.shields.io/badge/Email-contact%40visnusingh.com-111111?style=for-the-badge" alt="Email" /></a>
</p>

Full stack engineer, backend-leaning. I built and run two booking systems in production for UK businesses as the sole engineer, from first commit to live customers to day-to-day operation; the current one takes 1,000+ bookings a month. Node.js and Express REST APIs, Stripe payments, Firestore and Google Cloud Run, authentication and role-based access, email automation, Docker. Looking for a backend or full stack role in a product team.

Right to work: Graduate visa to Oct 2027; eligible for Skilled Worker sponsorship at the new entrant rate.

## In production

| Status | Platform | What it does | Role | When |
| --- | --- | --- | --- | --- |
| 🟢 Live | [greggmaurice.co.uk](https://greggmaurice.co.uk) | Airport parking bookings for Heathrow & Gatwick, 1,000+ a month | Full Stack Engineer, in-house, sole engineer | Nov 2025 – now |
| 🟢 Live | [teknifyltd.com](https://teknifyltd.com) | Store discovery & bookings for a retail business | Freelance Full Stack Engineer | Aug – Oct 2025 |

## Experience

### Full Stack Engineer · [Gregg Maurice Parking](https://greggmaurice.co.uk), London · Nov 2025 – present

Independent airport parking operator for Heathrow and Gatwick · in-house, sole engineer.

- Built the booking site and admin system end to end and run it in production at 1,000+ bookings a month: Node.js and Express on Google Cloud Run, React and Vite with prerendered SEO pages on Firebase Hosting, Firestore, Stripe.
- Booking and payment: quotes from banded, calendar-driven pricing; promo codes with HMAC-hashed email checks against abuse; Stripe payment intents confirmed by webhook; confirmation emails for every change.
- Self-service amend and extend: OTP-verified lookup with signed tokens, repricing or late-return charging, Stripe payment and an audit-log entry.
- Partner integrations: a versioned quote-and-book API for resellers and an outbound pricing client with markup and a price cache; supplier commission reports with per-supplier email dispatch, CSV export.
- Supplier-email import replacing manual data entry: IMAP poller, per-supplier parsers for text, HTML tables and CSV, Gemini extraction for unstructured emails, a review queue, Cloud Scheduler every five minutes.
- Operations: Dockerised deploys via Cloud Build, Firestore-backed rate limiting and IP blocking, pre-commit secret scanning, database backups, internal tools for staff attendance and group invoicing.

### Freelance Full Stack Engineer · [TEKNIFY LTD](https://teknifyltd.com) · Aug 2025 – Oct 2025

Store discovery and booking site for a retail business, delivered solo from backend to deployment in three months.

- Designed and shipped the REST API (Node.js, Express) and admin for store discovery, bookings and dynamic site configuration; SQLite and Firebase for data, Dockerised deployment.
- Nearest-store search: browser geolocation, Haversine distance, ETA logic and the Google Maps API.
- Booking confirmations with branded SMTP templates, retry-safe states and delivery logging, so failed sends are retried.
- Google OAuth and protected routes for admin operations.

## Projects

- **[visnusingh.com](https://visnusingh.com)** · hand-built site on Firebase Hosting behind Cloudflare; Cloud Functions contact form with Turnstile, Firestore rate limiting and SMTP delivery, under a strict CSP.
- **[Smart Security Camera](https://github.com/visnusingh/Smart-Security-Camera)** · university project (Python, Flask, OpenCV, SQLite, AWS EC2): motion detection, live stream and incident log.
- **[Online Learning Platform](https://github.com/visnusingh/Online-Learning-Platform)** · university project (Node.js, Express, MySQL, JWT, Multer, Turnstile): role-based sign-up for students and professors, video upload, course search.
- **IBM × Barclays Cyber Security Hackathon, Oct 2024** · top 10 of 50 teams; four-person team building a real-time intrusion-detection prototype in Python.

## Stack

**Backend**<br>
<img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white" alt="Express.js" />
<img src="https://img.shields.io/badge/REST%20API%20design-0B6E62" alt="REST API design" />
<img src="https://img.shields.io/badge/Stripe-635BFF?logo=stripe&logoColor=white" alt="Stripe" />
<img src="https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white" alt="JWT" />
<img src="https://img.shields.io/badge/OAuth%202.0%20(Google)-0B6E62" alt="OAuth 2.0 (Google)" />
<img src="https://img.shields.io/badge/Role--based%20access-0B6E62" alt="Role-based access" />
<img src="https://img.shields.io/badge/Nodemailer-0B6E62" alt="Nodemailer" />
<img src="https://img.shields.io/badge/IMAP-0B6E62" alt="IMAP" />
<img src="https://img.shields.io/badge/Gemini%20API-0B6E62" alt="Gemini API" />
<img src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white" alt="Flask" />

**Data**<br>
<img src="https://img.shields.io/badge/Firestore-FFCA28?logo=firebase&logoColor=black" alt="Firestore" />
<img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white" alt="MySQL" />
<img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white" alt="SQLite" />

**Infrastructure**<br>
<img src="https://img.shields.io/badge/Google%20Cloud%20Run-4285F4?logo=googlecloud&logoColor=white" alt="Google Cloud Run" />
<img src="https://img.shields.io/badge/Cloud%20Build-4285F4?logo=googlecloud&logoColor=white" alt="Cloud Build" />
<img src="https://img.shields.io/badge/Cloud%20Scheduler-4285F4?logo=googlecloud&logoColor=white" alt="Cloud Scheduler" />
<img src="https://img.shields.io/badge/Firebase%20Hosting-FFCA28?logo=firebase&logoColor=black" alt="Firebase Hosting" />
<img src="https://img.shields.io/badge/Cloud%20Functions-FFCA28?logo=firebase&logoColor=black" alt="Cloud Functions" />
<img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/AWS%20EC2-232F3E" alt="AWS EC2" />
<img src="https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white" alt="Cloudflare" />
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
<img src="https://img.shields.io/badge/Git%20%26%20GitHub%20flow-F05032?logo=git&logoColor=white" alt="Git and GitHub flow" />
<img src="https://img.shields.io/badge/AI--assisted%20development%20with%20Claude%20Code-D97757?logo=claude&logoColor=white" alt="AI-assisted development with Claude Code" />

## Education & certifications

- **BSc Computer Science** · University of Northampton, UK · 2024 – 2025. Final-year top-up as a transfer student; years 1–3 at Assumption University, Thailand (2021 – 2024).
- **Microsoft Certified: Azure Fundamentals** · Microsoft · Jun 2026 · [Verify on Credly](https://www.credly.com/badges/981500f7-20e6-4ba4-9d6b-5440d5379fee)
- **AWS Academy Cloud Foundations** · Amazon Web Services · Feb 2024 · [Verify on Credly](https://www.credly.com/badges/66a67ad5-75c8-4ea5-a4c8-fcbbd377084d)

## Contributions

<p align="center">
  <img src="https://ghchart.rshah.org/0B6E62/visnusingh" alt="GitHub contribution calendar for visnusingh" />
</p>

<p align="center">
  Open to a backend or full-stack role in a product team, UK · <a href="mailto:contact@visnusingh.com">contact@visnusingh.com</a> · <a href="https://visnusingh.com/lets-talk">send a message</a>
</p>
