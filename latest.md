# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T19:45:16Z**
- feed_generated_utc: 2026-10-21T19:45:18+00:00
- source_sha256: `9b9026a8f058e73f9c80191b25aa8f501d1098b9a2290a5cc6b9016c940c9a83`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T19:45+00:00, close=84480, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T19:00+00:00, close=84374.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002458|-13.57|73.34|-13.53|9123088|8.14|
|BR_USDT|0.498350|-7.97|22.21|-7.93|14946790|3.01|
|AKE_USDT|0.025373|-4.93|-1.96|-4.89|10172382|1.18|
|INJ_USDT|8.529000|-2.61|11.65|-2.57|58178471|1.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025373|0.025346|0.025373|0.40|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.498350|0.497170|0.497830|0.79|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002458|0.002138|0.002458|0.31|N|Y/Y|N/N|N|N|
|INJ_USDT|8.529000|8.474000|8.529000|0.82|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T19:45:01+00:00, last15m_closed_end=2026-10-21T19:45+00:00, prior8high=0.026445, depth_time=2026-10-21T19:45:12+00:00, book20_bid_proxy_usdt=16194, book20_ask_proxy_usdt=12222, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=10172382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T19:45:01+00:00, last15m_closed_end=2026-10-21T19:45+00:00, prior8high=0.528660, depth_time=2026-10-21T19:45:10+00:00, book20_bid_proxy_usdt=2533, book20_ask_proxy_usdt=2736, funding_indicative=-0.000129, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.97%, turnover=14946790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T19:45:01+00:00, last15m_closed_end=2026-10-21T19:45+00:00, prior8high=0.002442, depth_time=2026-10-21T19:45:08+00:00, book20_bid_proxy_usdt=197417, book20_ask_proxy_usdt=126175, funding_indicative=0.000012, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=1, 24h_change=-13.57%, turnover=9123088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T19:45:01+00:00, last15m_closed_end=2026-10-21T19:45+00:00, prior8high=8.717000, depth_time=2026-10-21T19:45:14+00:00, book20_bid_proxy_usdt=306829, book20_ask_proxy_usdt=279952, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=58178471. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
