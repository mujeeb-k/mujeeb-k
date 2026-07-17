### Hi, I'm Mujeeb

Bachelor's in Computer Science and Engineering

Master's in Quantitative Finance

Early work on valuation models, credit risk, and systematic trading tools.

I'm working on agent workflows for invoice exceptions, workforce plans, financial research, and the prompt layer in front of coding agents.

I care less about AI replacing people than about AI making the hard parts of a job faster to do well: gather the evidence, surface a recommendation, leave the call with the human.

---

### Featured work

#### [Averroes](https://github.com/mujeeb-k/averroes-public)
Coding agents do not usually fail because the model is dumb. They fail because the request was vague, overloaded, or missing the constraint that mattered. Averroes is meant to sit in front of that handoff as a prompt-quality gateway: take a rough ask, tighten it, then pass a sharper instruction to whatever coding model or agent you already use. In the active path, a coach walks the request through a short dialogue until it is specific enough to run. In the passive path, it watches as you type and flags weak prompts before they reach the agent. The piece shipping today is that coach loop in a chat UI (Commentator critique after each turn, Workshop mode when you still need to invent the prompt). Open the demo, give it a messy coding ask, and see what comes back.

[Live demo](https://averroes-llm.vercel.app/)

#### [AP Three-Way Matching Agent](https://github.com/mujeeb-k/AP-Three-Way-Matching-Agent)
SAP can tell you an invoice failed a three-way match. It usually cannot tell you why, or what to do next. This pilot compares supplier invoices against purchase orders and goods receipts, classifies the failure across 14 discrepancy types (price variance, missing receipt, wrong PO, duplicate invoice, and so on), explains the root cause, and routes the case to correct, review, or escalate. Nothing writes back without human approval. Runs on synthetic data so you can open it and follow a full exception from detection through the work queue.

#### [Workforce Planning Agent](https://github.com/mujeeb-k/workforce-planning-agent)
A headcount target is not a hiring number. This Streamlit prototype takes a role, target headcount, deadline, and budget, then builds an executive briefing: who is already confirmed capable, who can move from another team, who is one course away, who needs manager verification, and how many people still have to be hired externally. Each action is costed and sequenced against an all-external baseline, with confidence tied to whether the skill evidence is trusted or self-declared.

[Live demo](https://workforce-planning-agent.streamlit.app/)

---

### Quantitative finance

- **[mbs-val](https://github.com/mujeeb-k/mbs-val)** — Mortgage-backed security valuation
- **[dtd](https://github.com/mujeeb-k/dtd)** — Distance-to-default using a market-value proxy method and a volatility-constrained method
- **[us-delinquency-forecast](https://github.com/mujeeb-k/us-delinquency-forecast)** — Forecasting U.S. delinquency rates from economic data
- **[strat-backtest](https://github.com/mujeeb-k/strat-backtest)** — MATLAB GUI for backtesting an algorithmic strategy (MACD + RSI on Mag 7 names), with position tracking and portfolio P&L
