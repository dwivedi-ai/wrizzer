# XO — company reference

> Single source of truth for XO (the user's company) so it doesn't mix with cultron's writing-research memory. Load this whenever the task is making content for XO. Kept current by wrizzer; the user owns and posts the content.
>
> Related memory: voice/craft rules in `memory/semantic/preferences.md`, hard rules in `memory/semantic/constraints.md` ("Company-account social media"), the engagement method in `memory/procedural/company-account-social-engagement.md`. Drafts live in `/home/coder/xo-projects/cultron/drafts/`.

---

## What XO is

XO is a serious agentic-infrastructure startup selling to businesses. The user is an owner/operator and posts the company's social content himself.

**Core product — XO Workspaces.** A containerized, remote execution environment. A sandbox where AI agents run securely on your own infrastructure. Properties:

- **On-demand** — spin one up in seconds.
- **Shareable** — a team collaborates inside the same agent environment.
- **Scalable** — run one or a thousand, no hardware constraints.
- **Secure** — guardrails, oversight, and full visibility, so you always know what your agents are doing.

**Value prop.** Takes AI agents from experimentation to production. "You don't need a Mac Mini. You don't need DevOps. You need XO."

## The four problems XO names

1. **Hardware dependency** — you need a Mac Mini or dedicated hardware to run OpenClaw and other agents, and owning one doesn't make it simple to run or manage.
2. **No visibility** — no oversight, no guardrails, no view into what agents are actually doing.
3. **The scale cliff** — going from one developer experimenting to a team running agents in production is a cliff, not a ramp.
4. **No AI workforce layer** — every org needs an AI workforce running for it, and the infrastructure to make that happen doesn't exist yet.

## Narrative and messaging

- Hero line: **"Welcome to Your Agentic Experience."**
- **Agents are the new employees. XO is the new org chart.**
- The infrastructure was always the moat. Products change, the platform endures.
- Accessibility is non-negotiable. If you need a CS degree to use agents, XO has failed.
- CTA frontrunner: "Re-org Yourself." Alternatives: "Launch Your Org", "Build Your AI Org", "Start Your Agentic Experience."
- This isn't a pivot, it's a convergence. Same core story since Suraj's EthCC 2025 talk.

## Product surface (from the new dashboard, June 2026)

Workspaces come in types, including **OpenClaw workspaces** and **Hermes workspaces** (Hermes is a self-learning system the user built). The dashboard has four tabs:

- **Launch** — the agent's home. Workspace status with start/stop, live CPU/RAM and cowork API status, direct connections to VS Code, Cursor, the OpenClaw Gateway (OpenClaw workspaces) or Hermes Gateway (Hermes workspaces), and machine logs. Connections are on the page now, not hidden behind a Configure button.
- **Setup** — Overview (setup checklist: model, data, channels, secrets), Models (Claude Code, Codex, and now OpenRouter), Data (Google Drive, OneDrive, GitHub, Vercel; credentials stay in the project's workspace, not on the platform), Channels (Telegram, WhatsApp, Slack; tokens validated locally, scoped to the project), Secrets (edit the project's `.env` directly, saved instantly).
- **Work** — every XO project in one place. Token usage, timeline, todos, activity, and a Files view to browse and upload, all without opening the IDE.
- **Usage** — accurate cost, tokens, messages, latency, with charts over time. Numbers reconcile, no discrepancy.

## XO's social wedge (how to position it in content)

- When content celebrates massively parallel / fan-out agents, the honest hook is that the ceiling on all that parallelism is your own hardware. XO removes the ceiling and adds visibility. (This came up again and again: the Karpathy-reposted workflows article, the "Every Agentic Hack" article full of Mac Mini and power-brick pain.)
- Anchor co-signs to **where agents run**, not to orchestration logic. Tools like Claude Code's dynamic workflows ARE the harness logic; XO is where the harness runs. XO is **complementary** to Claude Code, not a competitor. Many XO buyers live in the Claude Code community.
- The "agents for teams and production" lane is wide open. Solo-dev laptop-hack content is crowded; nobody owns hacks for running agents as a team, at scale, with visibility. That's XO's lane to claim.

## Ecosystem note

The user built **Hermes** (self-learning ecosystem that gets better at repeated tasks) and **XO workspaces**. **OpenClaw** is an agent system XO runs/supports. The "Every Agentic Engineering Hack" viral article (June 2026) lists "Hermes for the self-learning ecosystem that gets better at repeated tasks", which may be the user's Hermes getting an organic mention — confirm with the user before leaning on it.
</content>
