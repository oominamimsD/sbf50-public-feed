# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T21:45:21Z**
- feed_generated_utc: 2026-10-25T21:45:24+00:00
- source_sha256: `564c4dcc1da236c2a7298299cb92b59f7a52972f114a3499a9253a422183fe69`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T21:45+00:00, close=80349.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T21:00+00:00, close=80457, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.036350|-5.43|197.95|-5.14|20379326|2.75|
|T_USDT|0.005242|-2.61|11.48|-2.32|8548175|7.62|
|TIA_USDT|0.526900|-1.89|-14.72|-1.60|18554047|1.90|
|USELESS_USDT|0.169330|-1.87|19.71|-1.58|5096488|1.18|
|DASH_USDT|51.580000|-1.58|7.72|-1.29|14201279|1.94|
|PEPE_USDT|0.000004|-1.47|12.35|-1.18|75665357|0.69|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.580000|51.350000|51.580000|0.26|N|Y/N|N/N|Y|N|
|IRYS_USDT|0.036350|0.035580|0.036350|0.73|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|2.46|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.526900|0.528400|0.526900|1.47|Y|Y/N|Y/Y|Y|N|
|T_USDT|0.005242|0.005255|0.005242|1.42|Y|Y/Y|N/N|Y|N|
|USELESS_USDT|0.169330|0.167710|0.169330|0.70|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-25T21:45:01+00:00, last15m_closed_end=2026-10-25T21:45+00:00, prior8high=52.280000, depth_time=2026-10-25T21:45:18+00:00, book20_bid_proxy_usdt=643115, book20_ask_proxy_usdt=600752, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=14201279. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T21:45:00+00:00, last15m_closed_end=2026-10-25T21:45+00:00, prior8high=0.036760, depth_time=2026-10-25T21:45:07+00:00, book20_bid_proxy_usdt=64960, book20_ask_proxy_usdt=54501, funding_indicative=-0.000034, next_funding_utc=2026-10-25T22:00:00+00:00, funding_cycle_h=1, 24h_change=-5.43%, turnover=20379326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-25T21:45:00+00:00, last15m_closed_end=2026-10-25T21:45+00:00, prior8high=0.000004, depth_time=2026-10-25T21:45:20+00:00, book20_bid_proxy_usdt=586138, book20_ask_proxy_usdt=96343, funding_indicative=0.000053, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=75665357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-25T21:45:01+00:00, last15m_closed_end=2026-10-25T21:45+00:00, prior8high=0.536000, depth_time=2026-10-25T21:45:10+00:00, book20_bid_proxy_usdt=180361, book20_ask_proxy_usdt=215748, funding_indicative=0.000033, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.89%, turnover=18554047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-25T21:45:00+00:00, last15m_closed_end=2026-10-25T21:45+00:00, prior8high=0.005412, depth_time=2026-10-25T21:45:10+00:00, book20_bid_proxy_usdt=99802, book20_ask_proxy_usdt=74943, funding_indicative=-0.003389, next_funding_utc=2026-10-25T22:00:00+00:00, funding_cycle_h=1, 24h_change=-2.61%, turnover=8548175. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T21:45:01+00:00, last15m_closed_end=2026-10-25T21:45+00:00, prior8high=0.170810, depth_time=2026-10-25T21:45:14+00:00, book20_bid_proxy_usdt=23147, book20_ask_proxy_usdt=22092, funding_indicative=0.000113, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.87%, turnover=5096488. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
