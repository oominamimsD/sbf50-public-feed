# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-22T00:09:18Z**
- feed_generated_utc: 2026-10-22T00:09:31+00:00
- source_sha256: `a1d73cb3341ae0fae11d02393bdcd5ac7917f99d06ef74dd915525488f3cb28d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.22 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-22T00:00+00:00, close=84050, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-22T00:00+00:00, close=84050, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-22T00:00+00:00, close=84050, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IOST_USDT|0.000962|-34.31|20.16|-34.03|15035749|9.37|
|DOOD_USDT|0.002287|-19.58|61.28|-19.30|9097636|4.35|
|BR_USDT|0.486440|-10.17|19.29|-9.89|14317684|0.62|
|AKE_USDT|0.024199|-9.33|-6.49|-9.05|10877516|7.02|
|STRK_USDT|0.057590|-7.06|-25.38|-6.78|24223197|1.74|
|ZRO_USDT|1.954400|-6.80|3.19|-6.52|7269478|0.51|
|TIA_USDT|0.601100|-4.96|12.67|-4.68|39928079|3.32|
|ARB_USDT|0.188700|-4.01|3.60|-3.73|31621405|0.53|
|DOT_USDT|1.150200|-2.51|2.28|-2.23|16988336|0.87|
|FET_USDT|0.195800|-2.39|-3.97|-2.11|7526390|5.11|
|ICP_USDT|2.895000|-2.39|-3.40|-2.11|5579650|3.46|
|AVAX_USDT|9.682000|-2.35|-1.37|-2.07|156667768|1.03|
|LDO_USDT|0.406700|-2.04|0.22|-1.76|5213700|2.46|
|HBAR_USDT|0.084240|-1.97|0.28|-1.69|13995734|1.19|
|AAVE_USDT|155.470000|-1.91|-0.26|-1.63|131288819|0.64|
|OP_USDT|0.129590|-1.75|-6.32|-1.47|6796881|1.54|
|TAO_USDT|272.700000|-1.74|1.76|-1.46|61390167|1.47|
|INJ_USDT|8.609000|-1.70|12.69|-1.42|50315274|1.16|
|DOGE_USDT|0.082100|-1.61|0.14|-1.33|82881166|1.22|
|APT_USDT|0.822100|-1.61|3.97|-1.33|8031981|1.22|
|UNI_USDT|7.500000|-1.57|4.98|-1.29|26275370|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.470000|154.930000|154.830000|0.97|N|Y/Y|N/N|N|N|
|AKE_USDT|0.024199|0.023846|0.023940|1.44|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.188700|0.188070|0.187860|1.37|Y|Y/Y|Y/N|N|N|
|AVAX_USDT|9.682000|9.652000|9.651000|0.76|N|Y/Y|Y/N|N|N|
|BR_USDT|0.486440|0.479330|0.488270|0.47|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002287|0.002241|0.002283|0.45|N|Y/Y|N/N|N|N|
|DOT_USDT|1.150200|1.144300|1.143200|1.32|Y|Y/Y|Y/N|N|N|
|FET_USDT|0.195800|0.195000|0.195100|0.50|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084240|0.083920|0.083810|0.40|N|Y/Y|Y/N|N|N|
|ICP_USDT|2.895000|2.888000|2.889000|1.86|N|Y/Y|Y/N|N|N|
|IOST_USDT|0.000962|0.001006|0.000989|2.21|Y|Y/Y|Y/N|N|N|
|LDO_USDT|0.406700|0.402400|0.404700|0.57|N|Y/Y|N/N|N|N|
|STRK_USDT|0.057590|0.057220|0.057310|0.40|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.601100|0.599600|0.599600|2.63|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.954400|1.932700|1.948800|0.83|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-22T00:08:20+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=156.960000, depth_time=2026-10-22T00:09:16+00:00, book20_bid_proxy_usdt=299356, book20_ask_proxy_usdt=254005, funding_indicative=-0.000014, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=131288819. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-22T00:08:20+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=0.025311, depth_time=2026-10-22T00:08:36+00:00, book20_bid_proxy_usdt=16755, book20_ask_proxy_usdt=16607, funding_indicative=0.000050, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.33%, turnover=10877516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-22T00:08:20+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=0.194030, depth_time=2026-10-22T00:08:51+00:00, book20_bid_proxy_usdt=93266, book20_ask_proxy_usdt=61330, funding_indicative=0.000052, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.01%, turnover=31621405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-22T00:08:20+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=9.840000, depth_time=2026-10-22T00:09:07+00:00, book20_bid_proxy_usdt=1566449, book20_ask_proxy_usdt=1858406, funding_indicative=0.000036, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.35%, turnover=156667768. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-22T00:08:20+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=0.504950, depth_time=2026-10-22T00:08:32+00:00, book20_bid_proxy_usdt=5148, book20_ask_proxy_usdt=3911, funding_indicative=-0.000246, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.17%, turnover=14317684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-22T00:08:20+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=0.002505, depth_time=2026-10-22T00:08:31+00:00, book20_bid_proxy_usdt=171428, book20_ask_proxy_usdt=139395, funding_indicative=-0.000123, next_funding_utc=2026-10-22T01:00:00+00:00, funding_cycle_h=1, 24h_change=-19.58%, turnover=9097636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-22T00:08:20+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=1.167300, depth_time=2026-10-22T00:08:57+00:00, book20_bid_proxy_usdt=295755, book20_ask_proxy_usdt=262451, funding_indicative=-0.000130, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=16988336. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-22T00:08:20+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=0.199200, depth_time=2026-10-22T00:08:59+00:00, book20_bid_proxy_usdt=1504975, book20_ask_proxy_usdt=1182178, funding_indicative=0.000100, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=7526390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-22T00:08:20+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=0.085160, depth_time=2026-10-22T00:09:14+00:00, book20_bid_proxy_usdt=481152, book20_ask_proxy_usdt=1028264, funding_indicative=0.000006, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=13995734. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-22T00:08:20+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=2.951000, depth_time=2026-10-22T00:09:02+00:00, book20_bid_proxy_usdt=1002564, book20_ask_proxy_usdt=890048, funding_indicative=0.000025, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=5579650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IOST_USDT: quote_utc=2026-10-22T00:08:20+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=0.001553, depth_time=2026-10-22T00:08:28+00:00, book20_bid_proxy_usdt=11633, book20_ask_proxy_usdt=8990, funding_indicative=-0.011156, next_funding_utc=2026-10-22T01:00:00+00:00, funding_cycle_h=1, 24h_change=-34.31%, turnover=15035749. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-22T00:08:17+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=0.410800, depth_time=2026-10-22T00:09:11+00:00, book20_bid_proxy_usdt=522641, book20_ask_proxy_usdt=414030, funding_indicative=0.000017, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=5213700. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-22T00:08:20+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=0.060420, depth_time=2026-10-22T00:08:36+00:00, book20_bid_proxy_usdt=489472, book20_ask_proxy_usdt=492826, funding_indicative=-0.000029, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.06%, turnover=24223197. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-22T00:08:20+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=0.621300, depth_time=2026-10-22T00:08:47+00:00, book20_bid_proxy_usdt=217986, book20_ask_proxy_usdt=285574, funding_indicative=-0.000139, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.96%, turnover=39928079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-22T00:08:17+00:00, last15m_closed_end=2026-10-22T00:00+00:00, prior8high=1.999900, depth_time=2026-10-22T00:08:43+00:00, book20_bid_proxy_usdt=186211, book20_ask_proxy_usdt=42436, funding_indicative=0.000010, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.80%, turnover=7269478. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
