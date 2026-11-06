# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T15:00:16Z**
- feed_generated_utc: 2026-11-06T15:00:17+00:00
- source_sha256: `e4cb8dc70a9a2493c44deaaa9021b96a2b49fdb2ddb5cab63f3cd6662deb450e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T15:00+00:00, close=75511.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T15:00+00:00, close=75511.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T12:00+00:00, close=76114.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|268.060000|-5.87|-7.01|-5.24|6459108|5.60|
|XRP_USDT|1.186000|-4.70|-9.43|-4.07|458057648|0.84|
|QNT_USDT|190.540000|-4.55|-4.12|-3.92|39215741|0.53|
|ASTER_USDT|0.683600|-1.99|-5.14|-1.36|5010816|1.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.683600|0.679300|0.683600|2.96|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|268.060000|264.300000|268.060000|3.89|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|190.540000|187.280000|190.540000|4.95|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.186000|1.174300|1.186000|2.20|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-11-06T15:00:02+00:00, last15m_closed_end=2026-11-06T15:00+00:00, prior8high=0.687800, depth_time=2026-11-06T15:00:15+00:00, book20_bid_proxy_usdt=574073, book20_ask_proxy_usdt=590654, funding_indicative=0.000050, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=5010816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-06T15:00:02+00:00, last15m_closed_end=2026-11-06T15:00+00:00, prior8high=270.360000, depth_time=2026-11-06T15:00:07+00:00, book20_bid_proxy_usdt=47375, book20_ask_proxy_usdt=61583, funding_indicative=-0.000039, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.87%, turnover=6459108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T15:00:02+00:00, last15m_closed_end=2026-11-06T15:00+00:00, prior8high=192.220000, depth_time=2026-11-06T15:00:12+00:00, book20_bid_proxy_usdt=49982, book20_ask_proxy_usdt=42967, funding_indicative=-0.000014, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.55%, turnover=39215741. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T15:00:01+00:00, last15m_closed_end=2026-11-06T15:00+00:00, prior8high=1.195100, depth_time=2026-11-06T15:00:10+00:00, book20_bid_proxy_usdt=1135574, book20_ask_proxy_usdt=1322076, funding_indicative=0.000071, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.70%, turnover=458057648. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
