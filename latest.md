# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T11:45:42Z**
- feed_generated_utc: 2026-10-18T11:45:45+00:00
- source_sha256: `8c03b49ca34c5ace0c58c8f3748333f2f4582c7b327bb7ee045d6d43748da054`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T11:45+00:00, close=81998.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T11:00+00:00, close=82060.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.061740|-6.66|-33.91|-7.49|15284638|1.62|
|EIGEN_USDT|0.240600|-6.12|2.12|-6.95|6540485|4.16|
|SAND_USDT|0.060350|-4.26|-10.31|-5.09|47434326|1.66|
|PUMPFUN_USDT|0.004276|-3.08|-25.31|-3.91|23393858|2.34|
|FILECOIN_USDT|1.055200|-2.96|-6.43|-3.79|18126230|1.90|
|ZRO_USDT|1.838000|-2.50|-9.03|-3.33|6570202|1.09|
|XPL_USDT|0.078160|-2.45|-9.91|-3.28|5890949|1.28|
|OP_USDT|0.126080|-2.26|-9.00|-3.09|8799471|0.79|
|ZEC_USDT|1125.710000|-1.36|-8.61|-2.19|1216953412|0.09|
|ICP_USDT|2.890000|-1.29|-8.22|-2.12|6088481|3.46|
|DOT_USDT|1.103400|-1.25|-12.21|-2.08|16805634|1.81|
|AVAX_USDT|9.738000|-0.82|-7.47|-1.65|82114858|1.03|
|INJ_USDT|8.402000|-0.70|15.19|-1.53|40076547|1.19|
|ONDO_USDT|0.437000|-0.59|-11.64|-1.42|22504675|2.29|
|ENA_USDT|0.188080|-0.57|-15.29|-1.40|27832463|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AVAX_USDT|9.738000|9.767000|9.738000|1.73|Y|Y/N|Y/Y|Y|N|
|DOT_USDT|1.103400|1.103200|1.103400|0.79|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.240600|0.242100|0.240600|1.30|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.188080|0.188750|0.188080|2.04|Y|Y/Y|Y/Y|Y|Y|
|FILECOIN_USDT|1.055200|1.054800|1.055200|1.57|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.890000|2.889000|2.890000|3.00|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.402000|8.393000|8.402000|0.74|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.437000|0.437600|0.437000|0.69|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.126080|0.126120|0.126080|1.55|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.004276|0.004272|0.004277|1.17|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.060350|0.060210|0.060350|0.40|N|Y/N|N/N|Y|N|
|STRK_USDT|0.061740|0.061570|0.061740|2.43|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.078160|0.078400|0.078160|1.45|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1125.710000|1124.560000|1125.580000|1.08|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.838000|1.829900|1.838000|0.57|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AVAX_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=9.891000, depth_time=2026-10-18T11:45:34+00:00, book20_bid_proxy_usdt=747611, book20_ask_proxy_usdt=833069, funding_indicative=-0.000004, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.82%, turnover=82114858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=1.120400, depth_time=2026-10-18T11:45:31+00:00, book20_bid_proxy_usdt=340838, book20_ask_proxy_usdt=303199, funding_indicative=-0.000071, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=16805634. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=0.249900, depth_time=2026-10-18T11:45:09+00:00, book20_bid_proxy_usdt=501612, book20_ask_proxy_usdt=405738, funding_indicative=-0.000004, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.12%, turnover=6540485. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=0.191320, depth_time=2026-10-18T11:45:41+00:00, book20_bid_proxy_usdt=190330, book20_ask_proxy_usdt=224064, funding_indicative=-0.000021, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.57%, turnover=27832463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=1.069800, depth_time=2026-10-18T11:45:18+00:00, book20_bid_proxy_usdt=528834, book20_ask_proxy_usdt=703007, funding_indicative=0.000019, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=18126230. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=2.941000, depth_time=2026-10-18T11:45:28+00:00, book20_bid_proxy_usdt=844938, book20_ask_proxy_usdt=1061097, funding_indicative=0.000028, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=6088481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=8.541000, depth_time=2026-10-18T11:45:36+00:00, book20_bid_proxy_usdt=240276, book20_ask_proxy_usdt=245162, funding_indicative=0.000229, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.70%, turnover=40076547. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=0.442900, depth_time=2026-10-18T11:45:38+00:00, book20_bid_proxy_usdt=1811078, book20_ask_proxy_usdt=2095787, funding_indicative=0.000039, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.59%, turnover=22504675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=0.128100, depth_time=2026-10-18T11:45:23+00:00, book20_bid_proxy_usdt=59086, book20_ask_proxy_usdt=128958, funding_indicative=-0.000229, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=8799471. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=0.004347, depth_time=2026-10-18T11:45:15+00:00, book20_bid_proxy_usdt=1846416, book20_ask_proxy_usdt=1038014, funding_indicative=0.000030, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=23393858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=0.062370, depth_time=2026-10-18T11:45:12+00:00, book20_bid_proxy_usdt=514132, book20_ask_proxy_usdt=873076, funding_indicative=-0.005641, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.26%, turnover=47434326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=0.063680, depth_time=2026-10-18T11:45:08+00:00, book20_bid_proxy_usdt=262232, book20_ask_proxy_usdt=342868, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.66%, turnover=15284638. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=0.079080, depth_time=2026-10-18T11:45:21+00:00, book20_bid_proxy_usdt=585408, book20_ask_proxy_usdt=462600, funding_indicative=0.000049, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.45%, turnover=5890949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=1143.000000, depth_time=2026-10-18T11:45:27+00:00, book20_bid_proxy_usdt=319646, book20_ask_proxy_usdt=286649, funding_indicative=0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=1216953412. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T11:45:00+00:00, last15m_closed_end=2026-10-18T11:45+00:00, prior8high=1.874500, depth_time=2026-10-18T11:45:20+00:00, book20_bid_proxy_usdt=48890, book20_ask_proxy_usdt=86317, funding_indicative=-0.000036, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=6570202. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
