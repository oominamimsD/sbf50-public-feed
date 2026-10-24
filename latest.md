# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T23:45:12Z**
- feed_generated_utc: 2026-10-24T23:45:15+00:00
- source_sha256: `76ba0cc5aec08662ec11fef8c8b2d08c5fcd315c0104c20e5b2c1c83ef448349`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T23:45+00:00, close=80832.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T23:00+00:00, close=80571.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.041590|-9.68|225.94|-11.02|34125904|2.40|
|BIRB_USDT|0.089870|-7.97|85.22|-9.31|11674834|2.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.089870|0.083640|0.089870|1.97|N|Y/Y|N/N|Y|N|
|IRYS_USDT|0.041590|0.041450|0.041600|0.87|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T23:44:59+00:00, last15m_closed_end=2026-10-24T23:45+00:00, prior8high=0.091400, depth_time=2026-10-24T23:45:12+00:00, book20_bid_proxy_usdt=11387, book20_ask_proxy_usdt=10204, funding_indicative=-0.008893, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.97%, turnover=11674834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T23:44:59+00:00, last15m_closed_end=2026-10-24T23:45+00:00, prior8high=0.045580, depth_time=2026-10-24T23:45:09+00:00, book20_bid_proxy_usdt=83149, book20_ask_proxy_usdt=87299, funding_indicative=-0.000011, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=1, 24h_change=-9.68%, turnover=34125904. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
