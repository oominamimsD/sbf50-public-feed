# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T00:15:08Z**
- feed_generated_utc: 2026-11-08T00:15:09+00:00
- source_sha256: `59d67ed0a51203a26be9b06d816976ef20fdb40586d4a042f4ae7afe4db15a3c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T00:15+00:00, close=75786, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|196.400000|-1.23|-2.31|-1.30|42551047|1.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|QNT_USDT|196.400000|194.800000|196.400000|0.90|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- QNT_USDT: quote_utc=2026-11-08T00:15:00+00:00, last15m_closed_end=2026-11-08T00:15+00:00, prior8high=196.750000, depth_time=2026-11-08T00:15:06+00:00, book20_bid_proxy_usdt=88994, book20_ask_proxy_usdt=51398, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=42551047. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
