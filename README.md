# AI OS Starter

**A `CLAUDE.md` and a two-file board that turn an AI assistant into something that actually tracks your work.**

Free. Four core files. No install, no dependencies, nothing to sign up for beyond the AI assistant you already use. Copy the folder and start.

---

## The problem this fixes

Most people use an AI assistant like a search engine. Every session starts cold. It doesn't know what you're working on, it forgets what you decided yesterday, and it never tells you something is late.

That isn't a model problem. It's a missing-context problem. The fix is four plain text files the assistant reads before it does anything:

| File | What it does |
|---|---|
| `CLAUDE.md` | House rules. Who you are, what you're building, how the assistant is supposed to behave. Read first, every session. |
| `00-cockpit/_dashboard.md` | Your board. Top 3 today, top 3–5 this week, and an **Overdue** section that things don't quietly leave. |
| `00-cockpit/_handoff.md` | The sticky note. What you finished, what you're mid-way through, the exact next thing to do. |
| `_references/ground-rules.md` | The six guardrails, and the reasoning behind each one. |

That's it. That's the whole thing.

---

## Setup — about 10 minutes

1. **Download or clone this folder.** Put it wherever you keep your work.
2. **Open `CLAUDE.md` and fill in the brackets.** Your name, what your business does, what you want from the assistant. Ten minutes of honesty here is what makes the rest work.
3. **Point your assistant at the folder.**
   - **Claude Code** — open the folder as your project. It reads `CLAUDE.md` automatically.
   - **Claude Cowork / Projects** — add the folder, or paste `CLAUDE.md` into your project instructions.
   - **Anything else that reads a project instructions file** — same idea. These are plain Markdown files, not code.
4. **Say "sign in."** It should check the date, read your board, and tell you where you left off.
5. **Say "close session" when you stop.** That's the step that saves tomorrow.

Steps 4 and 5 are the whole loop. Everything else is detail.

---

## What it actually changes

The rules in `CLAUDE.md` are opinionated on purpose. The ones that do the most work:

- **Every task gets a hard date.** No date means it won't happen, so the assistant asks for one before writing anything down.
- **Late stuff comes first.** Overdue items go at the top of the session, before the summary and before whatever you asked for — every session, until they're done.
- **A deadline moves only out loud.** Sliding a date is fine. Sliding it silently is what the board exists to stop.
- **Ask before sending, ask before deleting.** Nothing goes to a customer and nothing gets overwritten without you seeing it first.
- **Never guess with numbers.** Unsure means leave it blank and flag it. A confident wrong number is the dangerous kind.

You can change any of them. `_references/ground-rules.md` explains why each one is there so you know what you're giving up.

---

## Where this came from

I spend every weekday inside a different business, in person, making non-technical teams AI-native. These files are the stripped-down version of what I set up on day one, every time. They're boring on purpose — the boring part is what survives contact with a real week.

I run my own operation on the same structure.

---

## The full kit — $149

This starter is the structure: what your assistant *reads*. The paid kit is the automation: what *runs on its own*.

- **Six routines** — sign-in, session-closer, plan-week, weekly review, meeting notes, and an adversarial review pass that argues against your own plan before you commit to it.
- **Four local Python hooks** (Claude Code) that fire on their own — session panel, data-save reminder, deadline detector, and a promise verifier that catches "I'll do that later" and turns it into a dated item. Readable source, **no network calls**.
- **Both surfaces packaged** — a Claude Code build and a Markdown-only Cowork build.
- **A calendar add-on** that pushes your hard deadlines onto your actual calendar, because the assistant only exists when you open a session and your phone doesn't.
- Install guide and a cheat sheet of the exact phrases that get the best results.

**→ [the11th.ai](https://the11th.ai)**

If the free version is all you ever need, that's a good outcome. Use it.

---

## License

MIT — see [LICENSE](LICENSE). Use it, change it, ship it inside your own client work. No attribution required.

## Not affiliated with Anthropic

Claude, Claude Code, and Claude Cowork are products of Anthropic, PBC. Referenced here for compatibility only. This project is independent and is not affiliated with, endorsed by, or reviewed by Anthropic. You need your own Claude account; nothing here includes or resells one.
