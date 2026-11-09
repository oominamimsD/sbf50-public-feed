# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T00:15:27Z**
- feed_generated_utc: 2026-11-09T00:15:28+00:00
- source_sha256: `b949193b8438c6b8fe9e76a62eff0562c96725f011fe0f1e8870219d9c8f5144`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T00:15+00:00, close=74875.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001737|-11.29|49.15|-9.77|11939749|0.57|
|PUMPFUN_USDT|0.003559|-4.76|-15.62|-3.24|8557064|2.81|
|LIT_USDT|3.051900|-4.43|-5.51|-2.91|11073036|0.33|
|DASH_USDT|45.710000|-4.39|-5.94|-2.87|14859767|2.19|
|WLD_USDT|0.314400|-3.52|-20.54|-2.00|30782049|3.18|
|XRP_USDT|1.116500|-3.40|-10.67|-1.88|226998459|0.90|
|HYPE_USDT|75.097000|-3.01|-14.35|-1.49|37098192|0.13|
|DOT_USDT|0.864700|-2.94|-8.69|-1.42|6743278|1.16|
|ENA_USDT|0.149940|-2.61|-19.02|-1.09|34883086|0.67|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|45.710000|44.540000|45.710000|1.24|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.864700|0.853900|0.863800|0.26|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.149940|0.145780|0.149940|1.05|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|75.097000|73.900000|75.106000|0.81|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.051900|3.023100|3.051900|0.34|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001737|0.001638|0.001737|0.60|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003559|0.003501|0.003559|1.41|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.314400|0.306700|0.314100|2.40|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.116500|1.105600|1.116500|1.84|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-09T00:15:00+00:00, last15m_closed_end=2026-11-09T00:15+00:00, prior8high=46.230000, depth_time=2026-11-09T00:15:12+00:00, book20_bid_proxy_usdt=326528, book20_ask_proxy_usdt=608642, funding_indicative=0.000033, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.39%, turnover=14859767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T00:15:00+00:00, last15m_closed_end=2026-11-09T00:15+00:00, prior8high=0.877300, depth_time=2026-11-09T00:15:22+00:00, book20_bid_proxy_usdt=186162, book20_ask_proxy_usdt=454674, funding_indicative=0.000018, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=6743278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-09T00:15:00+00:00, last15m_closed_end=2026-11-09T00:15+00:00, prior8high=0.152610, depth_time=2026-11-09T00:15:25+00:00, book20_bid_proxy_usdt=128926, book20_ask_proxy_usdt=131221, funding_indicative=-0.000035, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=34883086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T00:15:00+00:00, last15m_closed_end=2026-11-09T00:15+00:00, prior8high=75.837000, depth_time=2026-11-09T00:15:21+00:00, book20_bid_proxy_usdt=157748, book20_ask_proxy_usdt=48930, funding_indicative=0.000016, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=37098192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T00:15:00+00:00, last15m_closed_end=2026-11-09T00:15+00:00, prior8high=3.135200, depth_time=2026-11-09T00:15:11+00:00, book20_bid_proxy_usdt=19108, book20_ask_proxy_usdt=17424, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.43%, turnover=11073036. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T00:15:00+00:00, last15m_closed_end=2026-11-09T00:15+00:00, prior8high=0.001757, depth_time=2026-11-09T00:15:07+00:00, book20_bid_proxy_usdt=9237, book20_ask_proxy_usdt=5263, funding_indicative=-0.000845, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.29%, turnover=11939749. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T00:15:00+00:00, last15m_closed_end=2026-11-09T00:15+00:00, prior8high=0.003662, depth_time=2026-11-09T00:15:08+00:00, book20_bid_proxy_usdt=3558766, book20_ask_proxy_usdt=3065541, funding_indicative=-0.000027, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.76%, turnover=8557064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-09T00:15:00+00:00, last15m_closed_end=2026-11-09T00:15+00:00, prior8high=0.319800, depth_time=2026-11-09T00:15:16+00:00, book20_bid_proxy_usdt=2421787, book20_ask_proxy_usdt=5140582, funding_indicative=-0.000139, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.52%, turnover=30782049. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T00:15:00+00:00, last15m_closed_end=2026-11-09T00:15+00:00, prior8high=1.131800, depth_time=2026-11-09T00:15:17+00:00, book20_bid_proxy_usdt=928640, book20_ask_proxy_usdt=3145054, funding_indicative=0.000066, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.40%, turnover=226998459. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
