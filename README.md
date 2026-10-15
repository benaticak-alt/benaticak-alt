### Hi, I build data and trading-research tools in Python, and I'm careful about which results to trust

Most of my work tests whether something actually works: trading signals, prediction-market strategies, game economies. When a result looks too good, I find out why before I believe it.

**Open to contract work:** Python automation, data pipelines, backtesting and research tooling, and API integrations.

---

#### Featured

**[polylab](https://github.com/benaticak-alt/polylab)**: a strategy tournament over 112,636 resolved Polymarket markets. One rule showed +18% per trade on a 75k-market holdout (t = 8) and passed look-ahead and order-book checks. Then I traced it to a selection bias: filtering markets on their *final* volume leaks the outcome. The write-up covers how it was caught. It also includes a paper market-maker that tests whether liquidity rewards outpay adverse selection.

**[claude-daytrader](https://github.com/benaticak-alt/claude-daytrader)**: an equities trading research platform with paper trading, shadow strategies, ML signal models and an SEC Form 4 insider-buying study. Every intraday strategy failed out of sample, and the README says so up front. The one signal that survived (insider buys, month-clustered t = +3.4) is being forward-tested live.

**[polymarket_bot](https://github.com/benaticak-alt/polymarket_bot)**: an async trading system for Polymarket's 5- and 15-minute crypto markets. It has a 58-feature signal vector, an online-retrained gradient-boosting model, fractional-Kelly sizing and CLOB execution. It also found its own biggest bug: half the paper P&L came from a price-feed fallback.

**[screenpilot](https://github.com/benaticak-alt/screenpilot)**: a desktop chat app where an AI sees your screen and can click and type. It runs on a free local vision model by default, so nothing leaves your machine.

**[mogul](https://github.com/benaticak-alt/mogul)**: an incremental game in Godot 4 with a prestige loop and a 22-perk legacy tree. Its pacing was tuned with an in-engine bot instead of guesswork, which took a full playthrough from guessed to 5h18m, measured.

---

**Stack:** Python (pandas, NumPy, scikit-learn, LightGBM, asyncio), REST and WebSocket APIs, SEC EDGAR, Alpaca, Polymarket CLOB, Godot/GDScript, Blender
