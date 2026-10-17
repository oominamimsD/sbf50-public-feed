# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T20:15:11Z**
- feed_generated_utc: 2026-10-17T20:15:13+00:00
- source_sha256: `d66706da13c43be9ed1a966b193d6797fe3317891d6b64d1364ccbcd6bdd320e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T20:15+00:00, close=81587.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.259800|-4.52|UNKNOWN|-4.85|6692889|7.71|
|STRK_USDT|0.065510|-0.96|-29.88|-1.29|15336642|6.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DNA_USDT|0.259800|0.249000|0.260000|0.18|N|Y/Y|?|Y|N|
|STRK_USDT|0.065510|0.064620|0.065530|1.37|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DNA_USDT: quote_utc=2026-10-17T20:14:59+00:00, last15m_closed_end=2026-10-17T20:15+00:00, prior8high=0.264600, depth_time=2026-10-17T20:15:07+00:00, book20_bid_proxy_usdt=79130, book20_ask_proxy_usdt=87683, funding_indicative=-0.001212, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.52%, turnover=6692889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T20:14:59+00:00, last15m_closed_end=2026-10-17T20:15+00:00, prior8high=0.068240, depth_time=2026-10-17T20:15:10+00:00, book20_bid_proxy_usdt=302660, book20_ask_proxy_usdt=213644, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=15336642. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
