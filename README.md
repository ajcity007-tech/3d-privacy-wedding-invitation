# 3D Digital Wedding Invitation — Privacy-by-Design Web Architecture

[![Live Production Demo](https://img.shields.io/badge/Live_Demo-Netlify_App-dab25c?style=for-the-badge)](https://anuj-vaishali-wedding-invitation.netlify.app/?to=Hiring+Leaders+%26+Tech+Peers)
[![Legal Framework](https://img.shields.io/badge/Compliance-DPDP_Act_2023_%26_Art._21-2ecc8c?style=for-the-badge)](https://www.meity.gov.in/static/uploads/2024/06/2bf1f0e9f04e6fb4f8fef35e82c42aa5.pdf)
[![Architecture](https://img.shields.io/badge/State_Engine-Zero_Database_DOM-4e101c?style=for-the-badge)](https://anuj-vaishali-wedding-invitation.netlify.app/?to=Founders+%26+Engineering+Leaders)

> **An interdisciplinary Systems Architecture & Legal-Tech case study by [Anuj Kumar (`ajcity007-tech`)](https://github.com/ajcity007-tech)** — demonstrating how first-principles **Physics** (3D motion geometry & deterministic state machines), **Indian Cyber & Privacy Law** (stateless PII minimization), and **AI-assisted front-end compilation** transform a traditional wedding invitation into a zero-trust, sub-second web application.

## Live Parameterized Endpoints (Try Stateless DOM Rendering)

Click any link below to see how the application dynamically parses the URL token client-side and embosses the recipient's title in gold foil on the 3D C5 envelope without a single database query:

* **Recruiter & Hiring Team View:** [`https://anuj-vaishali-wedding-invitation.netlify.app/?to=Hiring+Leaders+%26+Tech+Peers`](https://anuj-vaishali-wedding-invitation.netlify.app/?to=Hiring+Leaders+%26+Tech+Peers)
* **Legal-Tech & AI Founders View:** [`https://anuj-vaishali-wedding-invitation.netlify.app/?to=Founders+%26+Engineering+Leaders`](https://anuj-vaishali-wedding-invitation.netlify.app/?to=Founders+%26+Engineering+Leaders)
* **Hash-Fragment Stateless Mode (`#g=`):** [`https://anuj-vaishali-wedding-invitation.netlify.app/#g=My%20LinkedIn%20Network`](https://anuj-vaishali-wedding-invitation.netlify.app/#g=My%20LinkedIn%20Network)

## Why This Architecture Exists (The Engineering Thesis)

Most digital invitations and generative AI web templates suffer from two fundamental flaws:
1. **Visual & Code Slop:** One-click AI outputs flatten cultural typography, distort print aspect ratios (C5/A5), and rely on bloated JavaScript bundles.
2. **Surveillance & PII Leakage:** Commercial e-invite platforms collect guest names, phone numbers, and location logs in centralized backend databases—creating unnecessary data honeypots.

This project solves both problems by treating generative AI as a **constraint-driven compiler** governed by mathematical geometry and statutory **Privacy-by-Design**.

## 3 Core Systems & Legal-Tech Pillars

| Architectural Pillar | Technical Implementation | Indian Legal & Statutory Grounding |
| :--- | :--- | :--- |
| **1. Stateless Client-Side Personalization** | Reads `?to=` and `#g=` tokens via in-browser `URLSearchParams`, sanitizes strings against DOM injection, and binds them directly to the 3D envelope's gold-foil `TO:` lines. **Zero backend database; 0 bytes of guest PII stored on any server.** | Honors core **Data Minimization** principles under the [Digital Personal Data Protection Act, 2023 (DPDP Act)](https://www.meity.gov.in/static/uploads/2024/06/2bf1f0e9f04e6fb4f8fef35e82c42aa5.pdf), operates cleanly within the personal/domestic exemption under [Section 3(c)(i) of the DPDP Act, 2023](https://indiankanoon.org/doc/84660522/), and eliminates corporate data-breach liability under [Section 43A of the Information Technology Act, 2000](https://indiankanoon.org/doc/76191164/). |
| **2. Physics-Driven 3D Envelope & 5-Stage State Machine** | Preserves exact C5 envelope and A5 card ratios with hardware-accelerated CSS 3D perspective transforms (`rotateY` / `rotateX`), dual interaction modes (Auto-Slide Timer + Touch Swipe), and instant mobile rendering. | Demonstrates human-in-the-loop AI systems engineering—enforcing strict geometric and typographic invariants over raw LLM output. |
| **3. Public Feed OPSEC & Redaction** | Masks QR finder matrices and redacts private family phone numbers and exact residential/venue coordinates in public portfolio artifacts while keeping 100% of the UI engine inspectable. | Operationalizes constitutional **Informational Privacy** and decisional autonomy under Article 21 as affirmed by the Supreme Court of India in [Justice K.S. Puttaswamy (Retd.) v. Union of India](https://indiankanoon.org/doc/91938676/). |

## 5-Stage Invitation State Flow

1. **Stage 0 — 3D C5 Maroon Envelope (Front & Back Flip):** Displays personalized gold-foil recipient lines (`TO: ...`) and flips 180° to reveal the cream *Shubh Vivah (19 · 11 · 2026)* royal wax seal before extracting the inner card.
2. **Page 1 — Royal Cover:** High-resolution traditional maroon and gold-foil cover preserving 300-DPI print fidelity.
3. **Page 2 — Cordial Family Invitation:** Personalized guest greeting banner and formal family invitation.
4. **Page 3 — Ceremony Timeline (*Manglik Karyakram*):** Chronological schedule covering *Teva, Sagai, Lagan,* and *Shubh Vivah*.
5. **Page 4 — Venue QR & One-Tap Navigation:** Interactive location card (sanitized with an OPSEC shield on public repository builds).
6. **Page 5 — Family Blessings & WhatsApp Studio:** Built-in client-side link generator allowing family members to generate individualized guest links on the fly.

## About the Architect

**Anuj Kumar (`ajcity007-tech`)**
* **Academic Foundation:** M.Sc. in Physics | Bachelor of Education (B.Ed.) | Final-Year LL.B. Candidate
* **Core Focus:** AI Systems Architecture, Legal-Tech Intelligence & Statutory Automation (Creator of *Nyay Sahayak AI* / `LAW-by-Anuj-Pandit`), STEM & RLHF Reasoning Evaluation, and Privacy-by-Design Web Engineering.
* **Collaboration:** Open to remote roles and advisory engagements in **Legal-Tech Engineering, AI Systems Architecture, AI Governance/Compliance, and LLM Reasoning Evaluation**.
