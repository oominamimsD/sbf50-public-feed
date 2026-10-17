# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T17:00:32Z**
- feed_generated_utc: 2026-10-17T17:00:34+00:00
- source_sha256: `9508253123d5f84b6ebf8fc4256127fed99687dd14e44426c154b513c9c1a08f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T17:00+00:00, close=81226.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T17:00+00:00, close=81226.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T16:00+00:00, close=81315.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.260200|-4.37|UNKNOWN|-4.26|8696489|3.84|
|FET_USDT|0.185700|-2.31|-18.40|-2.20|11441625|5.38|
|QNT_USDT|196.600000|-1.90|-19.79|-1.79|66187957|0.51|
|EIGEN_USDT|0.252200|-1.59|7.04|-1.48|9272755|3.96|
|ARB_USDT|0.181130|-1.51|-2.96|-1.40|30007271|0.55|
|ZRO_USDT|1.858300|-1.43|-8.03|-1.32|10840985|3.23|
|PUMPFUN_USDT|0.004351|-1.38|-24.00|-1.27|43208081|2.30|
|WLD_USDT|0.488800|-1.37|-12.55|-1.26|73168230|2.05|
|ZEC_USDT|1127.290000|-1.23|-8.48|-1.12|1223390271|0.09|
|ICP_USDT|2.893000|-1.19|-8.12|-1.08|7642364|3.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.181130|0.182560|0.181130|2.46|Y|Y/Y|Y/Y|Y|Y|
|DNA_USDT|0.260200|0.254400|0.260200|0.61|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.252200|0.253400|0.252200|0.96|N|Y/Y|N/N|Y|N|
|FET_USDT|0.185700|0.188300|0.185700|6.05|Y|Y/Y|Y/Y|Y|Y|
|ICP_USDT|2.893000|2.912000|2.893000|4.04|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.004351|0.004335|0.004351|1.03|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|196.600000|198.820000|196.600000|2.26|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.488800|0.492900|0.488800|2.21|Y|Y/Y|Y/N|Y|N|
|ZEC_USDT|1127.290000|1131.650000|1127.280000|1.56|Y|Y/Y|Y/Y|Y|Y|
|ZRO_USDT|1.858300|1.863400|1.858300|0.69|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T16:59:59+00:00, last15m_closed_end=2026-10-17T17:00+00:00, prior8high=0.186480, depth_time=2026-10-17T17:00:19+00:00, book20_bid_proxy_usdt=57295, book20_ask_proxy_usdt=101005, funding_indicative=-0.000036, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=30007271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T16:59:59+00:00, last15m_closed_end=2026-10-17T17:00+00:00, prior8high=0.276900, depth_time=2026-10-17T17:00:07+00:00, book20_bid_proxy_usdt=68830, book20_ask_proxy_usdt=72505, funding_indicative=-0.001340, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.37%, turnover=8696489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T16:59:59+00:00, last15m_closed_end=2026-10-17T17:00+00:00, prior8high=0.261800, depth_time=2026-10-17T17:00:16+00:00, book20_bid_proxy_usdt=570360, book20_ask_proxy_usdt=292205, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.59%, turnover=9272755. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T16:59:59+00:00, last15m_closed_end=2026-10-17T17:00+00:00, prior8high=0.193500, depth_time=2026-10-17T17:00:11+00:00, book20_bid_proxy_usdt=1555636, book20_ask_proxy_usdt=1398352, funding_indicative=-0.000033, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.31%, turnover=11441625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-17T16:59:59+00:00, last15m_closed_end=2026-10-17T17:00+00:00, prior8high=2.965000, depth_time=2026-10-17T17:00:30+00:00, book20_bid_proxy_usdt=1224692, book20_ask_proxy_usdt=1003171, funding_indicative=-0.000035, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=7642364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-17T16:59:59+00:00, last15m_closed_end=2026-10-17T17:00+00:00, prior8high=0.004529, depth_time=2026-10-17T17:00:24+00:00, book20_bid_proxy_usdt=1171614, book20_ask_proxy_usdt=1209468, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.38%, turnover=43208081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T16:59:59+00:00, last15m_closed_end=2026-10-17T17:00+00:00, prior8high=203.160000, depth_time=2026-10-17T17:00:14+00:00, book20_bid_proxy_usdt=72619, book20_ask_proxy_usdt=56761, funding_indicative=-0.000098, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=66187957. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-17T16:59:59+00:00, last15m_closed_end=2026-10-17T17:00+00:00, prior8high=0.500000, depth_time=2026-10-17T17:00:25+00:00, book20_bid_proxy_usdt=1603132, book20_ask_proxy_usdt=2037525, funding_indicative=-0.000055, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=73168230. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T16:59:59+00:00, last15m_closed_end=2026-10-17T17:00+00:00, prior8high=1166.910000, depth_time=2026-10-17T17:00:28+00:00, book20_bid_proxy_usdt=306014, book20_ask_proxy_usdt=402076, funding_indicative=0.000072, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=1223390271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T16:59:59+00:00, last15m_closed_end=2026-10-17T17:00+00:00, prior8high=1.905900, depth_time=2026-10-17T17:00:20+00:00, book20_bid_proxy_usdt=43824, book20_ask_proxy_usdt=40691, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=10840985. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
