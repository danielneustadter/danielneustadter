# Daniel Neustadter

Software developer in the U.S. Air Force with an interest in security engineering and building tools that solve real operational problems.

Most of what I work on sits somewhere between software development, cybersecurity, and automation. I enjoy building things that are practical first and flashy second.

## Current Focus

- **[e2096](https://github.com/danielneustadter/e2096)** — automating DAF Form 2096 personnel actions end-to-end (SBIR concept prototype)
- **[VetClaims Local](https://github.com/danielneustadter/vetclaims-local)** — fully-local, self-hosted VA disability claim preparation
- **[Nestward360](https://github.com/danielneustadter/nestward360)** — a privacy-first family safety app built with an agentic planning workflow

## Featured Projects

### e2096 — DAF Form 2096 Automation Platform

An airman describes a personnel action in plain English; an LLM grounded on an AFECD/AFOCD retrieval corpus derives the correct classification action, fills the **actual DAF Form 2096 PDF**, routes it through human approvals with real **PAdES digital signatures**, and archives every version in a hash-chained, write-once signature vault. Built as an SBIR demonstration prototype — all data is fictional and every generated PDF is watermarked.

| Platform Dashboard | Signed DAF Form 2096 | Demonstration Report |
|:------------------:|:--------------------:|:--------------------:|
| [![e2096 dashboard](https://raw.githubusercontent.com/danielneustadter/e2096/main/docs/dashboard.png)](https://github.com/danielneustadter/e2096) | [![Fully signed DAF Form 2096](https://raw.githubusercontent.com/danielneustadter/e2096/main/docs/form_signed.png)](https://github.com/danielneustadter/e2096) | [![SBIR demonstration report](https://raw.githubusercontent.com/danielneustadter/e2096/main/docs/report.png)](https://github.com/danielneustadter/e2096) |

`Python` `FastAPI` `pyHanko` `pypdf` `RAG` `PAdES / digital signatures` `SQLite`

---

### VetClaims Local

Self-hosted VA disability claim preparation that never sends your records to anyone's cloud. Upload service and medical records, let a local LLM (via Ollama) analyze them with cited condition suggestions, and walk away with a filled, ready-to-file claim packet — 21-526EZ, personal statements, Intent to File, and an indexed evidence PDF. Local inference, local OCR, zero telemetry. Under active development; not affiliated with the VA.

`Python` `FastAPI` `React` `TypeScript` `Vite` `Ollama` `SQLite`

---

### Nestward360

A Life360-style family safety app: private circles, live location on a shared map, place alerts, SOS, and a 48-hour location trail. Built safety-and-privacy-first — no covert tracking mode exists, consent is shown up front, and history is enforced by deletion. One React Native + Expo codebase for iOS and Android with a NestJS backend and realtime WebSocket fan-out, planned end-to-end with the BMAD agentic workflow.

`React Native` `Expo` `TypeScript` `NestJS` `Socket.IO` `PostgreSQL` `Docker`

---

### OCHO — Military Disaster Response PWA

Built for **Operation Agile Saber 2026**, OCHO helps coordinate disaster response when connectivity is unreliable. Field personnel submit damage reports, UXO sightings, accountability updates, and evacuation information while offline; everything syncs automatically once a connection returns, while EOC staff monitor activity through a live dashboard.

| EOC Dashboard | Accountability | UXO Hazard |
|:-------------:|:--------------:|:----------:|
| [![EOC Dashboard](https://raw.githubusercontent.com/danielneustadter/OCHO-Disaster-Response-App/main/pictures_demo/eoc_dashboard.png)](https://github.com/danielneustadter/OCHO-Disaster-Response-App) | [![Accountability](https://raw.githubusercontent.com/danielneustadter/OCHO-Disaster-Response-App/main/pictures_demo/eoc_accountability.png)](https://github.com/danielneustadter/OCHO-Disaster-Response-App) | [![UXO Hazard](https://raw.githubusercontent.com/danielneustadter/OCHO-Disaster-Response-App/main/pictures_demo/uxo_hazard_view.png)](https://github.com/danielneustadter/OCHO-Disaster-Response-App) |

| Mobile Reports | Map | Offline Queue |
|:--------------:|:---:|:-------------:|
| [![Field Reports](https://raw.githubusercontent.com/danielneustadter/OCHO-Disaster-Response-App/main/pictures_demo/mobile_field_reports.png)](https://github.com/danielneustadter/OCHO-Disaster-Response-App) | [![Map View](https://raw.githubusercontent.com/danielneustadter/OCHO-Disaster-Response-App/main/pictures_demo/mobile_map_view.png)](https://github.com/danielneustadter/OCHO-Disaster-Response-App) | [![Offline Queue](https://raw.githubusercontent.com/danielneustadter/OCHO-Disaster-Response-App/main/pictures_demo/mobile_queue.png)](https://github.com/danielneustadter/OCHO-Disaster-Response-App) |

`React` `Express` `PostgreSQL` `Docker` `PWA` `WebSockets` `IndexedDB`

---

### USAF Contracting AI Automation Tool

Converts stakeholder input into SMART requirements, market research prompts, RFIs, and complete RFP package documents. Originally built to streamline Air Force contracting workflows and eliminate a lot of repetitive document writing.

| Home | SMART Requirements | Market Research |
|:----:|:------------------:|:---------------:|
| [![Home](https://raw.githubusercontent.com/danielneustadter/USAF-Contracting-AI-Automation-Tool/main/docs/images/screenshot-1.png)](https://github.com/danielneustadter/USAF-Contracting-AI-Automation-Tool) | [![SMART Requirements](https://raw.githubusercontent.com/danielneustadter/USAF-Contracting-AI-Automation-Tool/main/docs/images/screenshot-2.png)](https://github.com/danielneustadter/USAF-Contracting-AI-Automation-Tool) | [![Market Research](https://raw.githubusercontent.com/danielneustadter/USAF-Contracting-AI-Automation-Tool/main/docs/images/screenshot-3.png)](https://github.com/danielneustadter/USAF-Contracting-AI-Automation-Tool) |

| RFI Editor | RFP Generation |
|:----------:|:--------------:|
| [![RFI Editor](https://raw.githubusercontent.com/danielneustadter/USAF-Contracting-AI-Automation-Tool/main/docs/images/screenshot-4.png)](https://github.com/danielneustadter/USAF-Contracting-AI-Automation-Tool) | [![RFP Package](https://raw.githubusercontent.com/danielneustadter/USAF-Contracting-AI-Automation-Tool/main/docs/images/screenshot-5.png)](https://github.com/danielneustadter/USAF-Contracting-AI-Automation-Tool) |

`Next.js` `React` `TypeScript` `Tailwind CSS` `Groq SDK`

## Other Projects

| Project | What it is |
|---------|------------|
| [**militarysmartcards.com**](https://github.com/danielneustadter/militarysmartcards.com) | Open-source, up-to-date guide for servicemembers configuring their CAC to DISA standard. |
| [**usaf-mobile-index**](https://github.com/danielneustadter/usaf-mobile-index) | Open-source index documenting Air Force and military mobile apps — because no such project existed. |
| [**danielneustadter.com**](https://github.com/danielneustadter/danielneustadter.com) | My personal site and resume. |

## Tech I Use

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-20232A?style=flat&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/-React%20Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)

## Find Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/daniel-neustadter/)
[![Website](https://img.shields.io/badge/Website-black?style=flat&logo=googlechrome)](https://danielneustadter.com/)

If one of my projects is useful, feel free to open an issue, submit a PR, or just steal an idea and build something better. That's half the point of open source.
