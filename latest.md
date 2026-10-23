# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T16:45:16Z**
- feed_generated_utc: 2026-10-23T16:45:23+00:00
- source_sha256: `84dc11c29e8afd220cf7e437676530828f2cf990f70267161f138f76debb87c4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.12 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T16:45+00:00, close=81725.2, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T16:00+00:00, close=81651.2, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-23T16:00+00:00, close=81651.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BR_USDT|0.506400|-4.52|7.81|-4.61|8985782|5.92|
|AGT_USDT|0.071090|-2.24|80.27|-2.33|6103051|2.81|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.071090|0.065290|0.071090|0.88|N|N/N|N/N|Y|N|
|BR_USDT|0.506400|0.515600|0.505700|1.52|Y|N/N|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-23T16:45:05+00:00, last15m_closed_end=2026-10-23T16:45+00:00, prior8high=0.081480, depth_time=2026-10-23T16:45:09+00:00, book20_bid_proxy_usdt=15921, book20_ask_proxy_usdt=11978, funding_indicative=0.000399, next_funding_utc=2026-10-23T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=6103051. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-23T16:45:05+00:00, last15m_closed_end=2026-10-23T16:45+00:00, prior8high=0.557500, depth_time=2026-10-23T16:45:13+00:00, book20_bid_proxy_usdt=24458, book20_ask_proxy_usdt=29375, funding_indicative=0.000050, next_funding_utc=2026-10-23T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.52%, turnover=8985782. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
