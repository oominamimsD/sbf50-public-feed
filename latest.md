# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T10:45:14Z**
- feed_generated_utc: 2026-10-16T10:45:16+00:00
- source_sha256: `f0da0298a2ebf51f1cb003206bdc421e516da778e0d7aaf3fa0a40b76fa4c581`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T10:45+00:00, close=82183.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T10:00+00:00, close=81985.9, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.076610|-20.49|27.34|-20.27|44268215|1.30|
|ZEREBRO_USDT|0.046790|-8.78|70.41|-8.56|6399089|5.14|
|AKE_USDT|0.030124|-4.68|3.79|-4.46|20017714|0.33|
|NIL_USDT|0.083950|-3.37|-3.04|-3.15|6241294|2.38|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030124|0.028930|0.030127|0.54|N|Y/Y|N/N|Y|N|
|NIL_USDT|0.083950|0.081680|0.083950|0.99|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.076610|0.077190|0.076610|2.07|Y|Y/Y|Y/Y|Y|Y|
|ZEREBRO_USDT|0.046790|0.046202|0.046790|4.60|N|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T10:44:59+00:00, last15m_closed_end=2026-10-16T10:45+00:00, prior8high=0.031827, depth_time=2026-10-16T10:45:11+00:00, book20_bid_proxy_usdt=15386, book20_ask_proxy_usdt=11519, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.68%, turnover=20017714. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T10:44:59+00:00, last15m_closed_end=2026-10-16T10:45+00:00, prior8high=0.084570, depth_time=2026-10-16T10:45:13+00:00, book20_bid_proxy_usdt=38066, book20_ask_proxy_usdt=24556, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.37%, turnover=6241294. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T10:44:59+00:00, last15m_closed_end=2026-10-16T10:45+00:00, prior8high=0.079390, depth_time=2026-10-16T10:45:07+00:00, book20_bid_proxy_usdt=593042, book20_ask_proxy_usdt=417007, funding_indicative=0.000043, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-20.49%, turnover=44268215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T10:44:59+00:00, last15m_closed_end=2026-10-16T10:45+00:00, prior8high=0.055777, depth_time=2026-10-16T10:45:09+00:00, book20_bid_proxy_usdt=28022, book20_ask_proxy_usdt=6939, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.78%, turnover=6399089. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
