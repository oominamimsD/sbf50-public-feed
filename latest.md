# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T02:15:24Z**
- feed_generated_utc: 2026-11-05T02:15:25+00:00
- source_sha256: `a439bcb91604c25f8813ef29aad0ec4c675ebfb8613ad33bb19696c6034412ac`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T02:15+00:00, close=80691, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-05T02:00+00:00, close=80640.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T00:00+00:00, close=80466.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.232000|-13.48|-27.91|-14.00|27121616|8.11|
|AKE_USDT|0.002487|-11.49|-87.62|-12.01|17010051|4.02|
|IDOL_USDT|0.021292|-9.27|145.95|-9.79|5895477|0.47|
|VVV_USDT|21.465000|-7.29|-9.87|-7.81|5042702|2.79|
|BTW_USDT|1.023000|-6.91|-41.13|-7.43|5941067|0.98|
|WLD_USDT|0.375300|-4.28|-13.28|-4.80|73570544|2.67|
|ZRO_USDT|1.825500|-2.10|6.62|-2.62|10422062|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002487|0.002197|0.002487|5.16|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.023000|1.003000|1.023000|0.79|N|Y/Y|Y/N|N|N|
|IDOL_USDT|0.021292|0.020956|0.021292|0.45|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.232000|1.233000|1.232000|0.97|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.465000|20.977000|21.465000|0.83|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.375300|0.370800|0.375300|0.75|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.825500|1.807200|1.825500|1.31|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T02:14:59+00:00, last15m_closed_end=2026-11-05T02:15+00:00, prior8high=0.002514, depth_time=2026-11-05T02:15:10+00:00, book20_bid_proxy_usdt=31764, book20_ask_proxy_usdt=59646, funding_indicative=-0.000741, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.49%, turnover=17010051. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T02:14:59+00:00, last15m_closed_end=2026-11-05T02:15+00:00, prior8high=1.037600, depth_time=2026-11-05T02:15:16+00:00, book20_bid_proxy_usdt=12798, book20_ask_proxy_usdt=18372, funding_indicative=0.000032, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.91%, turnover=5941067. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T02:14:59+00:00, last15m_closed_end=2026-11-05T02:15+00:00, prior8high=0.022404, depth_time=2026-11-05T02:15:12+00:00, book20_bid_proxy_usdt=6766, book20_ask_proxy_usdt=6665, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.27%, turnover=5895477. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T02:14:59+00:00, last15m_closed_end=2026-11-05T02:15+00:00, prior8high=1.284000, depth_time=2026-11-05T02:15:05+00:00, book20_bid_proxy_usdt=1719993, book20_ask_proxy_usdt=1484523, funding_indicative=-0.000389, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.48%, turnover=27121616. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T02:14:59+00:00, last15m_closed_end=2026-11-05T02:15+00:00, prior8high=21.525000, depth_time=2026-11-05T02:15:14+00:00, book20_bid_proxy_usdt=24915, book20_ask_proxy_usdt=12813, funding_indicative=-0.000374, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.29%, turnover=5042702. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T02:14:59+00:00, last15m_closed_end=2026-11-05T02:15+00:00, prior8high=0.381000, depth_time=2026-11-05T02:15:20+00:00, book20_bid_proxy_usdt=2519974, book20_ask_proxy_usdt=2692554, funding_indicative=-0.000375, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.28%, turnover=73570544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T02:14:59+00:00, last15m_closed_end=2026-11-05T02:15+00:00, prior8high=1.831700, depth_time=2026-11-05T02:15:23+00:00, book20_bid_proxy_usdt=22750, book20_ask_proxy_usdt=72976, funding_indicative=0.000050, next_funding_utc=2026-11-05T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.10%, turnover=10422062. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
