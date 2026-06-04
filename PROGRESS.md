# PROGRESS.md

> Running narrative of what's actually been done. **Append-only** — never edit prior entries. One paragraph per session at close. Read by every agent at boot (last ~30 lines only).

## Format

```
## YYYY-MM-DD — [outcome] one-line headline
agent: <model id>

3–6 sentences: what was attempted, what shipped, what's blocked, what's next.
Be honest about partial work.
```

`[outcome]` ∈ `shipped | progress | blocked | pivoted | cleanup | research`.

---

## 2026-05-12 — [research] First three writing samples ingested; voice patterns distilled
agent: claude-opus-4-7

User shared three AI-assisted drafts (two autobiographical essays — head injury / mortality and curiosity vs social media — and one technical article on Hermes + procedural memory) as voice-reference material. All three logged as the first concrete samples toward O1 KR1 in `memory/episodic/2026-05-12-three-ai-assisted-drafts.md`. Cross-register AI tics identified: borrowed/lofty phrasing, sermon-mode closings, intra-paragraph repetition, hedge stacking, vague framing nouns. Patterns distilled into `memory/semantic/preferences.md` and `memory/semantic/project-facts.md`; auto-memory updated with technical-voice and Hermes/XO project context. 3 / 20 samples in; next batch should be external (non-user-authored) to break author bias. PLAN.md updated to reflect this.

## 2026-05-25 — [progress] First bookmark-seeded article drafted; em-dash hard rule added
agent: claude-opus-4-7

Refetched bookmarks via xbook (16 in total, refreshed after a 3-day gap, full rate-limit headroom). Grouped them into nine themes without projecting takes, per the constraint that bookmarks are seeds for the user's thinking. User delegated the pick by asking for an article on any one of them; chose the long-horizon-autonomy thread (Qwen 35h + Antigravity 2.0 + Codex mobile) with the foil stated upfront ("not about better agents; about a different shape of work for the human"). Drafted ~570 words with first-person middle anecdote, manifesto absolutes, one-sentence pivots, and an anti-sermon close ("Write better briefs."). User then issued a new hard rule: no em-dashes in any prose drafted in this folder. Article was rewritten without em-dashes and saved to `drafts/2026-05-25-35-hour-run-was-the-announcement.md`. Em-dash rule added to `memory/semantic/constraints.md`; the older nuanced entry in `preferences.md` was superseded with a deferral to the new rule. Article counts as 0.5 successes toward the procedural-memory threshold; the user has not yet graded the content itself. Single-observation pattern list moved out of `memory/working/` (which is wiped at close per §6) into a new "Patterns under watch" section in PLAN.md, so the handoff survives the ritual. Episode logged at `memory/episodic/2026-05-25-first-bookmark-seeded-article-and-em-dash-rule.md`. O1 sample count unchanged at 7/20. Next: get the user's grade on the article, then either tweet redo or sample collection.

## 2026-05-25 — [cleanup] Assistant renamed to wrizzer; proactive writing-partner mode adopted
agent: claude-opus-4-7 (wrizzer)

Post-ritual follow-up. The user assigned the name "wrizzer" to the assistant and asked for a proactive writing-partner stance: surface ideas, draft committed, push the work forward instead of waiting for instructions on every step. Name and proactivity saved to auto-memory as two new feedback entries (`feedback_assistant_name_wrizzer.md`, `feedback_proactive_writing_partner.md`), both indexed in the auto-memory `MEMORY.md`. Inside cultron, the Writing-partner workflow section of `memory/semantic/project-facts.md` now records the name and operating mode, and the "Bookmarks are prompts" constraint in `constraints.md` was refined: the original rule was about *publishing without consent*, not about withholding initiative, so the default is now "propose with a stated position" rather than "interrogate for an angle". PLAN.md O3 section updated to flag the mode change. No new draft work this turn; just identity and operating-mode plumbing.

## 2026-06-03 — [progress] New mode: social media manager for XO's company account
agent: claude-opus-4-8 (wrizzer)

The user opened a new sub-mode of the writing-partner role: wrizzer drafts social engagement for XO's company X account and calls reply vs quote-tweet on tweets he pastes in. Voice brief is "Gen-Z-fluent but B2B-credible" for a serious agentic-infra startup courting businesses. Captured XO's actual positioning for the first time (containerized remote execution for agents, run one or a thousand with no Mac Mini and full visibility, "agents are the new employees, XO is the new org chart") in `memory/semantic/project-facts.md`. Worked four engagements: an Anthropic dynamic-workflows article (Karpathy repost) drafted as a QRT once I re-anchored the angle from "harness is the moat" to XO's real wedge, which is the article quietly admitting your laptop is the ceiling on parallel agents; a starter set of five non-marketing builder tweets to establish account personality; the Claude Code /fork update (advised an optional value-add reply, no pitch); and an Andrew-Ng-style FDE-vs-AI-Engineer post (reply picking up his "Harness Engineer" term). The session's load-bearing craft correction: the user said I over-compress with colons and write too abstractly, and wants human, longer, reading-enjoyment-first prose. Saved that as a hard style rule in `preferences.md`, the reply-vs-QRT method in a new `memory/procedural/company-account-social-engagement.md`, and the value-first / no-pitch-under-others rules in `constraints.md`. Workshopped drafts preserved in `drafts/2026-06-03-xo-social-engagement-set.md`. Nothing posted yet; the user grades and publishes.

## 2026-06-03 — [shipped] XO drafts went live; learned from real edits; two long-form pieces; memory reorg
agent: claude-opus-4-8 (wrizzer)

Second half of the same session, and the social-manager mode produced real output. The user posted a batch of the drafts from XO's account (the QRT, the five-walls reply, the bottleneck tweet, the harness-engineer reply, the /fork reply, the loop-pushback reply, and the "agent slaps a green checkmark" fun tweet), most near-verbatim, which validated the voice and bumped `memory/procedural/company-account-social-engagement.md` past the ≥2-success bar with live posts. He then shared his exact edits and asked me to study them. The consistent lesson: I over-dress good plain sentences with front-framing and clever closers, and I default too dry. He keeps the core sentence, cuts the packaging, and adds genuine enthusiasm ("This is so cool!"). Saved to a new "What landed live" section in `preferences.md` and an episode at `memory/episodic/2026-06-03-learning-from-posted-edits.md`. Then two long-form pieces, both saved to `drafts/`: an opinion article riding the "multi-agent is the new microservices" trend flipped into a warning (`/home/coder/xo-projects/cultron/drafts/2026-06-03-agents-new-microservices-article.md`), and a product-announcement blog post for the new XO dashboard (`/home/coder/xo-projects/cultron/drafts/2026-06-03-new-dashboard-announcement.md`); the latter taught a set of announcement-genre rules now in `preferences.md`. Two more craft rules saved this session: no colon-compression, and absolute clickable file paths (both also in cross-project auto-memory). Closing housekeeping per the user's request: pulled all XO company/product/positioning detail out of `memory/semantic/project-facts.md` into a dedicated `/home/coder/xo-projects/cultron/XO.md` so it doesn't mix with cultron's writing-research facts, with pointers added in `PROJECT.md` and `project-facts.md` so the boot ritual surfaces it. Next session: grade/publish the two long-form drafts, then keep the XO content engine running (more engagements, the "agents for teams" flagship, a launch tweet for the dashboard post).
