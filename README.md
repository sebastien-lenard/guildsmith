<!-- README.md -->
<!-- SPDX-FileCopyrightText: Copyright (C) 2026 Sebastien Lenard <sebastien.lenard@gmail.com> and Contributors -->
<!-- SPDX-License-Identifier: Apache-2.0 -->
# Guildsmith 🛠️ — A deterministic framework designed to build software automation

<img src="assets/images/guildsmith_logo_64.png" alt="Guildsmith deterministic framework designed to build software automation logo" align="left" width="64" height="64" style="margin-right: 15px; margin-bottom: 10px;"> A deterministic, zero-cost framework designed to build custom software automation using isolated, standard web-based AI interfaces (like gemini.google.com). 

Drawing inspiration from both historical trade guilds and high-stakes cooperative gaming, **Guildsmith** establishes a structured operational protocol to coordinate an elite party of specialized, independent AI contractors. This framework allows a single human operator to manage data flow between separate chats—addressing operational automation needs **without the need for an IT department, software code expertise, or expensive software infrastructure**, while actively mitigating the risks of automated AI drift.

---

## 💼 Why This Matters for Production Managers

As a production manager on a shop floor, your day is focused on metrics, logistics, and reporting—not writing code or managing databases. Traditional automation solutions usually require dedicated IT support or expensive cloud subscriptions. 

Guildsmith flips the script by applying standard manufacturing principles to AI:
* **Zero Software Costs ($0):** Operates entirely within standard, free web browser chats. No API keys or software licenses required.
* **No "Black Box" Volatility:** Unlike typical AI pipelines that think for themselves behind the scenes, you act as the physical conveyor belt between separate chats. You see every input and approve every step.
* **Built-in Quality Control:** Features an aggressive "Weighted Decision Framework" and dedicated tester protocols ensuring the AI never changes your logic or generates outdated methods.
* **Airtight Security:** Designed to prevent sensitive company passwords or proprietary parameters from ever leaking into public servers.

---

## 🏗️ Repository Architecture

The project files follow a strict layout to separate historical decisions from operational blueprints:

```text
├── README.md               # This landing page and framework overview
└── docs/
    ├── designs/           # Active, executable blueprints and prompts
    │   └── 0001-system-design-v0.1.md    
    └── history/            # Origin files, transcripts, and context
        └── 0001-genesis-transcript.md

```

---

## 🚀 How to Get Started

1. **Review the Framework Blueprint:** Read the strict organizational rules and multi-LLM setup protocol in [`docs/designs/0001-system-design-v0.1.md`](docs/designs/0001-system-design-v0.1.md).
2. **Deploy the Team:** Open four separate browser tabs on your computer. Use the dedicated system prompts provided inside the blueprint to spin up your individual virtual team:
* **Tab 1:** The Business Analyst (Processes your raw operations layout)
* **Tab 2:** The Software Architect (Balances your security vs. efficiency weights)
* **Tab 3:** The Developer (Compiles the clean, documented code)
* **Tab 4:** The Tester & QA (Attempts to break the code before deployment)


3. **Audit the Origin:** To understand the specific structural decisions and why the protocol was engineered this way, read the origin log in [`docs/history/0001-genesis-transcript.md`](docs/history/0001-genesis-transcript.md).