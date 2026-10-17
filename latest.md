# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T21:00:13Z**
- feed_generated_utc: 2026-10-17T21:00:14+00:00
- source_sha256: `07a9312a7ede93ee5d86d1e45002093f6ffccef0290e78ede65f20fb4ecc305c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T21:00+00:00, close=81610.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T21:00+00:00, close=81610.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-17T20:00+00:00, close=81575.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.257100|-5.51|UNKNOWN|-5.87|6738586|7.78|
|STRK_USDT|0.065040|-1.67|-30.38|-2.03|15842666|1.54|
|EIGEN_USDT|0.253600|-1.05|7.64|-1.41|9860833|3.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DNA_USDT|0.257100|0.249000|0.257100|0.65|N|Y/Y|?|Y|N|
|EIGEN_USDT|0.253600|0.252800|0.253600|1.01|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.065040|0.064620|0.065040|2.24|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DNA_USDT: quote_utc=2026-10-17T20:59:59+00:00, last15m_closed_end=2026-10-17T21:00+00:00, prior8high=0.260200, depth_time=2026-10-17T21:00:05+00:00, book20_bid_proxy_usdt=89762, book20_ask_proxy_usdt=82975, funding_indicative=-0.001070, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.51%, turnover=6738586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-17T20:59:59+00:00, last15m_closed_end=2026-10-17T21:00+00:00, prior8high=0.256500, depth_time=2026-10-17T21:00:11+00:00, book20_bid_proxy_usdt=620649, book20_ask_proxy_usdt=421843, funding_indicative=-0.000009, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.05%, turnover=9860833. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T20:59:59+00:00, last15m_closed_end=2026-10-17T21:00+00:00, prior8high=0.068240, depth_time=2026-10-17T21:00:10+00:00, book20_bid_proxy_usdt=271389, book20_ask_proxy_usdt=407925, funding_indicative=0.000050, next_funding_utc=2026-10-18T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.67%, turnover=15842666. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
