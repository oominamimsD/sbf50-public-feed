# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T11:15:16Z**
- feed_generated_utc: 2026-11-06T11:15:17+00:00
- source_sha256: `62cfe5654067113d7ff64f487e44747caf03ba625751c1f6d57b8565ec147d8f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T11:15+00:00, close=75966.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T11:00+00:00, close=76033.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|XRP_USDT|1.191000|-4.30|-9.04|-4.24|481251820|0.84|
|BCH_USDT|267.190000|-4.27|-7.31|-4.21|7391603|3.37|
|XPL_USDT|0.057640|-1.60|-26.97|-1.54|12181267|1.74|
|QNT_USDT|188.830000|-1.55|-4.98|-1.49|35087028|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|267.190000|265.820000|267.190000|0.78|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.830000|188.400000|188.830000|0.91|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057640|0.057490|0.057640|0.47|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.191000|1.187400|1.191000|0.92|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T11:15:00+00:00, last15m_closed_end=2026-11-06T11:15+00:00, prior8high=269.310000, depth_time=2026-11-06T11:15:09+00:00, book20_bid_proxy_usdt=62810, book20_ask_proxy_usdt=72544, funding_indicative=-0.000053, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.27%, turnover=7391603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T11:15:00+00:00, last15m_closed_end=2026-11-06T11:15+00:00, prior8high=189.850000, depth_time=2026-11-06T11:15:13+00:00, book20_bid_proxy_usdt=65555, book20_ask_proxy_usdt=80517, funding_indicative=0.000003, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=35087028. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T11:15:00+00:00, last15m_closed_end=2026-11-06T11:15+00:00, prior8high=0.057930, depth_time=2026-11-06T11:15:11+00:00, book20_bid_proxy_usdt=561905, book20_ask_proxy_usdt=417211, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.60%, turnover=12181267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T11:15:00+00:00, last15m_closed_end=2026-11-06T11:15+00:00, prior8high=1.201800, depth_time=2026-11-06T11:15:07+00:00, book20_bid_proxy_usdt=5399056, book20_ask_proxy_usdt=3921211, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.30%, turnover=481251820. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
