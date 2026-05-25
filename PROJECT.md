# PROJECT.md

## Name

cultron

## One-line description

A research project studying content creation and what makes writing feel human — with the goal of distilling reusable patterns, rubrics, and prompts.

## Why this exists

AI-generated writing is fluent but often hollow: it averages, hedges, and signals its origin. The goal here is to study what makes human writing land — voice, specificity, rhythm, risk — and turn those observations into a practical playbook that can guide both humans and agents toward writing that doesn't read as machine-made.

## In scope

- Collecting and analyzing examples of writing that feels distinctly human
- Identifying patterns: voice, structure, diction, rhythm, specificity, stance
- Distilling findings into reusable artifacts: rubrics, prompts, style notes
- Comparative study (human vs AI drafts of similar pieces)
- Acting as the user's writing partner inside this folder — using X bookmarks (via the local `xbook` tool) as topic seeds for drafting tweets, posts, and articles in the Mozart-of-writing voice

## Out of scope

- Shipping a production writing tool or agent to others (the writing partner runs *inside this folder*, for this user, not as a packaged product)
- Domain-specific copywriting work for clients
- Building model fine-tunes or training pipelines
- Any write-side automation on X (posting, liking, following). xbook is read-only by deliberate design — that boundary holds.

## Stack & conventions

Markdown-first knowledge base. No build system. Memory and notes live in this folder per AGENTS.md.

**External tooling:**
- `xbook` (`github.com/dwivedi-ai/xbook`) — fetches the user's X bookmarks to `bookmarks.json`. Setup is per-machine via `xbook --setup`. Its agent skill is installed **project-scoped** at `.claude/skills/xbook/SKILL.md` — never globally.

## Stakeholders

- **Owner:** tools@kosh.network
- **Other peers:** see `.xo/peers.json`

## How to run / build / test

No build yet — this is a knowledge/research project. Notes live in `memory/` and `PROGRESS.md`.
