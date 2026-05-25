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
