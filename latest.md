# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T16:45:12Z**
- feed_generated_utc: 2026-10-24T16:45:15+00:00
- source_sha256: `5921493d6cd932fbd7913916305034aa9eef9e2acafbde5d9b29fdc63e1216dd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T16:45+00:00, close=79844.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.065720|-1.80|-8.79|-1.90|10421032|3.05|
|DOT_USDT|1.025800|-1.27|-8.19|-1.37|13388571|1.95|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.065720|0.065630|0.065720|1.21|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.025800|1.026800|1.025800|3.49|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-24T16:45:00+00:00, last15m_closed_end=2026-10-24T16:45+00:00, prior8high=0.072890, depth_time=2026-10-24T16:45:05+00:00, book20_bid_proxy_usdt=11078, book20_ask_proxy_usdt=13291, funding_indicative=0.000092, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.80%, turnover=10421032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T16:45:00+00:00, last15m_closed_end=2026-10-24T16:45+00:00, prior8high=1.055200, depth_time=2026-10-24T16:45:11+00:00, book20_bid_proxy_usdt=234606, book20_ask_proxy_usdt=398980, funding_indicative=-0.000145, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=13388571. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
