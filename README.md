<h1 align="center">Hi, I'm Sreelekha Guda 👋</h1>

<p align="center">
  <b>Full-Stack Developer</b> — React · TypeScript · Java / Spring Boot · Python / ML<br>
  <a href="mailto:sreelekha2.guda@gmail.com">sreelekha2.guda@gmail.com</a>
  ·
  <a href="https://www.linkedin.com/in/sreelekha-guda-051473243">LinkedIn</a>
  ·
  Hyderabad, Telangana, India
</p>

<p align="center">
  <a href="https://sreelekha-22.github.io/Sreelekha-Full-Stack-Developer-Portfolio/"><img src="https://img.shields.io/badge/Portfolio-Live%20site-5ba3ff?style=flat-square" alt="Portfolio" /></a>
  <a href="https://github.com/sreelekha-22/Vykronis"><img src="https://img.shields.io/badge/Flagship-Vykronis-2fbf6f?style=flat-square" alt="Vykronis" /></a>
  <img src="https://img.shields.io/badge/roles-Full--stack%20%7C%20Backend%20%7C%20AI%2FML-ff9f43?style=flat-square" alt="Roles" />
</p>

---

## What I build

I work across the whole stack. On the backend I design **event-driven microservices** and REST APIs
in **Java / Spring Boot** and **Python**. On the frontend I build **React + TypeScript** applications
with **Redux Toolkit**. And I like wiring in **applied AI/ML** — LLMs as tool-calling agents,
speech and vision models — where it genuinely earns its place.

My flagship project, **Vykronis**, is an autonomous incident-response platform: it detects production
anomalies, investigates root cause with a tool-constrained agent, and refuses to touch production
without a human approval — a closed loop, verified end to end.

---

## 🚀 Featured work

<table>
<tr><td width="50%">

### [Vykronis](https://github.com/sreelekha-22/Vykronis)
**Autonomous Incident Response Platform**
`Java` `Spring Boot` `Kafka` `PostgreSQL` `Redis`

9 Spring Boot microservices that detect, investigate, policy-gate and human-approve production
remediations.

- 6 Kafka topics with versioned JSON-Schema contracts
- Kafka Streams correlation engine (60s windowed detection)
- 9-state incident state machine, persisted & auditable
- **Fail-closed** policy matrix — automation denied for prod
- 298 tests across 70 classes (≈46% of the codebase)
- Full loop verified live in **0.8 min** on a 7.9 GB laptop

[Repo →](https://github.com/sreelekha-22/Vykronis)

</td><td width="50%">

### [lessongen](https://github.com/sreelekha-22/lessongen)
**Self-Evaluating Lesson Generator**
`Python` `LangGraph` `LiteLLM`

An agentic `generate → evaluate → regenerate` loop that writes a lesson and refuses to ship it
until it passes a hard rubric.

- 13 pass/fail checkpoints, deterministic + LLM-judge
- Ships the lesson **with a rejection-log audit trail**
- Self-evolving memory with bounded rubric adaptation
- Audits the judge itself for stability & agreement
- Runs offline with a deterministic stub — no API key needed

[Repo →](https://github.com/sreelekha-22/lessongen)

</td></tr>
<tr><td width="50%">

### [Language Profiling App](https://github.com/sreelekha-22/LanguageProfilingApp_1)
`React` `FastAPI` `Whisper` `MediaPipe` `spaCy`

Transcribes speech and analyses video frames to build a fluency, grammar, sentiment and confidence
profile across two structured speaking rounds. **100% local — no API keys.**

[Repo →](https://github.com/sreelekha-22/LanguageProfilingApp_1)

</td><td width="50%">

### [Absentra](https://github.com/sreelekha-22/Absentra)
**Role-Based Leave Management System**
`React` `TypeScript` `Redux Toolkit` `RTK Query`

Employee / Manager / HR roles with a real leave approval workflow, protected routes and persistent
balances.

[Repo →](https://github.com/sreelekha-22/Absentra)

</td></tr>
<tr><td width="50%">

### [Fake News Detection](https://github.com/sreelekha-22/ML_projects/tree/main/Fake_News_DetectionHK)
`React` `Flask` `TensorFlow` `LSTM`

Real-time fake-news classification, ~94% accuracy, with a confidence score per request.

[Repo →](https://github.com/sreelekha-22/ML_projects)

</td><td width="50%">

### [Appointments Made Easy](https://github.com/sreelekha-22/Appointments-Made-Easy)
`Node.js` `Express` `EJS` `MongoDB`

Two-sided appointment scheduling with automated email notifications.

[Repo →](https://github.com/sreelekha-22/Appointments-Made-Easy)

</td></tr>
<tr><td width="50%">

### [Watch Hub](https://github.com/sreelekha-22/WatchHub)
`React` `Express` `MongoDB` `JWT`

Video platform with authentication, filtering and full admin CRUD.

[Repo →](https://github.com/sreelekha-22/WatchHub)

</td><td width="50%">

### [UrlShorty](https://github.com/sreelekha-22/UrlShorty)
`Java` `Spring Boot` `MongoDB`

URL shortener REST API with a clean DTO-layered architecture.

[Repo →](https://github.com/sreelekha-22/UrlShorty)

</td></tr>
</table>

### More

- **[ML Projects](https://github.com/sreelekha-22/ML_projects)** — three applied ML projects:
  - [Fake News Detection](https://github.com/sreelekha-22/ML_projects/tree/main/Fake_News_DetectionHK) — LSTM text classifier, ~94% accuracy, Flask API + React UI
  - [Medicinal Plant Detection](https://github.com/sreelekha-22/ML_projects/tree/main/Med_Plant_Detection) — **80-class** Ayurvedic plant identifier (Tulsi, Neem, Amla, Turmeric…), VGG19 transfer learning
  - [Poultry Disease Detection](https://github.com/sreelekha-22/ML_projects/tree/main/Poultry_disease_detection) — 4-class poultry condition classifier, VGG19 transfer learning
- **[Medicinal Plant Identification](https://github.com/sreelekha-22/Medicinal-Plant-Identification)** —
  Flask app serving a VGG19 leaf-image classifier
- **[Full portfolio site →](https://sreelekha-22.github.io/Sreelekha-Full-Stack-Developer-Portfolio/)**

---

## 🛠 Tech stack

| Domain | Technologies |
|---|---|
| **Frontend** | React, TypeScript, Redux Toolkit, RTK Query, Vite, EJS |
| **Backend** | Java 25, Spring Boot 4, Spring Cloud, Node.js, Express, FastAPI, Flask |
| **Data & Messaging** | PostgreSQL, MongoDB, Redis, Apache Kafka, Kafka Streams, Flyway |
| **AI / ML** | Python, TensorFlow, Keras, LSTM, Whisper, spaCy, MediaPipe, LangGraph, LiteLLM |
| **DevOps** | Docker, Docker Compose, Helm, kind, GitHub Actions, GraalVM native-image |
| **Observability** | OpenTelemetry, JFR, Prometheus, Grafana, OpenSearch |

---

## 💬 A few things I care about

- **Failing closed over failing open.** Vykronis denies a remediation it isn't sure about. That
  principle shows up in how I write policy code.
- **No fabricated evidence.** The investigation agent is tool-constrained, and has a deterministic
  fallback, so it degrades honestly instead of inventing a plausible answer.
- **Tests as documentation.** Roughly half the Vykronis codebase is tests — the state machine, Kafka
  topologies and policy decisions are all pinned down.
- **It should run somewhere real.** Vykronis boots on a 7.9 GB laptop with no paid services. If it
  runs there, it runs in the cloud.

---

## 📫 Let's talk

I'm open to **full-stack** and **backend** engineering roles.

- **Email** — [sreelekha2.guda@gmail.com](mailto:sreelekha2.guda@gmail.com)
- **LinkedIn** — [linkedin.com/in/sreelekha-guda-051473243](https://www.linkedin.com/in/sreelekha-guda-051473243)
- **Portfolio** — [sreelekha-22.github.io](https://sreelekha-22.github.io/Sreelekha-Full-Stack-Developer-Portfolio/)
- **Location** — Hyderabad, Telangana, India

---

<p align="center">
  <sub>© 2026 Sreelekha Guda</sub>
</p>
