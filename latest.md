# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T00:30:21Z**
- feed_generated_utc: 2026-11-11T00:30:22+00:00
- source_sha256: `eefa9824a2f45127827fe9796d870458055a02c80c36265751b8ec6a3d016b9d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T00:30+00:00, close=73628.1, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.837400|-9.31|56.32|-9.92|5316382|2.18|
|ZEC_USDT|1043.120000|-4.59|-13.34|-5.20|2184707328|0.10|
|DASH_USDT|43.240000|-4.20|-6.28|-4.81|14223267|2.31|
|JCT_USDT|0.005142|-2.52|23.07|-3.13|18895649|5.83|
|UNI_USDT|6.699000|-1.91|-8.89|-2.52|32096962|1.49|
|ARB_USDT|0.160730|-0.40|0.53|-1.01|33679555|1.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.160730|0.159830|0.160730|0.11|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.240000|42.400000|43.240000|0.93|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005142|0.005060|0.005142|1.79|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.837400|1.808000|1.837400|0.42|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.699000|6.611000|6.699000|1.01|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1043.120000|1030.550000|1043.270000|0.95|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-11T00:30:00+00:00, last15m_closed_end=2026-11-11T00:30+00:00, prior8high=0.161710, depth_time=2026-11-11T00:30:19+00:00, book20_bid_proxy_usdt=80040, book20_ask_proxy_usdt=59126, funding_indicative=-0.000174, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.40%, turnover=33679555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T00:30:01+00:00, last15m_closed_end=2026-11-11T00:30+00:00, prior8high=43.380000, depth_time=2026-11-11T00:30:11+00:00, book20_bid_proxy_usdt=722937, book20_ask_proxy_usdt=547120, funding_indicative=-0.000159, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.20%, turnover=14223267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-11T00:30:00+00:00, last15m_closed_end=2026-11-11T00:30+00:00, prior8high=0.005343, depth_time=2026-11-11T00:30:15+00:00, book20_bid_proxy_usdt=40160, book20_ask_proxy_usdt=40162, funding_indicative=0.000429, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=18895649. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T00:30:00+00:00, last15m_closed_end=2026-11-11T00:30+00:00, prior8high=1.856600, depth_time=2026-11-11T00:30:06+00:00, book20_bid_proxy_usdt=8160, book20_ask_proxy_usdt=10008, funding_indicative=0.000050, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.31%, turnover=5316382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T00:30:01+00:00, last15m_closed_end=2026-11-11T00:30+00:00, prior8high=6.769000, depth_time=2026-11-11T00:30:17+00:00, book20_bid_proxy_usdt=1799064, book20_ask_proxy_usdt=2488067, funding_indicative=-0.000004, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=32096962. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T00:30:00+00:00, last15m_closed_end=2026-11-11T00:30+00:00, prior8high=1063.120000, depth_time=2026-11-11T00:30:11+00:00, book20_bid_proxy_usdt=325470, book20_ask_proxy_usdt=291187, funding_indicative=0.000047, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.59%, turnover=2184707328. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
