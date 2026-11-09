# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T02:45:21Z**
- feed_generated_utc: 2026-11-09T02:45:22+00:00
- source_sha256: `ed04ce8ec3f52e249f398bb365ffc3d2361b8fdbf071d05548301f75946d18c4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T02:45+00:00, close=75371.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T02:00+00:00, close=75130.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001694|-13.47|45.48|-12.60|11296207|0.59|
|AKE_USDT|0.005045|-5.82|-44.92|-4.95|13032165|1.98|
|AIOT_USDT|0.143380|-5.14|63.41|-4.27|6462659|6.28|
|JCT_USDT|0.009338|-5.04|87.54|-4.17|64610436|3.22|
|XRP_USDT|1.120100|-3.08|-10.38|-2.21|231433279|0.89|
|HYPE_USDT|75.123000|-2.98|-14.32|-2.11|40337538|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIOT_USDT|0.143380|0.140510|0.143560|1.17|N|N/N|N/N|Y|N|
|AKE_USDT|0.005045|0.004921|0.005045|0.11|N|Y/Y|N/N|Y|N|
|HYPE_USDT|75.123000|74.059000|75.123000|0.53|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009338|0.009211|0.009327|0.43|N|Y/N|N/N|Y|N|
|ONE_USDT|0.001694|0.001687|0.001694|0.15|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.120100|1.106800|1.120100|0.36|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AIOT_USDT: quote_utc=2026-11-09T02:45:01+00:00, last15m_closed_end=2026-11-09T02:45+00:00, prior8high=0.164030, depth_time=2026-11-09T02:45:13+00:00, book20_bid_proxy_usdt=4826, book20_ask_proxy_usdt=8000, funding_indicative=0.000406, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.14%, turnover=6462659. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-09T02:45:01+00:00, last15m_closed_end=2026-11-09T02:45+00:00, prior8high=0.005297, depth_time=2026-11-09T02:45:09+00:00, book20_bid_proxy_usdt=29508, book20_ask_proxy_usdt=95851, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.82%, turnover=13032165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T02:45:01+00:00, last15m_closed_end=2026-11-09T02:45+00:00, prior8high=75.332000, depth_time=2026-11-09T02:45:19+00:00, book20_bid_proxy_usdt=41749, book20_ask_proxy_usdt=70115, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.98%, turnover=40337538. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T02:45:01+00:00, last15m_closed_end=2026-11-09T02:45+00:00, prior8high=0.012446, depth_time=2026-11-09T02:45:16+00:00, book20_bid_proxy_usdt=21171, book20_ask_proxy_usdt=18989, funding_indicative=0.001574, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.04%, turnover=64610436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T02:45:01+00:00, last15m_closed_end=2026-11-09T02:45+00:00, prior8high=0.001757, depth_time=2026-11-09T02:45:08+00:00, book20_bid_proxy_usdt=12092, book20_ask_proxy_usdt=11942, funding_indicative=-0.000736, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.47%, turnover=11296207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T02:45:01+00:00, last15m_closed_end=2026-11-09T02:45+00:00, prior8high=1.125700, depth_time=2026-11-09T02:45:17+00:00, book20_bid_proxy_usdt=2140140, book20_ask_proxy_usdt=3933631, funding_indicative=0.000011, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.08%, turnover=231433279. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
