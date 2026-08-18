# The three layers, and what each one adds

Background for explaining where the files live and why. Use the short version in the session. The rest is for when somebody asks a real question.

The important thing to hold: **these are layers, not alternatives.** Each one sits on the one below and adds something. Nobody has to have all three.

---

## Layer 1 — A Claude Project

A container inside Claude. It holds a set of instructions and some documents, and everything you do inside that Project arrives with all of it attached.

**What it gives you:** context that follows you without being re-explained. Works on every device including a phone. Takes two minutes and needs nothing installed.

**One thing worth knowing about the two boxes.** The instructions field is read every time. The documents are searched when they look relevant, which on a cold question sometimes means not at all — and as the documents grow, more of the reading turns into searching. So standing instructions belong in the instructions box, and detail belongs in the documents. Most people paste everything into the documents and then wonder why it is inconsistent.

**What it doesn't:** the files are inside Claude rather than on your machine. You cannot easily edit them, they do not link to each other, and if you ever want them somewhere else you are copying them out by hand.

Good enough on its own. A very large number of people never go past this and are perfectly well served.

---

## Layer 2 — The same content, as files in a folder

Identical content, kept as plain text files on the machine. Claude reads them and writes to them directly.

**What it adds over a Project:**

- **You can edit them in anything.** Any text editor, on any device, without opening Claude.
- **Claude can write to them as it works.** Meeting notes accumulate, priorities update, the record grows without a copy-paste step.
- **They are yours.** Plain text on your own disk. No lock-in, works offline, survives any change of tool or vendor.
- **They can grow.** A Project is a fixed set of documents you maintain by hand. A folder is a filing system.

**What it costs:** a laptop, and the desktop app, so Claude can reach the folder.

---

## Layer 3 — Obsidian on top of that folder

Obsidian is a free application that opens a folder of markdown files. It does not store anything of its own and it does not change your files. Point it at the folder from layer two and everything is already there.

**This is the part worth explaining properly**, because "another notes app" undersells it badly.

### Relationships that maintain themselves

Write a person's name in double brackets — `[[Priya Raman]]` — and it becomes a link. Open Priya's file and you see every meeting, project and decision that has ever mentioned her, listed automatically.

Nobody built that list. Nobody maintains it. You linked from one direction and the other direction filled itself in.

That is the whole argument. In an ordinary folder you would have to remember to go and update Priya's file every time she came up, which means after three weeks you stop, and the connections rot. Here the graph builds itself out of ordinary writing.

### It helps Claude too, not only you

This is the bit people miss. The conventions Obsidian encourages — consistent naming, links, a bit of structure at the top of each file — make the folder easier for Claude to navigate, not just you. File names and links are part of what an assistant reads to work out where to look. A linked, consistently named vault is a better corpus than a flat pile of prose.

### Structure you can query

A few labelled fields at the top of a file — a date, an owner, a status — turn the folder into something you can ask questions of. Every person not spoken to in ninety days. Every project without a next step. That is a database's worth of usefulness with nobody administering a database.

### The ordinary reasons people stay

Instant search across everything. Daily notes, so capturing something is one keystroke rather than a decision about where it goes. Templates, so every meeting note comes out the same shape — which, again, makes them easier for Claude to read. And a graph view which is mostly a toy but does let people see the shape of what they have built.

---

## The honest summary

**Claude works identically with or without Obsidian.** It reads and writes the files either way. Anyone who does not want another application on their machine loses nothing today.

What Obsidian changes is what happens as the folder grows. Three files do not need it. Thirty files linked to each other are a different thing entirely, and that is where it earns its place.

And there is one reason that is not technical at all, which is probably the strongest. **A folder buried in Documents does not get opened. An application on your dock with your own thinking in it does.** The entire maintenance argument — that files nobody reads are furniture — depends on people looking. Obsidian is the thing that makes you look.

---

## The thirty-second version, for the session

> Three layers, and you can stop at any of them.
>
> A Project holds your context inside Claude and works on any device. That alone puts you ahead of almost everyone.
>
> Files in a folder are the same thing but on your own machine, where I can write to them as we go and they grow over time.
>
> And Obsidian is a free app that opens that folder. You don't need it. What it adds is that your files start linking to each other — mention someone once and every future mention finds them, without you keeping a list. That matters at thirty files, not three.
