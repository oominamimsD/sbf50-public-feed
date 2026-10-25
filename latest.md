# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T23:30:19Z**
- feed_generated_utc: 2026-10-25T23:30:21+00:00
- source_sha256: `a5066838aafee9836c5995093870a790669356fc95fb1104feb772f9c387fc9f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T23:30+00:00, close=80039.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T23:00+00:00, close=80429.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.006145|-11.86|233.42|-11.18|10154999|3.25|
|USELESS_USDT|0.167820|-2.75|18.65|-2.07|5033219|1.79|
|PEPE_USDT|0.000004|-2.43|11.25|-1.75|75615338|0.94|
|XMR_USDT|592.960000|-2.35|1.79|-1.67|6687895|1.01|
|DASH_USDT|51.400000|-1.92|7.35|-1.24|13888222|1.95|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.400000|51.310000|51.400000|0.72|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.006145|0.006081|0.006168|2.83|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|3.09|Y|Y/Y|Y/Y|Y|Y|
|USELESS_USDT|0.167820|0.167580|0.167770|2.32|N|Y/Y|N/N|Y|N|
|XMR_USDT|592.960000|592.960000|592.960000|0.71|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-25T23:30:01+00:00, last15m_closed_end=2026-10-25T23:30+00:00, prior8high=51.970000, depth_time=2026-10-25T23:30:18+00:00, book20_bid_proxy_usdt=654784, book20_ask_proxy_usdt=243467, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=13888222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-25T23:30:01+00:00, last15m_closed_end=2026-10-25T23:30+00:00, prior8high=0.006991, depth_time=2026-10-25T23:30:08+00:00, book20_bid_proxy_usdt=20991, book20_ask_proxy_usdt=24070, funding_indicative=0.000083, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.86%, turnover=10154999. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-25T23:30:01+00:00, last15m_closed_end=2026-10-25T23:30+00:00, prior8high=0.000004, depth_time=2026-10-25T23:30:13+00:00, book20_bid_proxy_usdt=67030, book20_ask_proxy_usdt=52975, funding_indicative=0.000029, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=75615338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T23:30:01+00:00, last15m_closed_end=2026-10-25T23:30+00:00, prior8high=0.171640, depth_time=2026-10-25T23:30:10+00:00, book20_bid_proxy_usdt=23933, book20_ask_proxy_usdt=17407, funding_indicative=0.000050, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=5033219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T23:30:01+00:00, last15m_closed_end=2026-10-25T23:30+00:00, prior8high=601.720000, depth_time=2026-10-25T23:30:15+00:00, book20_bid_proxy_usdt=15373, book20_ask_proxy_usdt=28964, funding_indicative=0.000101, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.35%, turnover=6687895. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
