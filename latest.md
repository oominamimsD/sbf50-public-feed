# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T20:00:16Z**
- feed_generated_utc: 2026-11-08T20:00:17+00:00
- source_sha256: `720b1b6e3306145364834a17a7ba84dbe2871da559cd4d7746f11d654e96e4fd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001751|-10.59|50.33|-10.41|16455722|0.57|
|AKE_USDT|0.005233|-2.31|-42.87|-2.13|18419411|1.91|
|ARB_USDT|0.166640|-1.91|0.27|-1.73|19272330|0.60|
|NEAR_USDT|3.638000|-1.70|-16.00|-1.52|32123244|2.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005233|0.005112|0.005233|0.73|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.166640|0.166560|0.166640|0.32|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.638000|3.600000|3.640000|1.11|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001751|0.001766|0.001751|1.43|Y|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T19:59:59+00:00, last15m_closed_end=2026-11-08T20:00+00:00, prior8high=0.005317, depth_time=2026-11-08T20:00:10+00:00, book20_bid_proxy_usdt=45249, book20_ask_proxy_usdt=87210, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=18419411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-08T19:59:59+00:00, last15m_closed_end=2026-11-08T20:00+00:00, prior8high=0.169110, depth_time=2026-11-08T20:00:12+00:00, book20_bid_proxy_usdt=92487, book20_ask_proxy_usdt=69012, funding_indicative=-0.000033, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=19272330. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T19:59:59+00:00, last15m_closed_end=2026-11-08T20:00+00:00, prior8high=3.666000, depth_time=2026-11-08T20:00:13+00:00, book20_bid_proxy_usdt=3527924, book20_ask_proxy_usdt=2762587, funding_indicative=0.000100, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=32123244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T19:59:59+00:00, last15m_closed_end=2026-11-08T20:00+00:00, prior8high=0.001846, depth_time=2026-11-08T20:00:07+00:00, book20_bid_proxy_usdt=12834, book20_ask_proxy_usdt=10124, funding_indicative=-0.000428, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.59%, turnover=16455722. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
