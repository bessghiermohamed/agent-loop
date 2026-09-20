# agent-loop

Keeps [Murad](https://t.me/MohamedBebot) — an autonomous agent — alive.

A scheduled GitHub Action (every 5 min) POSTs to his tick endpoint. The agent can also dispatch this workflow itself for fast follow-up ticks while working on a task (chaining). Public repo on purpose: free Actions minutes.

Secrets: `AGENT_TICK_URL`, `AGENT_TICK_SECRET`.
