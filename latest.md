# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T19:00:13Z**
- feed_generated_utc: 2026-11-08T19:00:14+00:00
- source_sha256: `307ba599e48f2459b4fe651ea346a8db9ba427fdd66ffb5cbd18edbf7f15cd24`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T19:00+00:00, close=75913.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T19:00+00:00, close=75913.5, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001803|-4.65|54.87|-4.49|16225801|0.56|
|AKE_USDT|0.005187|-2.70|-43.37|-2.54|18203520|3.86|
|LIT_USDT|3.180500|-1.51|-1.53|-1.35|6852982|0.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005187|0.005162|0.005187|0.68|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.180500|3.136500|3.180500|0.20|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001803|0.001693|0.001803|0.25|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T19:00:03+00:00, last15m_closed_end=2026-11-08T19:00+00:00, prior8high=0.005344, depth_time=2026-11-08T19:00:09+00:00, book20_bid_proxy_usdt=54463, book20_ask_proxy_usdt=57150, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.70%, turnover=18203520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-08T19:00:03+00:00, last15m_closed_end=2026-11-08T19:00+00:00, prior8high=3.193100, depth_time=2026-11-08T19:00:10+00:00, book20_bid_proxy_usdt=19204, book20_ask_proxy_usdt=34845, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=6852982. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T19:00:03+00:00, last15m_closed_end=2026-11-08T19:00+00:00, prior8high=0.001846, depth_time=2026-11-08T19:00:07+00:00, book20_bid_proxy_usdt=15928, book20_ask_proxy_usdt=9902, funding_indicative=-0.000915, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.65%, turnover=16225801. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
