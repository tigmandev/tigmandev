# Hi 👋, I'm Tigran Manukyan

### Senior Backend Developer | NestJS · Node.js · TypeScript · Microservices

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/tigmandev/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat\&logo=gmail\&logoColor=white)](mailto:tigran.manukyan.2002@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat\&logo=telegram\&logoColor=white)](https://t.me/tigmandev)

---

## 🚀 About Me

I'm a **Senior Backend Developer with 5+ years of professional experience** building production-ready applications, backend systems, SaaS platforms and real-time products.

I specialize in **NestJS, Node.js, TypeScript, PostgreSQL, Redis and microservices architecture**.

I enjoy taking ownership of products end-to-end:

**Architecture → Development → Integrations → Testing → Deployment → Production**

My main areas of expertise:

* ⚙️ **Backend architecture** — scalable and maintainable Node.js/NestJS systems
* 🏗️ **Microservices** — RabbitMQ, TCP RPC and distributed services
* 🔌 **Real-time systems** — WebSocket, Socket.IO and Server-Sent Events
* 💳 **Payments** — Stripe, crypto, TON and Web3 integrations
* 🔐 **Authentication & Security** — JWT, OAuth, 2FA and RBAC
* 📱 **Telegram** — Bots and Telegram Mini Apps
* 🤖 **AI integrations** — AI-powered features and automation
* 🔗 **Third-party APIs** — external services, providers and payment systems
* 🗄️ **Databases** — PostgreSQL, MongoDB and Redis
* 🚀 **Infrastructure** — Docker, Nginx, Linux and production deployments

---

# 🌐 Rcozzy

## CozzySIM — Production eSIM Platform

**CozzySIM** is a production eSIM platform developed under **Rcozzy** for purchasing and managing international mobile connectivity.

The platform combines a modern web application, Telegram Mini App, backend services, Admin CRM, payment flows, eSIM provider integrations and real-time customer support.

<p align="center">
  <img src="./assets/cozzysim-web.png" width="70%" />
  <img src="./assets/cozzysim-mobile.png" width="25%" />
</p>

### 🚀 What I Built

* 🌍 International eSIM catalog
* 📱 Telegram Mini App
* 🔐 Authentication and user management
* 💳 Payment and transaction flows
* 💰 Balance and wallet management
* 📲 eSIM purchasing and activation
* 🔳 QR-code based eSIM activation
* 🔌 eSIM provider API integrations
* 🧑‍💼 Admin CRM
* 📊 Analytics and management tools
* 💬 Real-time customer support
* 📡 WebSocket communication
* 🤖 AI-powered country content generation
* 🌐 Multilingual interface
* 🌓 Dark / Light themes
* 🔄 Automated backend processes

### 🏗️ Architecture

The platform connects multiple applications and services:

```text
                    ┌──────────────────┐
                    │   Customer Web   │
                    └────────┬─────────┘
                             │
                             │ WebSocket / REST
                             ▼
                    ┌──────────────────┐
                    │     Backend      │
                    │ NestJS / Node.js │
                    └───────┬──────────┘
                            │
              ┌─────────────┼─────────────┐
              │             │             │
              ▼             ▼             ▼
        ┌──────────┐  ┌──────────┐  ┌──────────────┐
        │PostgreSQL│  │  Redis   │  │ eSIM Provider│
        └──────────┘  └──────────┘  └──────────────┘
              │
              ▼
        ┌──────────────┐
        │   Admin CRM  │
        └──────┬───────┘
               │
               ▼
        ┌──────────────┐
        │   Telegram   │
        └──────────────┘
```

### 💬 Real-Time Support

One of the key parts of the platform is the real-time support architecture connecting:

**Customer Web App ↔ Backend ↔ Admin CRM ↔ Telegram**

This allows support agents to communicate with customers across multiple channels from a centralized CRM.

### 🛠️ CozzySIM Stack

`NestJS` `Node.js` `TypeScript` `PostgreSQL` `Redis`

`React` `Next.js` `WebSocket` `Socket.IO`

`Telegram Mini Apps` `Docker` `Nginx`

`REST API` `AI Integrations` `Third-party APIs`

---

# 🛠️ Tech Stack

### Backend

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat\&logo=nestjs\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat\&logo=nodedotjs\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat\&logo=typescript\&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat\&logo=graphql\&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-61DAFB?style=flat\&logo=react\&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat\&logo=nextdotjs\&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat\&logo=tailwindcss\&logoColor=white)

### Data & Infrastructure

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat\&logo=postgresql\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat\&logo=mongodb\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat\&logo=redis\&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat\&logo=rabbitmq\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat\&logo=docker\&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat\&logo=nginx\&logoColor=white)

### APIs & Integrations

![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat\&logo=stripe\&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat\&logo=socketdotio\&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat\&logo=telegram\&logoColor=white)

---

# 🌟 Featured Projects

## 🛒 Homeberries — Multi-Tenant E-Commerce Platform

Multi-tenant SaaS marketplace with isolated storefronts for individual companies.

The platform supports flexible payment methods, including Stripe and cryptocurrency, with a modern Next.js storefront.

### Key features

* Multi-tenant architecture
* Isolated company storefronts
* Payment integrations
* Stripe
* Bitcoin / Web3
* 3D product views
* Google Maps delivery integration

### Stack

`NestJS` `Next.js` `React` `PostgreSQL` `RabbitMQ` `Stripe`

---

## 🥩 Ararat Family Meat Co. — B2B Order Management

B2B platform developed to replace spreadsheets and paper-based workflows for a wholesale food distributor.

### Key features

* Weight-based invoicing
* Per-client pricing
* Order management
* Payment tracking
* Automated PDF generation
* Customer management

### Stack

`Next.js` `NestJS` `PostgreSQL` `Sequelize` `Docker`

---

## 📦 Order — Offline-First Warehouse & Delivery App

Mobile-first warehouse and delivery application designed for environments with unreliable internet connectivity.

The application supports offline order queueing, automatic synchronization and business analytics.

### Key features

* Offline-first architecture
* Automatic synchronization
* Order queueing
* Price snapshots
* Revenue analytics
* Profit analytics

### Stack

`React 19` `TypeScript` `Vite`

`TanStack Query` `Zustand`

---

# 📊 Engineering Focus

I particularly enjoy working on systems where architecture and reliability matter:

* High-load backend services
* Distributed systems
* Microservices
* Real-time communication
* Payment infrastructure
* API integrations
* SaaS platforms
* Telegram Mini Apps
* Automation
* AI-powered products
* Production infrastructure

---

# 📫 Get in Touch

* 💼 LinkedIn: `tigmandev`
* ✉️ Email: `tigran.manukyan.2002@gmail.com`
* 💬 Telegram: `@tigmandev`
* 📍 Vanadzor, Armenia

---

### Open to new opportunities

**Senior Backend / Full-Stack Developer — Remote or Hybrid**

I'm available for backend development, full-stack projects, system architecture, API integrations, Telegram Mini Apps and long-term product development.

If you are building a product that needs a reliable backend, scalable architecture or complex integrations, feel free to reach out.
