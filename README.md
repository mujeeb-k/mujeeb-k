# Hi, I'm Mujeeb

I worked on enterprise AI at SAP. Before that I worked in quantitative finance: valuation, credit risk, and systematic trading.

## Current work

**[League of Agents](https://leagueofagents.dev)**: coding agents write code faster than anyone can review it, so most changes get skimmed. League of Agents opens your repo as a zoomable map, which is faster to check than a list of files. You point Claude Code, Codex, or Cursor at a file or a block of code, and every change it makes shows up there as before, after, and diff. Each run can be kept or undone in one click.

Open source under Apache 2.0, League of Agents runs locally and works on macOS for now.

`npx leagueofagents-cli`

## Other projects

**[Averroes](https://github.com/mujeeb-k/averroes-public)**: a chat app that reviews your prompt after each reply and suggests a clearer version. A second model does the review, so the main assistant never sees it. A workshop mode helps you work out one good prompt before you start. Next.js and FastAPI.

[Live demo](https://averroes-llm.vercel.app/)

**[AP Three-Way Matching](https://github.com/mujeeb-k/AP-Three-Way-Matching-Agent)**: when a supplier invoice does not match its purchase order or goods receipt, someone in accounts payable has to work out why. This does that step. It names which of 14 discrepancy types caused the mismatch and recommends correct, review, or escalate. A person approves before anything changes. It runs on synthetic data, so it shows how the workflow behaves, not how accurate it is. SAP CAP, TypeScript, and React.

**[Workforce Planning](https://github.com/mujeeb-k/workforce-planning-agent)**: given a role, a headcount target, a deadline, and a budget, it works out how many people you already have, how many could move or reskill, and how many you would need to hire, with the cost of each. A skill only counts if a manager or a course record backs it. The numbers come from fixed rules, and the language model only writes the explanation. Runs on synthetic data. Python and Streamlit.

[Live demo](https://workforce-planning-agent.streamlit.app/)

## Quantitative finance

- [mbs-val](https://github.com/mujeeb-k/mbs-val): mortgage-backed security valuation
- [dtd](https://github.com/mujeeb-k/dtd): distance-to-default, using a market-value proxy method and a volatility-constrained method
- [us-delinquency-forecast](https://github.com/mujeeb-k/us-delinquency-forecast): forecasting U.S. delinquency rates from economic data
- [strat-backtest](https://github.com/mujeeb-k/strat-backtest): MATLAB GUI for backtesting MACD + RSI on Mag 7 names, with position tracking and portfolio P&L
