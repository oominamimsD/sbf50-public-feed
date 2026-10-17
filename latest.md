# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T05:15:32Z**
- feed_generated_utc: 2026-10-17T05:15:34+00:00
- source_sha256: `dc54c9c020a31b7a3ed78785e15a8deeb80c14339ad3f70fce31daab80069c2f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T05:15+00:00, close=81592.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T05:00+00:00, close=81500.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.976500|-5.93|-2.96|-6.26|14438206|1.01|
|RIVER_USDT|1.082000|-3.90|-8.46|-4.23|5010631|9.25|
|BAT_USDT|0.198140|-3.36|62.86|-3.69|14215063|1.01|
|STRK_USDT|0.071480|-3.34|-5.08|-3.67|21471024|1.40|
|FET_USDT|0.194600|-2.50|-10.32|-2.83|11336321|5.14|
|ARB_USDT|0.191090|-1.97|5.69|-2.30|32578990|0.52|
|ZEC_USDT|1166.100000|-1.84|-4.29|-2.17|1370640221|0.09|
|TAO_USDT|276.450000|-1.48|0.64|-1.81|74910940|1.08|
|APT_USDT|0.847000|-1.06|5.80|-1.39|12331821|1.18|
|AAVE_USDT|156.200000|-0.68|-8.03|-1.01|28297132|0.64|
|AVAX_USDT|10.015000|-0.67|-1.73|-1.00|118249670|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|156.200000|154.690000|156.200000|0.68|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.847000|0.835000|0.847000|0.33|N|N/Y|N/N|Y|N|
|ARB_USDT|0.191090|0.187870|0.191090|0.81|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|10.015000|9.934000|10.015000|0.66|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.198140|0.195330|0.198140|0.31|N|Y/N|N/N|Y|N|
|FET_USDT|0.194600|0.194100|0.194600|0.52|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.082000|1.071000|1.082000|0.95|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.071480|0.069640|0.071480|1.23|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|276.450000|273.300000|276.460000|0.70|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1166.100000|1142.250000|1166.100000|1.33|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.976500|1.948900|1.976500|0.56|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T05:14:59+00:00, last15m_closed_end=2026-10-17T05:15+00:00, prior8high=156.680000, depth_time=2026-10-17T05:15:29+00:00, book20_bid_proxy_usdt=343351, book20_ask_proxy_usdt=316150, funding_indicative=0.000048, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.68%, turnover=28297132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T05:14:59+00:00, last15m_closed_end=2026-10-17T05:15+00:00, prior8high=0.856200, depth_time=2026-10-17T05:15:27+00:00, book20_bid_proxy_usdt=129484, book20_ask_proxy_usdt=129210, funding_indicative=0.000055, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=12331821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T05:14:59+00:00, last15m_closed_end=2026-10-17T05:15+00:00, prior8high=0.191810, depth_time=2026-10-17T05:15:19+00:00, book20_bid_proxy_usdt=66701, book20_ask_proxy_usdt=62842, funding_indicative=-0.000010, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=32578990. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T05:14:59+00:00, last15m_closed_end=2026-10-17T05:15+00:00, prior8high=10.037000, depth_time=2026-10-17T05:15:31+00:00, book20_bid_proxy_usdt=1120744, book20_ask_proxy_usdt=819945, funding_indicative=0.000072, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.67%, turnover=118249670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T05:14:59+00:00, last15m_closed_end=2026-10-17T05:15+00:00, prior8high=0.203660, depth_time=2026-10-17T05:15:12+00:00, book20_bid_proxy_usdt=40475, book20_ask_proxy_usdt=22823, funding_indicative=-0.000052, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.36%, turnover=14215063. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T05:14:59+00:00, last15m_closed_end=2026-10-17T05:15+00:00, prior8high=0.196500, depth_time=2026-10-17T05:15:17+00:00, book20_bid_proxy_usdt=1747040, book20_ask_proxy_usdt=1232126, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=11336321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T05:14:59+00:00, last15m_closed_end=2026-10-17T05:15+00:00, prior8high=1.090000, depth_time=2026-10-17T05:15:05+00:00, book20_bid_proxy_usdt=423478, book20_ask_proxy_usdt=360572, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.90%, turnover=5010631. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T05:14:59+00:00, last15m_closed_end=2026-10-17T05:15+00:00, prior8high=0.072120, depth_time=2026-10-17T05:15:15+00:00, book20_bid_proxy_usdt=331798, book20_ask_proxy_usdt=204364, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.34%, turnover=21471024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T05:14:59+00:00, last15m_closed_end=2026-10-17T05:15+00:00, prior8high=277.190000, depth_time=2026-10-17T05:15:24+00:00, book20_bid_proxy_usdt=132537, book20_ask_proxy_usdt=70935, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.48%, turnover=74910940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T05:14:59+00:00, last15m_closed_end=2026-10-17T05:15+00:00, prior8high=1160.740000, depth_time=2026-10-17T05:15:22+00:00, book20_bid_proxy_usdt=841590, book20_ask_proxy_usdt=253213, funding_indicative=0.000027, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=1370640221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T05:14:59+00:00, last15m_closed_end=2026-10-17T05:15+00:00, prior8high=1.992900, depth_time=2026-10-17T05:15:08+00:00, book20_bid_proxy_usdt=50428, book20_ask_proxy_usdt=37537, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.93%, turnover=14438206. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
