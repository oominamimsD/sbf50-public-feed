# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T07:30:21Z**
- feed_generated_utc: 2026-10-21T07:30:23+00:00
- source_sha256: `2b7a4e90874463dcafe3bd964fac0ac60413a37e197fb18a5a18412195af4d33`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T07:30+00:00, close=83070, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T07:00+00:00, close=82752, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.044006|-31.90|172.02|-32.50|7068544|3.86|
|BAT_USDT|0.187970|-12.88|5.97|-13.48|10916046|1.06|
|BR_USDT|0.580350|-10.80|34.02|-11.40|30332709|2.59|
|XMR_USDT|585.510000|-5.59|10.91|-6.19|21677937|0.68|
|PHA_USDT|0.056970|-1.47|3.52|-2.07|5889822|1.75|
|SILVER_USDT|57.490000|-0.79|-3.19|-1.39|221435666|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.044006|0.038698|0.044006|4.98|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.187970|0.181950|0.187970|2.77|N|Y/Y|Y/N|N|N|
|BR_USDT|0.580350|0.577510|0.580020|1.66|N|Y/Y|N/N|N|N|
|PHA_USDT|0.056970|0.055950|0.056970|0.44|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.490000|57.210000|57.470000|0.39|N|Y/Y|Y/N|N|N|
|XMR_USDT|585.510000|576.030000|585.350000|1.65|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T07:30:01+00:00, last15m_closed_end=2026-10-21T07:30+00:00, prior8high=0.062194, depth_time=2026-10-21T07:30:07+00:00, book20_bid_proxy_usdt=16918, book20_ask_proxy_usdt=9002, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-31.90%, turnover=7068544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T07:30:01+00:00, last15m_closed_end=2026-10-21T07:30+00:00, prior8high=0.186130, depth_time=2026-10-21T07:30:10+00:00, book20_bid_proxy_usdt=35255, book20_ask_proxy_usdt=18048, funding_indicative=-0.000129, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-12.88%, turnover=10916046. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T07:30:01+00:00, last15m_closed_end=2026-10-21T07:30+00:00, prior8high=0.595790, depth_time=2026-10-21T07:30:13+00:00, book20_bid_proxy_usdt=3630, book20_ask_proxy_usdt=3443, funding_indicative=0.000048, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.80%, turnover=30332709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T07:30:01+00:00, last15m_closed_end=2026-10-21T07:30+00:00, prior8high=0.057160, depth_time=2026-10-21T07:30:17+00:00, book20_bid_proxy_usdt=83281, book20_ask_proxy_usdt=60461, funding_indicative=-0.000024, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.47%, turnover=5889822. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T07:30:01+00:00, last15m_closed_end=2026-10-21T07:30+00:00, prior8high=57.780000, depth_time=2026-10-21T07:30:17+00:00, book20_bid_proxy_usdt=41475195, book20_ask_proxy_usdt=36558938, funding_indicative=0.000034, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.79%, turnover=221435666. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T07:30:01+00:00, last15m_closed_end=2026-10-21T07:30+00:00, prior8high=588.220000, depth_time=2026-10-21T07:30:14+00:00, book20_bid_proxy_usdt=14381, book20_ask_proxy_usdt=16833, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.59%, turnover=21677937. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
