# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T04:45:36Z**
- feed_generated_utc: 2026-11-10T04:45:38+00:00
- source_sha256: `e517f49a3a6be0dc6d8535942528237b47b505499b133a2241ab5e24cc5a2ead`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T04:45+00:00, close=74674.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002532|-48.29|-53.98|-47.20|15530459|3.95|
|JCT_USDT|0.007604|-24.94|76.14|-23.85|27468177|1.32|
|ARB_USDT|0.171070|-7.04|7.36|-5.95|32301883|0.58|
|ZEC_USDT|1148.550000|-6.29|-8.41|-5.20|2439730514|0.52|
|AAVE_USDT|126.440000|-5.18|-3.15|-4.09|13908606|1.58|
|DOT_USDT|0.849900|-4.60|-9.01|-3.51|10995708|3.53|
|QNT_USDT|190.990000|-4.52|-5.66|-3.43|37477658|2.62|
|HYPE_USDT|73.956000|-3.09|-13.71|-2.00|47970213|0.14|
|DASH_USDT|46.170000|-3.04|-2.18|-1.95|14280869|2.17|
|PUMPFUN_USDT|0.003571|-3.01|-12.98|-1.92|7853816|2.80|
|SOL_USDT|85.890000|-2.27|-8.14|-1.18|648738145|1.16|
|INJ_USDT|8.002000|-2.14|14.16|-1.05|18425263|2.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.440000|127.510000|126.440000|8.01|Y|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002532|0.002302|0.002524|0.53|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.171070|0.170950|0.171070|0.44|N|Y/Y|N/N|Y|N|
|DASH_USDT|46.170000|45.750000|46.170000|0.05|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.849900|0.846300|0.849800|1.32|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.956000|73.284000|73.956000|1.41|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.002000|7.956000|8.002000|0.46|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.007604|0.007649|0.007578|1.34|Y|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003571|0.003550|0.003571|1.56|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|190.990000|190.530000|190.990000|2.09|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|85.890000|85.470000|85.890000|2.12|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1148.550000|1141.980000|1148.550000|1.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T04:45:01+00:00, last15m_closed_end=2026-11-10T04:45+00:00, prior8high=131.530000, depth_time=2026-11-10T04:45:17+00:00, book20_bid_proxy_usdt=427136, book20_ask_proxy_usdt=942824, funding_indicative=0.000014, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.18%, turnover=13908606. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T04:45:01+00:00, last15m_closed_end=2026-11-10T04:45+00:00, prior8high=0.002790, depth_time=2026-11-10T04:45:08+00:00, book20_bid_proxy_usdt=97790, book20_ask_proxy_usdt=48542, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-48.29%, turnover=15530459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T04:45:01+00:00, last15m_closed_end=2026-11-10T04:45+00:00, prior8high=0.173200, depth_time=2026-11-10T04:45:12+00:00, book20_bid_proxy_usdt=85498, book20_ask_proxy_usdt=59556, funding_indicative=-0.000009, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.04%, turnover=32301883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T04:45:01+00:00, last15m_closed_end=2026-11-10T04:45+00:00, prior8high=46.360000, depth_time=2026-11-10T04:45:24+00:00, book20_bid_proxy_usdt=665130, book20_ask_proxy_usdt=574014, funding_indicative=-0.000004, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.04%, turnover=14280869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T04:45:01+00:00, last15m_closed_end=2026-11-10T04:45+00:00, prior8high=0.854400, depth_time=2026-11-10T04:45:17+00:00, book20_bid_proxy_usdt=751109, book20_ask_proxy_usdt=578765, funding_indicative=0.000045, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.60%, turnover=10995708. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T04:45:01+00:00, last15m_closed_end=2026-11-10T04:45+00:00, prior8high=74.434000, depth_time=2026-11-10T04:45:24+00:00, book20_bid_proxy_usdt=93348, book20_ask_proxy_usdt=77182, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.09%, turnover=47970213. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-10T04:45:01+00:00, last15m_closed_end=2026-11-10T04:45+00:00, prior8high=8.091000, depth_time=2026-11-10T04:45:35+00:00, book20_bid_proxy_usdt=236802, book20_ask_proxy_usdt=246355, funding_indicative=-0.000052, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=18425263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T04:45:01+00:00, last15m_closed_end=2026-11-10T04:45+00:00, prior8high=0.009265, depth_time=2026-11-10T04:45:10+00:00, book20_bid_proxy_usdt=21858, book20_ask_proxy_usdt=16368, funding_indicative=0.000191, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-24.94%, turnover=27468177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T04:45:01+00:00, last15m_closed_end=2026-11-10T04:45+00:00, prior8high=0.003601, depth_time=2026-11-10T04:45:28+00:00, book20_bid_proxy_usdt=2511324, book20_ask_proxy_usdt=2478816, funding_indicative=0.000020, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=7853816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T04:45:01+00:00, last15m_closed_end=2026-11-10T04:45+00:00, prior8high=194.060000, depth_time=2026-11-10T04:45:22+00:00, book20_bid_proxy_usdt=92895, book20_ask_proxy_usdt=84610, funding_indicative=-0.000060, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.52%, turnover=37477658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T04:45:01+00:00, last15m_closed_end=2026-11-10T04:45+00:00, prior8high=86.240000, depth_time=2026-11-10T04:45:29+00:00, book20_bid_proxy_usdt=18938886, book20_ask_proxy_usdt=14900650, funding_indicative=-0.000001, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=648738145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T04:45:01+00:00, last15m_closed_end=2026-11-10T04:45+00:00, prior8high=1164.970000, depth_time=2026-11-10T04:45:15+00:00, book20_bid_proxy_usdt=265143, book20_ask_proxy_usdt=205260, funding_indicative=0.000069, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.29%, turnover=2439730514. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
