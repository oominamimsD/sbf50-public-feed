# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T17:15:29Z**
- feed_generated_utc: 2026-10-17T17:15:31+00:00
- source_sha256: `8ba70af14b4c8642136e7427eb22adb99d65be490096acf3aa389a93522babee`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T17:15+00:00, close=81255, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T17:00+00:00, close=81226.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T16:00+00:00, close=81315.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EIGEN_USDT|0.250000|-2.45|6.11|-2.38|9251209|4.00|
|DNA_USDT|0.266700|-1.98|UNKNOWN|-1.91|8005215|3.75|
|FILECOIN_USDT|1.066600|-1.91|-5.42|-1.84|25541472|0.94|
|ZEC_USDT|1122.640000|-1.63|-8.86|-1.56|1139213406|0.09|
|QNT_USDT|197.320000|-1.54|-19.50|-1.47|63888695|0.51|
|FET_USDT|0.187400|-1.42|-17.66|-1.35|11218459|5.34|
|ARB_USDT|0.181410|-1.36|-2.81|-1.29|29226809|0.55|
|WLD_USDT|0.488900|-1.35|-12.54|-1.28|70416336|2.05|
|ZRO_USDT|1.860500|-1.31|-7.92|-1.24|10018293|0.54|
|PUMPFUN_USDT|0.004361|-1.15|-23.82|-1.08|41873026|2.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.181410|0.180660|0.181410|1.66|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.266700|0.254400|0.266700|0.83|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.250000|0.252100|0.250000|1.72|Y|Y/Y|N/N|Y|N|
|FET_USDT|0.187400|0.185400|0.187500|4.50|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.066600|1.075900|1.067000|1.77|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.004361|0.004327|0.004360|0.52|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|197.320000|195.160000|197.320000|1.60|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.488900|0.488400|0.488900|1.52|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1122.640000|1122.950000|1123.010000|1.61|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.860500|1.856500|1.860500|2.50|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-17T17:15:01+00:00, last15m_closed_end=2026-10-17T17:15+00:00, prior8high=0.185970, depth_time=2026-10-17T17:15:21+00:00, book20_bid_proxy_usdt=60252, book20_ask_proxy_usdt=110342, funding_indicative=-0.000028, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=29226809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-17T17:15:01+00:00, last15m_closed_end=2026-10-17T17:15+00:00, prior8high=0.276100, depth_time=2026-10-17T17:15:09+00:00, book20_bid_proxy_usdt=86089, book20_ask_proxy_usdt=88004, funding_indicative=-0.001344, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.98%, turnover=8005215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T17:15:01+00:00, last15m_closed_end=2026-10-17T17:15+00:00, prior8high=0.259800, depth_time=2026-10-17T17:15:07+00:00, book20_bid_proxy_usdt=476502, book20_ask_proxy_usdt=370261, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.45%, turnover=9251209. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T17:15:01+00:00, last15m_closed_end=2026-10-17T17:15+00:00, prior8high=0.193400, depth_time=2026-10-17T17:15:19+00:00, book20_bid_proxy_usdt=1506177, book20_ask_proxy_usdt=1343809, funding_indicative=-0.000061, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=11218459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T17:15:01+00:00, last15m_closed_end=2026-10-17T17:15+00:00, prior8high=1.109900, depth_time=2026-10-17T17:15:12+00:00, book20_bid_proxy_usdt=581892, book20_ask_proxy_usdt=347605, funding_indicative=-0.000055, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=25541472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-17T17:15:01+00:00, last15m_closed_end=2026-10-17T17:15+00:00, prior8high=0.004519, depth_time=2026-10-17T17:15:28+00:00, book20_bid_proxy_usdt=1188973, book20_ask_proxy_usdt=1506431, funding_indicative=0.000049, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.15%, turnover=41873026. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T17:15:01+00:00, last15m_closed_end=2026-10-17T17:15+00:00, prior8high=202.600000, depth_time=2026-10-17T17:15:17+00:00, book20_bid_proxy_usdt=53439, book20_ask_proxy_usdt=65592, funding_indicative=-0.000105, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=63888695. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-17T17:15:01+00:00, last15m_closed_end=2026-10-17T17:15+00:00, prior8high=0.500000, depth_time=2026-10-17T17:15:23+00:00, book20_bid_proxy_usdt=1613499, book20_ask_proxy_usdt=2099098, funding_indicative=-0.000064, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=70416336. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T17:15:01+00:00, last15m_closed_end=2026-10-17T17:15+00:00, prior8high=1164.590000, depth_time=2026-10-17T17:15:14+00:00, book20_bid_proxy_usdt=712135, book20_ask_proxy_usdt=31226, funding_indicative=0.000066, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=1139213406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T17:15:01+00:00, last15m_closed_end=2026-10-17T17:15+00:00, prior8high=1.902900, depth_time=2026-10-17T17:15:25+00:00, book20_bid_proxy_usdt=27222, book20_ask_proxy_usdt=56221, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=10018293. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
