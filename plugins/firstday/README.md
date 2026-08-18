# The New Starter Pack

You have hired the best graduate you will ever hire. They have read everything ever written, and they have never met a single person you work with.

This pack runs their induction.

## How to start it

Four commands. Type the slash and the first few letters and it will complete.

| Type this | What happens |
|---|---|
| `/firstday:start` | The induction. Start here if you have nothing set up |
| `/firstday:review` | The six-month review. Start here if you already have something running |
| `/firstday:assistant` | Invent your assistant. Do this after the induction |
| `/firstday:brief` | Set up the morning brief |

You can also just ask in plain English — "set up my second brain" will find it. The commands are there so you never have to guess the words.

## The four skills

**Second Brain Setup** (`/firstday:start`) — the induction. About six questions on your role, your week, your people and what you are driving, then it writes four files: what it knows about you, who you deal with, what is live right now, and the standing instructions that tie them together. Twenty minutes. Start here.

**Six Month Review** (`/firstday:review`) — for anyone who already has a setup. Goes through what you have built and reports what has gone stale, what has bloated past the point of being followed, what contradicts itself, and the one capability you are missing that would matter most. Ends with something to delete.

**Morning Brief** (`/firstday:brief`) — a short brief that arrives every working morning: today's meetings, what each one needs from you, and what is still open. Sends you a real one before it finishes so you know the plumbing works.

**Design Your Assistant** (`/firstday:assistant`) — invent the colleague. Five questions, then it writes a full persona: who they are, how they got good at this, what shaped them, what they care about, how they are to work with, and exactly how they will deal with you. It gets a name and its own file. Then it reduces all of that to ten lines of instruction that go into your standing instructions, because the persona is the character and the instructions are what actually change the behaviour. Do this last, once there is something to have a voice about.

## What this needs access to

**Installing this plugin grants no access to anything.** It contains no code and
no credentials — it is a set of markdown instructions telling Claude how to run
an interview and what to write. It cannot request a permission, grant one, or
escalate one. A user who installs it can do exactly what they could do the day
before.

That means the question in front of you is not "what will this plugin be able to
reach", but "what should this user's Claude session be able to reach" — which is
a decision you have already made, under whatever policy you already apply.

**What the pack assumes.** The table below is the baseline it is designed
around. Pre-approving these deliberately is better than letting a session
inherit whatever happens to be switched on, which is the only reason this
section exists.

| Access | Used by | What for | If denied |
|---|---|---|---|
| **Filesystem — read and write, one folder the user nominates** | all four | Creating and maintaining `About me.md`, `People.md`, `CLAUDE.md`, `Assistant.md` and `Meetings/` | Everything still runs, but produces a pack the user copies into place by hand |
| **Calendar — read** | `brief` | Reading today's meetings, so the brief says what each one needs from them | The brief is built from the user's files alone — "what's open" rather than "here's your day" |
| **Mail — read** | `brief` | Surfacing what is outstanding and waiting on them | The brief loses the part that makes it feel current |
| **Scheduled tasks** | `brief` | Creating the recurring job that delivers the brief each morning | The brief works on request but never arrives on its own, which is most of the point |

**Not required, and not requested:** calendar write, mail send, contacts,
directory lookup, or access to any folder other than the one the user names.
It does not write to mail or calendar.

**If the user already has other connectors, the pack will use them — within
their existing approval, never beyond it.** Someone with an approved task
manager or chat connector gets a morning brief that also knows what is due and
what is awaiting a reply. This is not the plugin widening its own scope; it has
no scope of its own to widen. It is one already-approved capability being used
alongside another, in a session where both were already permitted.

The instructions constrain how that is done:

- **Task-scoped reads only.** It reads what the brief needs — today's meetings,
  today's open items — and nothing else. It is explicitly told not to inventory
  the user's tools or catalogue what is available.
- **No copying between systems.** Connector data is not written into the user's
  files unless they ask for it.
- **No asking for more.** If something absent would help, it may say so once and
  must then leave it. It never presses for access, and never implies it is
  broken without it.

Approving this plugin approves none of those connectors. They remain governed by
whatever already governs them, and a user who has none of them still gets a
working pack.

**Where the data goes.** The files are plain text on the user's own machine and
are read and written in place. Nothing is uploaded to a third party by the
plugin itself, and no data leaves the user's existing Claude session. The one
thing to confirm locally is the delivery route for the morning brief — that uses
whatever the surface provides, so check which mechanism applies in your
environment before approving that step.

**The data protection point worth knowing.** `People.md` holds named colleagues,
and `Meetings/` accumulates notes about them. The pack constrains this by
design: working context only, no performance, pay or health information, and a
standing instruction to flag departed people and notes older than six months for
removal. Users are asked where the folder lives before anything is written, and
warned if it is a shared or team folder.

## Where your files end up

Three plain text files in a folder on your machine. That is the whole thing, and it is yours — no app owns it and nothing is locked in.

**If Claude can reach a folder on the device you are using**, it writes them as you go and you are finished when the conversation is.

**If it cannot** — an iPad, a phone, the web — you get the identical conversation and a complete pack at the end: every file written out, plus a five-step card for setting it up in about five minutes when you are next at a laptop. It is not a lesser version. Some people end up with a tidier result that way, because nothing is being typed under time pressure.

**One of those files is about other people**, so it's worth being deliberate about it. Keep it to working context — what someone needs from you, how they like to be dealt with. Nothing about performance, pay or health. The test is the one the induction gives you: write it as though they'll read it one day. They might.

**So where you put the folder matters.** Anyone who can open the folder can read
that file. Your own drive or cloud account is fine. A folder shared with your
team is not the place for it, and the induction will ask you before it writes
anything. You will also be offered a clear-out from time to time — people you
have stopped working with, notes past six months — which you can decline, and
nothing is ever deleted without you saying so.

**Obsidian is optional and comes later.** It is a free app that opens the same folder. Nothing here needs it. What it adds is that your files start linking to each other, so mention a person once and every future mention finds them — which matters at thirty files rather than three.

## Keeping it alive

Two habits, and they are the whole maintenance job.

Point Claude at your files whenever you start something real. And correct one thing in them each week, when you notice it is wrong.

A set of files nobody opens is not a second brain. It is furniture.

---

Built for the A&E EXCO session, Stockholm, August 2026.
