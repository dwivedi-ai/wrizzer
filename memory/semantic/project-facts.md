# Project facts

> Distilled invariants of this project. Stack, conventions, structural rules. One claim per line. No narrative.

- cultron is a markdown-first research project; no build system, no production target yet.
- Goal: distill what makes writing feel human into reusable rubrics, prompts, and style notes (O1 → O2 in OBJECTIVES.md).
- O1 KR1 target: ≥20 annotated writing samples with notes on *why* each works.
- Samples live as one-file-per-episode in `memory/episodic/`; patterns live as distilled claims in `memory/semantic/`.
- Sample frame should span genres — collection now contains 7 / 20 samples covering autobiographical, technical/systems, career-strategy blog, pedagogical explainer, corporate manifesto + blog framing, and technical reflection. Still missing: literary essay, longform journalism, fiction, marketing/copy, short-form (tweet / aphorism).
- General craft principles (cross-author signatures) live in the Mozart section of `memory/semantic/preferences.md`; user-voice specifics live in the main list. Patterns are promoted to semantic only after 2+ independent observations.
- Ingestion workflow itself is captured in `memory/procedural/ingest-writing-sample.md` (validated against samples 4–7).
- Owner: tools@kosh.network. Folder is shared via the XO workspaces system (`.xo/` is watcher-owned; agents read but do not write it).
- The user is the author of the systems being written about in technical samples (Hermes, XO workspaces) — treat references as real architecture, not aspirational.

### Writing-partner workflow (added 2026-05-22)

- Project scope now includes acting as the user's writing partner inside this folder — drafting tweets, posts, and articles in the Mozart-of-writing voice. This is *being* the partner in-folder, not *shipping* a tool elsewhere (which is still out of scope per `PROJECT.md`).
- Topic seeds come from the user's X (Twitter) bookmarks, fetched locally via the **xbook** tool (`github.com/dwivedi-ai/xbook`). xbook is read-only by design: it intercepts the GraphQL `Bookmarks` response in a headless Chromium and writes `bookmarks.json`. It does not post, like, follow, or mutate X-side state.
- xbook ships an agent-facing skill at `.claude/skills/xbook/SKILL.md` inside the xbook repo. Install it **project-scoped** at `<cultron>/.claude/skills/xbook/SKILL.md` — **never** globally at `~/.claude/skills/xbook/`. The README's `cp` instruction targets `~/.claude/`; ignore that and copy into this project instead.
- Loop: fetch bookmarks → read tweets → identify recurring themes / trending topics → do a *light* context pass (a search or two, not a deep dive) → draft short-form pieces in the user's voice. The leverage is in the writing, not the research.
- Engagement is a target alongside voice — hook, payoff, brevity, contrast, foil framing. Engagement craft moves are tracked separately from voice patterns; see [[engagement-craft]] once that file exists.
