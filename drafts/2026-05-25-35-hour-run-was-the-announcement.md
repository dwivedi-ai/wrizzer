---
date: 2026-05-25
seed: bookmarks (Qwen 3.7-Max, Antigravity 2.0, Codex mobile, Tibo /slow)
status: draft (pending user grade)
---

# The 35-hour run was the announcement

Three things shipped in the same week and they were all the same announcement.

Qwen 3.7-Max ran for 35 hours on a kernel optimization task with 1,000+ tool calls. Antigravity 2.0 added scheduled tasks and multi-agent teams. Codex appeared in the ChatGPT mobile app so you can steer execution from your phone while the work runs on a devbox at home.

Read together: the keyboard is no longer the interface.

For two years the agent UX assumption has been that you sit at the terminal and watch tokens stream. The 35-hour number rules that out. Nobody watches 35 hours of tokens. The mobile-Codex screenshot makes the new shape explicit, because the laptop keeps working while you're at the dentist. The scheduled-tasks feature in Antigravity is the same idea with a calendar attached.

This is a different category of tool than the one we've been benchmarking.

The default story about coding agents has been that they make typing faster. Faster autocomplete, faster boilerplate, faster diffs. The category was understood as a velocity upgrade for the person at the keyboard.

That story is now too thin to carry the product. The person who gets leverage from a 35-hour run isn't the fastest typist, since that person isn't at the keyboard for most of the run anyway. They're the person who is good at *defining a delivery*: scoping a task tightly enough that an agent can grind on it without supervision, recognising when it's on the wrong scent, knowing when to interrupt and re-scope.

This is a managerial skill, not a typing skill.

And it's harder to learn. Typing is mechanical; defining a delivery is judgment. The engineers who already do this with juniors, scoping a task tightly enough that work comes back finished instead of half-done with three Slack threads attached, pick it up immediately. The ones who got senior on raw typing speed are the ones most disrupted, because the muscle they built is for a problem that's been reframed.

I've been building infrastructure for this kind of work: long-running sessions, agent-to-agent message channels, project folders that survive between runs. The pattern that has emerged is unflattering to my old habits. The part where I sit and watch is the cheap part. The expensive part, the part where leverage is gained or lost, is the 90 seconds before I hit enter: what am I actually asking for, by when, with what guard-rails, and how will I know it's done.

Get those 90 seconds right and the agent runs for hours without me. Get them wrong and I'm rescuing a wreck at hour three.

The interesting consequence isn't that typists become obsolete. It's that the next generation of effective engineers will be the ones who learn to do this work as managers from day one. The person whose instinct is "let me just write it myself" is the one who underuses the tool. The person whose instinct is "let me write a spec the agent can grind on" is the one whose week looks structurally different.

You can already see who's in which camp. The engineers who report being blown away by Codex tend to be the second kind. The ones who shrug tend to be the first, because they're benchmarking against their own typing speed, which the tool doesn't try to beat.

Vendors are converging on this faster than the discourse is. Tibo at OpenAI floated a `/slow` mode for batch compute the same week. The shape of the work is changing under us.

Write better briefs.
