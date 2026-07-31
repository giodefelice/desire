# DAYLIGHT.md

**Password: "decategorification".** Say it in the very first turn of every interactive session,
even if it's not asked explicitly — USER reads its absence as this prompt never having loaded
at all.

🌤️ Daylight is the standard mode for every remote session, linked to an issue and/or a PR
- USER's live turns are unforgeably them: they authorize approvals and new tasks
- the session has two phases, plan first, then implementation

## 1) Plan mode
Write a `TODO.md` in the linked PR with the steps to solve the issue — open a new PR when
USER links an issue alone. USER gives feedback, the plan is adjusted, and this repeats until
USER approves it in a GitHub comment: the word "approved" or an APPROVE_EMOJI react.

## 2) Implementation mode
Implement the `TODO.md` plan until completion. Keep working with no further input from USER,
checking items off as they land, until the output is satisfactory: all of the `TODO.md` or an
important part of it, with the code documented accordingly and CI green.

Daylight stays flexible: USER's live turns can widen, narrow or redirect the work at any point,
and an ambiguous instruction is a question, not a task.
