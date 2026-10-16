# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T23:15:45Z**
- feed_generated_utc: 2026-10-16T23:15:47+00:00
- source_sha256: `1918d4365eadfcdaf827294ba888b19c3d15b8a86e9545dd5fcd17a8f92f97da`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T23:15+00:00, close=81738.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T23:00+00:00, close=81750.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.195760|-4.52|60.90|-5.03|17181112|1.53|
|ZEC_USDT|1147.880000|-3.37|-5.78|-3.88|1394531528|0.09|
|INJ_USDT|8.704000|-3.05|25.61|-3.56|116060136|1.15|
|RIVER_USDT|1.093000|-2.93|-7.52|-3.44|5557542|9.14|
|ZRO_USDT|2.052200|-2.33|0.75|-2.84|16238488|0.49|
|FILECOIN_USDT|1.141700|-2.15|6.70|-2.66|22584930|0.88|
|TAO_USDT|274.980000|-2.00|0.11|-2.51|82091487|1.09|
|ARB_USDT|0.191170|-1.93|5.73|-2.44|30906225|1.57|
|APT_USDT|0.839500|-1.93|4.87|-2.44|12335073|1.19|
|OP_USDT|0.137360|-1.88|11.47|-2.39|14841952|0.73|
|AAVE_USDT|155.010000|-1.44|-8.73|-1.95|31193399|0.65|
|STRK_USDT|0.072880|-1.44|-3.22|-1.95|21298488|1.37|
|AVAX_USDT|9.969000|-1.13|-2.18|-1.64|126297814|2.01|
|QNT_USDT|199.770000|-0.88|-19.90|-1.39|67240762|0.50|
|ENA_USDT|0.198240|-0.84|-8.04|-1.35|40459402|0.51|
|ICP_USDT|3.014000|-0.78|-0.16|-1.29|8718206|3.32|
|HBAR_USDT|0.083580|-0.63|-8.01|-1.14|20853203|1.20|
|ONDO_USDT|0.454300|-0.61|-5.37|-1.12|28241134|2.20|
|FET_USDT|0.198600|-0.50|-8.47|-1.01|11157016|5.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.010000|153.830000|155.010000|0.82|N|Y/Y|Y/N|Y|N|
|APT_USDT|0.839500|0.833500|0.839500|0.30|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.191170|0.190720|0.191170|0.30|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.969000|9.920000|9.969000|0.46|N|Y/Y|Y/N|Y|N|
|BAT_USDT|0.195760|0.196090|0.195730|0.97|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.198240|0.196720|0.198240|0.36|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.141700|1.120000|1.141700|1.67|N|Y/Y|N/N|Y|N|
|INJ_USDT|8.704000|8.469000|8.704000|0.64|N|Y/Y|N/N|Y|N|
|OP_USDT|0.137360|0.135200|0.137360|0.45|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|199.770000|199.620000|199.890000|0.50|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.093000|1.092000|1.093000|2.06|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.072880|0.072540|0.072890|0.81|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|274.980000|270.100000|275.000000|1.81|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1147.880000|1134.590000|1147.880000|0.86|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|2.052200|2.027800|2.052200|2.02|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T23:15:01+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=155.840000, depth_time=2026-10-16T23:15:29+00:00, book20_bid_proxy_usdt=318695, book20_ask_proxy_usdt=293128, funding_indicative=0.000064, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=31193399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-16T23:15:01+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=0.844800, depth_time=2026-10-16T23:15:27+00:00, book20_bid_proxy_usdt=139888, book20_ask_proxy_usdt=126953, funding_indicative=0.000058, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=12335073. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T23:15:00+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=0.192520, depth_time=2026-10-16T23:15:24+00:00, book20_bid_proxy_usdt=73751, book20_ask_proxy_usdt=56671, funding_indicative=-0.000119, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=30906225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-16T23:15:00+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=10.009000, depth_time=2026-10-16T23:15:39+00:00, book20_bid_proxy_usdt=1152071, book20_ask_proxy_usdt=647640, funding_indicative=-0.000003, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=126297814. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T23:15:00+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=0.202830, depth_time=2026-10-16T23:15:07+00:00, book20_bid_proxy_usdt=15459, book20_ask_proxy_usdt=27066, funding_indicative=-0.000111, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.52%, turnover=17181112. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-16T23:15:00+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=0.199090, depth_time=2026-10-16T23:15:44+00:00, book20_bid_proxy_usdt=171711, book20_ask_proxy_usdt=188776, funding_indicative=0.000047, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=40459402. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-16T23:15:00+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=1.140300, depth_time=2026-10-16T23:15:20+00:00, book20_bid_proxy_usdt=447710, book20_ask_proxy_usdt=657260, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=22584930. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T23:15:00+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=8.717000, depth_time=2026-10-16T23:15:12+00:00, book20_bid_proxy_usdt=215946, book20_ask_proxy_usdt=302307, funding_indicative=-0.000099, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.05%, turnover=116060136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T23:15:01+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=0.137470, depth_time=2026-10-16T23:15:30+00:00, book20_bid_proxy_usdt=52821, book20_ask_proxy_usdt=44512, funding_indicative=0.000052, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=14841952. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-16T23:15:00+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=205.510000, depth_time=2026-10-16T23:15:42+00:00, book20_bid_proxy_usdt=58663, book20_ask_proxy_usdt=64920, funding_indicative=0.000008, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=67240762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T23:15:01+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=1.112000, depth_time=2026-10-16T23:15:15+00:00, book20_bid_proxy_usdt=443212, book20_ask_proxy_usdt=444966, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=5557542. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T23:15:00+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=0.073820, depth_time=2026-10-16T23:15:36+00:00, book20_bid_proxy_usdt=364515, book20_ask_proxy_usdt=145899, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.44%, turnover=21298488. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T23:15:00+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=274.540000, depth_time=2026-10-16T23:15:23+00:00, book20_bid_proxy_usdt=90464, book20_ask_proxy_usdt=155127, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=82091487. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T23:15:00+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=1148.950000, depth_time=2026-10-16T23:15:09+00:00, book20_bid_proxy_usdt=488948, book20_ask_proxy_usdt=136911, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.37%, turnover=1394531528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T23:15:00+00:00, last15m_closed_end=2026-10-16T23:15+00:00, prior8high=2.113300, depth_time=2026-10-16T23:15:18+00:00, book20_bid_proxy_usdt=23215, book20_ask_proxy_usdt=47359, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=16238488. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
