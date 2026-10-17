# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T01:00:44Z**
- feed_generated_utc: 2026-10-17T01:00:46+00:00
- source_sha256: `c55fc660b571cba673ef3de68be399e9ae824ddbcb30fe1ccaf69eba28842594`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T01:00+00:00, close=81532.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T01:00+00:00, close=81532.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.962800|-6.59|-3.63|-6.84|16896567|0.51|
|BAT_USDT|0.197620|-3.61|62.43|-3.86|16696357|0.51|
|ZEC_USDT|1146.450000|-3.49|-5.90|-3.74|1392173398|0.09|
|RIVER_USDT|1.088000|-3.37|-7.95|-3.62|5523293|9.20|
|INJ_USDT|8.695000|-3.15|25.48|-3.40|117030976|1.15|
|ARB_USDT|0.189570|-2.75|4.85|-3.00|31488688|0.53|
|FILECOIN_USDT|1.141400|-2.17|6.67|-2.42|23342956|0.88|
|TAO_USDT|274.650000|-2.12|0.00|-2.37|84008138|1.09|
|AAVE_USDT|154.530000|-1.74|-9.01|-1.99|31726901|0.65|
|APT_USDT|0.842400|-1.60|5.23|-1.85|12568653|1.19|
|FET_USDT|0.196400|-1.60|-9.49|-1.85|11334067|5.09|
|AVAX_USDT|9.935000|-1.46|-2.52|-1.71|127311294|1.01|
|STRK_USDT|0.072890|-1.43|-3.21|-1.68|21470392|1.37|
|ONDO_USDT|0.450600|-1.42|-6.14|-1.67|29219607|2.22|
|SUI_USDT|1.007300|-1.29|-4.75|-1.54|99562362|0.99|
|ENA_USDT|0.197390|-1.27|-8.43|-1.52|41840987|0.51|
|QNT_USDT|199.760000|-0.88|-19.91|-1.13|67997199|0.50|
|ICP_USDT|3.014000|-0.78|-0.16|-1.03|8903005|3.32|
|FARTCOIN_USDT|0.153500|-0.78|-6.04|-1.03|7099843|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.530000|154.100000|154.530000|1.03|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.842400|0.835400|0.842400|0.27|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189570|0.189590|0.189570|2.49|Y|Y/Y|N/N|Y|N|
|AVAX_USDT|9.935000|9.908000|9.935000|1.13|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.197620|0.194970|0.197620|0.61|N|Y/Y|N/N|Y|N|
|FET_USDT|0.196400|0.196400|0.196400|1.14|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.141400|1.134000|1.141400|1.99|N|Y/N|N/N|Y|N|
|INJ_USDT|8.695000|8.619000|8.695000|0.48|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.450600|0.450200|0.450600|2.00|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.088000|1.078000|1.088000|0.27|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.072890|0.071710|0.072890|2.20|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.007300|1.004200|1.007300|7.11|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|274.650000|273.750000|274.650000|0.72|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1146.450000|1142.940000|1146.450000|0.90|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.962800|1.938500|1.962800|2.13|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=155.320000, depth_time=2026-10-17T01:00:28+00:00, book20_bid_proxy_usdt=362319, book20_ask_proxy_usdt=331928, funding_indicative=0.000047, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=31726901. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=0.848400, depth_time=2026-10-17T01:00:30+00:00, book20_bid_proxy_usdt=141581, book20_ask_proxy_usdt=147106, funding_indicative=0.000031, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=12568653. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=0.191870, depth_time=2026-10-17T01:00:19+00:00, book20_bid_proxy_usdt=82406, book20_ask_proxy_usdt=47218, funding_indicative=-0.000129, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=31488688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=9.997000, depth_time=2026-10-17T01:00:35+00:00, book20_bid_proxy_usdt=745669, book20_ask_proxy_usdt=687309, funding_indicative=0.000048, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=127311294. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=0.198300, depth_time=2026-10-17T01:00:12+00:00, book20_bid_proxy_usdt=27968, book20_ask_proxy_usdt=23976, funding_indicative=-0.000062, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.61%, turnover=16696357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=0.199700, depth_time=2026-10-17T01:00:33+00:00, book20_bid_proxy_usdt=1987132, book20_ask_proxy_usdt=1357513, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=11334067. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=1.159600, depth_time=2026-10-17T01:00:22+00:00, book20_bid_proxy_usdt=505244, book20_ask_proxy_usdt=383224, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=23342956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=8.739000, depth_time=2026-10-17T01:00:18+00:00, book20_bid_proxy_usdt=237704, book20_ask_proxy_usdt=257316, funding_indicative=-0.000122, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.15%, turnover=117030976. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=0.456600, depth_time=2026-10-17T01:00:40+00:00, book20_bid_proxy_usdt=2274244, book20_ask_proxy_usdt=1951610, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.42%, turnover=29219607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=1.099000, depth_time=2026-10-17T01:00:15+00:00, book20_bid_proxy_usdt=381721, book20_ask_proxy_usdt=514648, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.37%, turnover=5523293. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=0.074200, depth_time=2026-10-17T01:00:37+00:00, book20_bid_proxy_usdt=455270, book20_ask_proxy_usdt=457643, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=21470392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=1.024100, depth_time=2026-10-17T01:00:42+00:00, book20_bid_proxy_usdt=923531, book20_ask_proxy_usdt=876237, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=99562362. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=276.100000, depth_time=2026-10-17T01:00:26+00:00, book20_bid_proxy_usdt=88252, book20_ask_proxy_usdt=84127, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=84008138. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=1153.700000, depth_time=2026-10-17T01:00:13+00:00, book20_bid_proxy_usdt=226201, book20_ask_proxy_usdt=150129, funding_indicative=0.000079, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.49%, turnover=1392173398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T00:59:59+00:00, last15m_closed_end=2026-10-17T01:00+00:00, prior8high=2.066300, depth_time=2026-10-17T01:00:07+00:00, book20_bid_proxy_usdt=21242, book20_ask_proxy_usdt=53237, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.59%, turnover=16896567. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
