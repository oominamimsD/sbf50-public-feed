# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T23:00:20Z**
- feed_generated_utc: 2026-10-25T23:00:23+00:00
- source_sha256: `d778a928c16d9637991b8b2d2c1a019964cddf8953c11788ac7f87ca7e2d7b19`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T23:00+00:00, close=80429.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T23:00+00:00, close=80429.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.006198|-10.23|236.29|-10.00|9927398|1.61|
|DASH_USDT|51.620000|-2.62|7.81|-2.39|13739531|1.94|
|XMR_USDT|593.430000|-2.44|1.87|-2.21|6576458|0.17|
|PEPE_USDT|0.000004|-2.14|12.38|-1.91|72902475|0.23|
|T_USDT|0.005346|-1.96|13.69|-1.73|8592578|1.87|
|BTW_USDT|1.646900|-1.38|-28.56|-1.15|12608807|1.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.646900|1.641800|1.646900|0.46|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|51.620000|51.310000|51.620000|0.58|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.006198|0.006153|0.006198|3.87|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.63|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.005346|0.005240|0.005346|0.52|N|Y/Y|N/N|Y|N|
|XMR_USDT|593.430000|593.960000|593.430000|2.61|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-25T23:00:00+00:00, last15m_closed_end=2026-10-25T23:00+00:00, prior8high=1.660900, depth_time=2026-10-25T23:00:17+00:00, book20_bid_proxy_usdt=17586, book20_ask_proxy_usdt=12838, funding_indicative=-0.007369, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.38%, turnover=12608807. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-25T23:00:00+00:00, last15m_closed_end=2026-10-25T23:00+00:00, prior8high=51.970000, depth_time=2026-10-25T23:00:10+00:00, book20_bid_proxy_usdt=492020, book20_ask_proxy_usdt=650644, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=13739531. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-25T23:00:00+00:00, last15m_closed_end=2026-10-25T23:00+00:00, prior8high=0.006991, depth_time=2026-10-25T23:00:07+00:00, book20_bid_proxy_usdt=36410, book20_ask_proxy_usdt=35368, funding_indicative=0.000147, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.23%, turnover=9927398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-25T23:00:00+00:00, last15m_closed_end=2026-10-25T23:00+00:00, prior8high=0.000004, depth_time=2026-10-25T23:00:14+00:00, book20_bid_proxy_usdt=75329, book20_ask_proxy_usdt=64530, funding_indicative=0.000033, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=72902475. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-25T23:00:00+00:00, last15m_closed_end=2026-10-25T23:00+00:00, prior8high=0.005405, depth_time=2026-10-25T23:00:17+00:00, book20_bid_proxy_usdt=71909, book20_ask_proxy_usdt=88071, funding_indicative=-0.004350, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=1, 24h_change=-1.96%, turnover=8592578. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T23:00:00+00:00, last15m_closed_end=2026-10-25T23:00+00:00, prior8high=602.000000, depth_time=2026-10-25T23:00:12+00:00, book20_bid_proxy_usdt=12827, book20_ask_proxy_usdt=10088, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=6576458. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
