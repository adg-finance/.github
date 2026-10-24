<p align="center">
  <img src="https://raw.githubusercontent.com/adg-finance/.github/main/profile/assets/brand/doc-header-light.svg#gh-light-mode-only" width="880" alt="ADG Finance — evidence-checked ML for a self-correcting live trader">
  <img src="https://raw.githubusercontent.com/adg-finance/.github/main/profile/assets/brand/doc-header-dark.svg#gh-dark-mode-only" width="880" alt="ADG Finance — evidence-checked ML for a self-correcting live trader">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/markets-US_equities_via_Alpaca-2563EB?style=flat" alt="Markets: US equities via Alpaca">
  <img src="https://img.shields.io/badge/method-ML4T_·_AFML-2563EB?style=flat" alt="Method: ML4T and AFML">
  <img src="https://img.shields.io/badge/stage-research_→_paper_trading-F59E0B?style=flat" alt="Stage: research to paper trading">
  <a href="https://github.com/Alejandro-Duenas"><img src="https://img.shields.io/badge/founder-Alejandro_Duenas-64748B?style=flat&logo=github&logoColor=white" alt="Founder: Alejandro Duenas"></a>
</p>

---

We're building a trading system for US equities that learns from its own errors. It doesn't
end at a backtest. It runs a closed loop: data, features, models, signals, sizing and execution
on Alpaca, followed by post-trade attribution, drift detection and retraining, including
reinforcement-learning retuning. Every model has to cross a sealed, deflated-Sharpe-checked
evidence boundary before it trades.

## How we work

- **Evidence over backtests.** We use point-in-time data, purged and embargoed cross-validation,
  and an untouched holdout. We report the trial count next to every result, so a lucky search
  can't pass for skill.
- **Reproducible by default.** Every research run can be replayed from versioned features,
  labels and studies, and each stage stops at a review gate.
- **Typed, tested, small.** Each package does one job, runs under strict type checks, and has to
  clear a high coverage gate.
- **Agents as colleagues.** LLM agents write, review and maintain much of the stack under explicit
  skills and conventions, and humans make the promotion calls.

## What we're building

| Area | What it is |
|---|---|
| **Portfolio management** | The research pipeline: Alpaca data, a 100+ indicator feature engine, triple-barrier labels, regime models, tuned gradient-boosting and deep-learning classifiers, and the Minimax Portfolio Engine for signals and sizing |
| **Finance & AI wiki** | An agent-maintained knowledge base of linked concept, entity and source pages built from books and papers on markets and machine learning. The pipeline is designed against it. |
| **AI skills** | Portable agent skills, in the open Agent Skills format, for specs, plans, code review, deep research, wikis and staged research workspaces |
| **to-markdown** | Converts EPUB and PDF books into clean, sectioned Markdown so they can feed the wiki |

Our repositories are private while the system matures. We'll open them up as each piece
stabilises.

## Roadmap

1. **Research foundation.** Data, features, labels and leakage-safe validation. *(in progress)*
2. **Backtest and sizing.** An event-driven backtester with realistic costs, plus Kelly and CVaR sizing.
3. **Paper trading.** Alpaca execution with kill switches and monitoring.
4. **Learning loop.** Post-trade attribution, drift detection, and scheduled and RL-driven retuning.

---

<p align="center">
  <img src="https://raw.githubusercontent.com/adg-finance/.github/main/profile/assets/brand/adg-logo.svg#gh-light-mode-only" width="32" alt="ADG logo">
  <img src="https://raw.githubusercontent.com/adg-finance/.github/main/profile/assets/brand/adg-logo-inverse.svg#gh-dark-mode-only" width="32" alt="ADG logo">
</p>
