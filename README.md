### Hi, I'm Mujeeb

I have a Master's in Quantitative Finance. Early on that meant valuation models, credit risk, and systematic trading tools. Now I build agent workflows for operational decisions: invoice exceptions, workforce plans, prompt quality. The pattern is the same across them. The system investigates and recommends; a person still approves anything that matters.

---

### Featured work

#### [Averroes](https://github.com/mujeeb-k/averroes-public)
Most chat apps only answer you. Averroes also coaches you. You talk to a main model as usual, while a separate coach (the Commentator) reads the exchange, calls out weak prompting, and proposes a tighter version you can paste back. Workshop mode is for when you do not have a prompt yet: a short dialogue whose only job is to produce one solid instruction before you settle into normal chat. You can attach PDF, DOCX, or plain text so both the assistant and the coach share the same context.

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
