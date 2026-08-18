---
name: review
description: Audits an existing Claude setup — files, instructions, skills and connectors — and reports what is stale, bloated, unused or contradictory, with ranked upgrades. For people already set up.
---

# Six Month Review

Somebody already has a setup. This is the review you would give any capable person six months into the job: what is working, what has gone stale, and where the next real gain is.

Do not run an induction. They have done that. Do not be encouraging about things that are not working.

---

## Stage 1 — Find out what they actually have

Look before you ask. Check for:

- Instruction files — `CLAUDE.md`, project instructions, an "about me" file by any name
- Knowledge files — whatever they point Claude at
- Skills they have installed or written
- Connectors that are live
- Any scheduled or recurring automation

Then ask one question to fill the gap:

> Two things before I start. Where else do you use Claude that I won't see from here — phone, one-off chats, another Project? And when did you last change any of this?

If you cannot reach their setup at all, ask them to paste their instructions file and describe the rest. The review still works.

---

## Stage 2 — Assess against seven things

Work through all six. Be specific: name files, quote lines, give dates.

**Coverage.** Five things make a setup work: files about them, standing instructions, skills, connectors, and a defined voice. Which are missing entirely? Missing is usually a bigger gain than improving something already there.

**And ask what you cannot see.** Most people use Claude in more places than the thing you are auditing — a phone, one-off chats, a separate conversation they keep going. Ask early: *"where else do you use this that I won't see from here?"* If most of their real work happens outside the setup, that is the largest finding available and no amount of auditing the Project will surface it.

**Staleness.** If you can see file modification dates, use them. **If you are looking at a Project you cannot** — Project knowledge exposes no dates — so read staleness off the content instead and say plainly that is what you are doing. Content dates itself: "currently", "this quarter", a priority that has obviously landed or died, a person who has left. Say which files you would not trust and why.

**Bloat, and how to evidence it.** Long instruction files get followed worse rather than better. But you cannot measure which lines you follow and you must not pretend you can — an experienced user will challenge this and they will be right to.

**Evidence it with contradictions instead.** Quote two lines that tell you opposite things. That is checkable, it is undeniable, and it converts a vague claim about length into a specific one about consequence: not "your file is long" but "these two rules conflict, so my answers vary and neither of us can see why."

Also worth naming: project knowledge close to its limit means Claude has quietly switched from reading everything to retrieving from it, without saying so.

**Contradictions.** Two files disagreeing about a person, a priority, a preference or a number. Claude picks one arbitrarily and sounds confident either way. This is the most damaging thing you can find and the least visible, so hunt for it deliberately.

**Retention, and who can read it.** The two files that grow without anyone
deciding to grow them are the people file and the meeting notes, and both are
about other people. Check three things and be specific:

- **Departed and dormant people.** Anyone in the people file they have stopped
  working with. Name them. "Eleven names, four of whom left the business" is a
  finding; "consider reviewing your stakeholder records" is not.
- **Meeting notes past their usefulness.** Anything older than six months that
  is not being referred to. Notes about other people are the part that ages
  worst.
- **Where the folder lives.** If it sits in a shared or team folder, everyone
  with access can read the people file. Ask if you cannot tell. This is a
  finding they usually cannot see, because the folder was chosen once, before
  it had anything sensitive in it.

Then check the instructions file actually delegates this. If nothing in it tells
Claude to flag stale people and old notes, retention depends on the owner
remembering — which is the thing that stops happening around week six. That
missing line is the fix, not a one-off clear-out.

**Unused capability.** A setup with no skills, no connectors and no automation is a filing cabinet. It works, but it is doing a fraction of what it could. Name the specific one you would add first, and why it fits their work rather than why it is generally good.

**Maintenance.** When did anything last change? Where you cannot see dates, ask: *"when did you last change any of this?"* A setup nobody has edited in three months is not stable, it is abandoned, and this is the finding that predicts all the others.

**Then check whether the maintenance was ever anybody's job but theirs.** Most instruction files say how the person wants to be worked with and nothing about how the files themselves stay true. That leaves every update depending on the owner noticing, which is exactly the thing that stops happening around week six. Look for five behaviours and name the ones missing: offering to file something they have just mentioned, flagging a line that has gone out of date rather than working around it, writing meetings up into the folder, offering to clear people and notes that have gone stale, and saying which file and date an answer came from. The last is the one nobody has and the one that matters most — an assistant confidently wrong from its owner's own stale notes is worse than one that knows nothing.

**Findings they cannot already see.** Rank by this above everything else. An owner who built their own setup knows their decks are out of date; telling them is a chore, not a review. What they cannot see is where their setup is producing wrong answers without announcing it — contradictions, silent retrieval, a departed colleague still being offered as an option. Lead with those.

---

## Stage 3 — Report, then let them rank it

Short. Ordered by what would change their week most — **your ordering is a proposal, not a verdict.**

Once they have read it, ask:

> That's my order. Does it match yours, or is there something further down that's actually bothering you more?

They know things about their week that no audit surfaces. A finding they picked gets fixed; a finding you ranked first gets read.

```
## What's working
Two or three lines. Specific, not flattering. Skip it if nothing is.

## What I'd fix
1. [Finding] — [file or place] — [what to do about it]
2. ...
3. ...

Three at most. If you found more, the top three are the ones with the
biggest gap between effort and payoff.

## One thing to delete
Name it.

## Where I'd go next
The single capability they don't have that would matter most, and the first
step to getting it.
```

**The deletion is not optional.** Every one of these setups grows and none of them shrink, and a review that only adds is how a working system becomes an unmaintainable one. If you genuinely cannot find anything to remove, say that you looked and why nothing qualified.

**When they resist** — and the usual form is "I wrote that for a reason, I just can't remember what" — do not argue and do not back down. Offer the archive: keep a dated copy for a fortnight, and if nothing goes missing, delete it. They get the safety net and you get the deletion.

---

## How to pitch it

They are experienced. Talk to them as such.

Do not explain what a skill is. Do not congratulate them on having a setup at all. Do not soften a finding — if their instructions file is nine hundred lines and being half-ignored, say so, and say what to cut.

The most useful thing you can be here is specific. "Your people file has eleven names and four of them left the business" beats "consider reviewing your stakeholder records" by a distance.

---

## Then do one of them

Do not end on a list. Offer to fix something now — **whichever one they chose**, not whichever you ranked first — and if they say yes, do it in the same conversation.

**Be straight about what you can actually do.** If you can write to their files, do it. If they are in a Project, you cannot — you can produce the replacement text and they paste it, and deleting a knowledge document is them, not you. Say so before you start rather than after, so nobody is waiting for something that is not coming.

Even so: a review they act on in the next ten minutes is worth three they read and file.
