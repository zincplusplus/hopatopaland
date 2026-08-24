---
name: feedback-work-on-main
description: "In the hopatopaland repo, work directly on main — never create branches or worktrees"
metadata: 
  node_type: memory
  type: feedback
  originSessionId: 93b2c82c-5d88-4f6d-89f4-770bc39d1cb6
---

In the `hopatopaland` repo, always work directly on the `main` branch. Do not create separate branches or worktrees. Commit and push directly to `main`. If a push is rejected, `git pull --rebase` then push; stop and report on conflicts rather than resolving them yourself.

**Why:** The people writing the site's content are non-technical. The owner wants the process to have as few moving parts as possible. This is documented in `AGENTS.md` under the "Flux de lucru" section.

**How to apply:** For any change in this repo, skip branch creation — edit, commit, and push straight to `main`.
