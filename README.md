### Hi, I'm Mujeeb

I'm a product-minded engineer focused on enterprise workflows, decision systems, and applied AI.

My recent work explores how AI can investigate operational problems, gather evidence, explain conclusions, and recommend next actions across workforce planning, invoice exception management, financial research, and developer productivity.

I hold a Bachelor's in Computer Science and Engineering and a Master's in Quantitative Finance. My earlier work included valuation models, credit risk, and systematic trading tools. That quantitative foundation continues to shape how I think about reliability, uncertainty, and decision-making.

I enjoy turning ambiguous business problems into practical systems that people can use and trust, while keeping humans in control of the outcome.

---

### Featured work

#### [Averroes](https://github.com/mujeeb-k/averroes-public)
Coding agents do not usually fail because the model is dumb. They fail because the request was vague, overloaded, or missing the constraint that mattered. Averroes is meant to sit in front of that handoff as a prompt-quality gateway: take a rough ask, tighten it, then pass a sharper instruction to whatever coding model or agent you already use. In the active path, a coach walks the request through a short dialogue until it is specific enough to run. In the passive path, it watches as you type and flags weak prompts before they reach the agent. The piece shipping today is that coach loop in a chat UI (Commentator critique after each turn, Workshop mode when you still need to invent the prompt). Open the demo, give it a messy coding ask, and see what comes back.

[Try the live demo here](https://averroes-llm.vercel.app/)

#### [Workforce Planning Agent](https://github.com/mujeeb-k/workforce-planning-agent)
A headcount target is not a hiring number. This Streamlit prototype takes a role, target headcount, deadline, and budget, then builds an executive briefing: who is already confirmed capable, who can move from another team, who is one course away, who needs manager verification, and how many people still have to be hired externally. Each action is costed and sequenced against an all-external baseline, with confidence tied to whether the skill evidence is trusted or self-declared.

[Try the live demo here](https://workforce-planning-agent.streamlit.app/)

#### [AP Three-Way Matching Agent](https://github.com/mujeeb-k/AP-Three-Way-Matching-Agent)
SAP can tell you an invoice failed a three-way match. It usually cannot tell you why, or what to do next. This pilot compares supplier invoices against purchase orders and goods receipts, classifies the failure across 14 discrepancy types (price variance, missing receipt, wrong PO, duplicate invoice, and so on), explains the root cause, and routes the case to correct, review, or escalate. Nothing writes back without human approval. Runs on synthetic data so you can open it and follow a full exception from detection through the work queue.

---

### Quantitative finance

- **[mbs-val](https://github.com/mujeeb-k/mbs-val)** — Mortgage-backed security valuation
- **[dtd](https://github.com/mujeeb-k/dtd)** — Distance-to-default using a market-value proxy method and a volatility-constrained method
- **[us-delinquency-forecast](https://github.com/mujeeb-k/us-delinquency-forecast)** — Forecasting U.S. delinquency rates from economic data
- **[strat-backtest](https://github.com/mujeeb-k/strat-backtest)** — MATLAB GUI for backtesting an algorithmic strategy (MACD + RSI on Mag 7 names), with position tracking and portfolio P&L
