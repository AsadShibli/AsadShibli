<div align="center">

# Shibli · Full-Stack Web Developer

### Shipping web products that hold up in **production**
Next.js · Express · Django REST · PostgreSQL · Docker · AI

<p>
  <img src="https://komarev.com/ghpvc/?username=asadshibli&label=Profile%20views&color=0e75b6&style=flat" alt="asadshibli" />
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shibliasadullah)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mdasadullahshibli@gmail.com)

</div>

---

## The Mission

I build **full-stack web apps** — screens, APIs, auth, and a database that stays correct under load — then ship them. I work on both stacks: **Next.js + Express** and **React + Django REST**.

AI is a second skill I reach for when the product needs it: LLM integration with validation and fallbacks, or computer vision for counting and tracking. The web app is still the product.

---

## 🛡️ Deep Spike: Correctness under pressure

I don't just render pages. I make the data layer **safe**.

- **Tenant isolation:** StudioDesk shares one Postgres between studios. The dangerous bug is a missed `WHERE orgId`. `prismaForOrg(orgId)` injects the tenant on every query so Harbor cannot see Northshore's clients.
- **The last seat:** In Dhaka Tesla Pool, two riders can race for the final seat. Capacity is checked and written inside one database transaction, so a three-seat car never carries a fourth passenger.

> **Philosophy:** If a missed filter or a race can leak data or double-book a resource, the architecture is not done.

---

## 🛠️ Tech Stack

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,express,python,django,fastapi,postgres,prisma,supabase,docker,vercel,pytorch" alt="Tech Stack" />
  </a>
</p>

| Domain | Tools |
|---|---|
| **Frontend** | Next.js, React, TypeScript, Tailwind CSS |
| **Backend (JS)** | Node.js, Express, Zod, REST APIs |
| **Backend (Python)** | Django, Django REST Framework, FastAPI, Pydantic |
| **Database** | PostgreSQL, Prisma, Django ORM, Supabase |
| **Auth & Access** | JWT (httpOnly cookies), session cookies, RBAC, feature flags |
| **Deploy** | Docker, Docker Compose, Vercel, Render |
| **AI** | LLM APIs (Groq, OpenRouter, Gemini), PuLP, PyTorch |
| **Computer Vision** | YOLO, OpenCV, ByteTrack, Supervision |

---

## 📂 Featured Systems

### 🚗 [Dhaka Tesla Pool](https://github.com/AsadShibli/dhaka-tesla-pool) · [Live](https://tesla-pool-web.onrender.com)
Ride-pooling app: passengers book seats and a driver pools compatible requests into one Tesla. Capacity is enforced in a single transaction, fares are repriced when riders join or leave, and every step lands in an append-only event log. Runs with one `docker compose up`.

`Next.js` `Express` `PostgreSQL` `Docker`

---

### 🛍️ [Suqilic](https://github.com/AsadShibli/suqilic) · [Live](https://suqilic.onrender.com)
Full-stack online store: versioned Django REST API with JWT, a React/TypeScript storefront, and a custom staff dashboard for products, orders, and content. Guest carts merge on login; stock is locked on order and restored on cancel.

`Django` `DRF` `React` `TypeScript` `PostgreSQL` `Docker`

---

### 🗂️ [StudioDesk](https://github.com/AsadShibli/studiodesk) · [Live](https://studiodesk-one.vercel.app)
Multi-tenant studio ops: clients, bookings, invoices. Next.js UI, Express API, Postgres + Prisma. RBAC, plan flags, CSV import with undo. The browser never talks to the database.

`Next.js` `Express` `PostgreSQL` `Prisma`

---

### ⚡ [GridWise LLM](https://github.com/AsadShibli/gridwise-llm-fastapi) · [Live API](https://gridwise-llm-fastapi.onrender.com/docs)
Hackathon energy optimizer (BUP CSE Fest 2026). An LLM turns operator notes into directives, Python guardrails validate the JSON, and a PuLP/CBC solver minimizes grid cost. Multi-provider LLM fallback, Django console, Docker Compose.

`FastAPI` `Pydantic` `Django` `PuLP` `Docker`

---

### 🌉 [Dropbridge](https://github.com/AsadShibli/dropbridge) · [Live](https://dropbridge-kappa.vercel.app)
Ephemeral file and note transfer between your devices. Everything hard-deletes after 48 hours. Auth, private storage, and a cron job — no leftover files on a public machine.

`Next.js` `Supabase` `TypeScript` `Vercel`

---

### ⛳ [Golf Ball Track & Count](https://github.com/AsadShibli/Golf-Ball-Track-Count)
Custom YOLOv8 + ByteTrack for detecting, tracking, and counting golf balls across a line. Same family as [railway people counting](https://github.com/AsadShibli/railway-people-counting).

`YOLOv8` `ByteTrack` `Supervision` `OpenCV`

---

## 📊 Engineering Impact

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api?username=AsadShibli&show_icons=true&theme=tokyonight" height="195" alt="GitHub Stats" />
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=AsadShibli&layout=compact&theme=tokyonight" height="195" alt="Top Languages" />
</p>

---

## 🤝 Let's Connect

- 🔭 **Current Focus** : Shipping full-stack web apps and strengthening my backend skills in Python (Django, FastAPI) and Node
- 👯 **Open to Collaborate** : Product teams building with Next.js/React, Node or Django, and Postgres
- 💬 **Ask Me About** : Tenant isolation, transactions and race conditions, JWT in httpOnly cookies vs session cookies, Prisma, and LLM validation
- ⚡ **Fun Fact** : I would rather ship a boring session cookie than a JWT I cannot revoke

---

<div align="center">
  <i>"Great software isn't just the UI — it's a system reliable enough to deliver real work."</i>
</div>
