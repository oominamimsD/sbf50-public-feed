# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T05:00:27Z**
- feed_generated_utc: 2026-11-10T05:00:29+00:00
- source_sha256: `3fe211cf54d207b85237c7a809c43a0e7345f5673d5b50f7d5e9becc5b4295e7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T05:00+00:00, close=74754.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T05:00+00:00, close=74754.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002532|-46.70|-53.98|-45.72|15285004|3.95|
|JCT_USDT|0.007553|-31.17|74.95|-30.19|26465624|6.62|
|ON_USDT|0.166700|-16.23|-1.65|-15.25|5398491|6.00|
|ZEC_USDT|1151.550000|-6.05|-8.17|-5.07|2384838047|0.09|
|ARB_USDT|0.170700|-5.32|7.13|-4.34|32791229|2.34|
|AAVE_USDT|126.610000|-4.45|-3.02|-3.47|13427372|1.58|
|QNT_USDT|191.910000|-4.01|-5.20|-3.03|36267800|0.52|
|DOT_USDT|0.850500|-3.98|-8.94|-3.00|10630626|1.18|
|DASH_USDT|46.130000|-2.49|-2.26|-1.51|14066774|2.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.610000|126.070000|126.630000|0.61|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002532|0.002302|0.002532|0.32|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.170700|0.170530|0.170670|5.95|N|Y/Y|N/N|Y|N|
|DASH_USDT|46.130000|45.750000|46.130000|0.96|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.850500|0.846300|0.850500|1.57|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.007553|0.007550|0.007549|0.94|N|Y/Y|N/N|Y|N|
|ON_USDT|0.166700|0.159800|0.166700|0.39|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.910000|190.450000|191.910000|2.92|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1151.550000|1142.950000|1151.550000|0.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T05:00:00+00:00, last15m_closed_end=2026-11-10T05:00+00:00, prior8high=131.530000, depth_time=2026-11-10T05:00:19+00:00, book20_bid_proxy_usdt=540547, book20_ask_proxy_usdt=317657, funding_indicative=0.000009, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.45%, turnover=13427372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T05:00:00+00:00, last15m_closed_end=2026-11-10T05:00+00:00, prior8high=0.002790, depth_time=2026-11-10T05:00:07+00:00, book20_bid_proxy_usdt=68453, book20_ask_proxy_usdt=43916, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-46.70%, turnover=15285004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T05:00:00+00:00, last15m_closed_end=2026-11-10T05:00+00:00, prior8high=0.173080, depth_time=2026-11-10T05:00:17+00:00, book20_bid_proxy_usdt=276107, book20_ask_proxy_usdt=72046, funding_indicative=-0.000009, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.32%, turnover=32791229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T05:00:00+00:00, last15m_closed_end=2026-11-10T05:00+00:00, prior8high=46.360000, depth_time=2026-11-10T05:00:26+00:00, book20_bid_proxy_usdt=635498, book20_ask_proxy_usdt=459681, funding_indicative=-0.000001, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=14066774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T05:00:00+00:00, last15m_closed_end=2026-11-10T05:00+00:00, prior8high=0.854500, depth_time=2026-11-10T05:00:24+00:00, book20_bid_proxy_usdt=676856, book20_ask_proxy_usdt=518256, funding_indicative=0.000014, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.98%, turnover=10630626. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T05:00:00+00:00, last15m_closed_end=2026-11-10T05:00+00:00, prior8high=0.009262, depth_time=2026-11-10T05:00:10+00:00, book20_bid_proxy_usdt=31306, book20_ask_proxy_usdt=25102, funding_indicative=0.000111, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-31.17%, turnover=26465624. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ON_USDT: quote_utc=2026-11-10T05:00:00+00:00, last15m_closed_end=2026-11-10T05:00+00:00, prior8high=0.167700, depth_time=2026-11-10T05:00:10+00:00, book20_bid_proxy_usdt=82190, book20_ask_proxy_usdt=64136, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.23%, turnover=5398491. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T05:00:00+00:00, last15m_closed_end=2026-11-10T05:00+00:00, prior8high=194.060000, depth_time=2026-11-10T05:00:22+00:00, book20_bid_proxy_usdt=92115, book20_ask_proxy_usdt=95683, funding_indicative=-0.000074, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.01%, turnover=36267800. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T05:00:00+00:00, last15m_closed_end=2026-11-10T05:00+00:00, prior8high=1164.970000, depth_time=2026-11-10T05:00:14+00:00, book20_bid_proxy_usdt=460104, book20_ask_proxy_usdt=278242, funding_indicative=0.000070, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.05%, turnover=2384838047. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
