# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T02:00:39Z**
- feed_generated_utc: 2026-11-06T02:00:41+00:00
- source_sha256: `4494f65d094a071f4dbf68a6307cf00e5afe7609c80fb1e2cabea98f60a716bf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T02:00+00:00, close=76099, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T02:00+00:00, close=76099, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002250|-12.38|-89.31|-9.61|19121779|8.90|
|XPL_USDT|0.057630|-8.48|-26.98|-5.71|12433286|1.74|
|FLUID_USDT|2.402000|-7.18|16.37|-4.41|6992869|8.33|
|ENA_USDT|0.163060|-6.08|-23.77|-3.31|52381334|1.23|
|ZRO_USDT|1.599600|-5.71|-9.33|-2.94|7093516|0.62|
|DASH_USDT|45.130000|-5.36|-12.35|-2.59|15317638|2.22|
|XRP_USDT|1.216700|-4.99|-7.08|-2.22|426525513|0.82|
|PUMPFUN_USDT|0.003923|-4.87|-13.30|-2.10|11719175|2.55|
|ATOM_USDT|1.406000|-4.74|-13.79|-1.97|6393191|7.11|
|QNT_USDT|190.870000|-4.39|-3.95|-1.62|40529860|2.10|
|ETH_USDT|2240.150000|-4.38|-5.39|-1.61|2351109891|0.04|
|FET_USDT|0.146700|-4.18|-20.61|-1.41|7642410|6.82|
|PENGU_USDT|0.006644|-3.80|-18.28|-1.03|5792580|1.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002250|0.002077|0.002250|1.33|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.406000|1.350000|1.406000|0.53|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|45.130000|44.330000|45.130000|1.19|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.163060|0.159190|0.163060|0.30|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2240.150000|2228.420000|2240.150000|0.20|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.146700|0.142800|0.146700|0.68|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.402000|2.406000|2.402000|0.73|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.006644|0.006418|0.006644|0.67|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003923|0.003823|0.003923|0.44|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|190.870000|187.900000|190.870000|0.51|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057630|0.056740|0.057630|0.36|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.216700|1.206100|1.216700|0.38|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.599600|1.583900|1.599600|0.33|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T02:00:00+00:00, last15m_closed_end=2026-11-06T02:00+00:00, prior8high=0.002355, depth_time=2026-11-06T02:00:06+00:00, book20_bid_proxy_usdt=38445, book20_ask_proxy_usdt=59518, funding_indicative=-0.001041, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.38%, turnover=19121779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-06T02:00:00+00:00, last15m_closed_end=2026-11-06T02:00+00:00, prior8high=1.409000, depth_time=2026-11-06T02:00:27+00:00, book20_bid_proxy_usdt=1761949, book20_ask_proxy_usdt=2018660, funding_indicative=-0.000026, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.74%, turnover=6393191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-06T02:00:00+00:00, last15m_closed_end=2026-11-06T02:00+00:00, prior8high=45.890000, depth_time=2026-11-06T02:00:18+00:00, book20_bid_proxy_usdt=819674, book20_ask_proxy_usdt=438476, funding_indicative=-0.000073, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.36%, turnover=15317638. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-06T02:00:00+00:00, last15m_closed_end=2026-11-06T02:00+00:00, prior8high=0.164790, depth_time=2026-11-06T02:00:14+00:00, book20_bid_proxy_usdt=98721, book20_ask_proxy_usdt=129054, funding_indicative=0.000031, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.08%, turnover=52381334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-06T02:00:00+00:00, last15m_closed_end=2026-11-06T02:00+00:00, prior8high=2248.930000, depth_time=2026-11-06T02:00:33+00:00, book20_bid_proxy_usdt=2630930, book20_ask_proxy_usdt=2009103, funding_indicative=0.000080, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.38%, turnover=2351109891. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-06T02:00:00+00:00, last15m_closed_end=2026-11-06T02:00+00:00, prior8high=0.146900, depth_time=2026-11-06T02:00:36+00:00, book20_bid_proxy_usdt=1226865, book20_ask_proxy_usdt=999745, funding_indicative=-0.000208, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.18%, turnover=7642410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T02:00:00+00:00, last15m_closed_end=2026-11-06T02:00+00:00, prior8high=2.470000, depth_time=2026-11-06T02:00:12+00:00, book20_bid_proxy_usdt=191503, book20_ask_proxy_usdt=169092, funding_indicative=0.000360, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.18%, turnover=6992869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-06T02:00:00+00:00, last15m_closed_end=2026-11-06T02:00+00:00, prior8high=0.006656, depth_time=2026-11-06T02:00:37+00:00, book20_bid_proxy_usdt=194402, book20_ask_proxy_usdt=196405, funding_indicative=0.000022, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.80%, turnover=5792580. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-06T02:00:00+00:00, last15m_closed_end=2026-11-06T02:00+00:00, prior8high=0.003946, depth_time=2026-11-06T02:00:25+00:00, book20_bid_proxy_usdt=1436580, book20_ask_proxy_usdt=390712, funding_indicative=0.000045, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.87%, turnover=11719175. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T02:00:00+00:00, last15m_closed_end=2026-11-06T02:00+00:00, prior8high=193.410000, depth_time=2026-11-06T02:00:31+00:00, book20_bid_proxy_usdt=54839, book20_ask_proxy_usdt=56365, funding_indicative=0.000009, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.39%, turnover=40529860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T02:00:00+00:00, last15m_closed_end=2026-11-06T02:00+00:00, prior8high=0.058300, depth_time=2026-11-06T02:00:09+00:00, book20_bid_proxy_usdt=382724, book20_ask_proxy_usdt=380627, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.48%, turnover=12433286. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T02:00:00+00:00, last15m_closed_end=2026-11-06T02:00+00:00, prior8high=1.222700, depth_time=2026-11-06T02:00:22+00:00, book20_bid_proxy_usdt=2647713, book20_ask_proxy_usdt=3167511, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.99%, turnover=426525513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T02:00:00+00:00, last15m_closed_end=2026-11-06T02:00+00:00, prior8high=1.618800, depth_time=2026-11-06T02:00:16+00:00, book20_bid_proxy_usdt=88279, book20_ask_proxy_usdt=24745, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.71%, turnover=7093516. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
