# ZEROCROWD // PHISHGAME

> **Analyse the message. Recognise the phishing.**
> A gamified cybersecurity education platform that trains genuine phishing-recognition skills — not merely awareness.

## Play · Learn · Defend

This repository hosts the official website (a unified, single-HTML document) for ZEROCROWD // PHISHGAME, a web-based training environment for phishing recognition. Users are placed in the role of an analyst: realistic email simulations across **five escalating difficulty tiers**, where you annotate the suspicious elements, justify your assessment, and issue a final judgment — **phishing or legitimate**.

Available bilingually in **English (EN)** and **Greek (ΕΛ)**.

## How It Works

- **Structured Annotation** — Select any part of the sender, subject, or body and classify it as safe or malicious. Each annotation is stored as a structured note comprising the text, its classification, and the field in which it was identified.
- **Reasoning Assessment** — The free-text justification is evaluated either by a **Large Language Model** or by a **deterministic algorithm** based on concept coverage, alignment with known indicators, and the relevance of the selected snippets.
- **Progression & Ranking** — **Nine achievements**, a **five-tier progression system**, and a **global leaderboard of the top fifty users** ranked by experience points reward distinct competencies rather than the overall score alone.

## Platform at a Glance

| Metric | Value |
|---|---|
| Scoring dimensions | 5 |
| Difficulty tiers | 5 |
| Indicator categories | 6 |
| Achievements | 9 |
| Arena modes | 3 |
| Educator sections | 7 |

## The Problem

Human judgment is a critical layer of cybersecurity.

Phishing is among the most significant forms of social engineering, and it exploits a critical characteristic of modern organisations: their daily dependence on electronic communication. Even when an organisation deploys email filtering, endpoint protection, firewalls, and detection systems, **the user remains a critical point of decision**.

Traditional cybersecurity awareness training relies on presentations, informational materials, and static quizzes. Such approaches transmit basic knowledge, but they do not necessarily ensure that a user can **apply** that knowledge when confronted with a genuinely suspicious message.

### The core pedagogical principle

> *"Awareness should be transformed into a repeatedly practised skill."*

Rather than merely informing users of the risks, PhishGame places them in the role of an analyst: they examine realistic emails, identify the critical elements, evaluate them, justify their decision, and assume responsibility for the final judgment.

## Comparative Advantage

| Traditional Training | ZeroCrowd PhishGame |
|---|---|
| Static presentations | Interactive analysis of realistic emails |
| Fixed examples | Dynamic scenario generation through LLM |
| Correct / incorrect | Multidimensional scoring engine |
| Single difficulty | Adaptive progression tiers |
| Periodic awareness | Continuous practical training |
| General feedback | Targeted EduTips |
| Individual assessment | Individual practice and group Arena |
| Theoretical knowledge | Practical decision-making |

> The best defence isn't merely knowing the risk. It is having practised recognising it.

## Site Structure

The website is a **Unified HTML (All-in-one)** document — a single self-contained HTML file with no frameworks, no build tools, and no backend, covering the following sections:

- Platform overview
- How It Works
- Features
- Arena
- Educators
- Organisation
- Applications
- Contact / Request a Demonstration
- Documentation

## Getting Started

No install or build step is required:

```bash
# serve it locally (any static server works)
python -m http.server 8000
```

Then open `http://localhost:8000` — or simply open `phishgame.html` in a browser.

## Repository Contents

```
phishgame.html   # the entire website — markup, styles, and JS, all inline
README.md        # this file
LICENSE.md       # proprietary license — see below
```

## License

**Copyright © 2026 Dr. Stylianos Karagiannis. All rights reserved. Full Intellectual Property rights claimed by Dr. Stylianos Karagiannis.**

This project is proprietary software under an "All Rights Reserved" license. Unauthorised copying, use, modification, distribution, or sale is strictly prohibited. The Ionian University retains shared benefits and exploitability options as defined by separate written instruments. See [LICENSE.md](./LICENSE.md) for full terms.

The Licensor welcomes collaborations and investments, including proposals for branch products — all subject to a separate written agreement.

---

**Think · Analyse · Decide · Stay Safe**

© 2026 ZeroCrowd PhishGame. Better awareness. Stronger defences.