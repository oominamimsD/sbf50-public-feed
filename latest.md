# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T22:45:17Z**
- feed_generated_utc: 2026-11-04T22:45:18+00:00
- source_sha256: `f1bf407bf28671f9d55c1707f6a310789a6bdf9ff718a6bc9765b974620f179f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T22:45+00:00, close=80907.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T22:00+00:00, close=80198.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.270000|-10.81|-25.68|-11.60|26442812|7.88|
|IDOL_USDT|0.021242|-9.48|145.37|-10.27|6330794|4.71|
|AKE_USDT|0.002594|-7.68|-87.09|-8.47|16612354|3.86|
|BTW_USDT|1.037600|-5.58|-40.29|-6.37|6285416|0.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002594|0.002479|0.002594|0.42|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.037600|1.026000|1.037600|1.08|N|Y/Y|Y/N|N|N|
|IDOL_USDT|0.021242|0.020994|0.021242|0.32|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.270000|1.257000|1.270000|0.15|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T22:45:03+00:00, last15m_closed_end=2026-11-04T22:45+00:00, prior8high=0.002701, depth_time=2026-11-04T22:45:13+00:00, book20_bid_proxy_usdt=56631, book20_ask_proxy_usdt=108098, funding_indicative=-0.000912, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.68%, turnover=16612354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-04T22:45:00+00:00, last15m_closed_end=2026-11-04T22:45+00:00, prior8high=1.046600, depth_time=2026-11-04T22:45:15+00:00, book20_bid_proxy_usdt=27971, book20_ask_proxy_usdt=14916, funding_indicative=0.000035, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.58%, turnover=6285416. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-04T22:45:03+00:00, last15m_closed_end=2026-11-04T22:45+00:00, prior8high=0.022051, depth_time=2026-11-04T22:45:04+00:00, book20_bid_proxy_usdt=9162, book20_ask_proxy_usdt=2718, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.48%, turnover=6330794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T22:45:04+00:00, last15m_closed_end=2026-11-04T22:45+00:00, prior8high=1.295000, depth_time=2026-11-04T22:45:07+00:00, book20_bid_proxy_usdt=1079737, book20_ask_proxy_usdt=934147, funding_indicative=-0.000182, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.81%, turnover=26442812. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
