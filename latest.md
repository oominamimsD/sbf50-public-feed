# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T06:00:22Z**
- feed_generated_utc: 2026-10-26T06:00:25+00:00
- source_sha256: `c3bd245416aa6d1fbe03208f6801e81f8bec22498a390bb1d3650da51aeaf2af`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T06:00+00:00, close=80234.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T06:00+00:00, close=80234.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.033140|-13.78|171.63|-13.33|13226861|3.03|
|T_USDT|0.004863|-9.66|3.42|-9.21|5803466|2.06|
|DASH_USDT|51.270000|-3.28|7.08|-2.83|12077891|1.95|
|XMR_USDT|590.280000|-2.96|1.33|-2.51|6338922|0.17|
|DOT_USDT|1.015600|-2.27|-5.03|-1.82|10943675|0.98|
|WLD_USDT|0.442600|-2.12|-7.07|-1.67|70750965|2.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.270000|50.050000|51.270000|1.48|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.015600|1.011600|1.015500|0.86|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.033140|0.032920|0.033210|1.17|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004863|0.004814|0.004860|0.76|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.442600|0.434800|0.442600|0.85|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|590.280000|588.910000|590.280000|0.38|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-26T06:00:04+00:00, last15m_closed_end=2026-10-26T06:00+00:00, prior8high=51.450000, depth_time=2026-10-26T06:00:12+00:00, book20_bid_proxy_usdt=819295, book20_ask_proxy_usdt=701406, funding_indicative=0.000078, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.28%, turnover=12077891. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T06:00:04+00:00, last15m_closed_end=2026-10-26T06:00+00:00, prior8high=1.024300, depth_time=2026-10-26T06:00:19+00:00, book20_bid_proxy_usdt=224761, book20_ask_proxy_usdt=505266, funding_indicative=-0.000048, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=10943675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T06:00:03+00:00, last15m_closed_end=2026-10-26T06:00+00:00, prior8high=0.037430, depth_time=2026-10-26T06:00:09+00:00, book20_bid_proxy_usdt=145792, book20_ask_proxy_usdt=59822, funding_indicative=-0.000265, next_funding_utc=2026-10-26T07:00:00+00:00, funding_cycle_h=1, 24h_change=-13.78%, turnover=13226861. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T06:00:03+00:00, last15m_closed_end=2026-10-26T06:00+00:00, prior8high=0.004976, depth_time=2026-10-26T06:00:07+00:00, book20_bid_proxy_usdt=59942, book20_ask_proxy_usdt=96409, funding_indicative=-0.000727, next_funding_utc=2026-10-26T07:00:00+00:00, funding_cycle_h=1, 24h_change=-9.66%, turnover=5803466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T06:00:03+00:00, last15m_closed_end=2026-10-26T06:00+00:00, prior8high=0.446600, depth_time=2026-10-26T06:00:21+00:00, book20_bid_proxy_usdt=2941050, book20_ask_proxy_usdt=2526370, funding_indicative=-0.000024, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=70750965. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T06:00:04+00:00, last15m_closed_end=2026-10-26T06:00+00:00, prior8high=595.240000, depth_time=2026-10-26T06:00:16+00:00, book20_bid_proxy_usdt=26049, book20_ask_proxy_usdt=14136, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=6338922. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
