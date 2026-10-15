# Hi, I'm Mujeeb

I worked on enterprise analytics and AI at SAP. Before that, I built financial models and software to measure portfolio risk, value bonds, and analyze trading performance. I'm currently building applications for working with AI, investigating operational problems, and making decisions from data.

## Current work

### [League of Agents](https://github.com/mujeeb-k/league-of-agents)

Coding agents write code faster than anyone can review it. Reviewing their work means understanding where changes landed, how they fit into the project, and whether anything broke.

League of Agents opens your repo as a zoomable map. Select a file, folder, or block of code and ask your coding agent for a change. Every changed file appears on the map, with before, after, and diff views. Run your configured tests and type checks, then keep or undo the run in one click.

You can also edit code yourself and review changes made from your terminal or editor. Each run is recorded with Git snapshots without changing your branch or staging area.

Runs locally on macOS. Works with Claude Code; Codex and Cursor support is in beta. Open source under Apache 2.0.

**Get started:** run this inside a Git repo.

```bash
npx leagueofagents-cli@latest
```

[Try it here →](https://leagueofagents.dev)

## Other projects

### [Averroes](https://github.com/mujeeb-k/averroes-public)

A chat app with an AI coach that helps you write clearer prompts. After each reply, the coach checks for missing context and unclear instructions, suggesting a rewrite when useful.

The coach sees the conversation, but the main assistant never sees its feedback. Workshop mode helps you develop a rough idea before starting a conversation, and document uploads provide context to both.

Next.js · FastAPI · SQLite

[Live demo →](https://averroes-llm.vercel.app/)

### [AP Three-Way Matching](https://github.com/mujeeb-k/AP-Three-Way-Matching-Agent)

When an invoice does not match what a company ordered or received, someone has to investigate before it can be paid.

This prototype compares the invoice, purchase order, and delivery records across 14 discrepancy types. It identifies the mismatch, shows the evidence, and recommends a next step. Reviewers can approve a correction, override the recommendation, assign the case, or escalate it, with each decision recorded.

Rules handle matching, tolerances, and routing; AI assists with ambiguous cases. Corrections require human approval, and financial write-back is disabled.

SAP CAP · TypeScript · React · Synthetic data

### [Workforce Planning](https://github.com/mujeeb-k/workforce-planning-agent)

Helps a team decide how to meet a staffing target through internal transfers, training, and external hiring.

Given a role, headcount target, deadline, and budget, it identifies employees who qualify, those who need training or skill verification, and the remaining hiring gap after expected departures. It shows the cost and timing of each action against hiring everyone externally.

Skills count as confirmed only with recent manager or course evidence. Missing evidence becomes a verification task. Fixed rules calculate the plan; an optional language model explains the results.

Python · Streamlit · Synthetic data

[Live demo →](https://workforce-planning-agent.streamlit.app/)

## Quantitative finance

- [mbs-val](https://github.com/mujeeb-k/mbs-val): mortgage-backed security valuation
- [dtd](https://github.com/mujeeb-k/dtd): distance-to-default estimation using market-value proxy and volatility-constrained methods
- [us-delinquency-forecast](https://github.com/mujeeb-k/us-delinquency-forecast): forecasting U.S. delinquency rates from economic data
- [strat-backtest](https://github.com/mujeeb-k/strat-backtest): MATLAB GUI for backtesting MACD and RSI strategies on the Magnificent Seven, with position tracking and portfolio P&L
