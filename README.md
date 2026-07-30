# desire

> *Lilacs out of the dead land, mixing*
> 
> *Memory and desire, stirring*

Software engineering prompts inspired by the asymmetric board game Root:

- 🐦 [Birdsong](BIRDSONG.md) reports open pull requests and issues every weekday morning
- 🌙 [Evening](EVENING.md) turns your GitHub feedback into `TODO.md` checkboxes

[AGENTS.md](AGENTS.md) is the operating base they both follow. The workflow is deliberately
small:

- There is no Daylight mode and no interactive daytime workflow.
- Every agent session is linked to a pull request or issue.
- GitHub activity is queued input; comments do not wake agents or trigger an immediate response.
- An unscheduled run starts only when you explicitly prompt it.

## Get started

1) Open a GitHub account for your agents and add it as a collaborator where it needs to work.
2) Set `USER`, `AGENT`, and `WORK_REPOS` in [AGENTS.md](AGENTS.md).
3) Schedule Birdsong on weekday mornings and Evening when you want feedback distilled.
4) Assign every run a pull request or issue before it starts.
