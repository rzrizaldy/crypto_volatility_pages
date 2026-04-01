# Crypto Volatility Intelligence — Live Preview

**Author:** Rizaldy Utomo · `rutomo@andrew.cmu.edu`
**Course:** Fundamentals of Operationalizing AI — Carnegie Mellon University

Static dashboard served via GitHub Pages. Source code is private.

---

## Pages

| Link | Description |
|---|---|
| [Dashboard](https://rzrizaldy.github.io/crypto_volatility_pages/) | Real session data — BTC-USD + ETH-USD, Apr 1 2026 |
| [Evidently Drift Report](https://rzrizaldy.github.io/crypto_volatility_pages/reports/evidently.html) | Train-vs-test feature distribution shift |
| [Model Evaluation PDF](https://rzrizaldy.github.io/crypto_volatility_pages/reports/model_eval.pdf) | Full evaluation report |

> **Live streaming mode** (real-time Coinbase prices + model inference) requires running the full pipeline locally. Source available on request.

---

## Results

| Model | PR-AUC | F1 |
|---|---:|---:|
| Baseline z-score | 0.8257 | 0.7582 |
| **Logistic regression** | **0.8439** | **0.8397** |

Session: Coinbase Advanced Trade · BTC-USD + ETH-USD · 2026-04-01T02:33–03:25 UTC (≈ 52.7 min)
Data: 37,435 live ticks → 6,316 usable 1-second feature bars
