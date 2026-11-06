# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T07:15:17Z**
- feed_generated_utc: 2026-11-06T07:15:19+00:00
- source_sha256: `72b744ed66943a156039c787a721f44e1fa09b17c915380172eaf7baa5cf9fc6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T07:15+00:00, close=75355, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T07:00+00:00, close=75670, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FLUID_USDT|2.388000|-5.68|15.69|-4.82|5649455|8.36|
|XRP_USDT|1.184400|-4.83|-9.55|-3.97|451079218|0.84|
|BCH_USDT|267.010000|-4.33|-7.37|-3.47|7331411|2.62|
|ELSA_USDT|0.077630|-4.33|3.92|-3.47|5477024|6.44|
|XPL_USDT|0.057210|-2.33|-27.51|-1.47|12183612|1.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|267.010000|266.830000|267.010000|8.87|N|Y/Y|Y/Y|Y|N|
|ELSA_USDT|0.077630|0.076350|0.077630|0.43|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.388000|2.409000|2.388000|1.44|Y|Y/Y|N/N|Y|N|
|XPL_USDT|0.057210|0.056460|0.057210|1.39|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.184400|1.188800|1.184400|3.76|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T07:15:00+00:00, last15m_closed_end=2026-11-06T07:15+00:00, prior8high=277.780000, depth_time=2026-11-06T07:15:12+00:00, book20_bid_proxy_usdt=58366, book20_ask_proxy_usdt=47682, funding_indicative=0.000082, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.33%, turnover=7331411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ELSA_USDT: quote_utc=2026-11-06T07:15:00+00:00, last15m_closed_end=2026-11-06T07:15+00:00, prior8high=0.078390, depth_time=2026-11-06T07:15:13+00:00, book20_bid_proxy_usdt=20718, book20_ask_proxy_usdt=23382, funding_indicative=0.000072, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.33%, turnover=5477024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T07:15:00+00:00, last15m_closed_end=2026-11-06T07:15+00:00, prior8high=2.459000, depth_time=2026-11-06T07:15:03+00:00, book20_bid_proxy_usdt=149458, book20_ask_proxy_usdt=162406, funding_indicative=0.000319, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.68%, turnover=5649455. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T07:15:00+00:00, last15m_closed_end=2026-11-06T07:15+00:00, prior8high=0.057590, depth_time=2026-11-06T07:15:16+00:00, book20_bid_proxy_usdt=364483, book20_ask_proxy_usdt=417291, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=12183612. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T07:14:59+00:00, last15m_closed_end=2026-11-06T07:15+00:00, prior8high=1.204400, depth_time=2026-11-06T07:15:09+00:00, book20_bid_proxy_usdt=2956375, book20_ask_proxy_usdt=2619816, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.83%, turnover=451079218. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
