# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T01:15:26Z**
- feed_generated_utc: 2026-11-09T01:15:28+00:00
- source_sha256: `35cefd387bb4cae5b18ad9affa5dbbf6f4ebe86f735a56af6bc7844536e89c24`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T01:15+00:00, close=75065.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T01:00+00:00, close=75213.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001724|-11.95|48.04|-10.67|11516805|0.58|
|HOT_USDT|0.000397|-7.61|10.37|-6.33|6239438|2.52|
|PUMPFUN_USDT|0.003565|-4.60|-15.48|-3.32|8389023|2.81|
|DASH_USDT|45.770000|-4.26|-5.82|-2.98|15095372|2.19|
|AKE_USDT|0.005129|-4.25|-44.00|-2.97|13661798|3.90|
|HYPE_USDT|74.652000|-3.58|-14.86|-2.30|37904818|0.13|
|XRP_USDT|1.114600|-3.56|-10.82|-2.28|227717425|0.90|
|LIT_USDT|3.081800|-3.49|-4.59|-2.21|12024757|0.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005129|0.005147|0.005140|1.12|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.770000|44.960000|45.770000|2.50|N|Y/Y|Y/Y|Y|N|
|HOT_USDT|0.000397|0.000400|0.000397|1.52|Y|Y/N|N/N|Y|N|
|HYPE_USDT|74.652000|74.227000|74.652000|1.18|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.081800|3.031200|3.081800|1.10|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001724|0.001698|0.001724|0.33|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003565|0.003495|0.003564|0.83|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.114600|1.105100|1.114600|0.69|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T01:15:02+00:00, last15m_closed_end=2026-11-09T01:15+00:00, prior8high=0.005351, depth_time=2026-11-09T01:15:17+00:00, book20_bid_proxy_usdt=57900, book20_ask_proxy_usdt=32188, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=13661798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-09T01:15:02+00:00, last15m_closed_end=2026-11-09T01:15+00:00, prior8high=46.230000, depth_time=2026-11-09T01:15:14+00:00, book20_bid_proxy_usdt=734902, book20_ask_proxy_usdt=614962, funding_indicative=0.000022, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.26%, turnover=15095372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-09T01:15:02+00:00, last15m_closed_end=2026-11-09T01:15+00:00, prior8high=0.000411, depth_time=2026-11-09T01:15:10+00:00, book20_bid_proxy_usdt=95546, book20_ask_proxy_usdt=116135, funding_indicative=-0.000893, next_funding_utc=2026-11-09T02:00:00+00:00, funding_cycle_h=1, 24h_change=-7.61%, turnover=6239438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T01:15:02+00:00, last15m_closed_end=2026-11-09T01:15+00:00, prior8high=75.837000, depth_time=2026-11-09T01:15:19+00:00, book20_bid_proxy_usdt=75897, book20_ask_proxy_usdt=65138, funding_indicative=0.000017, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.58%, turnover=37904818. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T01:15:02+00:00, last15m_closed_end=2026-11-09T01:15+00:00, prior8high=3.135200, depth_time=2026-11-09T01:15:25+00:00, book20_bid_proxy_usdt=18579, book20_ask_proxy_usdt=26986, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.49%, turnover=12024757. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T01:15:02+00:00, last15m_closed_end=2026-11-09T01:15+00:00, prior8high=0.001763, depth_time=2026-11-09T01:15:07+00:00, book20_bid_proxy_usdt=8726, book20_ask_proxy_usdt=13661, funding_indicative=-0.001092, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.95%, turnover=11516805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T01:15:02+00:00, last15m_closed_end=2026-11-09T01:15+00:00, prior8high=0.003662, depth_time=2026-11-09T01:15:10+00:00, book20_bid_proxy_usdt=3047827, book20_ask_proxy_usdt=2418777, funding_indicative=0.000018, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.60%, turnover=8389023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T01:15:02+00:00, last15m_closed_end=2026-11-09T01:15+00:00, prior8high=1.131800, depth_time=2026-11-09T01:15:23+00:00, book20_bid_proxy_usdt=2440652, book20_ask_proxy_usdt=2489847, funding_indicative=0.000058, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.56%, turnover=227717425. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
