# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T17:30:21Z**
- feed_generated_utc: 2026-11-10T17:30:23+00:00
- source_sha256: `a05391f7cd8c013cc784d803acf76d11aee59dd084f32949542b53e7ad6c10c3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T17:30+00:00, close=73021.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T17:00+00:00, close=72844.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.850100|-8.68|57.40|-8.47|9644916|5.94|
|ZEC_USDT|1028.860000|-5.89|-14.53|-5.68|2356706412|0.29|
|DASH_USDT|43.320000|-4.03|-6.11|-3.82|13774179|2.31|
|ARB_USDT|0.157570|-2.36|-1.44|-2.15|39552821|0.63|
|UNI_USDT|6.706000|-1.81|-8.79|-1.60|26164081|1.49|
|JCT_USDT|0.005200|-1.42|24.46|-1.21|23039357|3.85|
|NEAR_USDT|3.517000|-1.23|-8.86|-1.02|36615115|2.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.157570|0.155820|0.157570|0.34|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.320000|42.350000|43.320000|0.67|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005200|0.004969|0.005200|0.34|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.517000|3.469000|3.517000|0.48|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.850100|1.817800|1.850600|0.67|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.706000|6.637000|6.706000|0.92|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1028.860000|993.710000|1028.980000|1.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-10T17:30:01+00:00, last15m_closed_end=2026-11-10T17:30+00:00, prior8high=0.165190, depth_time=2026-11-10T17:30:10+00:00, book20_bid_proxy_usdt=58300, book20_ask_proxy_usdt=70215, funding_indicative=-0.000119, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.36%, turnover=39552821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T17:30:01+00:00, last15m_closed_end=2026-11-10T17:30+00:00, prior8high=47.210000, depth_time=2026-11-10T17:30:11+00:00, book20_bid_proxy_usdt=355348, book20_ask_proxy_usdt=673239, funding_indicative=-0.000071, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.03%, turnover=13774179. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T17:30:01+00:00, last15m_closed_end=2026-11-10T17:30+00:00, prior8high=0.006200, depth_time=2026-11-10T17:30:18+00:00, book20_bid_proxy_usdt=44858, book20_ask_proxy_usdt=55052, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.42%, turnover=23039357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-10T17:30:01+00:00, last15m_closed_end=2026-11-10T17:30+00:00, prior8high=3.716000, depth_time=2026-11-10T17:30:20+00:00, book20_bid_proxy_usdt=2566209, book20_ask_proxy_usdt=2739024, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=36615115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T17:30:01+00:00, last15m_closed_end=2026-11-10T17:30+00:00, prior8high=2.065500, depth_time=2026-11-10T17:30:06+00:00, book20_bid_proxy_usdt=14276, book20_ask_proxy_usdt=18172, funding_indicative=0.000197, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.68%, turnover=9644916. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T17:30:01+00:00, last15m_closed_end=2026-11-10T17:30+00:00, prior8high=7.110000, depth_time=2026-11-10T17:30:16+00:00, book20_bid_proxy_usdt=1817030, book20_ask_proxy_usdt=2742941, funding_indicative=0.000054, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=26164081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T17:30:01+00:00, last15m_closed_end=2026-11-10T17:30+00:00, prior8high=1183.300000, depth_time=2026-11-10T17:30:09+00:00, book20_bid_proxy_usdt=247112, book20_ask_proxy_usdt=1337274, funding_indicative=-0.000012, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.89%, turnover=2356706412. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
