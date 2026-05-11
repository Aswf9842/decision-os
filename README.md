<p align="center">
  <a href="https://img.shields.io/badge/license-MIT-blue"><img src="https://img.shields.io/badge/license-MIT-blue" alt="MIT"></a>
  <a href="https://img.shields.io/badge/PRs-welcome-ff69b4"><img src="https://img.shields.io/badge/PRs-welcome-ff69b4" alt="PRs Welcome"></a>
</p>

<h1 align="center">🧠 Decision OS</h1>

<p align="center">
  <b>Structure your choice. Let AI simulate every path.<br>
  Read the first-person letter from the "you who chose differently."</b>
</p>

---

## What is this?

A decision-making tool with two parts:

1. **Web app** — Structure your decision. Define options. Generate a precise prompt for AI.
2. **AI prompt** — Paste into ChatGPT or Claude. It simulates each option with a specific timeline, then writes a **first-person reflection from the alternate self** — the version of you who chose the other path.

You don't get generic advice. You get **a concrete simulation of what each version of you actually experienced, thought, and felt.**

---

## How It Works

```
You face a choice
    ↓
Web app organizes: situation → options → stakes → gut feeling
    ↓
Copy the AI prompt → paste into ChatGPT/Claude/Gemini
    ↓
AI simulates EVERY option:
  • Month 1-3: What happens immediately
  • Month 4-12: How things develop
  • Year 2-5: Where this path leads
  • "Alternate Self" letter: First-person reflection from that version of you
    ↓
You decide (with concrete, specific information)
    ↓
Log the outcome → your next decision is smarter
```

---

## Quick Start

```bash
# 1. Open the web app
open index.html

# 2. Describe your situation + options
# 3. Click "Structure My Decision"
# 4. Copy the AI prompt → paste into ChatGPT
# 5. Read the simulation results
```

Total time: **2 minutes.**

[See QUICKSTART.md](QUICKSTART.md) for detailed steps.

---

## What Makes This Different

| Other tools | Decision OS |
|-------------|-------------|
| "Make a pros/cons list" | Multi-branch simulation with concrete timelines |
| "You'll learn and grow" | Specific events at month 1, 4, 12, 24 |
| Third-person advice | **First-person letter from your alternate self** |
| One-time use | History + templates = compound learning |
| Requires an account | Open index.html. That's it. |

---

## Project Structure

```
decision-os/
├── index.html              ← ⭐ Web app (open in browser)
├── PROMPT.md               ← AI simulation prompt
├── README.md               ← You are here
├── QUICKSTART.md           ← 2-minute guide
├── CHANGELOG.md            ← Version history
├── LICENSE.txt             ← MIT
├── templates/              ← For systematic tracking
│   ├── profile.md
│   ├── behaviors.yaml
│   ├── decision-log.md
│   └── alternate-selves-log.md
└── examples/
    └── career-decision.md
```

---

## Example Alternate Self Letter

When you paste the prompt into AI with "Should I take this startup job?", the AI generates something like this:

> *"I took the startup. Month 2, the CTO quit. I was suddenly responsible for the entire backend. I cried in the bathroom on a Tuesday. But by month 7, I had architected a system I'd never have touched at BigCo. I can't say it was fun. But I would tell my past self: take it. Not because it's safe — because you'll find out who you are when it isn't."*

That's the kind of output this system produces. Not "you'll grow." **A specific person, in a specific situation, telling you exactly what they went through.**

---

## Who This Is For

- **Anyone facing a real decision** and tired of pros/cons lists
- **People who want concrete** — "what will actually happen if I choose this?"
- **Growth-minded** — you want to learn from every choice, not just make it
- **Overthinkers** who need structure, not more options

---

## Community

- ⭐ **Star** this repo
- 🐛 **Open an issue** — what would make this better?
- 🔀 **Fork and PR** — contributions welcome
- 🗣️ **Share** with someone facing a tough choice

---

## License

MIT — use it, fork it, improve it.

---

<p align="center">
  <i>Every choice creates a version of you. The only question is: do you get to learn from them?</i>
</p>
