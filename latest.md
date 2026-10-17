# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T00:45:43Z**
- feed_generated_utc: 2026-10-17T00:45:45+00:00
- source_sha256: `f253738317d5fce9b3d0ce2b4f18695baa3c4806ee018f17ad06a36e0b4b5e5d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 22; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T00:45+00:00, close=81535, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.958900|-6.77|-3.82|-7.03|16712779|0.51|
|RIVER_USDT|1.081000|-3.99|-8.54|-4.25|5518629|9.25|
|BAT_USDT|0.197380|-3.73|62.23|-3.99|16643533|1.52|
|ZEC_USDT|1146.880000|-3.46|-5.86|-3.72|1383063416|0.17|
|INJ_USDT|8.690000|-3.20|25.41|-3.46|116745327|1.15|
|STRK_USDT|0.071920|-2.74|-4.50|-3.00|21307062|1.39|
|ARB_USDT|0.189790|-2.64|4.97|-2.90|31185284|0.53|
|FILECOIN_USDT|1.137800|-2.48|6.33|-2.74|22996326|0.88|
|TAO_USDT|273.890000|-2.39|-0.28|-2.65|83701685|1.09|
|OP_USDT|0.137130|-2.05|11.28|-2.31|14869369|3.65|
|AAVE_USDT|154.160000|-1.98|-9.23|-2.24|31507059|0.65|
|APT_USDT|0.839600|-1.92|4.88|-2.18|12551129|1.19|
|AVAX_USDT|9.918000|-1.63|-2.68|-1.89|126581631|1.01|
|FET_USDT|0.196400|-1.60|-9.49|-1.86|11279950|5.09|
|ONDO_USDT|0.450200|-1.50|-6.22|-1.76|28875525|2.22|
|SUI_USDT|1.005400|-1.47|-4.93|-1.73|97008841|0.99|
|ENA_USDT|0.197190|-1.37|-8.53|-1.63|41098981|0.51|
|ICP_USDT|3.006000|-1.05|-0.43|-1.31|8784799|3.33|
|QNT_USDT|199.850000|-0.84|-19.87|-1.10|67655564|0.50|
|HBAR_USDT|0.083410|-0.83|-8.19|-1.09|21273279|1.20|
|NEAR_USDT|5.006000|-0.79|5.36|-1.05|157467563|2.00|
|FARTCOIN_USDT|0.153550|-0.75|-6.01|-1.01|7072840|1.95|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.160000|154.100000|154.160000|0.89|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.839600|0.834600|0.839600|0.37|N|N/Y|N/N|Y|N|
|ARB_USDT|0.189790|0.189990|0.189790|1.23|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.918000|9.908000|9.918000|0.88|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.197380|0.194970|0.197380|0.88|N|Y/Y|N/N|Y|N|
|FET_USDT|0.196400|0.196800|0.196400|1.99|Y|Y/Y|Y/Y|Y|Y|
|FILECOIN_USDT|1.137800|1.132000|1.137800|2.11|N|N/Y|N/N|Y|N|
|INJ_USDT|8.690000|8.621000|8.690000|0.71|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.450200|0.450900|0.450200|0.63|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.137130|0.136400|0.137180|0.83|N|N/Y|Y/Y|Y|N|
|RIVER_USDT|1.081000|1.078000|1.081000|1.10|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.071920|0.072280|0.071920|3.07|Y|Y/Y|Y/Y|Y|Y|
|TAO_USDT|273.890000|273.390000|273.890000|0.57|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1146.880000|1140.570000|1146.880000|0.77|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.958900|1.947200|1.958900|1.04|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=155.320000, depth_time=2026-10-17T00:45:31+00:00, book20_bid_proxy_usdt=328275, book20_ask_proxy_usdt=337991, funding_indicative=0.000051, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=31507059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=0.848400, depth_time=2026-10-17T00:45:34+00:00, book20_bid_proxy_usdt=97424, book20_ask_proxy_usdt=153258, funding_indicative=0.000032, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=12551129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=0.191870, depth_time=2026-10-17T00:45:20+00:00, book20_bid_proxy_usdt=64984, book20_ask_proxy_usdt=70790, funding_indicative=-0.000128, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=31185284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=9.997000, depth_time=2026-10-17T00:45:36+00:00, book20_bid_proxy_usdt=1923168, book20_ask_proxy_usdt=806881, funding_indicative=0.000037, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=126581631. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=0.200120, depth_time=2026-10-17T00:45:13+00:00, book20_bid_proxy_usdt=20913, book20_ask_proxy_usdt=26988, funding_indicative=-0.000075, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.73%, turnover=16643533. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=0.199700, depth_time=2026-10-17T00:45:38+00:00, book20_bid_proxy_usdt=1861832, book20_ask_proxy_usdt=1197136, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=11279950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=1.159600, depth_time=2026-10-17T00:45:24+00:00, book20_bid_proxy_usdt=618743, book20_ask_proxy_usdt=392946, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=22996326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=8.739000, depth_time=2026-10-17T00:45:17+00:00, book20_bid_proxy_usdt=290500, book20_ask_proxy_usdt=261926, funding_indicative=-0.000125, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.20%, turnover=116745327. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=0.456600, depth_time=2026-10-17T00:45:42+00:00, book20_bid_proxy_usdt=1987242, book20_ask_proxy_usdt=1929649, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=28875525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=0.139430, depth_time=2026-10-17T00:45:30+00:00, book20_bid_proxy_usdt=27794, book20_ask_proxy_usdt=56575, funding_indicative=0.000030, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=14869369. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=1.102000, depth_time=2026-10-17T00:45:09+00:00, book20_bid_proxy_usdt=625627, book20_ask_proxy_usdt=346674, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.99%, turnover=5518629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=0.074200, depth_time=2026-10-17T00:45:19+00:00, book20_bid_proxy_usdt=291124, book20_ask_proxy_usdt=613516, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=21307062. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=276.100000, depth_time=2026-10-17T00:45:27+00:00, book20_bid_proxy_usdt=107080, book20_ask_proxy_usdt=176765, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.39%, turnover=83701685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=1153.700000, depth_time=2026-10-17T00:45:15+00:00, book20_bid_proxy_usdt=206410, book20_ask_proxy_usdt=764977, funding_indicative=0.000082, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.46%, turnover=1383063416. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T00:44:59+00:00, last15m_closed_end=2026-10-17T00:45+00:00, prior8high=2.066300, depth_time=2026-10-17T00:45:08+00:00, book20_bid_proxy_usdt=42672, book20_ask_proxy_usdt=29929, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.77%, turnover=16712779. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
