<div align="center">

# Shibli · Full-Stack Web Developer

### Shipping web products that hold up in **production**
*Next.js · Express · PostgreSQL · then Computer Vision when the product needs it.*

<p>
  <img src="https://komarev.com/ghpvc/?username=asadshibli&label=Profile%20views&color=0e75b6&style=flat" alt="asadshibli" />
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shibliasadullah)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mdasadullahshibli@gmail.com)

</div>

---

## The Mission

I build **full-stack web apps** — screens, APIs, auth, and a database that stays isolated per tenant — then ship them.

AI is a second skill I reach for when the product needs vision or automation: counting, tracking, OCR. The web app is still the product.

---

## 🛡️ Deep Spike: Multi-tenant SaaS

I don't just render pages. I **isolate data**.

StudioDesk shares one Postgres between studios. The dangerous bug is a missed `WHERE orgId`. `prismaForOrg(orgId)` injects the tenant on every query so Harbor cannot see Northshore's clients.

> **Philosophy:** If a missed filter can leak another customer's data, the architecture is not done.

---

## 🛠️ Tech Stack

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,react,nextjs,nodejs,express,postgres,prisma,supabase,docker,vercel,python,pytorch" alt="Tech Stack" />
  </a>
</p>

| Domain | Tools |
|---|---|
| **Frontend** | Next.js, React, TypeScript, Tailwind CSS |
| **Backend** | Node.js, Express, Zod, REST APIs |
| **Database** | PostgreSQL, Prisma, Supabase |
| **Auth & Access** | Session cookies, RBAC, feature flags |
| **Deploy** | Vercel, Docker, pnpm workspaces |
| **Computer Vision** | YOLO, OpenCV, ByteTrack, Supervision |
| **AI** | PyTorch, FastAPI, LangGraph |

---

## 📂 Featured Systems

### 🗂️ [StudioDesk](https://github.com/AsadShibli/studiodesk) · [Live](https://studiodesk-one.vercel.app)
Multi-tenant studio ops: clients, bookings, invoices. Next.js UI, Express API, Postgres + Prisma. RBAC, plan flags, CSV import with undo. The browser never talks to the database.

`Next.js` `Express` `PostgreSQL` `Prisma`

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

- 🔭 **Current Focus** : Shipping full-stack web apps — StudioDesk, Dropbridge, and the next product after that
- 👯 **Open to Collaborate** : Product teams building with Next.js, Node, and Postgres
- 💬 **Ask Me About** : Tenant isolation, session cookies vs JWT, Prisma, and when YOLO is the right tool
- ⚡ **Fun Fact** : I would rather ship a boring session cookie than a JWT I cannot revoke

---

<div align="center">
  <i>"Great software isn't just the UI — it's a system reliable enough to deliver real work."</i>
</div>
