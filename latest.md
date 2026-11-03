# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T11:30:33Z**
- feed_generated_utc: 2026-11-03T11:30:35+00:00
- source_sha256: `320a86288ab50880f3cf04c8d66cfec0c3366b6a358a30e6a20473cfe7df2c2e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T11:30+00:00, close=77176.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T11:00+00:00, close=77103.4, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-03T08:00+00:00, close=76799.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004559|-17.13|-85.18|-16.74|12869303|4.39|
|BTW_USDT|0.928500|-15.34|-22.34|-14.95|10539636|2.16|
|XPL_USDT|0.064570|-7.20|-13.08|-6.81|11538888|1.55|
|ZEC_USDT|1175.140000|-6.29|-5.81|-5.90|1800005055|0.51|
|NEAR_USDT|3.850000|-3.99|-15.81|-3.60|77253402|2.60|
|SILVER_USDT|49.100000|-3.83|-9.45|-3.44|432742922|2.04|
|TIA_USDT|0.440900|-3.50|-17.69|-3.11|12762164|2.27|
|DASH_USDT|45.830000|-2.90|-12.23|-2.51|9039708|2.18|
|XLM_USDT|0.163060|-2.70|-3.85|-2.31|34370246|0.61|
|ENA_USDT|0.171050|-2.27|-18.69|-1.88|68439753|0.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004559|0.004436|0.004559|0.42|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.928500|0.870600|0.928500|7.03|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|45.830000|45.630000|45.830000|0.12|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.171050|0.169020|0.171050|1.18|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.850000|3.794000|3.850000|0.54|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|49.100000|48.820000|49.100000|0.41|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.440900|0.436200|0.440900|0.94|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.163060|0.161580|0.163060|0.86|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.064570|0.063400|0.064570|5.34|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1175.140000|1133.350000|1175.140000|1.44|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T11:30:00+00:00, last15m_closed_end=2026-11-03T11:30+00:00, prior8high=0.004638, depth_time=2026-11-03T11:30:07+00:00, book20_bid_proxy_usdt=41446, book20_ask_proxy_usdt=40173, funding_indicative=-0.001804, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.13%, turnover=12869303. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-03T11:30:00+00:00, last15m_closed_end=2026-11-03T11:30+00:00, prior8high=0.922000, depth_time=2026-11-03T11:30:11+00:00, book20_bid_proxy_usdt=26330, book20_ask_proxy_usdt=16071, funding_indicative=-0.000270, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-15.34%, turnover=10539636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T11:30:00+00:00, last15m_closed_end=2026-11-03T11:30+00:00, prior8high=45.990000, depth_time=2026-11-03T11:30:26+00:00, book20_bid_proxy_usdt=758667, book20_ask_proxy_usdt=499900, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=9039708. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T11:30:00+00:00, last15m_closed_end=2026-11-03T11:30+00:00, prior8high=0.171000, depth_time=2026-11-03T11:30:32+00:00, book20_bid_proxy_usdt=146963, book20_ask_proxy_usdt=283778, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=68439753. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T11:30:00+00:00, last15m_closed_end=2026-11-03T11:30+00:00, prior8high=3.868000, depth_time=2026-11-03T11:30:19+00:00, book20_bid_proxy_usdt=3539764, book20_ask_proxy_usdt=3547938, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.99%, turnover=77253402. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-03T11:30:00+00:00, last15m_closed_end=2026-11-03T11:30+00:00, prior8high=49.240000, depth_time=2026-11-03T11:30:22+00:00, book20_bid_proxy_usdt=53041797, book20_ask_proxy_usdt=43165693, funding_indicative=0.000060, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.83%, turnover=432742922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T11:30:00+00:00, last15m_closed_end=2026-11-03T11:30+00:00, prior8high=0.441100, depth_time=2026-11-03T11:30:24+00:00, book20_bid_proxy_usdt=322614, book20_ask_proxy_usdt=314795, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.50%, turnover=12762164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T11:30:00+00:00, last15m_closed_end=2026-11-03T11:30+00:00, prior8high=0.163180, depth_time=2026-11-03T11:30:28+00:00, book20_bid_proxy_usdt=327217, book20_ask_proxy_usdt=147284, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=34370246. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T11:30:00+00:00, last15m_closed_end=2026-11-03T11:30+00:00, prior8high=0.064500, depth_time=2026-11-03T11:30:13+00:00, book20_bid_proxy_usdt=459421, book20_ask_proxy_usdt=289601, funding_indicative=0.000050, next_funding_utc=2026-11-03T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.20%, turnover=11538888. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-03T11:29:59+00:00, last15m_closed_end=2026-11-03T11:30+00:00, prior8high=1173.610000, depth_time=2026-11-03T11:30:17+00:00, book20_bid_proxy_usdt=1092145, book20_ask_proxy_usdt=190341, funding_indicative=0.000022, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.29%, turnover=1800005055. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
