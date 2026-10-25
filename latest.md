# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T22:00:21Z**
- feed_generated_utc: 2026-10-25T22:00:25+00:00
- source_sha256: `8af6907b1a617a012c2894181442ebda74892fb52ca951e675b6270e016c2449`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T22:00+00:00, close=80235.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T22:00+00:00, close=80235.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.036540|-4.94|199.50|-4.50|19966109|8.21|
|T_USDT|0.005254|-2.39|11.73|-1.95|8552896|3.80|
|USELESS_USDT|0.168230|-2.33|18.94|-1.89|5003169|2.38|
|DASH_USDT|51.330000|-2.06|7.20|-1.62|13794413|1.94|
|XMR_USDT|596.810000|-1.89|2.45|-1.45|6433020|0.17|
|PEPE_USDT|0.000004|-1.65|12.15|-1.21|72382896|0.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.330000|51.350000|51.330000|1.67|Y|Y/Y|N/N|Y|N|
|IRYS_USDT|0.036540|0.035580|0.036520|0.40|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|2.77|Y|Y/Y|Y/Y|Y|Y|
|T_USDT|0.005254|0.005240|0.005278|0.85|N|Y/Y|N/N|Y|N|
|USELESS_USDT|0.168230|0.168290|0.168230|1.58|Y|Y/Y|N/N|Y|N|
|XMR_USDT|596.810000|595.550000|596.810000|2.73|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-25T22:00:03+00:00, last15m_closed_end=2026-10-25T22:00+00:00, prior8high=52.280000, depth_time=2026-10-25T22:00:14+00:00, book20_bid_proxy_usdt=256576, book20_ask_proxy_usdt=385364, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.06%, turnover=13794413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T22:00:03+00:00, last15m_closed_end=2026-10-25T22:00+00:00, prior8high=0.036760, depth_time=2026-10-25T22:00:07+00:00, book20_bid_proxy_usdt=59666, book20_ask_proxy_usdt=58045, funding_indicative=-0.000068, next_funding_utc=2026-10-25T23:00:00+00:00, funding_cycle_h=1, 24h_change=-4.94%, turnover=19966109. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-25T22:00:03+00:00, last15m_closed_end=2026-10-25T22:00+00:00, prior8high=0.000004, depth_time=2026-10-25T22:00:21+00:00, book20_bid_proxy_usdt=31176, book20_ask_proxy_usdt=192920, funding_indicative=0.000057, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=72382896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-25T22:00:03+00:00, last15m_closed_end=2026-10-25T22:00+00:00, prior8high=0.005412, depth_time=2026-10-25T22:00:11+00:00, book20_bid_proxy_usdt=60418, book20_ask_proxy_usdt=60514, funding_indicative=-0.003502, next_funding_utc=2026-10-25T23:00:00+00:00, funding_cycle_h=1, 24h_change=-2.39%, turnover=8552896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T22:00:03+00:00, last15m_closed_end=2026-10-25T22:00+00:00, prior8high=0.170810, depth_time=2026-10-25T22:00:13+00:00, book20_bid_proxy_usdt=36767, book20_ask_proxy_usdt=13355, funding_indicative=0.000105, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=5003169. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T22:00:03+00:00, last15m_closed_end=2026-10-25T22:00+00:00, prior8high=605.460000, depth_time=2026-10-25T22:00:17+00:00, book20_bid_proxy_usdt=11893, book20_ask_proxy_usdt=17228, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=6433020. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
