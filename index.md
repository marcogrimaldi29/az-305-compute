---
layout: home
title: AZ-305 Compute Services Deep Dive
nav_order: 1
description: "Study notes for AZ-305: Designing Microsoft Azure Infrastructure Solutions — deep dive into Azure Compute services (VMs, App Service, AKS, Container Instances, Container Apps, Functions, Logic Apps) with feature comparisons, exam tips, and decision trees."
permalink: /
mermaid: true
---

# 🥽 AZ-305: Compute Services — Deep Dive
{: .no_toc }

**Study Notes & Exam Prep — 2026 Edition**
{: .fs-5 .fw-300 }

[![Deploy to GitHub Pages](https://github.com/marcogrimaldi29/az-305-compute/actions/workflows/pages.yml/badge.svg)](https://github.com/marcogrimaldi29/az-305-compute/actions/workflows/pages.yml)
[![Personal Hub of Marco Grimaldi](https://img.shields.io/badge/Blog-marcogrimaldi29.com-blue?logo=rss)](https://marcogrimaldi29.com)
[![AZ-305 Study Notes](https://img.shields.io/badge/AZ--305-Study%20Notes-blue?logo=microsoftazure)](https://marcogrimaldi29.com/az-305-study-notes/)

[View on GitHub](https://github.com/marcogrimaldi29/az-305-compute){: .btn .fs-5 .mb-4 .mb-md-0 target="_blank" }

> - 🎯 **Purpose:** Deep-dive study notes covering the full Azure Compute spectrum for the **AZ-305: Designing Microsoft Azure Infrastructure Solutions** exam — with extra depth on serverless: Container Apps, Functions, and Logic Apps.
> - 📅 **Version:** 2026
> - ✍️ **Author:** [Marco Grimaldi](https://www.linkedin.com/in/marco-grimaldi29/)
> - 🌐 **Published:** [🖥️ AZ-305: Compute Services — Deep Dive](https://marcogrimaldi29.com/az-305-compute/)
> - 🔗 **Companion repos:** [📘 AZ-305 Study Notes](https://marcogrimaldi29.com/az-305-study-notes/) · [🥽 AZ-305: Azure Messaging Services — Deep Dive](https://marcogrimaldi29.com/az-305-messaging/) · [🥽 AZ-305: Data & Analytics Services — Deep Dive](https://marcogrimaldi29.com/az-305-data-analytics/) · [🥽 AZ-305: Migration, HA & BCDR — Deep Dive](https://marcogrimaldi29.com/az-305-bcdr/) · [📘 AZ-104 Study Notes](https://marcogrimaldi29.com/az-104-study-notes/) 

---

## 🗺️ What's in This Repository?

| File | Coverage |
|------|----------|
| [🖥️ 01 — Azure Virtual Machines & VMSS](01-virtual-machines.md) | VM sizes, tiers, Availability Sets/Zones, VMSS, SLAs, cost patterns |
| [🌐 02 — Azure App Service](02-app-service.md) | Plans, tiers, deployment slots, scaling, networking, hybrid connections |
| [🐳 03 — Azure Kubernetes Service](03-aks.md) | Node pools, networking modes, RBAC, scaling, add-ons, upgrade strategy |
| [📦 04 — Azure Container Instances](04-container-instances.md) | Use cases, restart policies, networking, container groups, limits |
| [☁️ 05 — Azure Container Apps](05-container-apps.md) | Serverless focus — environments, revisions, KEDA scaling, Dapr, ingress |
| [⚡ 06 — Azure Functions](06-azure-functions.md) | Serverless focus — hosting plans, triggers, bindings, Durable Functions, cold start |
| [🔗 07 — Azure Logic Apps](07-logic-apps.md) | Serverless focus — Consumption vs Standard, connectors, ISE, B2B, error handling |
| [📊 08 — Feature Comparison](08-feature-comparison.md) | IaaS→serverless spectrum, side-by-side tables, decision matrices |
| [🎯 09 — Exam Caveats & Cheatsheet](09-exam-caveats-cheatsheet.md) | Decision trees, exam traps, quick-fire numbers, final checklist |

---

## 🔑 Why Compute Matters for AZ-305

Compute is the **largest exam domain at 30–35%** (Design Infrastructure Solutions). The exam tests:

- **IaaS vs PaaS vs Serverless trade-offs** — the most frequent scenario type
- **When containers are right** and which container service to choose (ACI vs AKS vs Container Apps)
- **Azure Functions hosting plan selection** — Consumption vs Premium vs Dedicated and their cold-start, VNet, and scaling implications
- **Logic Apps Consumption vs Standard** — when ISE was replaced by Standard, and what that means for VNet connectivity
- **App Service tier feature gates** — which features require Standard, Premium, or Isolated

> ⚠️ The exam rarely asks what a service does in isolation — it presents a scenario with **constraints** (cost, VNet isolation, latency, scale, compliance) and asks which compute option is the **best fit**. This repo is built around exactly those trade-offs.

---

## ⚡ Quick Navigation

| I need to know… | Go to |
|-----------------|-------|
| VM SLA with/without Availability Zones | [01 — VMs § SLA](01-virtual-machines.md#sla) |
| App Service tier feature gates | [02 — App Service § Plans & Tiers](02-app-service.md#plans-and-tiers) |
| AKS networking modes compared | [03 — AKS § Networking](03-aks.md#networking) |
| ACI vs Container Apps vs AKS | [08 — Comparison § Containers](08-feature-comparison.md#container-compute) |
| Functions Consumption vs Premium vs Dedicated | [06 — Functions § Hosting Plans](06-azure-functions.md#hosting-plans) |
| Logic Apps Consumption vs Standard | [07 — Logic Apps § Hosting Models](07-logic-apps.md#hosting-models) |
| Container Apps KEDA scaling rules | [05 — Container Apps § Scaling](05-container-apps.md#scaling) |
| All exam traps in one place | [09 — Exam Caveats](09-exam-caveats-cheatsheet.md) |

---

## ©️ Credits & Acknowledgements

The [Just the Docs](https://github.com/just-the-docs/just-the-docs) theme is used for a clean, documentation-style layout. Licensed under [MIT](https://opensource.org/license/MIT).

Created with the help of AI. Model used: [Claude Sonnet 4.6](https://www.anthropic.com/news/claude-sonnet-4-6). The content has been reviewed and edited by the author for accuracy and clarity, but may contain errors. Always verify against the latest [Microsoft documentation](https://learn.microsoft.com/en-us/azure/).

> *Not affiliated with or endorsed by Microsoft.*