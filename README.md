# Marco Fabroni

### Python Developer · Quantitative Research & Financial Software

I design and build software systems that combine **Python, financial data, quantitative research, automation, and risk-aware execution**.

My public work focuses on turning complex workflows into modular, testable software rather than building isolated prototypes.

---

## What I build

- **Quantitative & financial systems** — research workflows, backtesting, portfolio logic, risk controls, execution and monitoring
- **AI-assisted tooling** — MCP-based tooling and AI-assisted workflows around financial data
- **Data persistence & tooling** — SQLite-backed storage, MCP server/client tooling, reporting and integrations
- **Automation & developer tooling** — reproducible workflows, CLI/TUI tools, reporting and operational tooling
- **System architecture** — separation of research, strategy, risk, execution, state and monitoring concerns

## Core skills

What you can verify in my **public repositories**:

| Area | Technologies / practices |
|---|---|
| Languages | **Python** |
| Quant & Finance | Backtesting, walk-forward validation, risk gating, portfolio optimisation (PyPortfolioOpt), market data (yfinance, Alpaca) |
| AI & Agents | MCP server/client tooling, reinforcement-learning environments (Gymnasium, Stable-Baselines3) |
| Data | Pandas, NumPy, SciPy, SQLite |
| Engineering | pytest test suites, GitHub Actions CI, modular architecture, configuration via environment variables |

---

## Featured work

### [TradingLab](https://github.com/iFabbro/TradingLab) · [![CI](https://github.com/iFabbro/TradingLab/actions/workflows/ci.yml/badge.svg)](https://github.com/iFabbro/TradingLab/actions/workflows/ci.yml)

A controlled quantitative trading laboratory focused on the separation of **research, risk, execution and persistent system state**.

**Focus:** Python · quantitative research · risk management · execution · testing · system design

**Result worth reading:** a strategy with a +45.65% net out-of-sample return was rejected by the research protocol after comparison with buy-and-hold (+101.26% over the same days).

**Status:** research and supervised-execution project (paper/dry-run), *not* a production trading system.

**Read:** [Case study: a research pipeline that rejects its own strategies](https://github.com/iFabbro/TradingLab/blob/main/docs/CASE_STUDY.md)

### [STMAA](https://github.com/iFabbro/STMAA) · [![CI](https://github.com/iFabbro/STMAA/actions/workflows/ci.yml/badge.svg)](https://github.com/iFabbro/STMAA/actions/workflows/ci.yml)

A modular trading architecture combining **market data, feature engineering, strategies, portfolio weights, risk overlays, broker integration and monitoring**.

**Focus:** Python · quantitative systems · strategy architecture · risk overlays · execution · backtesting

**Status:** alpha / experimental, paper-trading by default.

### [financial-micro-saas](https://github.com/iFabbro/financial-micro-saas) · [![CI](https://github.com/iFabbro/financial-micro-saas/actions/workflows/ci.yml/badge.svg)](https://github.com/iFabbro/financial-micro-saas/actions/workflows/ci.yml)

A local financial software project exploring **financial data workflows, MCP-based tooling, reporting and reproducible application architecture**.

**Focus:** Python · MCP · financial data · APIs · automation · testing

---

## Engineering approach

I prefer systems that are:

- modular rather than monolithic;
- explicit about boundaries between components;
- reproducible and testable;
- conservative around credentials, state and execution;
- documented well enough that another developer can understand the architecture quickly.

For financial and automated systems, I treat **risk controls and failure modes as first-class engineering concerns**, not as features added after the core logic.

---

## Currently focusing on

- Strengthening quantitative execution architectures
- Building practical tooling around financial workflows
- Improving testing, linting and CI across my projects
- Turning selected research projects into clean, reproducible portfolio case studies

---

## Selected technologies

`Python` `Pandas` `NumPy` `SciPy` `SQLite` `pytest` `GitHub Actions` `MCP` `yfinance` `Alpaca API` `Gymnasium`

---

## Contact

Based in Milan, Italy · Italian (native), English (technical reading and writing)

Open to **remote** software / quantitative-development roles. Reach me on [LinkedIn](www.linkedin.com/in/marco-fabroni-436b2440b) or GitHub: [@iFabbro](https://github.com/iFabbro)

---

<sub>This profile highlights selected engineering work. Individual repositories contain the implementation details, limitations, tests and documentation for each project.</sub>
