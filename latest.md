# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T01:15:14Z**
- feed_generated_utc: 2026-10-25T01:15:17+00:00
- source_sha256: `6b1dcbc43c89ec76693c990ea1f9b87097fd29a6be2e961a8772f4a9c0553150`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T01:15+00:00, close=80766.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T01:00+00:00, close=80842.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.034570|-24.92|170.92|-26.17|34102109|2.91|
|BIRB_USDT|0.074890|-23.31|54.34|-24.56|10268415|4.01|
|ORDER_USDT|0.055080|-18.27|77.96|-19.52|13297462|3.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.074890|0.069260|0.074910|2.05|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.034570|0.033300|0.034570|2.96|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.055080|0.054870|0.055080|1.11|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T01:15:00+00:00, last15m_closed_end=2026-10-25T01:15+00:00, prior8high=0.100590, depth_time=2026-10-25T01:15:11+00:00, book20_bid_proxy_usdt=11424, book20_ask_proxy_usdt=4899, funding_indicative=-0.018934, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-23.31%, turnover=10268415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T01:15:00+00:00, last15m_closed_end=2026-10-25T01:15+00:00, prior8high=0.047160, depth_time=2026-10-25T01:15:09+00:00, book20_bid_proxy_usdt=50065, book20_ask_proxy_usdt=55427, funding_indicative=-0.000304, next_funding_utc=2026-10-25T02:00:00+00:00, funding_cycle_h=1, 24h_change=-24.92%, turnover=34102109. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T01:15:00+00:00, last15m_closed_end=2026-10-25T01:15+00:00, prior8high=0.073400, depth_time=2026-10-25T01:15:13+00:00, book20_bid_proxy_usdt=62104, book20_ask_proxy_usdt=65558, funding_indicative=-0.002517, next_funding_utc=2026-10-25T02:00:00+00:00, funding_cycle_h=1, 24h_change=-18.27%, turnover=13297462. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
