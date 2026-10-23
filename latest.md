# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T17:15:13Z**
- feed_generated_utc: 2026-10-23T17:15:20+00:00
- source_sha256: `4455c0fc351cd37011eb43fe9352ef2d6fdfce48ad7f22e137d3883b4ab1b49c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.11 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T17:15+00:00, close=81764.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T17:00+00:00, close=81682.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T16:00+00:00, close=81651.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BR_USDT|0.502700|-5.22|7.02|-5.35|8179903|7.97|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BR_USDT|0.502700|0.504100|0.502700|0.73|N|N/N|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BR_USDT: quote_utc=2026-10-23T17:15:04+00:00, last15m_closed_end=2026-10-23T17:15+00:00, prior8high=0.557500, depth_time=2026-10-23T17:15:12+00:00, book20_bid_proxy_usdt=23056, book20_ask_proxy_usdt=26339, funding_indicative=0.000050, next_funding_utc=2026-10-23T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.22%, turnover=8179903. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
