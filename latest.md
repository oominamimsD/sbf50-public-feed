# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T02:00:20Z**
- feed_generated_utc: 2026-11-09T02:00:21+00:00
- source_sha256: `070c2d3d022925c9d484ef45be1460d95fb084a61bc3d0eb84ad97d1718c07d7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T02:00+00:00, close=75130.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T02:00+00:00, close=75130.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T00:00+00:00, close=74823.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001693|-13.52|45.39|-12.34|11230628|0.59|
|HOT_USDT|0.000396|-8.65|10.06|-7.47|6244939|2.53|
|AKE_USDT|0.005021|-5.81|-45.18|-4.63|12984479|3.98|
|JCT_USDT|0.009430|-4.10|89.39|-2.92|63552041|5.30|
|XRP_USDT|1.112800|-4.05|-10.96|-2.87|227524059|0.90|
|HYPE_USDT|74.825000|-3.36|-14.66|-2.18|39674913|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005021|0.005017|0.005021|1.66|N|Y/Y|N/N|Y|N|
|HOT_USDT|0.000396|0.000397|0.000396|0.68|N|Y/Y|N/N|Y|N|
|HYPE_USDT|74.825000|74.059000|74.839000|0.44|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009430|0.009725|0.009464|0.70|N|Y/N|N/N|Y|N|
|ONE_USDT|0.001693|0.001698|0.001692|0.86|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.112800|1.105100|1.112800|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T02:00:01+00:00, last15m_closed_end=2026-11-09T02:00+00:00, prior8high=0.005297, depth_time=2026-11-09T02:00:12+00:00, book20_bid_proxy_usdt=46331, book20_ask_proxy_usdt=32387, funding_indicative=0.000050, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.81%, turnover=12984479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-09T02:00:01+00:00, last15m_closed_end=2026-11-09T02:00+00:00, prior8high=0.000411, depth_time=2026-11-09T02:00:10+00:00, book20_bid_proxy_usdt=90252, book20_ask_proxy_usdt=119695, funding_indicative=-0.000209, next_funding_utc=2026-11-09T03:00:00+00:00, funding_cycle_h=1, 24h_change=-8.65%, turnover=6244939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T02:00:01+00:00, last15m_closed_end=2026-11-09T02:00+00:00, prior8high=75.415000, depth_time=2026-11-09T02:00:19+00:00, book20_bid_proxy_usdt=176486, book20_ask_proxy_usdt=64224, funding_indicative=0.000044, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.36%, turnover=39674913. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T02:00:01+00:00, last15m_closed_end=2026-11-09T02:00+00:00, prior8high=0.012446, depth_time=2026-11-09T02:00:14+00:00, book20_bid_proxy_usdt=27743, book20_ask_proxy_usdt=19502, funding_indicative=0.002095, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.10%, turnover=63552041. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T02:00:01+00:00, last15m_closed_end=2026-11-09T02:00+00:00, prior8high=0.001763, depth_time=2026-11-09T02:00:07+00:00, book20_bid_proxy_usdt=9307, book20_ask_proxy_usdt=8285, funding_indicative=-0.000957, next_funding_utc=2026-11-09T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.52%, turnover=11230628. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T02:00:01+00:00, last15m_closed_end=2026-11-09T02:00+00:00, prior8high=1.125700, depth_time=2026-11-09T02:00:17+00:00, book20_bid_proxy_usdt=3701934, book20_ask_proxy_usdt=1779771, funding_indicative=0.000018, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.05%, turnover=227524059. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
