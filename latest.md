# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T09:45:32Z**
- feed_generated_utc: 2026-11-09T09:45:33+00:00
- source_sha256: `e318fce825d14f4433af58996374281508e3b0049faee840975bc43dcd99319a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T09:45+00:00, close=74202.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T09:00+00:00, close=74524.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001589|-18.82|36.49|-16.40|8178472|2.52|
|ASTER_USDT|0.631300|-7.13|-9.73|-4.71|5472618|1.58|
|ETH_USDT|2105.620000|-6.04|-7.06|-3.62|1513163588|0.05|
|XRP_USDT|1.090400|-5.65|-12.76|-3.23|263782598|0.92|
|HYPE_USDT|73.335000|-5.28|-16.36|-2.86|47285776|0.14|
|TAO_USDT|216.130000|-4.37|-7.96|-1.95|50317921|1.39|
|NEAR_USDT|3.543000|-4.26|-18.19|-1.84|43877521|2.82|
|PUMPFUN_USDT|0.003578|-4.25|-15.17|-1.83|10425471|2.80|
|ZEC_USDT|1217.790000|-4.16|-1.62|-1.74|2294124690|0.08|
|INJ_USDT|7.821000|-3.81|8.74|-1.39|20508817|1.28|
|SOL_USDT|86.500000|-3.54|-8.71|-1.12|688121857|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.631300|0.625900|0.631000|1.42|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2105.620000|2083.410000|2105.760000|0.70|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.335000|72.442000|73.335000|1.26|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.821000|7.836000|7.814000|0.96|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.543000|3.460000|3.543000|0.81|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001589|0.001557|0.001590|1.34|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003578|0.003485|0.003578|0.43|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.500000|85.240000|86.500000|0.33|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|216.130000|212.010000|216.130000|1.39|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.090400|1.082500|1.090400|0.52|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1217.790000|1185.330000|1217.820000|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-11-09T09:45:01+00:00, last15m_closed_end=2026-11-09T09:45+00:00, prior8high=0.637200, depth_time=2026-11-09T09:45:07+00:00, book20_bid_proxy_usdt=506024, book20_ask_proxy_usdt=657260, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.13%, turnover=5472618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T09:45:01+00:00, last15m_closed_end=2026-11-09T09:45+00:00, prior8high=2127.470000, depth_time=2026-11-09T09:45:12+00:00, book20_bid_proxy_usdt=3350231, book20_ask_proxy_usdt=3121876, funding_indicative=-0.000036, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.04%, turnover=1513163588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T09:45:01+00:00, last15m_closed_end=2026-11-09T09:45+00:00, prior8high=74.219000, depth_time=2026-11-09T09:45:16+00:00, book20_bid_proxy_usdt=99205, book20_ask_proxy_usdt=73603, funding_indicative=0.000036, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.28%, turnover=47285776. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-09T09:45:01+00:00, last15m_closed_end=2026-11-09T09:45+00:00, prior8high=8.039000, depth_time=2026-11-09T09:45:28+00:00, book20_bid_proxy_usdt=207250, book20_ask_proxy_usdt=362191, funding_indicative=0.000231, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.81%, turnover=20508817. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T09:45:01+00:00, last15m_closed_end=2026-11-09T09:45+00:00, prior8high=3.578000, depth_time=2026-11-09T09:45:21+00:00, book20_bid_proxy_usdt=2891358, book20_ask_proxy_usdt=1988163, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.26%, turnover=43877521. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T09:45:01+00:00, last15m_closed_end=2026-11-09T09:45+00:00, prior8high=0.001616, depth_time=2026-11-09T09:45:06+00:00, book20_bid_proxy_usdt=7902, book20_ask_proxy_usdt=6690, funding_indicative=-0.000108, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.82%, turnover=8178472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T09:45:01+00:00, last15m_closed_end=2026-11-09T09:45+00:00, prior8high=0.003597, depth_time=2026-11-09T09:45:24+00:00, book20_bid_proxy_usdt=2307221, book20_ask_proxy_usdt=2970674, funding_indicative=0.000032, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=10425471. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T09:45:01+00:00, last15m_closed_end=2026-11-09T09:45+00:00, prior8high=87.260000, depth_time=2026-11-09T09:45:31+00:00, book20_bid_proxy_usdt=16854918, book20_ask_proxy_usdt=13565131, funding_indicative=-0.000014, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.54%, turnover=688121857. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T09:45:01+00:00, last15m_closed_end=2026-11-09T09:45+00:00, prior8high=218.060000, depth_time=2026-11-09T09:45:18+00:00, book20_bid_proxy_usdt=74791, book20_ask_proxy_usdt=117468, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.37%, turnover=50317921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T09:45:01+00:00, last15m_closed_end=2026-11-09T09:45+00:00, prior8high=1.101300, depth_time=2026-11-09T09:45:14+00:00, book20_bid_proxy_usdt=3516957, book20_ask_proxy_usdt=3680600, funding_indicative=0.000072, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.65%, turnover=263782598. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T09:45:01+00:00, last15m_closed_end=2026-11-09T09:45+00:00, prior8high=1233.140000, depth_time=2026-11-09T09:45:26+00:00, book20_bid_proxy_usdt=134741, book20_ask_proxy_usdt=683964, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.16%, turnover=2294124690. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
