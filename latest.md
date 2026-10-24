# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T18:15:11Z**
- feed_generated_utc: 2026-10-24T18:15:13+00:00
- source_sha256: `62aafede31605a09b871dd02972fc40bed5ce5bb24a3686991e01f378b7d95e4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T18:15+00:00, close=80318.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T18:00+00:00, close=80238.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.094660|-3.07|95.09|-3.76|11862247|3.16|
|BR_USDT|0.462300|-0.94|23.08|-1.63|5191220|2.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.094660|0.091630|0.094660|0.56|N|Y/Y|N/N|Y|N|
|BR_USDT|0.462300|0.458600|0.462300|0.64|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T18:15:00+00:00, last15m_closed_end=2026-10-24T18:15+00:00, prior8high=0.097760, depth_time=2026-10-24T18:15:07+00:00, book20_bid_proxy_usdt=13808, book20_ask_proxy_usdt=13674, funding_indicative=-0.007705, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=11862247. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-24T18:15:00+00:00, last15m_closed_end=2026-10-24T18:15+00:00, prior8high=0.479200, depth_time=2026-10-24T18:15:10+00:00, book20_bid_proxy_usdt=29860, book20_ask_proxy_usdt=32510, funding_indicative=0.000050, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.94%, turnover=5191220. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
