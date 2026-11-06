# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T18:15:10Z**
- feed_generated_utc: 2026-11-06T18:15:11+00:00
- source_sha256: `39a9442dbda2600ac96b7e0225634bf9ffbd5db4563854d7765b154b798849f5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T18:15+00:00, close=75797.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T18:00+00:00, close=75750.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T16:00+00:00, close=75832.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ANTHROPIC_USDT|1351.870000|-5.54|-19.35|-5.50|6203039|2.88|
|LIT_USDT|3.341600|-1.49|18.32|-1.45|12517878|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1351.870000|1326.270000|1351.870000|2.05|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.341600|3.340800|3.341600|2.98|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T18:14:59+00:00, last15m_closed_end=2026-11-06T18:15+00:00, prior8high=1432.140000, depth_time=2026-11-06T18:15:07+00:00, book20_bid_proxy_usdt=21530, book20_ask_proxy_usdt=16372, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.54%, turnover=6203039. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T18:14:59+00:00, last15m_closed_end=2026-11-06T18:15+00:00, prior8high=3.455000, depth_time=2026-11-06T18:15:09+00:00, book20_bid_proxy_usdt=21463, book20_ask_proxy_usdt=28811, funding_indicative=0.000036, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.49%, turnover=12517878. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
