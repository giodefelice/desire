# EVENING.md

🌙 Evening translates GitHub feedback into a task list.

- Run only when scheduled or explicitly prompted by USER.
- Read new USER feedback in the session's linked pull request or issue, including comments USER
  approved with APPROVE_EMOJI.
- Translate every actionable request into a concise unchecked checkbox in `TODO.md`.
- Put the source comment's direct GitHub link beside its checkbox.
- Preserve existing tasks and checked state, and do not add duplicates.
- Do not turn non-actionable feedback into a task.
- Do not implement the tasks or react to GitHub activity in real time.
