# Stockholm

Plugins from the Stockholm session. Install them, keep them, change them —
they're yours and they're MIT licensed.

## Install

Two lines in Claude Code. Type them exactly:

```
/plugin marketplace add https://github.com/jacksails/stockholm
```

```
/plugin install firstday@stockholm
```

Restart Claude Code and type `/firstday:` — the four commands will complete.

The full URL matters: the short `jacksails/stockholm` form works too, but only
if you already have GitHub SSH keys set up. The URL works for everyone.

## What's in it

### The New Starter Pack — `firstday`

You have hired the best graduate you will ever hire. They have read everything
ever written, and they have never met a single person you work with. This pack
runs their induction.

| Type this | What happens |
|---|---|
| `/firstday:start` | The induction. Start here if you have nothing set up |
| `/firstday:review` | The six-month review. Start here if you already have something running |
| `/firstday:assistant` | Invent your assistant. Do this after the induction |
| `/firstday:brief` | Set up the morning brief |

If in doubt, type `start`. It will send you to the right place.

Full detail in [plugins/firstday/README.md](plugins/firstday/README.md).

## For IT

**Installing `firstday` grants no access to anything.** It is markdown
instructions — no code, no credentials — so it cannot request, grant or escalate
a permission. A user who installs it can do exactly what they could the day
before.

The baseline it is designed around: read/write on one folder the user nominates,
plus calendar read, mail read and scheduled tasks for the morning brief. Never
calendar write, mail send, contacts, or any other folder.

Where a user already has other connectors approved, the pack makes use of them
for the task in hand — it is told to read only what the brief needs, not to
inventory anything, not to copy between systems, and never to press for access
it does not have. Approving the plugin approves none of those connectors; they
stay governed by whatever governs them today.

Full detail, including how named colleagues in `People.md` are constrained and
aged out, in
[plugins/firstday/README.md](plugins/firstday/README.md#what-this-needs-access-to).

## If you're not on Claude Code

The skills assume a folder they can write to, which means the desktop app on a
laptop. On the web, an iPad or a phone you get the identical conversation and a
complete pack at the end — every file written out, plus a five-step card for
setting it up in about five minutes when you're next at a laptop. It is not a
lesser version.

## Updating

If something here changes after the session:

```
/plugin marketplace update stockholm
```

## Licence

MIT — see [LICENSE](LICENSE). Take it, fork it, rewrite it for your own team.
