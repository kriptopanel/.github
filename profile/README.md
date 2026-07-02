<div align="center">

# KriptoPanel

**Real-time crypto market analytics with an ML sentiment engine.**

Live exchange data fused with model-driven sentiment — so a signal is never read in isolation.

### [→ kriptopanel.com](https://kriptopanel.com)

</div>

---

### What it is

KriptoPanel continuously ingests live market data, computes technical-analysis indicators, and scores market mood with a machine-learning sentiment engine — then fuses the two into a single, real-time view. Production ML, not a notebook.

### How it works

- **Streaming ingestion** — an async pipeline pulling live market data from exchange APIs (Binance, Bybit) alongside social & news feeds
- **Technical-analysis engine** — orderflow-aware indicators: Market Profile / Auction Market Theory, CVD, Open Interest, Fibonacci
- **ML / NLP sentiment** — an ensemble of transformer + rule-based models: CryptoBERT, FinBERT, twitter-roberta, VADER
- **Signal fusion** — sentiment score fused with live price into one actionable signal

### Stack

`Python` · async streaming pipeline · `Hugging Face Transformers` · `scikit-learn` / `SciPy` · exchange APIs · `PostgreSQL`

---

<sub>Designed and built solo by <a href="https://github.com/mertgunay">Mert G.</a> · Source is private · Full case study → <a href="https://kriptopanel.com">kriptopanel.com</a></sub>
