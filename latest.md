# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T20:30:11Z**
- feed_generated_utc: 2026-10-17T20:30:12+00:00
- source_sha256: `ebb8d68409b5047aa71d1ab7899dbc3d13eb3e0a7e312a12b2e57a9813e836be`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T20:30+00:00, close=81591.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.255100|-6.24|UNKNOWN|-6.57|6708150|3.92|
|STRK_USDT|0.065060|-1.64|-30.36|-1.97|15465394|1.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DNA_USDT|0.255100|0.249000|0.255100|0.55|N|Y/Y|?|Y|N|
|STRK_USDT|0.065060|0.064620|0.065060|0.64|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DNA_USDT: quote_utc=2026-10-17T20:30:01+00:00, last15m_closed_end=2026-10-17T20:30+00:00, prior8high=0.264600, depth_time=2026-10-17T20:30:06+00:00, book20_bid_proxy_usdt=76258, book20_ask_proxy_usdt=81032, funding_indicative=-0.001173, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.24%, turnover=6708150. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T20:30:02+00:00, last15m_closed_end=2026-10-17T20:30+00:00, prior8high=0.068240, depth_time=2026-10-17T20:30:10+00:00, book20_bid_proxy_usdt=251841, book20_ask_proxy_usdt=283991, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.64%, turnover=15465394. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
