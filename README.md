# UDC Workshop 1 — Homework (greenfield)

Starter repo for the first homework of the UDC "Modern Development with Agentic
AI" course.

> Workshop 1: **Сучасний стан розробки з AI** (Modern AI-assisted Development)
> Автор: В'ячеслав Колдовський (Programming Mentor)

This is a **greenfield** exercise: you initialize your **own** small project
inside your fork, configure your Agentic IDE, build a small feature with AI, and
analyze the token/cost footprint. ~1-2 hours.

## Quick start

```bash
gh repo fork koldovsky/2026-udc-01-current-state-ai-sdlc-hw --clone
cd 2026-udc-01-current-state-ai-sdlc-hw
git checkout -b ws01/<github-username>
# follow docs/walkthrough.md
gh pr create --title "WS1: <your name>" --fill
```

Full step-by-step instructions: [`docs/walkthrough.md`](docs/walkthrough.md).

## What's in here

| File | Purpose |
|---|---|
| `docs/walkthrough.md` | Step-by-step: setup, Task 1-4, Definition of Done |
| `.github/pull_request_template.md` | PR checklist (auto-applied) |
| `.coderabbit.yaml` | CodeRabbit auto-review tuned to this homework's DoD |
| `AGENTS.md` | Baseline guidance for your Agentic IDE in this repo |

You create everything else (`app/`, `AGENTS.md` inside it, `docs/*`) yourself —
that's the homework.

## Tools

Cursor / Claude Code / GitHub Copilot (at least one) + a GitHub account +
Node 22+. Questions → the course chat (feedback within 2 weeks).
