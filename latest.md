# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T18:00:18Z**
- feed_generated_utc: 2026-11-08T18:00:19+00:00
- source_sha256: `bf5e36cb3d705550305552603f57dbb70420445837b71fb3e9e73f04621c324a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T18:00+00:00, close=75716, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T18:00+00:00, close=75716, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001803|-7.89|54.86|-7.47|19164703|1.11|
|NEAR_USDT|3.602000|-2.67|-16.83|-2.25|31277572|2.78|
|AKE_USDT|0.005267|-1.68|-42.50|-1.26|21094436|1.90|
|PUMPFUN_USDT|0.003674|-1.68|-12.89|-1.26|10472059|2.72|
|ZEC_USDT|1250.560000|-1.58|1.02|-1.16|1425158063|0.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005267|0.005192|0.005264|0.50|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.602000|3.586000|3.602000|0.61|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001803|0.001693|0.001804|0.39|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003674|0.003635|0.003674|0.55|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1250.560000|1238.290000|1250.560000|0.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T17:59:59+00:00, last15m_closed_end=2026-11-08T18:00+00:00, prior8high=0.005415, depth_time=2026-11-08T18:00:12+00:00, book20_bid_proxy_usdt=40382, book20_ask_proxy_usdt=38912, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=21094436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T17:59:59+00:00, last15m_closed_end=2026-11-08T18:00+00:00, prior8high=3.711000, depth_time=2026-11-08T18:00:09+00:00, book20_bid_proxy_usdt=3809636, book20_ask_proxy_usdt=4113609, funding_indicative=0.000061, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=31277572. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T17:59:59+00:00, last15m_closed_end=2026-11-08T18:00+00:00, prior8high=0.001987, depth_time=2026-11-08T18:00:07+00:00, book20_bid_proxy_usdt=13912, book20_ask_proxy_usdt=10638, funding_indicative=-0.001243, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.89%, turnover=19164703. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-08T17:59:59+00:00, last15m_closed_end=2026-11-08T18:00+00:00, prior8high=0.003757, depth_time=2026-11-08T18:00:14+00:00, book20_bid_proxy_usdt=2308777, book20_ask_proxy_usdt=2240503, funding_indicative=0.000001, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=10472059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T17:59:59+00:00, last15m_closed_end=2026-11-08T18:00+00:00, prior8high=1275.830000, depth_time=2026-11-08T18:00:17+00:00, book20_bid_proxy_usdt=202476, book20_ask_proxy_usdt=190087, funding_indicative=0.000034, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=1425158063. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
