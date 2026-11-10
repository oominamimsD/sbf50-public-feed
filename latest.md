# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T17:45:29Z**
- feed_generated_utc: 2026-11-10T17:45:31+00:00
- source_sha256: `431810b799bd497bbaf03dc34d1fab494e2eb5850b98a0158292b0c150fb2718`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T17:45+00:00, close=72944.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T17:00+00:00, close=72844.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.836700|-9.34|56.26|-9.01|9719431|2.72|
|ZEC_USDT|1040.290000|-4.85|-13.58|-4.52|2387122336|0.10|
|DASH_USDT|43.360000|-3.94|-6.02|-3.61|13909820|2.31|
|JCT_USDT|0.005075|-3.79|21.46|-3.46|23139818|3.95|
|ARB_USDT|0.156280|-3.16|-2.25|-2.83|39758149|1.92|
|AKE_USDT|0.002831|-2.84|-31.88|-2.51|15752325|3.53|
|UNI_USDT|6.643000|-2.73|-9.65|-2.40|26879575|1.51|
|HYPE_USDT|70.645000|-1.57|-19.12|-1.24|42276059|0.14|
|NEAR_USDT|3.510000|-1.43|-9.04|-1.10|36910749|2.85|
|ONDO_USDT|0.360700|-1.39|-7.32|-1.06|15523675|2.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002831|0.002637|0.002836|0.77|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.156280|0.155820|0.156310|0.54|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.360000|42.350000|43.360000|0.41|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|70.645000|70.596000|70.659000|1.07|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005075|0.004969|0.005072|0.49|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.510000|3.469000|3.510000|0.46|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.360700|0.355900|0.360700|0.23|N|Y/Y|Y/N|Y|N|
|PIEVERSE_USDT|1.836700|1.817800|1.836700|1.32|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.643000|6.637000|6.643000|1.49|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1040.290000|993.710000|1040.330000|1.11|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T17:45:01+00:00, last15m_closed_end=2026-11-10T17:45+00:00, prior8high=0.003336, depth_time=2026-11-10T17:45:16+00:00, book20_bid_proxy_usdt=26902, book20_ask_proxy_usdt=38172, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=15752325. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T17:45:01+00:00, last15m_closed_end=2026-11-10T17:45+00:00, prior8high=0.163760, depth_time=2026-11-10T17:45:16+00:00, book20_bid_proxy_usdt=86392, book20_ask_proxy_usdt=82226, funding_indicative=-0.000132, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=39758149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T17:45:01+00:00, last15m_closed_end=2026-11-10T17:45+00:00, prior8high=46.390000, depth_time=2026-11-10T17:45:10+00:00, book20_bid_proxy_usdt=525803, book20_ask_proxy_usdt=536164, funding_indicative=-0.000079, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.94%, turnover=13909820. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T17:45:01+00:00, last15m_closed_end=2026-11-10T17:45+00:00, prior8high=73.153000, depth_time=2026-11-10T17:45:24+00:00, book20_bid_proxy_usdt=49125, book20_ask_proxy_usdt=131657, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.57%, turnover=42276059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T17:45:01+00:00, last15m_closed_end=2026-11-10T17:45+00:00, prior8high=0.005891, depth_time=2026-11-10T17:45:13+00:00, book20_bid_proxy_usdt=64909, book20_ask_proxy_usdt=45573, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.79%, turnover=23139818. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-10T17:45:01+00:00, last15m_closed_end=2026-11-10T17:45+00:00, prior8high=3.675000, depth_time=2026-11-10T17:45:25+00:00, book20_bid_proxy_usdt=2262707, book20_ask_proxy_usdt=2673181, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=36910749. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T17:45:01+00:00, last15m_closed_end=2026-11-10T17:45+00:00, prior8high=0.374900, depth_time=2026-11-10T17:45:28+00:00, book20_bid_proxy_usdt=2574803, book20_ask_proxy_usdt=2691976, funding_indicative=-0.000022, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.39%, turnover=15523675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T17:45:00+00:00, last15m_closed_end=2026-11-10T17:45+00:00, prior8high=2.065500, depth_time=2026-11-10T17:45:06+00:00, book20_bid_proxy_usdt=14529, book20_ask_proxy_usdt=13020, funding_indicative=0.000140, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.34%, turnover=9719431. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T17:45:01+00:00, last15m_closed_end=2026-11-10T17:45+00:00, prior8high=7.006000, depth_time=2026-11-10T17:45:21+00:00, book20_bid_proxy_usdt=2264491, book20_ask_proxy_usdt=1189834, funding_indicative=0.000025, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=26879575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T17:45:01+00:00, last15m_closed_end=2026-11-10T17:45+00:00, prior8high=1155.280000, depth_time=2026-11-10T17:45:09+00:00, book20_bid_proxy_usdt=199306, book20_ask_proxy_usdt=67960, funding_indicative=-0.000016, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.85%, turnover=2387122336. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
