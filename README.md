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

`firstday` declares exactly what it needs so it can be pre-approved rather than
inheriting whatever a session already has: read/write on one user-nominated
folder, plus calendar read, mail read and scheduled tasks for the morning brief.
Approving all four is the intent — the pack's value is joining them together,
and filesystem alone gives you a filing cabinet rather than an assistant. What
it never asks for: calendar write, mail send, contacts, or any folder other than
the one the user names. Full table, including how named colleagues in
`People.md` are constrained and aged out, in
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
