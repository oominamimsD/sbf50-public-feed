# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T20:15:08Z**
- feed_generated_utc: 2026-11-09T20:15:08+00:00
- source_sha256: `f08299e22d7dcf68df54be1ef61073bc05c0aec3ecb638ca37b3ddf0cc7f6a4f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T20:15+00:00, close=74981.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1183.030000|-3.48|-5.66|-2.81|2488560765|0.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ZEC_USDT|1183.030000|1158.500000|1183.140000|0.98|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ZEC_USDT: quote_utc=2026-11-09T20:15:01+00:00, last15m_closed_end=2026-11-09T20:15+00:00, prior8high=1189.910000, depth_time=2026-11-09T20:15:07+00:00, book20_bid_proxy_usdt=103209, book20_ask_proxy_usdt=116115, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=2488560765. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
