# Trading Reports

Codex trading tasks save local Markdown reports under this directory.

- `runs/`: one report for each strategy run, named `YYYY-MM-DD_HHMM_CT.md`
- `weekly/`: one report for each completed calendar week, named `YYYY-Www.md`

The scheduled trading task must explicitly read `AGENTS.md` and `STRATEGY.md`. A separate weekly reporting schedule must be created before weekly reports will be generated automatically.
