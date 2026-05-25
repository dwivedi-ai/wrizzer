---
date: 2026-05-12
tags: [sample, ai-assisted, voice, autobiographical, technical, first-collection]
outcome: partial
---

## What

The user shared three AI-assisted drafts in one session as voice-reference material and asked them to be ingested — the first concrete samples toward O1 KR1 (≥20 annotated examples).

## Why it mattered

These are the first data points in the ultron collection, and they doubled as a working specification of the user's voice. They also let cross-register patterns emerge (same AI tics appeared in both autobiographical and technical drafts), which is exactly the kind of signal O1 is looking for.

## How it went

The three drafts:

1. **Autobiographical essay — head injury and mortality.** Concrete opening: closing and opening his hands after waking up unconscious in the hospital. Anchors to Steve Jobs's "last day of my life" quote. Indian-English register present ("Rupees" appears in the second essay, not this one; "took me to the hospital in time", "thanks to my friends"). AI tics: "make a dent in the universe", "advancement of all humankind", "the energy that's running this universe", a long compound mid-sentence ("I just looked at my hands and I closed it and opened it again"), and abstract uplift in the close ("I see a world that is learning and growing, which fascinates me with the spirit of humankind"). The mortality anecdote is the load-bearing thing; the philosophical scaffolding around it is the AI.

2. **Autobiographical essay — curiosity vs social media / money.** Concrete openings: the questions he asked his 9th-grade sister about gravity, the 300 Rupees first payment for a simple program. Anchors to Feynman's "it's fun to find things out". AI tics: a textbook sermon-mode close ("In conclusion, we must always be mindful of our curiosity and nourish it…"), repeated ideas across paragraphs (curiosity vs distraction is restated three different ways), and "we/us/people" drift where the feeling was personal. The two anecdotes (sister's questions, first payment) are gold; the moralising between and after them is the part to strip.

3. **Technical article — Hermes / systems engineering / procedural memory.** Frames a real incident: permission mismatch → temp files not clearing → cache growth → slow DB writes → queue backup → pipeline instability. Hermes detected and recovered, then stored the recovery as procedural memory. Signature stylistic move: one-sentence paragraphs at key beats ("Nothing failed immediately." / "Things degrade gradually." / "Scripts follow instructions." / "They do not understand context."). AI tics: hedge stacking ("quite a bit", "extremely important", "very quickly", "honestly", "of course"), vague framing nouns ("the nature of infrastructure management", "something important"), LinkedIn-cadence transitions ("But overall…", "And honestly…"), and the same idea restated in different words within the same post. The debugging chain and the one-sentence-paragraph rhythm are the human substrate.

Cross-register patterns that showed up in *both* the autobiographical and technical samples:
- **Borrowed/lofty phrasing where the borrowed line is doing the rhetorical work** (a quote, a metaphor, a stock phrase). The simpler human version replaces it with the user's own observation or cuts it entirely.
- **Sermon-mode / uplift closings** that abstract away from the specific moment the piece was built on.
- **Intra-piece repetition** — the same idea restated 2–3 times across paragraphs, which is a giveaway that the draft was generated rather than thought through.
- **Hedge stacking and meta-framing nouns** in places where a bare claim would land harder.

Patterns extracted into `memory/semantic/preferences.md`. Per AGENTS.md §8, this is one episode (a session's worth of analysis); future samples in other sessions will be their own episodes. Procedural memory was *not* written — no workflow has succeeded ≥2 times yet (the simplification recipe is described but not validated against an actual edit).

Auto-memory (cross-project, `~/.claude/.../memory/`) also updated with:
- `user_writing_voice.md` (autobiographical patterns)
- `user_writing_voice_technical.md` (technical patterns)
- `project_hermes_xo.md` (Hermes + XO context, since the technical sample referenced systems the user actually builds)
