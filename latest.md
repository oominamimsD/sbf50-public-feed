# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T21:15:19Z**
- feed_generated_utc: 2026-10-25T21:15:21+00:00
- source_sha256: `90a8fb28d0a85c81dd6fd5ae7ada988096cc03205b96eff5f39bdfd2bdf88d86`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T21:15+00:00, close=80467.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T21:00+00:00, close=80457, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.035990|-6.37|195.00|-6.21|20296351|2.78|
|T_USDT|0.005292|-1.69|12.54|-1.53|8530201|1.89|
|DASH_USDT|51.580000|-1.58|7.72|-1.42|13980418|1.94|
|USELESS_USDT|0.169880|-1.55|20.10|-1.39|5076692|1.77|
|PEPE_USDT|0.000004|-1.26|12.59|-1.10|73401722|2.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.580000|51.670000|51.610000|1.48|Y|Y/N|N/N|Y|N|
|IRYS_USDT|0.035990|0.035580|0.035990|0.74|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|4.14|Y|Y/Y|Y/Y|Y|Y|
|T_USDT|0.005292|0.005255|0.005295|0.36|N|Y/Y|N/N|Y|N|
|USELESS_USDT|0.169880|0.167500|0.169890|1.18|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-25T21:15:00+00:00, last15m_closed_end=2026-10-25T21:15+00:00, prior8high=52.450000, depth_time=2026-10-25T21:15:13+00:00, book20_bid_proxy_usdt=770064, book20_ask_proxy_usdt=511812, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=13980418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T21:15:00+00:00, last15m_closed_end=2026-10-25T21:15+00:00, prior8high=0.036760, depth_time=2026-10-25T21:15:07+00:00, book20_bid_proxy_usdt=73545, book20_ask_proxy_usdt=80271, funding_indicative=-0.000014, next_funding_utc=2026-10-25T22:00:00+00:00, funding_cycle_h=1, 24h_change=-6.37%, turnover=20296351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-25T21:15:00+00:00, last15m_closed_end=2026-10-25T21:15+00:00, prior8high=0.000004, depth_time=2026-10-25T21:15:18+00:00, book20_bid_proxy_usdt=26106, book20_ask_proxy_usdt=95922, funding_indicative=0.000035, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=73401722. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-25T21:15:00+00:00, last15m_closed_end=2026-10-25T21:15+00:00, prior8high=0.005459, depth_time=2026-10-25T21:15:09+00:00, book20_bid_proxy_usdt=91016, book20_ask_proxy_usdt=86233, funding_indicative=-0.003273, next_funding_utc=2026-10-25T22:00:00+00:00, funding_cycle_h=1, 24h_change=-1.69%, turnover=8530201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T21:15:00+00:00, last15m_closed_end=2026-10-25T21:15+00:00, prior8high=0.170640, depth_time=2026-10-25T21:15:15+00:00, book20_bid_proxy_usdt=28706, book20_ask_proxy_usdt=25349, funding_indicative=0.000134, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.55%, turnover=5076692. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
