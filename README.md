# ZeroCrowd-PhishGame

Website and information for **ZEROCROWD//PHISHGAME** — a live phishing simulation training arena. Hand-forged emails. 5 escalating tiers. Point-and-click the suspicious indicators, explain your reasoning, level up. Your call: PHISHING or LEGIT.

A self-contained **landing / marketing page** for PhishGame, a gamified phishing recognition training platform. Built as a single HTML file with no frameworks, no build tools, and no backend.

## Features

- **Inbox Mission** — 5-stage rounds: examine an email, highlight suspicious indicators, justify your reasoning, set confidence, then call it phishing or legit.
- **Adaptive difficulty** — 5 tiers (Beginner → Master), XP-gated.
- **Multidimensional scoring** — 5 signals (Decision, Indicators, Time, Reasoning, Bonus) with an Evidence Gate and combo multiplier.
- **6 phishing indicator categories** — fake domain, credential request, suspicious link, urgency, attachment risk, minor hint.
- **9 achievements** — first blood, perfect catch, fast hand, streak master, and more.
- **Deathmatch Arena** — real-time competitive modes (Deathmatch, Blitz, Custom) with configurable timers.
- **Educator Control Room** — 7 instructor sections: Overview, Players, Logs, Analytics, Comms, Corpus, Config.
- **AI-graded reasoning** — LLM or deterministic grading via OpenRouter, Ollama, or OpenAI-compatible APIs.
- **Bilingual** — Greek and English.

## Tech

- Vanilla HTML5 / CSS3 / JavaScript (no frameworks)
- Design: dark cyberpunk aesthetic, neon accents (amber / magenta / cyan / green), CSS custom properties, `clip-path` cut-corner geometry, CSS Grid + Flexbox responsive layout
- [FormSubmit.co](https://formsubmit.co) for zero-backend demo-request submissions
- Fonts: Google Fonts — Inter + JetBrains Mono

## Getting Started

No install or build step required:

```bash
# serve it locally (any static server works)
python -m http.server 8000
```

Then open `http://localhost:8000` — or simply open `phishgame.html` in a browser.

## Structure

```
phishgame.html   # the entire site — markup, styles, and JS, all inline
```