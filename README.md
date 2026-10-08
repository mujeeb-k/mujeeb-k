# Hi, I'm Mujeeb

I build tools for working with AI, investigating operational problems, and making decisions from data.

Previously, I worked on enterprise analytics and AI at SAP.
Before that, I built financial models and software to measure portfolio risk, value bonds, and analyze trading performance.

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

[Try the demo →](https://leagueofagents.dev)

## Other projects

### [Averroes](https://github.com/mujeeb-k/averroes-public)

A chat app that gives you feedback on how you ask AI for help.

After each reply, a separate coach reviews the exchange, identifies missing context or unclear instructions, and offers a rewritten prompt when the request needs one. Its feedback stays in a side panel; the main assistant never sees it.

Workshop mode helps you turn a rough idea into a clear prompt before starting a conversation. You can attach documents to give both the assistant and coach the context they need.

**Built with:** Next.js, FastAPI, and SQLite.

[Live demo →](https://averroes-llm.vercel.app/)

### [AP Three-Way Matching](https://github.com/mujeeb-k/AP-Three-Way-Matching-Agent)

When an invoice is blocked by a mismatch, accounts payable still has to investigate: is the price wrong, is a receipt missing, or does the invoice reference the wrong purchase order?

This prototype compares invoices, purchase orders, and goods receipts across 14 discrepancy types. It explains the mismatch, shows the supporting records, and recommends correction, review, or escalation.

An AP analyst can accept, override, assign, or escalate the recommendation from a work queue. Each case keeps a history of the system's findings and the reviewer's decisions.

Rules handle matching, tolerances, and routing. AI assists with ambiguous cases. Corrections require human approval; financial write-back is disabled.

**Built with:** SAP CAP, TypeScript, and React. Runs on synthetic data without an API key.

### [Workforce Planning](https://github.com/mujeeb-k/workforce-planning-agent)

A headcount target does not tell you how many people to hire. Some employees already qualify, some could move from another team, and others may need training or skill verification.

Given a role, target, deadline, and budget, this prototype builds a staffing plan: who is ready, who could move, who is one skill away, and how many external hires remain after estimated attrition. It shows the cost and timing of each action and compares the plan with hiring everyone externally.

Skills need recent manager or course evidence to count as confirmed capability. Unverified records become explicit verification actions. Fixed rules calculate the plan; an optional language model explains it.

**Built with:** Python and Streamlit. Runs on synthetic data without an API key.

[Live demo →](https://workforce-planning-agent.streamlit.app/)

## Quantitative finance

- [mbs-val](https://github.com/mujeeb-k/mbs-val): mortgage-backed security valuation
- [dtd](https://github.com/mujeeb-k/dtd): distance-to-default estimation using market-value proxy and volatility-constrained methods
- [us-delinquency-forecast](https://github.com/mujeeb-k/us-delinquency-forecast): forecasting U.S. delinquency rates from economic data
- [strat-backtest](https://github.com/mujeeb-k/strat-backtest): MATLAB GUI for backtesting MACD and RSI strategies on the Magnificent Seven, with position tracking and portfolio P&L
