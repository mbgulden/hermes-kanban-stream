---
name: Bug report
about: Something the plugin did wrong, or failed to do
title: ""
labels: bug
assignees: ""
---

**What happened**
A clear description of the bug — what the stream showed (or failed to
show), or what steering did.

**What you expected**
What should have happened instead.

**Environment**
- Plugin version (see `plugin.yaml`):
- Hermes version (`hermes --version`):
- Setup: 1:1 chat with the bot, or a group ops chat?
- Steering involved? If so, from the board or via the companion daemon?

**Evidence**
- The relevant log lines from the worker profile (grep for
  `kanban-stream`):
- `python3 bin/steer.py --check` output, if steering is involved
  (redact the bot token if it appears anywhere — it should not):

**Config**
Which `KANBAN_STREAM_*` variables are set in the profile's `.env`
(names only, never values).
