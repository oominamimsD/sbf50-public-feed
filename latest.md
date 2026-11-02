# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T16:00:14Z**
- feed_generated_utc: 2026-11-02T16:00:16+00:00
- source_sha256: `2d1a4aba262b6918a1be0c9264ba03ca77f6e59aab173c80a0337b4c5e365b9c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INJ_USDT|7.008000|-2.31|-11.67|-2.30|21722034|1.43|
|XPL_USDT|0.069600|-1.31|-6.31|-1.30|9297269|1.44|
|DASH_USDT|47.200000|-1.02|-9.61|-1.01|9154989|2.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|47.200000|47.420000|47.200000|4.85|Y|Y/Y|Y/Y|Y|Y|
|INJ_USDT|7.008000|7.125000|7.009000|5.32|Y|Y/Y|Y/Y|Y|Y|
|XPL_USDT|0.069600|0.070020|0.069580|7.38|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-02T16:00:04+00:00, last15m_closed_end=2026-11-02T16:00+00:00, prior8high=48.120000, depth_time=2026-11-02T16:00:13+00:00, book20_bid_proxy_usdt=329124, book20_ask_proxy_usdt=452377, funding_indicative=0.000029, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=9154989. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-02T16:00:03+00:00, last15m_closed_end=2026-11-02T16:00+00:00, prior8high=7.290000, depth_time=2026-11-02T16:00:08+00:00, book20_bid_proxy_usdt=155277, book20_ask_proxy_usdt=309218, funding_indicative=0.000181, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.31%, turnover=21722034. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T16:00:03+00:00, last15m_closed_end=2026-11-02T16:00+00:00, prior8high=0.071030, depth_time=2026-11-02T16:00:11+00:00, book20_bid_proxy_usdt=369101, book20_ask_proxy_usdt=335102, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=9297269. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
