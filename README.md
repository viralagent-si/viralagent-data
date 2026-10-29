---
license: cc-by-4.0
pretty_name: Viral Agent AI agent momentum
language:
- en
tags:
- ai-agents
- mcp
- github
- leaderboard
- trends
size_categories:
- 1K<n<10K
configs:
- config_name: agents
  data_files: agents.csv
- config_name: leaderboards
  data_files: leaderboards.csv
- config_name: signals_weekly
  data_files: signals_weekly.csv
---

# Viral Agent: AI agent momentum

Weekly leaderboards of AI agents and agent tools ranked by momentum, from [Viral Agent](https://viralagent.si). Updated every Monday.
Last updated 2026-10-29. 924 agents, 4 frozen weeks.

## Files

* `agents.csv`: one row per listed agent. Plain-English summary (written by an AI model from the project's own text), type, setup difficulty from 1 (works in a browser) to 5 (requires programming), cost model, audiences, tasks, and links.
* `leaderboards.csv`: every frozen weekly leaderboard, with score components. Also split by week in `leaderboards/`.
* `signals_weekly.csv`: public signals each Monday: GitHub stars and forks, Hugging Face likes, npm and PyPI downloads over the previous 7 days.

## How the score works

Star gain scaled by size, acceleration against the previous week, Hacker News attention, and download growth, with discounts for patterns typical of bought stars. Every rule is on the [methodology page](https://viralagent.si/methodology/).
Weeks marked `backfilled` were rebuilt from star history collected before the site launched.

## License and credit

CC BY 4.0. Please credit **Viral Agent** and link to https://viralagent.si. For example:

> Viral Agent (2026). AI agent momentum dataset. https://viralagent.si/data/. Licensed under CC BY 4.0.

Projects removed at their makers' request are removed from every file.
