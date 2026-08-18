# File templates

Three files. Write them in the person's own words. Mark anything you didn't get as `TODO` rather than guessing.

Priorities live inside `About me.md` as a dated section. They used to have their own file and it came out mostly empty, which is worse than not having one.

---

## About me.md

```markdown
# About me

**Name:**
**Role:**
**Updated:** YYYY-MM-DD

## What I'm responsible for
Two or three lines, in their words. The real remit, not the job title.

## What my week looks like
The shape of it. Recurring commitments, where the time goes, what a normal
Tuesday holds.

## How I want you to work with me
- Answer first, or reasoning first
- Short or thorough by default
- Push back, or get on with it
- Anything they've said they don't want

## What I'm driving now
**As at YYYY-MM-DD.** Three or four things, no more. If this list gets past
six it's a to-do list and it will be wrong within a month.

- **[Priority]** — where it's up to, and what's in the way

## Things I'd hand over
The recurring work they'd like off their desk. Useful later for spotting
automation candidates.
```

---

## People.md

```markdown
# People

**Updated:** YYYY-MM-DD

Working context only. What each person needs, how they like to be dealt with,
what they care about. No performance judgements, nothing about pay or health,
nothing you'd not be comfortable them reading.

Remove people you no longer work with — when they leave, change role, or the
project ends. An assistant that still offers a departed colleague as the person
to ask is worse than one that never knew them.

## [Name] — [relationship, e.g. my manager / my counterpart in Ops]
- What they need from me:
- How they like it:
- Currently:

## [Name] — [relationship]
- What they need from me:
- How they like it:
- Currently:
```

Six or so people. More than that and it stops being maintained.

**Do not leave a field as `TODO` for some people and full for others.** A file where the client is fully specified and a long-standing colleague has two blanks against their name reads as a judgement if anyone ever sees it. If you only have one useful line about someone, write the one line and drop the empty fields rather than marking them.

---

## CLAUDE.md

This is the one that gets read first. A page, two at the outside.

```markdown
# How to work with me

Read this before anything else, then read the files it points at.

## Who I am
One line. Name, role, organisation.

## Where things are
- `About me.md` — my role, my week, what I'm driving, how I want to be worked with
- `People.md` — who I deal with and what they need
- `Assistant.md` — who you are, if I've set that up
- `Meetings/` — notes from meetings as they accrue

## How I want you to work
- [Their answer to Q6, as concrete instructions]
- Check `People.md` before advising me on anyone by name
- Check what I'm driving in `About me.md` before telling me what matters
- If a file's date is more than a month old, say so rather than trusting it

## What I never want
- [Anything they named]
- Don't pad. Don't open with a summary of what I just asked.

## Keeping this current
- If I tell you something that belongs in one of these files, say so and offer
  to put it in. Don't file it silently.
- If something in a file is out of date or contradicts what I've just told you,
  say so and offer to fix it. Don't quietly work around it.
- After a meeting, offer to write it up into `Meetings/`.
- When an answer leans on one of these files, say which file and when it was
  last updated.
- If someone in `People.md` hasn't come up in months, or a note in `Meetings/`
  is older than six months, say so and offer to clear it. Never delete anything
  without asking me first.
```

**The "Keeping this current" section is written as it stands.** Everything else
in this file comes from their answers; that section doesn't. It is what turns
the folder from something Claude reads on request into something Claude tends.
Don't ask them to design it and don't let it grow — five lines is the whole of it.

**On length.** Two pages is a ceiling, not a target. A short instructions file
that gets followed beats a thorough one that doesn't.

**On growth.** Tell them the rule for adding to it: add a line when Claude makes
the same mistake twice. Not before.

**On retention.** The fifth line of *Keeping this current* is what stops the
folder becoming a liability. `People.md` names real colleagues and `Meetings/`
accumulates notes about them, and neither shrinks on its own. Claude offers,
they decide, nothing goes without being asked — but the offer has to be
somebody's job or it never happens. Six months is a default, not a rule; if
they want a different window, use theirs and write it into the line.
