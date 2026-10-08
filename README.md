<div align="center">
  <img width="100%" src="cover.png" alt="cover" />
</div>

# Mohammad Nasir Masud

**Full-Stack Developer — Next.js, TypeScript, Node.js, MongoDB.** I design and ship complete web products: authentication, role-based access, payments, and real databases — not front-end demos.

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to%20Collaboration-2ea44f?style=flat-square&logo=github&logoColor=white" alt="Open to collaboration"/>
  <img src="https://img.shields.io/badge/Available%20for%20Freelance%20Work-ff8c00?style=flat-square" alt="Available for freelance work"/>
  <img src="https://img.shields.io/badge/Frontend%20%E2%86%92%20Full-stack-0f7bbf?style=flat-square" alt="Frontend to full-stack"/>
  <img src="https://img.shields.io/badge/Dhaka%2C%20Bangladesh-0077B5?style=flat-square&logo=googlemaps&logoColor=white" alt="Location"/>
</p>

<p align="center">
  <a href="#-about">About</a> · <a href="#-tech-stack">Stack</a> · <a href="#-featured-projects">Projects</a> · <a href="#-how-i-work">How I Work</a> · <a href="#-github-stats">Stats</a> · <a href="#-connect">Connect</a>
</p>

---

## About

I'm a self-taught developer working from Dhaka, Bangladesh. I started in the browser — HTML, CSS, JavaScript — and kept pulling the thread backwards until I was comfortable owning the server, the schema, and the payment flow. That path is why my projects tend to be complete products rather than interface exercises.

Most of my work is marketplace-shaped: buyers, sellers, mentors, and admins sharing one database with different permissions. Auth, RBAC, search and filtering, dashboards, and payments are the parts I care most about getting right.

Outside of work I keep a heavily customised Windows desktop — Windhawk, Rainmeter, minimal.

## Currently

- 🔭 Building an **e-commerce store** and **Next Properties**
- 🌱 Deepening **Node.js/Express architecture**, **Prisma + PostgreSQL**, and TypeScript beyond the type-checking basics
- 🎯 Moving from frontend into full-stack delivery — smaller surface area, more ownership

---

## Tech Stack

**Frontend**

<p align="left">
  <img src="https://skillicons.dev/icons?i=js,ts,react,nextjs,tailwind,framer" />
</p>

**UI & Styling** — shadcn/ui, HeroUI, DaisyUI, Figma, responsive CSS architecture

**Backend & Data**

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,postgres,prisma,postman" />
</p>

**Auth & Payments** — BetterAuth (sessions, role-based access), Stripe Checkout

**Tooling**

<p align="left">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,vite,vercel,netlify,docker" />
</p>

---

## Featured Projects

### ⚑ Fable — E-book Marketplace

**A full-stack digital marketplace connecting readers, writers, and administrators.**

Stripe-powered purchases, role-specific dashboards for each side of the platform, and an architecture that keeps catalogue, orders, and payouts in separate domains instead of one growing `products` table.

- 💳 End-to-end Stripe checkout and webhook-driven order fulfilment
- 🔐 Three-role access model — reader, writer, admin — enforced server-side, not just hidden in the UI
- 🧩 Domain-separated feature folders so catalogue, orders, and payouts stay independently maintainable
- ✨ Interface work in Tailwind CSS 4 + shadcn/ui with Framer Motion for state and layout transitions
- 🗄 Express + MongoDB data layer behind a Next.js 16 (React 19) front end

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white) ![Express](https://img.shields.io/badge/Express-404D59?style=flat-square&logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white) ![BetterAuth](https://img.shields.io/badge/BetterAuth-000000?style=flat-square)

**[→ Live demo](https://fable-amber.vercel.app)**

### Other Builds

<table>
  <tr>
    <td width="50%" valign="top">

**MediQueue — Medical Tutoring Marketplace**

A booking platform where medical students find 1-on-1 mentors and reserve real slots. Search filters narrow by subject and availability, slot management stays consistent under concurrent booking, and access is split between student, mentor, and admin.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black) ![DaisyUI](https://img.shields.io/badge/DaisyUI-5D0C7D?style=flat-square) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4155?style=flat-square&logo=tanstack&logoColor=white)

**[→ Live demo](https://b13-a9-client.vercel.app)**

    </td>
    <td width="50%" valign="top">

**Skill Sphere — Learning Platform**

A course-discovery platform with authenticated accounts, catalogue browsing, and enrolment flow. Built to prove I can ship the unglamorous parts — session handling, empty states, responsive layouts — and still get the details right.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black) ![HeroUI](https://img.shields.io/badge/HeroUI-6C2FF8?style=flat-square) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)

**[→ Live demo](https://b13-a8.vercel.app)**

    </td>
  </tr>
</table>

---

## How I Work

- **I model the data before the pixels.** Roles, permissions, and API shape get decided while the database is still an empty collection. Rewriting an auth model after the UI exists is the expensive way round.
- **A feature isn't done until the edges work.** Loading, empty, error, and unauthorised states are part of the ticket, not a follow-up.
- **Boring technology, chosen deliberately.** I reach for the tool I can debug at 2am, and I only add something unfamiliar when the project is the reason to learn it.
- **Security is part of the feature, not a phase.** Server-side authorisation checks, validated input, and no secrets shipped to the client — even in projects that never leave localhost.

---

<details>
<summary><strong>📊 GitHub Stats & Activity</strong></summary>

<br>

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=nasirmasud&show_icons=true&theme=tokyonight_strict&hide_border=true&include_all_commits=true&count_private=true" alt="Nasir's GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nasirmasud&layout=compact&theme=tokyonight_strict&hide_border=true&langs_count=8" alt="Top languages"/>
</p>

<p align="center">
  <img height="150" src="https://streak-stats.demolab.com/?user=nasirmasud&theme=tokyo-night&hide_border=true&timezone=Asia%2FDhaka&count_private=true" alt="GitHub streak"/>
</p>

<br>

**Contribution Activity**

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=nasirmasud&theme=tokyo-night&hide_border=true&radius=8" width="100%" alt="Contribution activity graph"/>
</p>

<br>

**Contribution Graph**

<p align="center">
  <img src="https://ghchart.rshah.org/7aa2f7/nasirmasud" width="100%" alt="Contributions per day"/>
</p>

<br>

**Trophy Case**

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=nasirmasud&theme=tokyonight&no-frame=true&no-bg=true&row=1" alt="GitHub trophies"/>
</p>

<br>

**Contribution Snake**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nasirmasud/nasirmasud/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/nasirmasud/nasirmasud/output/github-contribution-grid-snake.svg"/>
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/nasirmasud/nasirmasud/output/github-contribution-grid-snake.svg"/>
</picture>

</details>

---

## Connect

<p align="center">
  <a href="https://github.com/nasirmasud">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://linkedin.com/in/mohammadnasirmasud">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://nasirmasud-portfolio.netlify.app">
    <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=react&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="mailto:nasir.masud@ymail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="tel:+8801911907105">
    <img src="https://img.shields.io/badge/Phone-%2B8801911907105-25D366?style=for-the-badge&logo=phone&logoColor=white" alt="Phone"/>
  </a>
</p>

<p align="center">
  Open to freelance projects and collaborations. If you have a marketplace, booking, or dashboard product in mind — or just want to compare approaches — email me and I'll reply.
</p>

---

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=90&color=gradient&text=Thanks%20for%20stopping%20by&reversal=false&section=footer&fontSize=24&animation=fadeIn" alt="footer"/>
  <img src="https://komarev.com/ghpvc/?username=nasirmasud&color=5D0C7D&style=flat-square" alt="Profile views"/>
</div>
