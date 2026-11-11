# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T00:45:17Z**
- feed_generated_utc: 2026-11-11T00:45:19+00:00
- source_sha256: `20a305b2485340b40911120219f4c3fc117d412162d8d69728ce4c74eb87aa4f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T00:45+00:00, close=73556.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.848700|-8.75|57.28|-9.26|5380795|0.54|
|ZEC_USDT|1039.690000|-4.90|-13.63|-5.41|2202642227|0.10|
|DASH_USDT|43.410000|-3.83|-5.91|-4.34|14268807|2.30|
|UNI_USDT|6.704000|-1.84|-8.82|-2.35|32728808|1.49|
|ARB_USDT|0.160470|-0.56|0.36|-1.07|34225445|0.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.160470|0.159830|0.160470|2.27|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.410000|42.400000|43.380000|0.36|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.848700|1.808000|1.848700|3.90|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.704000|6.611000|6.705000|2.91|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1039.690000|1030.550000|1039.690000|1.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-11T00:45:00+00:00, last15m_closed_end=2026-11-11T00:45+00:00, prior8high=0.161710, depth_time=2026-11-11T00:45:14+00:00, book20_bid_proxy_usdt=84032, book20_ask_proxy_usdt=58259, funding_indicative=-0.000171, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.56%, turnover=34225445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T00:45:00+00:00, last15m_closed_end=2026-11-11T00:45+00:00, prior8high=43.350000, depth_time=2026-11-11T00:45:11+00:00, book20_bid_proxy_usdt=704558, book20_ask_proxy_usdt=572268, funding_indicative=-0.000170, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.83%, turnover=14268807. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T00:45:00+00:00, last15m_closed_end=2026-11-11T00:45+00:00, prior8high=1.856600, depth_time=2026-11-11T00:45:07+00:00, book20_bid_proxy_usdt=10861, book20_ask_proxy_usdt=10762, funding_indicative=0.000062, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.75%, turnover=5380795. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T00:45:00+00:00, last15m_closed_end=2026-11-11T00:45+00:00, prior8high=6.716000, depth_time=2026-11-11T00:45:12+00:00, book20_bid_proxy_usdt=2447946, book20_ask_proxy_usdt=1737585, funding_indicative=-0.000002, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=32728808. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T00:45:00+00:00, last15m_closed_end=2026-11-11T00:45+00:00, prior8high=1055.540000, depth_time=2026-11-11T00:45:10+00:00, book20_bid_proxy_usdt=699061, book20_ask_proxy_usdt=210583, funding_indicative=0.000054, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.90%, turnover=2202642227. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
