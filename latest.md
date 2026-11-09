# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T10:00:31Z**
- feed_generated_utc: 2026-11-09T10:00:32+00:00
- source_sha256: `89721c8b88d2680d61e2a15cee6c020ff4d789c2b92d5627b9945d8da451bd25`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T10:00+00:00, close=74254.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T10:00+00:00, close=74254.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001571|-16.94|34.90|-14.61|7531738|0.64|
|JCT_USDT|0.009101|-7.45|82.78|-5.12|73043946|3.30|
|ASTER_USDT|0.630000|-7.01|-9.92|-4.68|5452574|1.59|
|XRP_USDT|1.089400|-6.07|-12.84|-3.74|263811147|0.92|
|ETH_USDT|2108.080000|-5.93|-6.96|-3.60|1491004362|0.05|
|HYPE_USDT|73.165000|-5.56|-16.56|-3.23|46270783|0.14|
|NEAR_USDT|3.521000|-5.24|-18.70|-2.91|43538159|2.84|
|TAO_USDT|215.970000|-4.52|-8.03|-2.19|51323317|1.39|
|PUMPFUN_USDT|0.003567|-4.47|-15.43|-2.14|10348728|2.80|
|ZEC_USDT|1216.830000|-4.23|-1.70|-1.90|2252278954|0.08|
|SOL_USDT|86.410000|-3.64|-8.81|-1.31|686032249|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.630000|0.626100|0.630000|0.58|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2108.080000|2083.410000|2107.800000|0.56|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.165000|72.442000|73.165000|0.52|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009101|0.007940|0.009100|0.83|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.521000|3.460000|3.521000|0.65|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001571|0.001557|0.001571|0.91|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003567|0.003485|0.003567|0.16|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.410000|85.240000|86.400000|0.33|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|215.970000|212.010000|215.970000|2.02|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.089400|1.082500|1.089400|1.48|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1216.830000|1185.330000|1216.340000|0.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-11-09T10:00:01+00:00, last15m_closed_end=2026-11-09T10:00+00:00, prior8high=0.637200, depth_time=2026-11-09T10:00:10+00:00, book20_bid_proxy_usdt=669633, book20_ask_proxy_usdt=733143, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.01%, turnover=5452574. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T10:00:01+00:00, last15m_closed_end=2026-11-09T10:00+00:00, prior8high=2127.470000, depth_time=2026-11-09T10:00:15+00:00, book20_bid_proxy_usdt=4546617, book20_ask_proxy_usdt=3658217, funding_indicative=-0.000030, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.93%, turnover=1491004362. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T10:00:01+00:00, last15m_closed_end=2026-11-09T10:00+00:00, prior8high=74.219000, depth_time=2026-11-09T10:00:17+00:00, book20_bid_proxy_usdt=34292, book20_ask_proxy_usdt=374543, funding_indicative=0.000037, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.56%, turnover=46270783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T10:00:01+00:00, last15m_closed_end=2026-11-09T10:00+00:00, prior8high=0.009792, depth_time=2026-11-09T10:00:09+00:00, book20_bid_proxy_usdt=20499, book20_ask_proxy_usdt=17368, funding_indicative=0.001334, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.45%, turnover=73043946. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T10:00:01+00:00, last15m_closed_end=2026-11-09T10:00+00:00, prior8high=3.578000, depth_time=2026-11-09T10:00:19+00:00, book20_bid_proxy_usdt=2630039, book20_ask_proxy_usdt=1955622, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.24%, turnover=43538159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T10:00:01+00:00, last15m_closed_end=2026-11-09T10:00+00:00, prior8high=0.001604, depth_time=2026-11-09T10:00:06+00:00, book20_bid_proxy_usdt=17813, book20_ask_proxy_usdt=9408, funding_indicative=-0.000131, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-16.94%, turnover=7531738. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T10:00:01+00:00, last15m_closed_end=2026-11-09T10:00+00:00, prior8high=0.003597, depth_time=2026-11-09T10:00:24+00:00, book20_bid_proxy_usdt=2614828, book20_ask_proxy_usdt=2691669, funding_indicative=0.000035, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.47%, turnover=10348728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T10:00:01+00:00, last15m_closed_end=2026-11-09T10:00+00:00, prior8high=87.260000, depth_time=2026-11-09T10:00:30+00:00, book20_bid_proxy_usdt=14424274, book20_ask_proxy_usdt=15570475, funding_indicative=-0.000004, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.64%, turnover=686032249. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T10:00:01+00:00, last15m_closed_end=2026-11-09T10:00+00:00, prior8high=218.060000, depth_time=2026-11-09T10:00:21+00:00, book20_bid_proxy_usdt=107941, book20_ask_proxy_usdt=178453, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.52%, turnover=51323317. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T10:00:01+00:00, last15m_closed_end=2026-11-09T10:00+00:00, prior8high=1.101300, depth_time=2026-11-09T10:00:13+00:00, book20_bid_proxy_usdt=5903300, book20_ask_proxy_usdt=3952970, funding_indicative=0.000078, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.07%, turnover=263811147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T10:00:01+00:00, last15m_closed_end=2026-11-09T10:00+00:00, prior8high=1233.140000, depth_time=2026-11-09T10:00:28+00:00, book20_bid_proxy_usdt=352812, book20_ask_proxy_usdt=714938, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.23%, turnover=2252278954. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
