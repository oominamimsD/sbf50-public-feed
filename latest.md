# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T09:30:31Z**
- feed_generated_utc: 2026-10-14T09:30:33+00:00
- source_sha256: `8be4934b3579c18563aaeebb3336377cc019dc37ec56c9db2cee598ffcef2262`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T09:30+00:00, close=83231.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T09:00+00:00, close=83400.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.078710|-9.45|50.81|-9.26|30338751|1.27|
|TIA_USDT|0.548500|-4.98|15.15|-4.79|38790661|1.82|
|W_USDT|0.016052|-4.46|10.61|-4.27|6805368|0.62|
|UNI_USDT|7.345000|-2.99|-15.23|-2.80|19583805|2.72|
|DOT_USDT|1.134700|-1.91|-5.55|-1.72|20390891|0.88|
|CRV_USDT|0.330900|-1.51|-8.03|-1.32|5064393|3.02|
|ICP_USDT|3.067000|-1.44|-9.84|-1.25|9932636|3.26|
|RENDER_USDT|1.960000|-1.35|-7.98|-1.16|10429790|5.11|
|XLM_USDT|0.188470|-1.31|-11.79|-1.12|10204876|0.53|
|ZRO_USDT|1.960200|-1.31|-12.93|-1.12|9286458|3.57|
|SILVER_USDT|58.620000|-1.29|-4.48|-1.10|252650431|1.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CRV_USDT|0.330900|0.331600|0.331000|15.97|Y|Y/Y|Y/Y|N|Y|
|DOT_USDT|1.134700|1.140900|1.134300|5.70|Y|Y/Y|Y/Y|N|Y|
|ICP_USDT|3.067000|3.089000|3.067000|2.01|Y|Y/Y|Y/Y|N|Y|
|RENDER_USDT|1.960000|1.979000|1.960000|6.88|Y|Y/Y|Y/Y|N|Y|
|SILVER_USDT|58.620000|58.560000|58.620000|1.88|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.078710|0.079380|0.078710|2.96|Y|Y/Y|Y/Y|N|Y|
|TIA_USDT|0.548500|0.547900|0.548600|1.94|N|Y/Y|Y/N|N|N|
|UNI_USDT|7.345000|7.339000|7.345000|0.76|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016052|0.016124|0.016054|2.41|Y|Y/Y|Y/Y|N|Y|
|XLM_USDT|0.188470|0.189050|0.188470|2.59|Y|Y/Y|Y/Y|N|Y|
|ZRO_USDT|1.960200|2.021800|1.960200|8.95|Y|Y/N|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CRV_USDT: quote_utc=2026-10-14T09:30:01+00:00, last15m_closed_end=2026-10-14T09:30+00:00, prior8high=0.337600, depth_time=2026-10-14T09:30:18+00:00, book20_bid_proxy_usdt=557949, book20_ask_proxy_usdt=395899, funding_indicative=-0.000014, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=5064393. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-14T09:30:00+00:00, last15m_closed_end=2026-10-14T09:30+00:00, prior8high=1.164200, depth_time=2026-10-14T09:30:16+00:00, book20_bid_proxy_usdt=143814, book20_ask_proxy_usdt=224835, funding_indicative=-0.000003, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=20390891. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T09:30:00+00:00, last15m_closed_end=2026-10-14T09:30+00:00, prior8high=3.139000, depth_time=2026-10-14T09:30:21+00:00, book20_bid_proxy_usdt=1055610, book20_ask_proxy_usdt=727225, funding_indicative=0.000081, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=9932636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RENDER_USDT: quote_utc=2026-10-14T09:30:00+00:00, last15m_closed_end=2026-10-14T09:30+00:00, prior8high=2.037000, depth_time=2026-10-14T09:30:23+00:00, book20_bid_proxy_usdt=2025246, book20_ask_proxy_usdt=1489413, funding_indicative=0.000010, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.35%, turnover=10429790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T09:30:00+00:00, last15m_closed_end=2026-10-14T09:30+00:00, prior8high=59.010000, depth_time=2026-10-14T09:30:28+00:00, book20_bid_proxy_usdt=51090822, book20_ask_proxy_usdt=46822113, funding_indicative=0.000077, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.29%, turnover=252650431. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T09:30:00+00:00, last15m_closed_end=2026-10-14T09:30+00:00, prior8high=0.083840, depth_time=2026-10-14T09:30:07+00:00, book20_bid_proxy_usdt=307618, book20_ask_proxy_usdt=246136, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.45%, turnover=30338751. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T09:30:00+00:00, last15m_closed_end=2026-10-14T09:30+00:00, prior8high=0.564000, depth_time=2026-10-14T09:30:09+00:00, book20_bid_proxy_usdt=111602, book20_ask_proxy_usdt=194583, funding_indicative=0.000006, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.98%, turnover=38790661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T09:30:00+00:00, last15m_closed_end=2026-10-14T09:30+00:00, prior8high=7.502000, depth_time=2026-10-14T09:30:14+00:00, book20_bid_proxy_usdt=1646589, book20_ask_proxy_usdt=1361309, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.99%, turnover=19583805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T09:30:00+00:00, last15m_closed_end=2026-10-14T09:30+00:00, prior8high=0.016686, depth_time=2026-10-14T09:30:12+00:00, book20_bid_proxy_usdt=29196, book20_ask_proxy_usdt=35040, funding_indicative=-0.000353, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=6805368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T09:30:00+00:00, last15m_closed_end=2026-10-14T09:30+00:00, prior8high=0.192050, depth_time=2026-10-14T09:30:25+00:00, book20_bid_proxy_usdt=129829, book20_ask_proxy_usdt=214488, funding_indicative=-0.000061, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=10204876. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-14T09:30:00+00:00, last15m_closed_end=2026-10-14T09:30+00:00, prior8high=2.093100, depth_time=2026-10-14T09:30:28+00:00, book20_bid_proxy_usdt=37217, book20_ask_proxy_usdt=47298, funding_indicative=0.000000, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=9286458. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
