# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T12:30:24Z**
- feed_generated_utc: 2026-11-03T12:30:25+00:00
- source_sha256: `ce8bab31339d6d52d3898985981215a69d411d061ef29fd63e7a596233683576`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T12:30+00:00, close=77374.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004497|-18.26|-85.38|-18.13|12134270|4.45|
|BTW_USDT|0.946300|-13.72|-20.85|-13.59|10043954|2.11|
|XPL_USDT|0.064990|-6.59|-12.51|-6.46|11652971|1.54|
|SILVER_USDT|49.300000|-3.44|-9.09|-3.31|434941732|2.03|
|NEAR_USDT|3.900000|-2.74|-14.71|-2.61|79183930|2.56|
|DASH_USDT|46.440000|-1.61|-11.06|-1.48|9549037|2.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004497|0.004436|0.004497|0.90|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.946300|0.870600|0.946300|0.56|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.440000|45.630000|46.440000|3.43|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.900000|3.824000|3.900000|2.21|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|49.300000|48.980000|49.300000|6.14|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.064990|0.063400|0.064990|1.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T12:30:00+00:00, last15m_closed_end=2026-11-03T12:30+00:00, prior8high=0.004632, depth_time=2026-11-03T12:30:07+00:00, book20_bid_proxy_usdt=32707, book20_ask_proxy_usdt=35274, funding_indicative=-0.001986, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-18.26%, turnover=12134270. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T12:30:00+00:00, last15m_closed_end=2026-11-03T12:30+00:00, prior8high=0.973900, depth_time=2026-11-03T12:30:10+00:00, book20_bid_proxy_usdt=14375, book20_ask_proxy_usdt=26627, funding_indicative=-0.000225, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.72%, turnover=10043954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T12:30:00+00:00, last15m_closed_end=2026-11-03T12:30+00:00, prior8high=45.990000, depth_time=2026-11-03T12:30:23+00:00, book20_bid_proxy_usdt=843384, book20_ask_proxy_usdt=613964, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.61%, turnover=9549037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T12:30:00+00:00, last15m_closed_end=2026-11-03T12:30+00:00, prior8high=3.888000, depth_time=2026-11-03T12:30:19+00:00, book20_bid_proxy_usdt=230952, book20_ask_proxy_usdt=898976, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=79183930. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-03T12:30:00+00:00, last15m_closed_end=2026-11-03T12:30+00:00, prior8high=49.240000, depth_time=2026-11-03T12:30:16+00:00, book20_bid_proxy_usdt=50997937, book20_ask_proxy_usdt=46724158, funding_indicative=0.000102, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.44%, turnover=434941732. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T12:30:00+00:00, last15m_closed_end=2026-11-03T12:30+00:00, prior8high=0.065520, depth_time=2026-11-03T12:30:13+00:00, book20_bid_proxy_usdt=373891, book20_ask_proxy_usdt=385446, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.59%, turnover=11652971. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
