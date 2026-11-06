# Ege Yesilyurt

**Software Engineering @ York University · Full-Stack & AI/ML**

I build full-stack web apps end to end. My biggest one is BundesPredict, a Bundesliga prediction site with paying subscribers, and I also built a systems tool in Rust, OverTerm.

I enjoy games (minecraft, tft, geoguessr), sports (soccer, badminton, bouldering), shows (breaking bad, the walking dead, IWGP), and anime (one piece, vinland saga, steins;gate)

---

## 🛠️ Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat&logo=html5&logoColor=white)

**Frameworks & Libraries**

![Django](https://img.shields.io/badge/Django_REST-092E20?style=flat&logo=django&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)

---

## Featured Projects

### ⚽ [BundesPredict: Bundesliga Prediction Subscription Site](https://github.com/egeyesss/BundesPredict)
A live subscription website with paying subscribers, built on a Bundesliga prediction
model I wrote. A hand-written Dixon–Coles model, fit on every result since 2020/21 and
refit daily, gives win, draw and loss odds plus expected goals for every fixture.
A chat agent running on Claude takes the news you tell it (an injured striker, a storm
on Saturday), checks it against squad data and the weather forecast, and reruns the
model with a small expected-goals change that the server caps at ±0.6, so the model
owns every number. Around it is the product: Google and email-code sign-in, free and
$5/month Pro plans on Stripe (Pro only switches on from a signed webhook), daily chat
quotas, a public track record scored after every match, a weekly matchday email, a
guided demo, and an admin dashboard for MRR, churn and AI cost per subscriber.
Backtested walk-forward over 1,827 matches, it lands within 4% of the closing
bookmaker odds.
Live at [bundespredict.egeyesilyurt.ca](https://bundespredict.egeyesilyurt.ca).
`Next.js` `TypeScript` `Django REST Framework` `Python` `PostgreSQL` `Stripe` `Anthropic API` `GitHub Actions`

### 🦓 [Zebra: Daily Logic-Grid Puzzle](https://github.com/egeyesss/zebra)
A daily competitive puzzle web app built around the classic Einstein riddle. One fresh
4×4 grid every day (plus a 5×5 bonus on Fridays), the same puzzle for every player.
Commit-based input with a hard countdown timer and zero auto-help. Every cell you
change counts against your score. Features an eliminate mode for crossing off candidate
values, a once-per-puzzle "check my work" button, and a stat-forward result card.
Dark engineer-noir aesthetic, monospace throughout.
Play today's puzzle at [zebra9.xyz](https://zebra9.xyz/).
`Next.js` `TypeScript` `Tailwind CSS`

### 🧩 [Zebra Puzzle Generator](https://github.com/egeyesss/csp-generator)
Open-source engine that generates zebra-style logic-grid puzzles with provably
unique solutions. Pairs an OR-Tools CP-SAT solver (the uniqueness oracle) with a
custom propagation tracer that mirrors human deduction to grade difficulty across
deduction depth, case-analysis depth, and a composite 0-10 score. Multi-theme,
with a manual-review CLI for curation.
`Python` `OR-Tools` `Pydantic` `Click` `pytest` `Hypothesis`

### 🖥️ [OverTerm: Agent-Aware Floating Terminal for macOS](https://github.com/egeyesss/overterm)
Native Rust + Tauri v2 terminal that detects whether an AI coding agent is running,
finished, or waiting: it shrinks to a status bar while the agent works and expands
when it needs you. Reads agent state from a vt100 screen model of the pseudoterminal
instead of the raw byte stream, so it works with any CLI tool, and picks up exact
turn events out of Claude Code hooks as OSC markers. One-command install behind a
tag-triggered GitHub Actions release pipeline with a Homebrew cask. MIT licensed,
with merged pull requests from 2 other contributors.
`Rust` `Tauri v2` `TypeScript` `xterm.js` `vt100`

### 🃏 [Deximon: Pokémon TCG Collector Platform](https://github.com/neelmu12-code/Deximon)
Social platform for Pokémon TCG collectors: a digital binder, a card-recognition
scanner (AWS Rekognition OCR + fuzzy match against the TCG API), and a
listing-scoped marketplace with real-time chat. Largest contributor on a 6-person
team (66 of 140 commits); reviewed 8 teammate PRs with written scores and
follow-up fix PRs.
Live at [deximon.ca](https://www.deximon.ca).
`Next.js` `TypeScript` `FastAPI` `Python` `PostgreSQL` `Docker Compose` `WebSockets`

### 🏋️ [Fitiva: Workout Training Planner](https://github.com/egeyesss/group2-fitiva)
Leading a 6-person team building a personalized workout planning platform for fitness
enthusiasts and trainers. Features authentication, fitness profiles, workout scheduling,
an exercise library, and smart recommendations. 40+ unit tests and counting.
`Next.js` `TypeScript` `Django REST Framework` `MySQL` `Docker` `Jira`

---

## Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/egeyesss/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:egeyesilyurtca@gmail.com) (egeyesilyurtca@gmail.com)
