# Agentic Trading

This repository defines the policies and operating instructions for an autonomous Robinhood trading agent. The
agent pursues speculative short-term opportunities in a restricted set of common stocks while using only
unleveraged buying power.

## Repository structure

- `AGENTS.md` defines the non-negotiable trading boundaries and has highest precedence.
- `STRATEGY.md` defines the short-term trading objective, evidence, and decision framework within those boundaries.
- `AUTOMATION.md` defines the monitoring schedule, execution safeguards, and reporting workflow.
- `reports/` contains generated per-run and weekly trading reports.

Before every authorized run, the agent must read all three instruction files. If instructions conflict,
`AGENTS.md` governs; if compliance or account state cannot be verified, the agent must not trade.
