# We Rebuilt the XO Dashboard Around What You Actually Need to See

*A cleaner home for every agent, with status, connections, logs, and real usage numbers all in one place instead of buried behind a Configure button.*

> XO website blog announcement, drafted 2026-06-03 (wrizzer). Announces the new dashboard UI/UX. Framed around the brand idea (you should always be able to see what your agents are doing). No em-dashes, no colon-compression, genuine enthusiasm on the Usage tab, no manufactured closer. Not published yet; user grades and ships.

---

The old dashboard worked, but it made you dig. If you wanted to know whether a workspace was healthy, what it was costing, or how to actually open it in your editor, the answer was usually a click or three away, tucked inside a Configure panel. For a product whose whole promise is that you always know what your agents are doing, that was the wrong default.

So we rebuilt it. The new dashboard is cleaner, leaner, and built around one habit. You should be able to glance at it and know the state of your work, without spelunking for it.

Here is what is new.

## A navigation pane that matches how you think

The first thing you'll notice is the navigation. Your projects are laid out clearly, with their type shown right alongside them, so moving between an OpenClaw workspace and a Hermes one feels natural instead of like hunting through a list. It's the kind of small thing you stop noticing in the best way, because it just gets out of your way.

## The Launch page is your agent's home

Every agent now opens to a Launch page that tells you everything at a glance.

Workspace status sits right at the top, with a start and stop button next to it, so spinning an agent up or shutting it down is one click instead of a menu hunt. Beside that are the numbers that tell you whether the thing is healthy, your CPU and RAM usage and your cowork API status, live, without you going looking for them.

The change you'll feel most is the connections. They used to hide behind a Configure button. Now they're right on the page. Click straight into VS Code or Cursor, into the OpenClaw Gateway on OpenClaw workspaces, or the Hermes gateway on Hermes ones. Your machine logs are on the same page too, so the moment something looks off you read what actually happened instead of guessing at it.

The rest of the dashboard is organized into four tabs. We just walked through Launch. Here are the other three.

## Setup takes an agent from empty to online

Setup is where a fresh agent becomes a working one, and it now walks you through it without getting in the way.

Overview opens with a setup checklist, four steps to bring an agent online, model, data, channels, and secrets, so you always know what's done and what's left. Agent identity and persona are going to live here too in a coming pass.

Models shows every model wired into the workspace, Claude Code, Codex, and now OpenRouter, which you can connect directly.

Data is where you plug in your sources. Connect Google Drive, OneDrive, GitHub, or Vercel and the agent can read from them. Your credentials stay inside your project's workspace, not on our platform, which is the way it should be.

Channels is how your agents reach you. Wire up Telegram, WhatsApp, or Slack, with at least one active so nothing your agents do happens silently. Tokens are validated locally before they save and scoped to that project only.

Secrets lets you see and edit your environment variables right there. Paste in a whole .env file or type them a line at a time, and changes save the moment you make them. No separate flow, no friction.

## Work puts every project in one place

The Work tab is where this starts to feel like a real command center. All of your XO projects live here together. You can see a project's token usage, its timeline, its todos, and everything it's been up to without ever opening the IDE. There's a Files view as well, so you can browse a project's files and drop new ones in straight from the browser. The point is simple. You can understand what's happening across everything you're running without launching a single editor.

## Usage shows the real numbers

Usage is the one we're quietly proudest of. It shows you what you're actually spending and using, total cost, total tokens, total messages, and average latency, with charts for tokens over time, daily cost, a message breakdown by role, and performance from min to p95 to max.

The part that matters most isn't the charts though. It's that the numbers are right. They're current and they reconcile, so what you see is what you actually used, with nothing to chase down at the end of the month.

## Go look

We built XO so you could run agents without babysitting a machine. This dashboard is that same idea pointed at the screen in front of you. Open it and the state of your work is just there, your agents, their health, their connections, their logs, and their real cost, all in one place you never have to dig through.

It's live now. Open your dashboard and have a look around.
</content>
