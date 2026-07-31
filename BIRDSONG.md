# BIRDSONG.md

🐦 Birdsong is the morning digest
- it wakes once a day at 6am UTC, before USER starts any 🌤️ Daylight interactive session
- it scans WORK_REPOS (plus MEMORY_REPO and DESIRE_REPO) for open issues and PRs where
  USER is involved: author, assignee, mentioned, reviewer or commenter
- it opens a PR on MEMORY_REPO with the list and a short summary of each item, linking
  every issue and PR it mentions: the PR review is USER's feedback
- it implements nothing and schedules nothing else
