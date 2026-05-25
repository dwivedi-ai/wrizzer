---
name: ingest-writing-sample
trigger_when: The user shares a writing sample (their own draft, a quoted article, a paste, a URL excerpt) and asks for it to be analysed and added to the cultron collection.
---

## Steps

1. **Strip identifiers before reasoning about the piece.** Confirm with the user once per session whether to keep author/site/year/figure metadata. Default (and confirmed standing default for this user as of 2026-05-22): **no PIIs, no dates, no identifying counts**. That means: no real-person names (including cited researchers, friends, public figures referenced for credibility), no site URLs or handles, no exact dates or years, no exact numbers that uniquely identify the source. Public technical concepts (programming-language names, framework names, named scientific patterns) are not PIIs and can stay when they're demonstrating a craft move.

2. **Identify the genre and register first.** Confessional autobiographical, manifesto, career blog, pedagogical explainer, corporate manifesto/values letter, technical reflection, founder letter, etc. The register sets expectations for which moves are appropriate — manifesto-voice and explainer-voice succeed with different toolkits.

3. **Catalogue the moves that land.** For each, quote the exemplary phrase (within PII bounds) and *name* the move ("caveat-without-yield", "frame-against-a-foil", "one-sentence paragraph at definitional beat", "calibrating hedge", "register-break truth-marker", etc.). Vague critique is forbidden per `memory/semantic/constraints.md` — be specific.

4. **Catalogue what doesn't land even in a piece the user otherwise likes.** These are valuable counterexamples — they show the failure modes coexisting with strong middles. Don't infer the user has changed his mind because a weak patch survives.

5. **Cross-reference each move against prior samples.** Sort each pattern observed into:
   - **3+ observations across independent samples** → locked-in cross-author signature (typically already in semantic; reinforce in the episode note).
   - **2 observations** → promote to `memory/semantic/preferences.md`. General craft moves go in the Mozart section at the bottom; user-voice specifics go in the main list.
   - **1 observation** → hold in the episode's "single-observation patterns held" list, and add to `memory/working/single-observation-watch.md` so the next session can pick up the thread.

6. **Write the episode file** as `memory/episodic/YYYY-MM-DD-{genre-slug}.md`. Slug describes the genre/topic, never the title (titles are identifiers). Format per AGENTS.md §8 (frontmatter + What / Why it mattered / How it went). Episode entries for this project run long on purpose — the "How it went" section is the load-bearing analysis. Number the sample in the tags (`sample-N`).

7. **Apply at most one or two semantic updates per ingestion.** The semantic file is auto-loaded into every session's prefix; keep it tight. Each new line should be a one-claim distillation, not a narrative.

8. **Do not touch `PLAN.md` per-sample.** Update it once per session with the new sample count, genre spread, and any shifts in held-pattern watchlist. Do not touch `PROGRESS.md` mid-session — it is closing-only per AGENTS.md §5.

## Gotchas

- **The "no hedges" rule has two faces.** `memory/semantic/preferences.md` distinguishes **flinching hedges** (cut — they soften a confident claim) from **calibrating hedges** (keep — they signal the strength of a contestable personal preference). Rule of thumb: if cutting the hedge would make the sentence more accurate, it was flinching; if cutting it would make the sentence over-claim, it was calibrating. Don't recommend cutting calibrating hedges.
- **The user's own drafts and external samples are different epistemic statuses.** The user's drafts are voice-reference for *his* voice; external samples are evidence for *general* human-writing patterns. Patterns observed in *both* a user draft and an external sample are the strongest signals — those are the safest to lift to semantic.
- **Three semantic files only.** `preferences.md`, `project-facts.md`, `constraints.md`. Do not add new files under `memory/semantic/`. General craft principles go in the Mozart section of `preferences.md`.
- **Scare-quotes are not all the same move.** The existing rule "drop scare-quotes around plain words" applies to apologetic quotes (the writer flinching from the word). Skeptical / interrogative quotes (the writer flagging "I'm about to complicate this term") are a different move and can stay — see sample 7's `"faster"` programming language.
- **A piece can have strong middle + weak Epilogue/coda** (samples 5 and 6 demonstrated this). Annotate the weak patch explicitly as a failure mode; do not pretend the user endorses it because he likes the piece.
- **Don't write a procedural memory after one success.** This file itself was written after the workflow above succeeded 4 times in a single session (samples 4–7 on 2026-05-22). Procedural memory is the highest-leverage kind and the most dangerous to fabricate.

## Last validated

2026-05-22 (workflow run 4 times this session across samples 4 through 7).
