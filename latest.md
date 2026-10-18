# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T13:00:44Z**
- feed_generated_utc: 2026-10-18T13:00:46+00:00
- source_sha256: `dfdfdfdc9a1b8073b36a4ae1b4b196dd2a3aaba96781a1de92e1e2a04b11186e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T13:00+00:00, close=81952.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T13:00+00:00, close=81952.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T12:00+00:00, close=82038.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EIGEN_USDT|0.239800|-6.43|1.78|-7.21|6126876|4.17|
|STRK_USDT|0.062030|-6.22|-33.60|-7.00|16062077|1.61|
|TIA_USDT|0.629500|-4.33|22.70|-5.11|60751214|1.59|
|PUMPFUN_USDT|0.004267|-3.28|-25.46|-4.06|22557694|2.34|
|XPL_USDT|0.078130|-3.26|-9.94|-4.04|5433972|1.28|
|ZRO_USDT|1.826500|-3.11|-9.60|-3.89|6621008|0.55|
|SAND_USDT|0.061190|-2.93|-9.06|-3.71|45563005|1.63|
|FILECOIN_USDT|1.057700|-2.73|-6.21|-3.51|18008085|0.94|
|INJ_USDT|8.291000|-2.02|13.66|-2.80|41199857|1.21|
|OP_USDT|0.126800|-1.70|-8.48|-2.48|8910170|0.79|
|ZEC_USDT|1126.510000|-1.29|-8.54|-2.07|1236305926|0.09|
|DOT_USDT|1.105000|-1.10|-12.08|-1.88|16813970|0.91|
|ICP_USDT|2.900000|-0.95|-7.90|-1.73|6144756|3.45|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.105000|1.102600|1.105000|0.73|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.239800|0.239100|0.239800|0.51|N|Y/Y|Y/Y|N|N|
|FILECOIN_USDT|1.057700|1.053700|1.057700|1.02|N|Y/Y|Y/Y|N|N|
|ICP_USDT|2.900000|2.889000|2.900000|1.93|N|Y/Y|Y/Y|N|N|
|INJ_USDT|8.291000|8.296000|8.294000|3.81|Y|Y/Y|Y/N|N|N|
|OP_USDT|0.126800|0.125830|0.126800|0.30|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004267|0.004259|0.004267|2.34|N|Y/Y|Y/Y|N|N|
|SAND_USDT|0.061190|0.060210|0.061190|0.24|N|Y/Y|N/N|N|N|
|STRK_USDT|0.062030|0.061150|0.062030|0.98|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.629500|0.632400|0.629500|2.66|Y|Y/Y|N/Y|N|N|
|XPL_USDT|0.078130|0.078080|0.078130|1.23|N|Y/Y|Y/Y|N|N|
|ZEC_USDT|1126.510000|1123.060000|1126.510000|1.34|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.826500|1.825500|1.826500|9.00|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T12:59:59+00:00, last15m_closed_end=2026-10-18T13:00+00:00, prior8high=1.112100, depth_time=2026-10-18T13:00:32+00:00, book20_bid_proxy_usdt=299138, book20_ask_proxy_usdt=215252, funding_indicative=-0.000023, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=16813970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T12:59:59+00:00, last15m_closed_end=2026-10-18T13:00+00:00, prior8high=0.246200, depth_time=2026-10-18T13:00:06+00:00, book20_bid_proxy_usdt=810970, book20_ask_proxy_usdt=370262, funding_indicative=0.000020, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.43%, turnover=6126876. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T12:59:59+00:00, last15m_closed_end=2026-10-18T13:00+00:00, prior8high=1.064600, depth_time=2026-10-18T13:00:24+00:00, book20_bid_proxy_usdt=593486, book20_ask_proxy_usdt=565228, funding_indicative=0.000036, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=18008085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T12:59:59+00:00, last15m_closed_end=2026-10-18T13:00+00:00, prior8high=2.914000, depth_time=2026-10-18T13:00:41+00:00, book20_bid_proxy_usdt=1199567, book20_ask_proxy_usdt=1051385, funding_indicative=0.000061, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.95%, turnover=6144756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-18T12:59:59+00:00, last15m_closed_end=2026-10-18T13:00+00:00, prior8high=8.489000, depth_time=2026-10-18T13:00:27+00:00, book20_bid_proxy_usdt=333303, book20_ask_proxy_usdt=285867, funding_indicative=0.000183, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=41199857. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T12:59:59+00:00, last15m_closed_end=2026-10-18T13:00+00:00, prior8high=0.127610, depth_time=2026-10-18T13:00:29+00:00, book20_bid_proxy_usdt=104476, book20_ask_proxy_usdt=62426, funding_indicative=-0.000172, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=8910170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T12:59:59+00:00, last15m_closed_end=2026-10-18T13:00+00:00, prior8high=0.004324, depth_time=2026-10-18T13:00:13+00:00, book20_bid_proxy_usdt=2239039, book20_ask_proxy_usdt=1563530, funding_indicative=0.000018, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=22557694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T12:59:59+00:00, last15m_closed_end=2026-10-18T13:00+00:00, prior8high=0.061400, depth_time=2026-10-18T13:00:21+00:00, book20_bid_proxy_usdt=476264, book20_ask_proxy_usdt=1181706, funding_indicative=-0.003982, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.93%, turnover=45563005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T12:59:59+00:00, last15m_closed_end=2026-10-18T13:00+00:00, prior8high=0.062550, depth_time=2026-10-18T13:00:10+00:00, book20_bid_proxy_usdt=513617, book20_ask_proxy_usdt=329732, funding_indicative=0.000050, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.22%, turnover=16062077. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T12:59:59+00:00, last15m_closed_end=2026-10-18T13:00+00:00, prior8high=0.658000, depth_time=2026-10-18T13:00:12+00:00, book20_bid_proxy_usdt=279333, book20_ask_proxy_usdt=292514, funding_indicative=-0.000063, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.33%, turnover=60751214. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T13:00:00+00:00, last15m_closed_end=2026-10-18T13:00+00:00, prior8high=0.078890, depth_time=2026-10-18T13:00:17+00:00, book20_bid_proxy_usdt=508962, book20_ask_proxy_usdt=329656, funding_indicative=0.000050, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.26%, turnover=5433972. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T12:59:59+00:00, last15m_closed_end=2026-10-18T13:00+00:00, prior8high=1137.070000, depth_time=2026-10-18T13:00:32+00:00, book20_bid_proxy_usdt=834695, book20_ask_proxy_usdt=225788, funding_indicative=0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=1236305926. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T12:59:59+00:00, last15m_closed_end=2026-10-18T13:00+00:00, prior8high=1.853400, depth_time=2026-10-18T13:00:20+00:00, book20_bid_proxy_usdt=88318, book20_ask_proxy_usdt=45284, funding_indicative=-0.000023, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=6621008. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
