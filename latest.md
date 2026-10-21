# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T23:45:44Z**
- feed_generated_utc: 2026-10-21T23:45:47+00:00
- source_sha256: `9ff203f345a2abc6dbd6599b69636fb0a8097117cfb50fefa8285c3dd9ba2452`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 23; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T23:45+00:00, close=84207.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T23:00+00:00, close=84408, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IOST_USDT|0.001032|-29.55|28.86|-29.21|14716809|5.82|
|DOOD_USDT|0.002280|-19.83|60.78|-19.49|9143493|4.39|
|BR_USDT|0.485030|-10.43|18.95|-10.09|14692541|1.03|
|AKE_USDT|0.024004|-10.06|-7.25|-9.72|10903868|0.42|
|STRK_USDT|0.057480|-7.24|-25.52|-6.90|24273078|3.48|
|ZRO_USDT|1.955700|-6.74|3.26|-6.40|7353665|0.51|
|TIA_USDT|0.600700|-5.02|12.59|-4.68|39837710|1.67|
|ARB_USDT|0.188610|-4.06|3.55|-3.72|33449303|0.53|
|LDO_USDT|0.403300|-2.86|-0.61|-2.52|5241480|2.48|
|DOT_USDT|1.146600|-2.82|1.96|-2.48|17044837|0.87|
|FET_USDT|0.195400|-2.59|-4.16|-2.25|7631927|5.12|
|AVAX_USDT|9.662000|-2.56|-1.57|-2.22|158376413|1.03|
|OP_USDT|0.128590|-2.50|-7.04|-2.16|6969009|0.78|
|ICP_USDT|2.894000|-2.42|-3.43|-2.08|5662032|3.46|
|UNI_USDT|7.448000|-2.25|4.25|-1.91|26336462|1.34|
|HBAR_USDT|0.084020|-2.23|0.02|-1.89|14692134|1.19|
|AAVE_USDT|155.030000|-2.19|-0.55|-1.85|133335394|1.29|
|TAO_USDT|271.540000|-2.15|1.33|-1.81|61728589|1.10|
|SUI_USDT|1.027900|-2.03|1.96|-1.69|65957367|0.97|
|DOGE_USDT|0.081850|-1.91|-0.15|-1.57|83858346|1.22|
|APT_USDT|0.820300|-1.83|3.74|-1.49|8261990|1.22|
|INJ_USDT|8.616000|-1.62|12.78|-1.28|51262113|1.16|
|SOL_USDT|106.820000|-1.48|2.88|-1.14|771792737|0.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.024004|0.023846|0.024004|0.96|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.188610|0.188070|0.188610|0.52|N|Y/N|N/N|N|N|
|AVAX_USDT|9.662000|9.652000|9.662000|1.55|N|Y/N|N/N|N|N|
|BR_USDT|0.485030|0.479330|0.485280|0.38|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002280|0.002280|0.002279|0.75|N|Y/Y|N/N|N|N|
|DOT_USDT|1.146600|1.145200|1.146600|1.29|N|Y/Y|N/N|N|N|
|FET_USDT|0.195400|0.195000|0.195400|0.24|N|Y/N|N/N|N|N|
|ICP_USDT|2.894000|2.888000|2.894000|0.50|N|Y/Y|N/N|N|N|
|IOST_USDT|0.001032|0.001018|0.001032|1.33|N|Y/N|N/N|N|N|
|LDO_USDT|0.403300|0.403300|0.403300|0.47|N|Y/Y|N/N|N|N|
|OP_USDT|0.128590|0.128400|0.128590|1.18|N|Y/Y|N/N|N|N|
|STRK_USDT|0.057480|0.057230|0.057480|0.51|N|Y/N|N/N|N|N|
|TIA_USDT|0.600700|0.599600|0.600800|0.57|N|Y/Y|Y/Y|N|N|
|UNI_USDT|7.448000|7.448000|7.448000|0.55|N|Y/N|N/N|N|N|
|ZRO_USDT|1.955700|1.932700|1.955700|0.30|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=0.025473, depth_time=2026-10-21T23:45:16+00:00, book20_bid_proxy_usdt=26530, book20_ask_proxy_usdt=12597, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.06%, turnover=10903868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=0.195090, depth_time=2026-10-21T23:45:26+00:00, book20_bid_proxy_usdt=71523, book20_ask_proxy_usdt=57090, funding_indicative=0.000066, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.06%, turnover=33449303. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=9.877000, depth_time=2026-10-21T23:45:36+00:00, book20_bid_proxy_usdt=1027688, book20_ask_proxy_usdt=945448, funding_indicative=0.000049, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=158376413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=0.504950, depth_time=2026-10-21T23:45:13+00:00, book20_bid_proxy_usdt=2910, book20_ask_proxy_usdt=2482, funding_indicative=-0.000208, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.43%, turnover=14692541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=0.002522, depth_time=2026-10-21T23:45:09+00:00, book20_bid_proxy_usdt=252666, book20_ask_proxy_usdt=155501, funding_indicative=-0.000095, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=1, 24h_change=-19.83%, turnover=9143493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=1.173500, depth_time=2026-10-21T23:45:28+00:00, book20_bid_proxy_usdt=313236, book20_ask_proxy_usdt=298475, funding_indicative=-0.000126, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=17044837. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=0.200300, depth_time=2026-10-21T23:45:33+00:00, book20_bid_proxy_usdt=1778510, book20_ask_proxy_usdt=1336078, funding_indicative=0.000100, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.59%, turnover=7631927. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=2.959000, depth_time=2026-10-21T23:45:41+00:00, book20_bid_proxy_usdt=861189, book20_ask_proxy_usdt=1023485, funding_indicative=0.000007, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=5662032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IOST_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=0.001571, depth_time=2026-10-21T23:45:09+00:00, book20_bid_proxy_usdt=8063, book20_ask_proxy_usdt=7868, funding_indicative=-0.015387, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=1, 24h_change=-29.55%, turnover=14716809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=0.411700, depth_time=2026-10-21T23:45:26+00:00, book20_bid_proxy_usdt=572147, book20_ask_proxy_usdt=551662, funding_indicative=0.000017, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=5241480. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=0.132060, depth_time=2026-10-21T23:45:38+00:00, book20_bid_proxy_usdt=89117, book20_ask_proxy_usdt=147810, funding_indicative=-0.000012, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=6969009. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=0.060860, depth_time=2026-10-21T23:45:16+00:00, book20_bid_proxy_usdt=416131, book20_ask_proxy_usdt=457526, funding_indicative=-0.000043, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.24%, turnover=24273078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=0.625800, depth_time=2026-10-21T23:45:23+00:00, book20_bid_proxy_usdt=249047, book20_ask_proxy_usdt=370767, funding_indicative=-0.000141, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.02%, turnover=39837710. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=7.650000, depth_time=2026-10-21T23:45:43+00:00, book20_bid_proxy_usdt=1400968, book20_ask_proxy_usdt=2363507, funding_indicative=0.000048, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=26336462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-21T23:45:00+00:00, last15m_closed_end=2026-10-21T23:45+00:00, prior8high=2.003300, depth_time=2026-10-21T23:45:21+00:00, book20_bid_proxy_usdt=51110, book20_ask_proxy_usdt=62870, funding_indicative=0.000004, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.74%, turnover=7353665. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
