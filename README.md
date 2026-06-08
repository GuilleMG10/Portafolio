# Portfolio — Guillermo Maldonado

Personal portfolio showcasing backend and fullstack projects built for production environments across multiple industry sectors.

**Live:** [View Portfolio](https://guillemg10.github.io/portfolio) <!-- replace with your actual URL -->

---

## Overview

Static portfolio site built with vanilla HTML, CSS, and JavaScript. No frameworks, no build step — just fast, clean markup deployed directly.

**Highlights:**
- 5 production systems shipped across medical, construction, fitness, and healthcare sectors
- 6th place ICPC Bolivia 2023
- Undergraduate thesis scored 100/100 — microservices architecture with Clean Architecture + SOLID

---

## Client Projects (Private · NDA)

| Project | Domain | Stack |
|---|---|---|
| [ACS Bolivia](acs-bolivia.html) | Medical / Non-Profit | NestJS, Next.js, PostgreSQL, Prisma |
| [Construction Management System](coninarde.html) | Construction | NestJS, PostgreSQL, TypeORM, Docker, CI/CD |
| [Gym Management Software](gym.html) | Fitness | Node.js, TypeScript, PostgreSQL, JWT, RBAC |
| [Estética Clínica Admin](clinica.html) | Healthcare | NestJS, Prisma, PostgreSQL, JWT |
| [Cost Management System](thesis.html) | Thesis | Microservices, Clean Architecture, SOLID |

## Open Source Projects

| Project | Domain | Stack | Repo |
|---|---|---|---|
| Multi-tenant SaaS API | SaaS Backend Infrastructure | NestJS, PostgreSQL, Stripe, JWT, Docker | [github.com/GuilleMG10/api-multitenant](https://github.com/GuilleMG10/api-multitenant) |
| O'Cañamos? | Mobile / React Native | Expo SDK 54, React Navigation, Animated API, EAS Build | [github.com/GuilleMG10/ocanamos](https://github.com/GuilleMG10/ocanamos) |

---

## Tech Stack

**Languages:** TypeScript, JavaScript, SQL  
**Backend:** NestJS, Node.js, Express  
**Frontend:** Next.js, React, Vanilla JS  
**Databases:** PostgreSQL (Prisma, TypeORM)  
**DevOps:** Docker, CI/CD pipelines  
**Auth:** JWT, RBAC  

---

## Structure

```
portfolio/
├── index.html          # Main landing page
├── shared.css          # Shared styles for detail pages
├── acs-bolivia.html
├── coninarde.html
├── gym.html
├── clinica.html
└── thesis.html
```

---

## Running Locally

No build step needed. Open `index.html` directly in a browser or serve it with any static file server:

```bash
# Using Python
python -m http.server 3000

# Using Node.js (npx)
npx serve .
```

Then visit `http://localhost:3000`.

---

## Contact

- **Email:** guichi.maldo@gmail.com
- **LinkedIn:** [linkedin.com/in/guillemg10](https://linkedin.com/in/guillemg10)
- **GitHub:** [github.com/GuilleMG10](https://github.com/GuilleMG10)

---

*Cochabamba, Bolivia · Backend Engineer*
