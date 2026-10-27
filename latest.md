# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T23:45:16Z**
- feed_generated_utc: 2026-10-27T23:45:18+00:00
- source_sha256: `98e059ab37ee4750ad3e8d7e2fbb802078178b49823f4b13c7ebb2ac4448d9e6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T23:45+00:00, close=80913.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T23:00+00:00, close=80874.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T20:00+00:00, close=80778.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.052546|-17.35|-57.19|-17.81|44968429|0.76|
|SYN_USDT|0.179000|-1.32|-2.50|-1.78|5826249|5.59|
|NIL_USDT|0.091850|-0.90|3.36|-1.36|5607582|6.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.091850|0.091090|0.091850|0.37|N|Y/Y|N/N|N|N|
|Q_USDT|0.052546|0.053222|0.052549|2.52|Y|Y/Y|Y/Y|N|Y|
|SYN_USDT|0.179000|0.178600|0.179000|3.83|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-27T23:45:00+00:00, last15m_closed_end=2026-10-27T23:45+00:00, prior8high=0.093310, depth_time=2026-10-27T23:45:15+00:00, book20_bid_proxy_usdt=12749, book20_ask_proxy_usdt=2226, funding_indicative=-0.000382, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.90%, turnover=5607582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-27T23:45:00+00:00, last15m_closed_end=2026-10-27T23:45+00:00, prior8high=0.055980, depth_time=2026-10-27T23:45:09+00:00, book20_bid_proxy_usdt=1840, book20_ask_proxy_usdt=2406, funding_indicative=-0.000120, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-17.35%, turnover=44968429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SYN_USDT: quote_utc=2026-10-27T23:45:00+00:00, last15m_closed_end=2026-10-27T23:45+00:00, prior8high=0.182700, depth_time=2026-10-27T23:45:11+00:00, book20_bid_proxy_usdt=100224, book20_ask_proxy_usdt=101684, funding_indicative=0.000050, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.32%, turnover=5826249. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
