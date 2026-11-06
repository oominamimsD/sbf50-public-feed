# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T21:30:10Z**
- feed_generated_utc: 2026-11-06T21:30:11+00:00
- source_sha256: `d96e81d9bdc6170ac69995fd27096ca408bd448aa56644a72b702c1d0360fe5a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T21:30+00:00, close=75763.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T21:00+00:00, close=75860, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ANTHROPIC_USDT|1339.070000|-6.43|-20.12|-6.34|6224079|3.28|
|LIT_USDT|3.312700|-2.34|17.29|-2.25|10564254|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1339.070000|1316.030000|1339.610000|2.24|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.312700|3.268700|3.312700|0.36|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T21:29:59+00:00, last15m_closed_end=2026-11-06T21:30+00:00, prior8high=1364.300000, depth_time=2026-11-06T21:30:06+00:00, book20_bid_proxy_usdt=24154, book20_ask_proxy_usdt=15408, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-6.43%, turnover=6224079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T21:29:59+00:00, last15m_closed_end=2026-11-06T21:30+00:00, prior8high=3.346900, depth_time=2026-11-06T21:30:07+00:00, book20_bid_proxy_usdt=25958, book20_ask_proxy_usdt=29376, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=10564254. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
