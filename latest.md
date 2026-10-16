# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T23:30:43Z**
- feed_generated_utc: 2026-10-16T23:30:45+00:00
- source_sha256: `d2d42789ebfdbf211297259d5081f80652c095c546496115244a7ccb539ddcf7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T23:30+00:00, close=81610.1, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T23:00+00:00, close=81750.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.197390|-3.72|62.24|-4.10|17261385|0.51|
|RIVER_USDT|1.088000|-3.37|-7.95|-3.75|5586715|9.19|
|ZEC_USDT|1149.580000|-3.23|-5.64|-3.61|1403622940|0.17|
|INJ_USDT|8.694000|-3.16|25.47|-3.54|116651055|1.15|
|ZRO_USDT|2.046000|-2.63|0.45|-3.01|16268638|0.49|
|ARB_USDT|0.190840|-2.10|5.55|-2.48|31071893|0.52|
|TAO_USDT|275.050000|-1.98|0.13|-2.36|82430395|1.09|
|APT_USDT|0.841300|-1.72|5.09|-2.10|12351135|1.19|
|AAVE_USDT|154.990000|-1.45|-8.74|-1.83|31425603|0.65|
|STRK_USDT|0.073000|-1.28|-3.06|-1.66|21307973|1.37|
|AVAX_USDT|9.955000|-1.26|-2.32|-1.64|126704037|1.00|
|QNT_USDT|199.390000|-1.07|-20.06|-1.45|67823398|3.51|
|HBAR_USDT|0.083290|-0.97|-8.33|-1.35|20925570|1.20|
|ICP_USDT|3.014000|-0.78|-0.16|-1.16|8721788|3.32|
|ONDO_USDT|0.454100|-0.65|-5.41|-1.03|28545774|2.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.990000|153.830000|154.990000|1.06|N|Y/Y|Y/N|Y|N|
|APT_USDT|0.841300|0.833500|0.841300|0.17|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.190840|0.190720|0.190840|1.34|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.955000|9.920000|9.955000|0.42|N|Y/Y|Y/N|Y|N|
|BAT_USDT|0.197390|0.194970|0.197460|0.69|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.083290|0.082990|0.083290|0.80|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|3.014000|2.985000|3.014000|0.07|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.694000|8.510000|8.694000|0.78|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.454100|0.451200|0.454100|2.35|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|199.390000|199.510000|199.350000|0.84|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.088000|1.091000|1.088000|1.67|Y|Y/Y|Y/N|Y|N|
|STRK_USDT|0.073000|0.072660|0.073000|0.11|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.050000|271.290000|275.050000|0.41|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1149.580000|1134.590000|1149.580000|0.71|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|2.046000|2.027800|2.046000|0.35|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=155.580000, depth_time=2026-10-16T23:30:24+00:00, book20_bid_proxy_usdt=350956, book20_ask_proxy_usdt=309618, funding_indicative=0.000061, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=31425603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=0.844800, depth_time=2026-10-16T23:30:24+00:00, book20_bid_proxy_usdt=98927, book20_ask_proxy_usdt=138360, funding_indicative=0.000049, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=12351135. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=0.192520, depth_time=2026-10-16T23:30:19+00:00, book20_bid_proxy_usdt=53591, book20_ask_proxy_usdt=66666, funding_indicative=-0.000128, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=31071893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=10.009000, depth_time=2026-10-16T23:30:31+00:00, book20_bid_proxy_usdt=943034, book20_ask_proxy_usdt=676882, funding_indicative=-0.000002, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=126704037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=0.202830, depth_time=2026-10-16T23:30:07+00:00, book20_bid_proxy_usdt=27082, book20_ask_proxy_usdt=27957, funding_indicative=-0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=17261385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=0.083810, depth_time=2026-10-16T23:30:37+00:00, book20_bid_proxy_usdt=1265762, book20_ask_proxy_usdt=1427814, funding_indicative=-0.000031, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.97%, turnover=20925570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=3.022000, depth_time=2026-10-16T23:30:38+00:00, book20_bid_proxy_usdt=922539, book20_ask_proxy_usdt=1184802, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.78%, turnover=8721788. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=8.717000, depth_time=2026-10-16T23:30:15+00:00, book20_bid_proxy_usdt=335504, book20_ask_proxy_usdt=260517, funding_indicative=-0.000108, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=116651055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=0.456600, depth_time=2026-10-16T23:30:41+00:00, book20_bid_proxy_usdt=1969350, book20_ask_proxy_usdt=2047632, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.65%, turnover=28545774. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=205.510000, depth_time=2026-10-16T23:30:34+00:00, book20_bid_proxy_usdt=63761, book20_ask_proxy_usdt=116038, funding_indicative=0.000002, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=67823398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=1.112000, depth_time=2026-10-16T23:30:09+00:00, book20_bid_proxy_usdt=528706, book20_ask_proxy_usdt=339634, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.37%, turnover=5586715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=0.073820, depth_time=2026-10-16T23:30:29+00:00, book20_bid_proxy_usdt=277000, book20_ask_proxy_usdt=248356, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=21307973. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=275.700000, depth_time=2026-10-16T23:30:21+00:00, book20_bid_proxy_usdt=135626, book20_ask_proxy_usdt=114807, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.98%, turnover=82430395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=1150.750000, depth_time=2026-10-16T23:30:11+00:00, book20_bid_proxy_usdt=415903, book20_ask_proxy_usdt=734919, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=1403622940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T23:29:59+00:00, last15m_closed_end=2026-10-16T23:30+00:00, prior8high=2.113300, depth_time=2026-10-16T23:30:17+00:00, book20_bid_proxy_usdt=30604, book20_ask_proxy_usdt=119116, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.63%, turnover=16268638. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
