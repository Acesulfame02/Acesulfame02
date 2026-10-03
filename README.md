# Hi, I'm Aaron Masembe 👋

**Software engineer in Lusaka, Zambia.** I build payment, wallet and logistics systems that
move real money across borders, and I care most about them being *correct*: money that
balances to the cent, approvals that can't double-debit, and failures that say so.

[![Portfolio](https://img.shields.io/badge/Portfolio-aarons--portifolio.vercel.app-000?style=flat&logo=vercel)](https://aarons-portifolio.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aaron%20Masembe-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aaron-masembe-4b51a925b/)
![Location](https://img.shields.io/badge/Lusaka-Zambia-198754?style=flat&logo=googlemaps&logoColor=white)

---

## What I do

I work across microservice backends, web and mobile apps, and the infrastructure they
run on.

- **Payments and wallets:** mobile money integrations (Airtel Money, M-Pesa),
  multi-currency wallets and FX, spending limits, and idempotency so retries don't charge
  twice.
- **Logistics:** cross-border clearance, toll payments, fuel and fleet services, with
  documents and pricing that vary by country.
- **Accounting sync:** ERP integrations (Odoo) that record exactly what was charged.
- **Reliability:** finding root causes of production incidents such as database
  connection-pool exhaustion, distributed locking for scheduled jobs, and Kafka-based
  service sync.
- **Infrastructure:** Kubernetes on AWS (EKS), serverless jobs, Docker, and Prometheus and
  Grafana monitoring.
- **Security review:** systematic code review that has found and closed 60+ defects in
  three months, including 16 high-severity authentication, transaction-integrity and
  availability issues.

**Founder of [Sulfame-Tech](https://github.com/Sulfame-Tech)**, where I'm building SFM TMS
(see below).

**Icon Streams.** I built the backend and frontend of a video streaming service, including
large-file uploads, analytics and payment gateway integration.

## Featured projects

### 🚚 SFM TMS: transport management system

A transport management system for haulage companies, built from scratch under Sulfame-Tech.
It has four parts:

- **API (Go):** customers, providers and crew, with documents required per country, payout
  accounts, a revenue ledger, staff fund requests, and email and SMS notifications.
- **Web app (TypeScript):** the operations and admin portal.
- **Customer app (Flutter):** booking and tracking for shippers.
- **Crew app (Flutter):** for drivers on the road, with cash handover and **offline
  payments**. It works offline first because trucks don't always have signal.

Deployed on Kubernetes with staging and production environments. *(Private repositories.)*

### 🎮 [Sulfame Engine](https://github.com/Acesulfame02/SulfameEngine): game engine

A game engine written from scratch in C++ to learn how engines work underneath.

- **Platform layer:** windowing and input on Windows through GLFW, rendering with OpenGL
  through GLAD.
- **Event system:** application, keyboard and mouse events dispatched through a **layer
  stack**, so game layers and overlays handle input in order.
- **Debug UI:** a Dear ImGui overlay with its own OpenGL renderer.
- **Engine and game kept separate:** the engine builds as a library behind a single
  `Sulfame.h` header, and a Sandbox app uses it the way a game would.
- **Build:** Premake generates the Visual Studio solution.

It follows an earlier engine experiment, KapMak (2024).

## By the numbers

| | |
|---|---|
| Pull requests merged | **1,056** of 1,099 (96%) |
| Commits | **2,400+** across 25+ repositories |
| Busiest month | **192 PRs** (September 2026) |
| Consistency | **16 months in a row** with 15+ merged PRs |

*Most of this work is in private organisation repositories.*

## Tech I work with

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=000)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white)

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat&logo=nextdotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Express](https://img.shields.io/badge/Express-000?style=flat&logo=express&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=flat&logo=sequelize&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat&logo=influxdb&logoColor=white)

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

## Other projects

| Project | What it is |
|---|---|
| [deploykit](https://github.com/Acesulfame02/deploykit) | Reusable Kubernetes deploy setup: one `deploy.yaml` per project, for a local kind cluster or remote clusters |
| [report-agent](https://github.com/Acesulfame02/report-agent) | Playwright automation that downloads fleet distance reports for every account in a telematics back office |
| [blender_ai_addon_dev](https://github.com/Acesulfame02/blender_ai_addon_dev) | Blender add-on that uses pretrained models to animate characters' hands, from webcam input or prerecorded motion |
| [KMSafe](https://github.com/Acesulfame02/KMSafe) | .NET MAUI and Firebase app for reporting campus emergencies on Android, iOS and Windows |
| [Discover Zambia](https://github.com/Acesulfame02/Tourism-Alternate-React-Project) | React tourism site for Zambia |

## Get in touch

Connect with me on [LinkedIn](https://www.linkedin.com/in/aaron-masembe-4b51a925b/) or have
a look at my [portfolio](https://aarons-portifolio.vercel.app).
