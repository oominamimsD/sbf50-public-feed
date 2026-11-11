# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T02:00:28Z**
- feed_generated_utc: 2026-11-11T02:00:30+00:00
- source_sha256: `55f2ed62301a9240f5c5a43d739aa40e31a30be990cd0872002562799f107479`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T02:00+00:00, close=73573.1, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T02:00+00:00, close=73573.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1019.590000|-14.01|-15.30|-14.54|2151875175|0.10|
|JCT_USDT|0.005250|-12.92|25.65|-13.45|17628956|3.81|
|DASH_USDT|43.320000|-6.93|-6.11|-7.46|13892343|2.31|
|UNI_USDT|6.713000|-4.98|-8.70|-5.51|34550055|1.49|
|HYPE_USDT|71.900000|-2.32|-17.68|-2.85|41045015|0.14|
|DOT_USDT|0.843700|-2.17|-10.49|-2.70|8366731|1.19|
|VVV_USDT|19.421000|-1.99|-13.14|-2.52|5314943|2.06|
|SOL_USDT|83.170000|-1.35|-11.25|-1.88|645843727|1.20|
|XRP_USDT|1.052600|-1.18|-17.81|-1.71|300529650|0.95|
|QNT_USDT|181.730000|-0.74|-7.00|-1.27|45371444|0.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|43.320000|42.760000|43.320000|0.48|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.843700|0.840800|0.843700|0.61|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|71.900000|71.689000|71.900000|1.09|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005250|0.004964|0.005250|3.04|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|181.730000|180.610000|181.730000|1.14|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|83.170000|82.830000|83.170000|1.23|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.713000|6.653000|6.713000|1.26|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.421000|19.215000|19.421000|1.13|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.052600|1.048600|1.052600|0.95|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1019.590000|1016.660000|1019.590000|1.79|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-11T02:00:00+00:00, last15m_closed_end=2026-11-11T02:00+00:00, prior8high=44.600000, depth_time=2026-11-11T02:00:09+00:00, book20_bid_proxy_usdt=517236, book20_ask_proxy_usdt=640098, funding_indicative=-0.000202, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.93%, turnover=13892343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T02:00:00+00:00, last15m_closed_end=2026-11-11T02:00+00:00, prior8high=0.851900, depth_time=2026-11-11T02:00:13+00:00, book20_bid_proxy_usdt=577472, book20_ask_proxy_usdt=552495, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=8366731. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-11T02:00:00+00:00, last15m_closed_end=2026-11-11T02:00+00:00, prior8high=72.632000, depth_time=2026-11-11T02:00:15+00:00, book20_bid_proxy_usdt=137017, book20_ask_proxy_usdt=127159, funding_indicative=0.000050, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.32%, turnover=41045015. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-11T02:00:00+00:00, last15m_closed_end=2026-11-11T02:00+00:00, prior8high=0.005301, depth_time=2026-11-11T02:00:09+00:00, book20_bid_proxy_usdt=37478, book20_ask_proxy_usdt=25804, funding_indicative=0.000400, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.92%, turnover=17628956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T02:00:00+00:00, last15m_closed_end=2026-11-11T02:00+00:00, prior8high=183.930000, depth_time=2026-11-11T02:00:25+00:00, book20_bid_proxy_usdt=60654, book20_ask_proxy_usdt=102819, funding_indicative=-0.000245, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.74%, turnover=45371444. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-11T02:00:00+00:00, last15m_closed_end=2026-11-11T02:00+00:00, prior8high=84.030000, depth_time=2026-11-11T02:00:23+00:00, book20_bid_proxy_usdt=14134514, book20_ask_proxy_usdt=15994669, funding_indicative=0.000082, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=645843727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T02:00:00+00:00, last15m_closed_end=2026-11-11T02:00+00:00, prior8high=6.820000, depth_time=2026-11-11T02:00:08+00:00, book20_bid_proxy_usdt=2814851, book20_ask_proxy_usdt=3370638, funding_indicative=0.000024, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.98%, turnover=34550055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T02:00:00+00:00, last15m_closed_end=2026-11-11T02:00+00:00, prior8high=19.688000, depth_time=2026-11-11T02:00:17+00:00, book20_bid_proxy_usdt=25178, book20_ask_proxy_usdt=16297, funding_indicative=0.000029, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=5314943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-11T02:00:00+00:00, last15m_closed_end=2026-11-11T02:00+00:00, prior8high=1.063100, depth_time=2026-11-11T02:00:25+00:00, book20_bid_proxy_usdt=3482131, book20_ask_proxy_usdt=3491803, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=300529650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T02:00:00+00:00, last15m_closed_end=2026-11-11T02:00+00:00, prior8high=1049.410000, depth_time=2026-11-11T02:00:07+00:00, book20_bid_proxy_usdt=559982, book20_ask_proxy_usdt=325427, funding_indicative=0.000089, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-14.01%, turnover=2151875175. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
