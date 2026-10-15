# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T22:15:10Z**
- feed_generated_utc: 2026-10-15T22:15:12+00:00
- source_sha256: `243858bb82fe17d3a9e6341483ca9191421cca4faad16a24bb63cc150e70af8d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T22:15+00:00, close=82416, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T22:00+00:00, close=82385.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T20:00+00:00, close=82350.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.051550|-3.28|54.85|-3.32|8137839|1.94|
|NIL_USDT|0.084210|-3.07|-2.74|-3.11|13404012|1.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.084210|0.081300|0.084240|0.20|N|Y/Y|N/N|Y|N|
|WAL_USDT|0.051550|0.050780|0.051550|1.04|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-15T22:15:02+00:00, last15m_closed_end=2026-10-15T22:15+00:00, prior8high=0.085480, depth_time=2026-10-15T22:15:09+00:00, book20_bid_proxy_usdt=30926, book20_ask_proxy_usdt=27990, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=13404012. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T22:15:02+00:00, last15m_closed_end=2026-10-15T22:15+00:00, prior8high=0.052350, depth_time=2026-10-15T22:15:07+00:00, book20_bid_proxy_usdt=150201, book20_ask_proxy_usdt=131825, funding_indicative=-0.000218, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=8137839. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
