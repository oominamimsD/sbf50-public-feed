# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T08:00:35Z**
- feed_generated_utc: 2026-11-11T08:00:36+00:00
- source_sha256: `c6d87e34b172b176e8434b7a34b27e6026831b88397e38042060503e620db5ee`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.203000|-19.10|50.95|-20.30|66766807|1.48|
|ZEC_USDT|1002.290000|-15.46|-16.74|-16.66|2145386244|0.10|
|ONE_USDT|0.001632|-9.05|46.13|-10.25|12126627|4.91|
|UNI_USDT|6.465000|-8.49|-12.07|-9.69|39249769|1.55|
|PEPE_USDT|0.000005|-5.47|7.35|-6.67|75814049|0.19|
|AKE_USDT|0.002564|-5.45|-38.30|-6.65|9079948|3.90|
|DASH_USDT|44.190000|-5.06|-4.22|-6.26|16380790|2.26|
|ARB_USDT|0.159130|-3.59|-0.46|-4.79|29184666|0.63|
|VVV_USDT|19.161000|-3.31|-14.31|-4.51|5379965|0.52|
|DOT_USDT|0.836100|-3.06|-11.29|-4.26|8587415|1.20|
|HBAR_USDT|0.065490|-2.13|-6.48|-3.33|6251307|1.53|
|QNT_USDT|179.610000|-1.90|-8.09|-3.10|45893815|0.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002564|0.002583|0.002564|1.38|Y|Y/Y|Y/Y|Y|Y|
|ARB_USDT|0.159130|0.157280|0.159130|0.49|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|44.190000|43.260000|44.190000|2.92|N|Y/N|Y/Y|Y|N|
|DOT_USDT|0.836100|0.824500|0.836000|0.96|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065490|0.064970|0.065490|8.00|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.203000|0.183320|0.203760|1.08|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001632|0.001605|0.001631|0.92|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.36|N|Y/Y|N/N|Y|N|
|QNT_USDT|179.610000|177.180000|179.610000|0.79|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.465000|6.373000|6.465000|1.70|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.161000|18.851000|19.161000|1.42|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1002.290000|965.410000|1002.290000|0.83|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T08:00:01+00:00, last15m_closed_end=2026-11-11T08:00+00:00, prior8high=0.002833, depth_time=2026-11-11T08:00:19+00:00, book20_bid_proxy_usdt=48100, book20_ask_proxy_usdt=59026, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.45%, turnover=9079948. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T08:00:01+00:00, last15m_closed_end=2026-11-11T08:00+00:00, prior8high=0.163260, depth_time=2026-11-11T08:00:23+00:00, book20_bid_proxy_usdt=53244, book20_ask_proxy_usdt=62547, funding_indicative=0.000001, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.59%, turnover=29184666. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T08:00:01+00:00, last15m_closed_end=2026-11-11T08:00+00:00, prior8high=45.380000, depth_time=2026-11-11T08:00:21+00:00, book20_bid_proxy_usdt=781110, book20_ask_proxy_usdt=508576, funding_indicative=-0.000107, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.06%, turnover=16380790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T08:00:01+00:00, last15m_closed_end=2026-11-11T08:00+00:00, prior8high=0.845300, depth_time=2026-11-11T08:00:28+00:00, book20_bid_proxy_usdt=625558, book20_ask_proxy_usdt=432186, funding_indicative=0.000063, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=8587415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T08:00:01+00:00, last15m_closed_end=2026-11-11T08:00+00:00, prior8high=0.065870, depth_time=2026-11-11T08:00:27+00:00, book20_bid_proxy_usdt=689815, book20_ask_proxy_usdt=546312, funding_indicative=-0.000014, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=6251307. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T08:00:01+00:00, last15m_closed_end=2026-11-11T08:00+00:00, prior8high=0.259000, depth_time=2026-11-11T08:00:07+00:00, book20_bid_proxy_usdt=10144, book20_ask_proxy_usdt=17863, funding_indicative=-0.007126, next_funding_utc=2026-11-11T09:00:00+00:00, funding_cycle_h=1, 24h_change=-19.10%, turnover=66766807. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T08:00:01+00:00, last15m_closed_end=2026-11-11T08:00+00:00, prior8high=0.001798, depth_time=2026-11-11T08:00:12+00:00, book20_bid_proxy_usdt=19245, book20_ask_proxy_usdt=23698, funding_indicative=-0.003051, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.05%, turnover=12126627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T08:00:01+00:00, last15m_closed_end=2026-11-11T08:00+00:00, prior8high=0.000005, depth_time=2026-11-11T08:00:15+00:00, book20_bid_proxy_usdt=22738, book20_ask_proxy_usdt=37876, funding_indicative=-0.000037, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.47%, turnover=75814049. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T08:00:01+00:00, last15m_closed_end=2026-11-11T08:00+00:00, prior8high=180.860000, depth_time=2026-11-11T08:00:33+00:00, book20_bid_proxy_usdt=88035, book20_ask_proxy_usdt=130152, funding_indicative=-0.000088, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=45893815. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T08:00:01+00:00, last15m_closed_end=2026-11-11T08:00+00:00, prior8high=6.687000, depth_time=2026-11-11T08:00:12+00:00, book20_bid_proxy_usdt=2629292, book20_ask_proxy_usdt=1549502, funding_indicative=0.000002, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.49%, turnover=39249769. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T08:00:01+00:00, last15m_closed_end=2026-11-11T08:00+00:00, prior8high=19.229000, depth_time=2026-11-11T08:00:27+00:00, book20_bid_proxy_usdt=30722, book20_ask_proxy_usdt=14695, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.31%, turnover=5379965. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T08:00:01+00:00, last15m_closed_end=2026-11-11T08:00+00:00, prior8high=1023.190000, depth_time=2026-11-11T08:00:09+00:00, book20_bid_proxy_usdt=480311, book20_ask_proxy_usdt=270815, funding_indicative=0.000045, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.46%, turnover=2145386244. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
