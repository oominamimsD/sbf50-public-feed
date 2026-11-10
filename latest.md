# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T22:30:26Z**
- feed_generated_utc: 2026-11-10T22:30:27+00:00
- source_sha256: `3b7f3668bfe755033faf44d42c6d12511ffd2d89ab4c4a3037f484d9be6c9450`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T22:30+00:00, close=73643.6, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T22:00+00:00, close=73819.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.193710|-22.80|44.04|-23.43|50359837|7.24|
|PIEVERSE_USDT|1.845900|-8.89|57.04|-9.52|5743854|0.54|
|DASH_USDT|43.030000|-4.67|-6.74|-5.30|14139575|2.32|
|ZEC_USDT|1051.590000|-3.81|-12.64|-4.44|2241613738|0.57|
|UNI_USDT|6.677000|-2.24|-9.19|-2.87|31163016|1.50|
|JCT_USDT|0.005186|-1.68|24.12|-2.31|19729397|5.78|
|JUP_USDT|0.249800|-1.34|0.28|-1.97|5506384|4.00|
|ARB_USDT|0.160020|-0.84|0.08|-1.47|33918658|1.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.160020|0.158140|0.160020|0.97|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.030000|42.550000|43.030000|0.80|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.193710|0.193390|0.193710|0.55|N|Y/N|N/N|Y|N|
|JCT_USDT|0.005186|0.005119|0.005186|0.55|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.249800|0.249400|0.249800|0.81|N|Y/N|N/N|Y|N|
|PIEVERSE_USDT|1.845900|1.782100|1.845900|0.41|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.677000|6.670000|6.677000|1.91|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1051.590000|1034.100000|1051.590000|0.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-10T22:30:00+00:00, last15m_closed_end=2026-11-10T22:30+00:00, prior8high=0.160810, depth_time=2026-11-10T22:30:21+00:00, book20_bid_proxy_usdt=78118, book20_ask_proxy_usdt=43820, funding_indicative=-0.000231, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.84%, turnover=33918658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T22:30:00+00:00, last15m_closed_end=2026-11-10T22:30+00:00, prior8high=43.460000, depth_time=2026-11-10T22:30:09+00:00, book20_bid_proxy_usdt=888430, book20_ask_proxy_usdt=539636, funding_indicative=-0.000195, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.67%, turnover=14139575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-10T22:30:00+00:00, last15m_closed_end=2026-11-10T22:30+00:00, prior8high=0.256190, depth_time=2026-11-10T22:30:07+00:00, book20_bid_proxy_usdt=30387, book20_ask_proxy_usdt=10210, funding_indicative=-0.020000, next_funding_utc=2026-11-10T23:00:00+00:00, funding_cycle_h=1, 24h_change=-22.80%, turnover=50359837. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T22:30:00+00:00, last15m_closed_end=2026-11-10T22:30+00:00, prior8high=0.005437, depth_time=2026-11-10T22:30:19+00:00, book20_bid_proxy_usdt=45147, book20_ask_proxy_usdt=55977, funding_indicative=0.000533, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=19729397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-11-10T22:30:00+00:00, last15m_closed_end=2026-11-10T22:30+00:00, prior8high=0.257600, depth_time=2026-11-10T22:30:20+00:00, book20_bid_proxy_usdt=490779, book20_ask_proxy_usdt=471346, funding_indicative=-0.000033, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=5506384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T22:30:00+00:00, last15m_closed_end=2026-11-10T22:30+00:00, prior8high=1.858500, depth_time=2026-11-10T22:30:08+00:00, book20_bid_proxy_usdt=20464, book20_ask_proxy_usdt=15706, funding_indicative=0.000096, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.89%, turnover=5743854. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T22:30:00+00:00, last15m_closed_end=2026-11-10T22:30+00:00, prior8high=6.774000, depth_time=2026-11-10T22:30:17+00:00, book20_bid_proxy_usdt=2403062, book20_ask_proxy_usdt=2113004, funding_indicative=-0.000023, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=31163016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T22:30:00+00:00, last15m_closed_end=2026-11-10T22:30+00:00, prior8high=1069.190000, depth_time=2026-11-10T22:30:14+00:00, book20_bid_proxy_usdt=172394, book20_ask_proxy_usdt=282949, funding_indicative=0.000008, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.81%, turnover=2241613738. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
