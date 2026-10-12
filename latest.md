# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-12T18:00:40Z**
- feed_generated_utc: 2026-10-12T18:00:43+00:00
- source_sha256: `f1f10c4453bd96f940b0e8d95a5c6b8a1c7e534a4eae53d57cf4c8292b6a38f1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-12T18:00+00:00, close=82470.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-12T18:00+00:00, close=82470.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-12T16:00+00:00, close=82680.3, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|RLC_USDT|0.960700|-6.41|75.31|-6.16|9925936|1.04|
|FILECOIN_USDT|1.152200|-4.46|5.95|-4.21|43600240|0.87|
|BTW_USDT|1.694700|-3.47|40.31|-3.22|11646644|1.18|
|CRV_USDT|0.348200|-3.30|-6.82|-3.05|5677516|2.87|
|NEAR_USDT|5.419000|-2.34|7.90|-2.09|259589783|1.85|
|EIGEN_USDT|0.255000|-2.33|-1.77|-2.08|6326879|3.92|
|JUP_USDT|0.335800|-2.29|-0.62|-2.04|7695829|2.98|
|ZEC_USDT|1237.510000|-2.16|-4.42|-1.91|1415167831|0.08|
|DOT_USDT|1.210300|-2.11|1.37|-1.86|22609036|0.83|
|AVAX_USDT|10.470000|-1.92|-3.50|-1.67|62367397|0.95|
|ARB_USDT|0.185230|-1.71|-8.65|-1.46|35301109|0.54|
|INJ_USDT|7.636000|-1.63|1.89|-1.38|33184421|1.31|
|CKB_USDT|0.001597|-1.59|20.52|-1.34|5640828|2.50|
|APT_USDT|0.829500|-1.53|1.77|-1.28|23788204|1.21|
|HBAR_USDT|0.089000|-1.51|-11.61|-1.26|14278530|1.12|
|SUI_USDT|1.069800|-1.49|-9.74|-1.24|89874803|0.94|
|ONDO_USDT|0.492400|-1.48|0.73|-1.23|64403570|2.03|
|TAO_USDT|282.400000|-1.39|-5.75|-1.14|103085270|0.71|
|PUMPFUN_USDT|0.005237|-1.35|-17.33|-1.10|25133621|3.82|
|ICP_USDT|3.268000|-1.32|-5.71|-1.07|18176605|3.06|
|VIRTUAL_USDT|0.710400|-1.31|-15.19|-1.06|5671097|1.41|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.829500|0.822200|0.829400|0.35|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.185230|0.183760|0.185170|1.05|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|10.470000|10.435000|10.470000|0.20|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.694700|1.675300|1.697600|2.37|N|Y/N|N/N|Y|N|
|CKB_USDT|0.001597|0.001574|0.001597|0.60|N|Y/Y|N/N|Y|N|
|CRV_USDT|0.348200|0.346300|0.348200|1.14|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.210300|1.209100|1.210800|0.69|N|Y/Y|N/N|Y|N|
|EIGEN_USDT|0.255000|0.253000|0.255000|0.21|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.152200|1.151400|1.152200|0.37|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.089000|0.088820|0.089000|0.48|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.636000|7.506000|7.636000|0.50|N|Y/Y|N/N|Y|N|
|JUP_USDT|0.335800|0.335000|0.335800|0.71|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|5.419000|5.375000|5.419000|0.62|N|Y/Y|N/N|Y|N|
|RLC_USDT|0.960700|0.953600|0.960700|1.04|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1237.510000|1231.440000|1237.650000|0.59|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=0.846600, depth_time=2026-10-12T18:00:35+00:00, book20_bid_proxy_usdt=168481, book20_ask_proxy_usdt=192423, funding_indicative=-0.000133, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=23788204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=0.189740, depth_time=2026-10-12T18:00:30+00:00, book20_bid_proxy_usdt=87477, book20_ask_proxy_usdt=105493, funding_indicative=0.000100, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=35301109. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=10.733000, depth_time=2026-10-12T18:00:27+00:00, book20_bid_proxy_usdt=657038, book20_ask_proxy_usdt=429045, funding_indicative=-0.000018, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=62367397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=1.880000, depth_time=2026-10-12T18:00:12+00:00, book20_bid_proxy_usdt=11172, book20_ask_proxy_usdt=10507, funding_indicative=0.000045, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.47%, turnover=11646644. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CKB_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=0.001665, depth_time=2026-10-12T18:00:34+00:00, book20_bid_proxy_usdt=10257, book20_ask_proxy_usdt=16627, funding_indicative=-0.000631, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=5640828. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-12T18:00:03+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=0.363800, depth_time=2026-10-12T18:00:14+00:00, book20_bid_proxy_usdt=725015, book20_ask_proxy_usdt=589373, funding_indicative=-0.000003, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.30%, turnover=5677516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=1.247900, depth_time=2026-10-12T18:00:26+00:00, book20_bid_proxy_usdt=267806, book20_ask_proxy_usdt=247869, funding_indicative=0.000100, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=22609036. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=0.264100, depth_time=2026-10-12T18:00:19+00:00, book20_bid_proxy_usdt=545819, book20_ask_proxy_usdt=806111, funding_indicative=0.000050, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=6326879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=1.183400, depth_time=2026-10-12T18:00:10+00:00, book20_bid_proxy_usdt=887153, book20_ask_proxy_usdt=525640, funding_indicative=0.000066, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.46%, turnover=43600240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=0.091020, depth_time=2026-10-12T18:00:40+00:00, book20_bid_proxy_usdt=450684, book20_ask_proxy_usdt=884859, funding_indicative=0.000092, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=14278530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=7.887000, depth_time=2026-10-12T18:00:33+00:00, book20_bid_proxy_usdt=390864, book20_ask_proxy_usdt=487414, funding_indicative=0.000225, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=33184421. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=0.344900, depth_time=2026-10-12T18:00:20+00:00, book20_bid_proxy_usdt=520963, book20_ask_proxy_usdt=544756, funding_indicative=-0.000095, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.29%, turnover=7695829. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=5.588000, depth_time=2026-10-12T18:00:15+00:00, book20_bid_proxy_usdt=1785865, book20_ask_proxy_usdt=1705652, funding_indicative=-0.000004, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=259589783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=1.004100, depth_time=2026-10-12T18:00:06+00:00, book20_bid_proxy_usdt=43062, book20_ask_proxy_usdt=53371, funding_indicative=-0.000879, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.41%, turnover=9925936. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-12T18:00:02+00:00, last15m_closed_end=2026-10-12T18:00+00:00, prior8high=1272.400000, depth_time=2026-10-12T18:00:24+00:00, book20_bid_proxy_usdt=1064727, book20_ask_proxy_usdt=26906, funding_indicative=0.000064, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=1415167831. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
