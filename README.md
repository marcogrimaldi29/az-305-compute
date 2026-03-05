# 🖥️ AZ-305: Compute Services — Deep Dive

### Study Notes Repository — 2026 Edition

[![Deploy to GitHub Pages](https://github.com/marcogrimaldi29/az-305-compute/actions/workflows/pages.yml/badge.svg)](https://github.com/marcogrimaldi29/az-305-compute/actions/workflows/pages.yml)
[![GitHub Pages Live](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?logo=github)](https://marcogrimaldi29.com/az-305-compute/)
[![Personal Hub of Marco Grimaldi](https://img.shields.io/badge/Blog-marcogrimaldi29.com-blue?logo=rss)](https://marcogrimaldi29.com)
[![AZ-305 Main Notes](https://img.shields.io/badge/AZ--305-Main%20Notes-blue?logo=microsoftazure)](https://marcogrimaldi29.com/az-305-study-notes/)

> 🎯 **Goal:** Master the Azure Compute spectrum for the **AZ-305: Designing Microsoft Azure Infrastructure Solutions** exam — with extra depth on serverless services
> 📅 **Notes Version:** 2026
> 🌐 **Published site:** [marcogrimaldi29.com/az-305-compute](https://marcogrimaldi29.com/az-305-compute/)
> ✍️ **Author:** [Marco Grimaldi](https://www.linkedin.com/in/marco-grimaldi29/)
> 🔗 **Companion repos:** [az-305-study-notes](https://marcogrimaldi29.com/az-305-study-notes/) · [az-305-messaging](https://marcogrimaldi29.com/az-305-messaging/) · [az-305-data-analytics](https://marcogrimaldi29.com/az-305-data-analytics/)

---

## 📋 Services Covered

| Service | Category | Key Use Case |
|---------|----------|--------------|
| 🖥️ **Azure VMs & VMSS** | IaaS | Full OS control, lift-and-shift, custom software |
| 🌐 **Azure App Service** | PaaS | Managed web apps, APIs, mobile back-ends |
| 🐳 **Azure Kubernetes Service** | Container orchestration | Microservices at scale, full Kubernetes control |
| 📦 **Azure Container Instances** | Serverless containers | Short-lived, simple containers without orchestration |
| ☁️ **Azure Container Apps** ★ | Serverless containers | Event-driven microservices, Dapr, KEDA auto-scaling |
| ⚡ **Azure Functions** ★ | Serverless compute | Event-driven, short-lived, trigger-based execution |
| 🔗 **Azure Logic Apps** ★ | Serverless workflow | No-code/low-code integration workflows and B2B |

★ = Extra depth — serverless focus

---

## 🗂️ Repository Structure

```
az-305-compute/
├── README.md                        ← 📍 You are here
├── index.md                         ← Site home page
├── 01-virtual-machines.md           ← Azure VMs & VMSS deep dive
├── 02-app-service.md                ← Azure App Service deep dive
├── 03-aks.md                        ← Azure Kubernetes Service deep dive
├── 04-container-instances.md        ← Azure Container Instances deep dive
├── 05-container-apps.md             ← Azure Container Apps deep dive ★
├── 06-azure-functions.md            ← Azure Functions deep dive ★
├── 07-logic-apps.md                 ← Azure Logic Apps deep dive ★
├── 08-feature-comparison.md         ← Side-by-side comparisons & decision tables
└── 09-exam-caveats-cheatsheet.md    ← Exam traps, decision tree, quick-fire facts
```

---

## ✅ Key Study Tips for Compute Questions

- 🎯 Know the **IaaS → PaaS → Serverless spectrum** and where each service sits
- 🔄 Know **Functions Consumption vs Premium vs Dedicated** cold-start and VNet implications
- 💰 Understand **Container Apps vs AKS** — Container Apps is the default answer for event-driven microservices; AKS only when full Kubernetes control is needed
- 📐 Know **Logic Apps Consumption vs Standard** — Standard replaced ISE for VNet connectivity
- ⚡ Understand **App Service Plan tiers** — deployment slots, VNet integration, and custom domains are tier-gated
- 🔐 Know which compute services support **VNet injection vs Private Endpoints vs neither**
- 📊 Memorise **SLA values** — single VM (99.9%), Availability Set (99.95%), Availability Zones (99.99%)

---

## 🌐 Published Website

👉 **[marcogrimaldi29.com/az-305-compute](https://marcogrimaldi29.com/az-305-compute/)**

---

## ✍️ Author

Maintained by **[Marco Grimaldi](https://www.linkedin.com/in/marco-grimaldi29/)** — Cloud Consultant, Language Trainer & Lifelong Learner.

🏠 **[marcogrimaldi29.com](https://marcogrimaldi29.com)**

---

## ©️ Credits & Acknowledgements

The [Just the Docs](https://github.com/just-the-docs/just-the-docs) theme. Licensed under [MIT](https://opensource.org/license/MIT).

[Claude Sonnet 4.6](https://www.anthropic.com/news/claude-sonnet-4-6) was used for initial content generation and structuring, with all final edits, fact-checking, and formatting done by the author.

> *Not affiliated with or endorsed by Microsoft. Always verify against the latest Microsoft documentation.*
