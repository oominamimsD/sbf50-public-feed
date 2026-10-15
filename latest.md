# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T22:00:14Z**
- feed_generated_utc: 2026-10-15T22:00:16+00:00
- source_sha256: `1f6d54f1860f7ccbf1e79b68b4d7125062cf0680644d706da4977c2ca53dcd33`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T22:00+00:00, close=82385.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T22:00+00:00, close=82385.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T20:00+00:00, close=82350.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|NIL_USDT|0.083520|-3.86|-3.54|-3.87|15906679|1.20|
|WAL_USDT|0.051390|-3.58|54.37|-3.59|9253890|1.95|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.083520|0.081300|0.083520|0.14|N|Y/Y|N/N|Y|N|
|WAL_USDT|0.051390|0.050780|0.051390|0.44|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-15T21:59:59+00:00, last15m_closed_end=2026-10-15T22:00+00:00, prior8high=0.089970, depth_time=2026-10-15T22:00:11+00:00, book20_bid_proxy_usdt=24583, book20_ask_proxy_usdt=34725, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.86%, turnover=15906679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T21:59:59+00:00, last15m_closed_end=2026-10-15T22:00+00:00, prior8high=0.052350, depth_time=2026-10-15T22:00:13+00:00, book20_bid_proxy_usdt=190117, book20_ask_proxy_usdt=109549, funding_indicative=-0.000223, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.58%, turnover=9253890. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
