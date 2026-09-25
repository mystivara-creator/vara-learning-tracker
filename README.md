# vara-learning-tracker

A lightweight, self-hosted web dashboard built to track daily progress in Japanese language acquisition and software engineering/scripting. Integrated with Gemini API for automated schedule balancing and rest advisories.

## Motivation

Managing time between Japanese immersion and kernel/scripting projects requires consistent tracking. Existing productivity apps are often bloated, closed-source, or lack custom logic. This project provides a minimal, locally-hosted Web UI running via Termux to maintain full control over personal logs and study data.

## Tech Stack

* **Backend:** Python 3 (Flask framework)
* **AI Engine:** Google Gemini API (`google-generativeai`)
* **Frontend:** HTML5, CSS (Tailwind CSS)
* **Environment:** Android (Termux / Linux environment)

## Core Features (Planned)

* **Daily Log Entry:** Simple Web UI to input study hours, kanji counts, or code commits.
* **AI Schedule Balancing:** Generates brief daily feedback, recommended focus topics, and rest reminders based on active workload.
* **Local Storage:** Keep logs stored locally without external database dependencies.

## Architecture & Roadmap

```
[ Termux Environment ]
  └─ Flask Server (app.py) 
      ├─ Local REST API Routes
      ├─ Gemini API Client Integration
      └─ Web Dashboard (HTML/JS)
```

- [x] Initial design and documentation
- [ ] Flask backend setup & routing
- [ ] Gemini API integration for log analysis
- [ ] UI layout implementation
- [ ] On-device testing in Termux

## LICENSE

MIT
