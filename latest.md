# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T20:30:43Z**
- feed_generated_utc: 2026-10-16T20:30:45+00:00
- source_sha256: `cdf8f2e91a7410c5536894949ce3eaa999b07c5102da0c9359d92effae5a22e1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 22; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T20:30+00:00, close=81608.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.196530|-4.14|61.54|-4.52|20425781|2.04|
|RIVER_USDT|1.084000|-3.73|-8.29|-4.11|5928813|9.24|
|INJ_USDT|8.652000|-3.63|24.86|-4.01|114860278|1.16|
|ZEC_USDT|1151.180000|-3.10|-5.51|-3.48|1486621154|0.09|
|OP_USDT|0.136050|-2.82|10.41|-3.20|15005262|1.47|
|FILECOIN_USDT|1.138600|-2.41|6.41|-2.79|24863691|0.88|
|STRK_USDT|0.072170|-2.40|-4.16|-2.78|24122745|2.77|
|PYTH_USDT|0.084290|-2.30|-1.28|-2.68|5147482|1.19|
|TAO_USDT|274.550000|-2.16|-0.04|-2.54|82003082|1.09|
|ZRO_USDT|2.058900|-2.01|1.08|-2.39|15247068|0.48|
|HBAR_USDT|0.082800|-1.55|-8.87|-1.93|21045994|1.21|
|APT_USDT|0.843100|-1.51|5.32|-1.89|12563438|1.19|
|DOT_USDT|1.155200|-1.33|-2.76|-1.71|22525862|0.86|
|ARB_USDT|0.192600|-1.20|6.52|-1.58|33429053|0.52|
|FARTCOIN_USDT|0.153020|-1.09|-6.33|-1.47|7459360|1.96|
|ICP_USDT|3.008000|-0.98|-0.36|-1.36|9178040|3.32|
|AAVE_USDT|155.830000|-0.92|-8.24|-1.30|32050109|0.64|
|AVAX_USDT|10.004000|-0.78|-1.84|-1.16|126928148|1.00|
|ONDO_USDT|0.453700|-0.74|-5.49|-1.12|29510153|2.20|
|ETH_USDT|2413.610000|-0.68|-2.98|-1.06|1780545204|0.04|
|WLD_USDT|0.505300|-0.66|2.59|-1.04|94628599|1.98|
|ENA_USDT|0.198610|-0.66|-7.87|-1.04|40319495|0.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.843100|0.829800|0.843100|0.78|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.192600|0.190240|0.192610|0.21|N|Y/Y|N/N|Y|N|
|BAT_USDT|0.196530|0.193710|0.196530|0.31|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.155200|1.140000|1.155200|0.24|N|Y/Y|N/N|Y|N|
|FARTCOIN_USDT|0.153020|0.151250|0.153020|0.06|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.138600|1.126700|1.138600|1.16|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.082800|0.082050|0.082800|0.52|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.652000|8.521000|8.652000|0.62|N|Y/Y|N/N|Y|N|
|OP_USDT|0.136050|0.134240|0.136050|0.28|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.084290|0.083060|0.084290|0.26|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.084000|1.066000|1.084000|0.20|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.072170|0.071560|0.072170|0.32|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|274.550000|272.300000|274.550000|0.23|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1151.180000|1131.850000|1151.280000|0.57|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|2.058900|2.009500|2.058900|0.43|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=0.845100, depth_time=2026-10-16T20:30:33+00:00, book20_bid_proxy_usdt=121963, book20_ask_proxy_usdt=123941, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=12563438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=0.194080, depth_time=2026-10-16T20:30:40+00:00, book20_bid_proxy_usdt=50362, book20_ask_proxy_usdt=50999, funding_indicative=0.000002, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=33429053. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=0.199860, depth_time=2026-10-16T20:30:07+00:00, book20_bid_proxy_usdt=27070, book20_ask_proxy_usdt=21772, funding_indicative=-0.000134, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.14%, turnover=20425781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=1.164400, depth_time=2026-10-16T20:30:37+00:00, book20_bid_proxy_usdt=258672, book20_ask_proxy_usdt=306038, funding_indicative=0.000083, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=22525862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=0.153850, depth_time=2026-10-16T20:30:38+00:00, book20_bid_proxy_usdt=67244, book20_ask_proxy_usdt=61946, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.09%, turnover=7459360. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=1.145500, depth_time=2026-10-16T20:30:19+00:00, book20_bid_proxy_usdt=293079, book20_ask_proxy_usdt=411779, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.41%, turnover=24863691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=0.083140, depth_time=2026-10-16T20:30:31+00:00, book20_bid_proxy_usdt=1149491, book20_ask_proxy_usdt=1017056, funding_indicative=0.000018, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=21045994. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=8.745000, depth_time=2026-10-16T20:30:12+00:00, book20_bid_proxy_usdt=232257, book20_ask_proxy_usdt=203165, funding_indicative=0.000226, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.63%, turnover=114860278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=0.137590, depth_time=2026-10-16T20:30:17+00:00, book20_bid_proxy_usdt=67733, book20_ask_proxy_usdt=62434, funding_indicative=0.000027, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=15005262. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=0.084430, depth_time=2026-10-16T20:30:24+00:00, book20_bid_proxy_usdt=285071, book20_ask_proxy_usdt=91376, funding_indicative=-0.000061, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.30%, turnover=5147482. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=1.107000, depth_time=2026-10-16T20:30:09+00:00, book20_bid_proxy_usdt=470894, book20_ask_proxy_usdt=346403, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.73%, turnover=5928813. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=0.073170, depth_time=2026-10-16T20:30:22+00:00, book20_bid_proxy_usdt=354227, book20_ask_proxy_usdt=390800, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=24122745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=276.560000, depth_time=2026-10-16T20:30:27+00:00, book20_bid_proxy_usdt=74333, book20_ask_proxy_usdt=70141, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.16%, turnover=82003082. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=1155.500000, depth_time=2026-10-16T20:30:15+00:00, book20_bid_proxy_usdt=508434, book20_ask_proxy_usdt=150851, funding_indicative=0.000098, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.10%, turnover=1486621154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T20:30:00+00:00, last15m_closed_end=2026-10-16T20:30+00:00, prior8high=2.075400, depth_time=2026-10-16T20:30:29+00:00, book20_bid_proxy_usdt=32379, book20_ask_proxy_usdt=36837, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=15247068. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
