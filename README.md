# Hi, I'm gtsmmst

Crypto native (10+ years) turned builder. I research prediction markets and sports/esports
betting — the places where bookmaker odds, Polymarket prices and public data disagree — and
build the tooling to test ideas end-to-end: data collection, probability models, paper-trading
labs and execution bots on a VPS.

I work with AI pair-programmers as the product owner: I set the hypotheses, filters and risk
rules; the models help write and test the code. Everything public here is research tooling —
nothing is a proven money-making strategy.

## Projects

| Repo | What it is |
|---|---|
| [sports-prob-models](https://github.com/gtsmmst/sports-prob-models) | Probability models (CS2 round → map → series, football Poisson/xG) and sizing math (Kelly, arbitrage, hedging). Pure Python, 183 tests. |
| [cs2-polymarket-latency-lab](https://github.com/gtsmmst/cs2-polymarket-latency-lab) | How fast do CS2 match events reach Polymarket prices? Go GOTV parser, CLOB websocket watcher, SQLite events bus, latency dashboards. |
| [polymarket-news-terminal](https://github.com/gtsmmst/polymarket-news-terminal) | News → entity extraction → Polymarket market matching → opportunity score. FastAPI research terminal. |
| panda-trading-stack *(private)* | The live stack: odds dashboard, strategy lab with pre-registered paper strategies, execution bots, GitHub-driven deploys to a VPS. |

## Stack

Python (FastAPI, SQLite, pytest) · Go · Polymarket CLOB / Gamma APIs · bookmaker odds feeds ·
Telegram alerts · Linux, systemd, GitHub Actions

## Interests

prediction markets · market microstructure · smart-contract security (learning) · automation
