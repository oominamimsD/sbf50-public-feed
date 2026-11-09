# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T05:00:28Z**
- feed_generated_utc: 2026-11-09T05:00:29+00:00
- source_sha256: `b7d7a7a3d42c57636132358cb6dfd3c1f3d939ac5c3bce68296abe418e6bfd75`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T05:00+00:00, close=74800, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T05:00+00:00, close=74800, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.008240|-16.20|65.49|-14.58|67302138|1.21|
|AKE_USDT|0.004640|-13.38|-49.34|-11.76|11261179|4.31|
|ONE_USDT|0.001643|-13.15|41.07|-11.53|10014767|0.61|
|ASTER_USDT|0.640400|-5.47|-8.43|-3.85|5123025|1.56|
|XRP_USDT|1.105100|-4.38|-11.58|-2.76|228873454|0.91|
|PUMPFUN_USDT|0.003575|-4.25|-15.24|-2.63|9262440|2.80|
|HYPE_USDT|74.509000|-3.77|-15.02|-2.15|39605636|0.13|
|LIT_USDT|3.113900|-3.57|-3.59|-1.95|13520689|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004640|0.004627|0.004656|0.62|N|Y/Y|Y/N|Y|N|
|ASTER_USDT|0.640400|0.637000|0.640400|7.27|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|74.509000|74.350000|74.541000|0.50|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008240|0.007861|0.008200|1.09|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.113900|3.086100|3.113900|0.30|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001643|0.001636|0.001643|1.63|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003575|0.003574|0.003575|0.23|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.105100|1.103000|1.105200|0.63|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T05:00:03+00:00, last15m_closed_end=2026-11-09T05:00+00:00, prior8high=0.005144, depth_time=2026-11-09T05:00:10+00:00, book20_bid_proxy_usdt=45132, book20_ask_proxy_usdt=52204, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.38%, turnover=11261179. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T05:00:03+00:00, last15m_closed_end=2026-11-09T05:00+00:00, prior8high=0.648500, depth_time=2026-11-09T05:00:13+00:00, book20_bid_proxy_usdt=528915, book20_ask_proxy_usdt=766494, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.47%, turnover=5123025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T05:00:03+00:00, last15m_closed_end=2026-11-09T05:00+00:00, prior8high=75.167000, depth_time=2026-11-09T05:00:24+00:00, book20_bid_proxy_usdt=68724, book20_ask_proxy_usdt=78687, funding_indicative=0.000038, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.77%, turnover=39605636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T05:00:03+00:00, last15m_closed_end=2026-11-09T05:00+00:00, prior8high=0.009714, depth_time=2026-11-09T05:00:08+00:00, book20_bid_proxy_usdt=24630, book20_ask_proxy_usdt=26967, funding_indicative=0.001511, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.20%, turnover=67302138. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T05:00:03+00:00, last15m_closed_end=2026-11-09T05:00+00:00, prior8high=3.158500, depth_time=2026-11-09T05:00:27+00:00, book20_bid_proxy_usdt=24140, book20_ask_proxy_usdt=20436, funding_indicative=-0.000032, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.57%, turnover=13520689. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T05:00:03+00:00, last15m_closed_end=2026-11-09T05:00+00:00, prior8high=0.001702, depth_time=2026-11-09T05:00:13+00:00, book20_bid_proxy_usdt=9626, book20_ask_proxy_usdt=9203, funding_indicative=-0.000271, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.15%, turnover=10014767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T05:00:03+00:00, last15m_closed_end=2026-11-09T05:00+00:00, prior8high=0.003668, depth_time=2026-11-09T05:00:21+00:00, book20_bid_proxy_usdt=2796129, book20_ask_proxy_usdt=2741492, funding_indicative=0.000009, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=9262440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T05:00:03+00:00, last15m_closed_end=2026-11-09T05:00+00:00, prior8high=1.120800, depth_time=2026-11-09T05:00:18+00:00, book20_bid_proxy_usdt=3138640, book20_ask_proxy_usdt=3346718, funding_indicative=-0.000009, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.38%, turnover=228873454. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
