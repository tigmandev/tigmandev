<!-- Header banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,100:3B82F6&height=200&section=header&text=Tigran%20Manukyan&fontColor=ffffff&fontSize=48&fontAlignY=38&desc=Backend%20Developer%20%C2%B7%20NestJS%20%C2%B7%20Node.js%20%C2%B7%20TypeScript&descSize=18&descAlignY=60" alt="Tigran Manukyan" />

<div align="center">

<a href="https://github.com/tigmandev">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1500&color=3B82F6&center=true&vCenter=true&width=640&lines=Production+backends+that+scale;Payments+%7C+Real-time+%7C+Microservices;Telegram+Mini+Apps+%26+AI+integrations" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tigmandev/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tigran.manukyan.2002@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/tigmandev)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/tigmandev)

<br/>

**🟢 Open to work: Backend / Full-Stack · Remote or Hybrid**

</div>

---

## About

5+ years of building and shipping products end-to-end: architecture, development, integrations, testing, deployment and production support.

<table>
  <tr>
    <td width="50%" valign="top">

**Architecture**<br/>
Scalable Node.js / NestJS systems, microservices (RabbitMQ, TCP RPC)

**Real-time**<br/>
WebSocket, Socket.IO, Server-Sent Events

**Payments**<br/>
Stripe, crypto, TON, Web3

  </td>
  <td width="50%" valign="top">

**Security**<br/>
JWT, OAuth, 2FA, RBAC

**Telegram & AI**<br/>
Bots, Mini Apps, AI-powered features

**Integrations**<br/>
Third-party APIs, providers, payment systems

  </td>
  </tr>
</table>

---

## Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=nestjs,nodejs,ts,graphql,postgres,mongodb,redis,rabbitmq,react,nextjs,tailwind,docker,nginx,linux&perline=7" alt="Tech stack" />

</div>

---

## Featured Projects

### CozzySIM: Production eSIM Platform

*Built under Rcozzy* · **[Live: cozzysim.com](https://cozzysim.com/)**

A platform for buying and managing international mobile connectivity: web app, Telegram Mini App, backend, admin CRM and real-time customer support.

<p align="center">
  <img src="./assets/cozzysim-web.png" width="70%" />
  <img src="./assets/cozzysim-mobile.png" width="25%" />
</p>

- eSIM catalog covering 200+ countries, instant purchase and QR-code activation
- eSIM provider API integration, payments, balance and wallet
- Real-time support: Customer Web ↔ Backend ↔ Admin CRM ↔ Telegram
- AI-generated country content, multilingual UI, dark / light themes

<!-- TODO: add a result, e.g. number of users / orders / countries -->

`NestJS` `PostgreSQL` `Redis` `Next.js` `Socket.IO` `Telegram Mini Apps` `Docker` `Nginx`

<details>
<summary><b>Architecture diagram</b></summary>

```mermaid
flowchart LR
  Web[Customer Web] -- REST / WebSocket --> API[NestJS Backend]
  TMA[Telegram Mini App] --> API
  API --> PG[(PostgreSQL)]
  API --> R[(Redis)]
  API --> ESIM[eSIM Provider]
  API <--> CRM[Admin CRM]
  CRM <--> TG[Telegram]
```

</details>

<br/>

<table>
  <tr>
    <td width="50%" valign="top">

#### Homeberries
**Multi-tenant e-commerce SaaS**

Marketplace where each company gets its own isolated storefront.

- Multi-tenant architecture
- Stripe and crypto (Bitcoin / Web3)
- 3D product views, Google Maps delivery

`NestJS` `Next.js` `PostgreSQL` `RabbitMQ` `Stripe`

  </td>
  <td width="50%" valign="top">

#### Ararat Family Meat Co.
**B2B order management**

Replaced spreadsheets and paper workflows for a wholesale food distributor.

- Weight-based invoicing, per-client pricing
- Payment tracking, automated PDF generation

`Next.js` `NestJS` `PostgreSQL` `Sequelize` `Docker`

  </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">

#### Order
**Offline-first warehouse & delivery app**

Mobile-first app for environments with unreliable internet: offline order queueing, automatic sync, price snapshots, revenue and profit analytics.

`React 19` `TypeScript` `Vite` `TanStack Query` `Zustand`

  </td>
  </tr>
</table>

---

<div align="center">

**Building a product that needs a reliable backend, solid architecture or complex integrations?**

[Write on Telegram](https://t.me/tigmandev) · [Send an email](mailto:tigran.manukyan.2002@gmail.com)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:3B82F6,100:0F172A&height=100&section=footer" alt="" />
