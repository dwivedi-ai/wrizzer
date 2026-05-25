---
date: 2026-05-25
tags: [o3, drafting, em-dashes, bookmarks, article]
outcome: partial
---

## What

First completed article drafted from a bookmark seed (after the failed tweet attempt on 2026-05-22). User picked the angle by delegation ("write an article on any one of these") and the agent picked Qwen 3.7-Max / Antigravity 2.0 / Codex mobile as the seed with a stated foil position ("not about better agents; about a different shape of work for the human"). After delivery, the user added a new hard rule: no em-dashes in any prose drafted in this folder. The article was then rewritten and saved to `drafts/2026-05-25-35-hour-run-was-the-announcement.md`.

## Why it mattered

Two firsts in one session. First, this is the inaugural complete article-length output of the writing-partner workflow (O3). The previous attempt produced five tweet candidates and a factual overclaim; this attempt produced one committed piece with the foil named upfront and the cold-reader test passed. Second, the em-dash rule is a real escalation of a craft principle already in semantic memory. The earlier rule said "em-dashes used to stage punchlines are slop, but genuine breaks are fine." The user has now collapsed the carve-out — no em-dashes, full stop. That tells us that the previous nuanced rule was not getting enforced strictly enough, and the failure mode (drafting prose peppered with em-dashes that read as AI) was happening on sight.

## How it went

Boot ritual ran clean: PROJECT, OBJECTIVES, PLAN, three semantic files, last PROGRESS, todos, activity, last 3 sessions. State was as PLAN.md described: 7/20 samples on O1, O3 in "redo the failed tweet" state, 11 bookmarks last fetched 3 days ago.

User opened with "hi", got a brief state summary and two-option offer (sample or tweet redo). Then asked for bookmarks fetched and themes. Pre-flight on xbook showed clean state (499/500 rate limit, no failures, 3-day-old fetch), so fetched -n 50, got 16 (cap hit user's actual total). Grouped the 16 bookmarks into nine themes without projecting takes onto them, per the constraint that bookmarks are seeds for the user's thinking and not raw material for the agent to opine on. Asked the user to pick a seed and supply the angle.

User instead said "write an article on any one of these". This was a delegation, which is the exception PLAN.md already authorised ("one I pick cold if they prefer, with a stated position they can grade"). Picked the long-horizon-autonomy thread (#2) because it had the strongest foil baked in (the "agents make typing faster" assumption) and connected to the user's own systems work (Hermes, XO workspaces, long-running sessions). Stated the position in one line before drafting, so the user could redirect cheaply if the angle was wrong.

Drafted ~570 words. Voice signatures landed: first-person middle anecdote about the 90-seconds-before-enter being where leverage is decided, manifesto absolutes ("This is a managerial skill, not a typing skill."), one-sentence pivot paragraphs at the foil-naming beats, flat anti-sermon close ("Write better briefs."), specific names throughout (Qwen 3.7-Max, 35 hours, 1,000+ tool calls, Antigravity 2.0, Codex mobile, Tibo's /slow mode). Self-critique noted one risk: the personal-infrastructure paragraph was generic enough that I might be projecting — flagged it to the user with a swap-or-drop offer.

User responded with the em-dash rule and the shutdown ritual ask. Did not grade the article content itself yet, which means the article is "draft pending user grade", not "successfully delivered". The procedural rule about "≥2 validated successes" before promoting to procedural memory still holds; this is at most 0.5 successes — the structure worked, the voice landed, but the user hasn't endorsed it.

Em-dash rewrite was mechanical: nine em-dash sites in the draft, all replaced with one of (a) a period split into two sentences, (b) a comma parenthetical, (c) a colon for list intro, or (d) an English connective ("because", "since", "instead of", "and so"). The "instead" replacement in particular saved a sentence that originally read with an em-dash as setup-into-reveal — the very pattern the old preferences entry already flagged as slop.

Open thread for next session: get the user's actual grade on the article. If they endorse it (or endorse it after light edits), that's success #1 toward the procedural-memory threshold. Then redo a tweet from a different bookmark for success #2.

Working-memory housekeeping: the previous session left `memory/working/single-observation-watch.md` in place as a cross-session handoff for O1 pattern-watching, which violates AGENTS.md §6 (working/ wiped at close). Resolved by moving the contents into a new "Patterns under watch" section in PLAN.md before wiping, so the information survives the ritual and the rule holds.
