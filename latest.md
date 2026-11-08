# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T19:15:16Z**
- feed_generated_utc: 2026-11-08T19:15:17+00:00
- source_sha256: `48ee134f9591efdb33767015e6139c105a73b320103b7d2ec13a81ae13e5e674`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T19:15+00:00, close=75813.1, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T19:00+00:00, close=75913.5, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001777|-9.24|52.58|-8.95|16295826|0.56|
|AKE_USDT|0.005126|-4.31|-44.03|-4.02|18282581|1.95|
|ARB_USDT|0.166710|-1.87|0.31|-1.58|19009720|0.60|
|NEAR_USDT|3.647000|-1.45|-15.79|-1.16|31488093|2.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005126|0.005162|0.005126|1.39|Y|Y/Y|N/N|Y|N|
|ARB_USDT|0.166710|0.167420|0.166710|10.87|Y|Y/Y|N/N|Y|N|
|NEAR_USDT|3.647000|3.586000|3.647000|1.18|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001777|0.001721|0.001777|0.89|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T19:14:59+00:00, last15m_closed_end=2026-11-08T19:15+00:00, prior8high=0.005319, depth_time=2026-11-08T19:15:10+00:00, book20_bid_proxy_usdt=40632, book20_ask_proxy_usdt=68227, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.31%, turnover=18282581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-08T19:14:59+00:00, last15m_closed_end=2026-11-08T19:15+00:00, prior8high=0.169110, depth_time=2026-11-08T19:15:12+00:00, book20_bid_proxy_usdt=125953, book20_ask_proxy_usdt=68830, funding_indicative=-0.000034, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=19009720. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T19:14:59+00:00, last15m_closed_end=2026-11-08T19:15+00:00, prior8high=3.665000, depth_time=2026-11-08T19:15:13+00:00, book20_bid_proxy_usdt=4472695, book20_ask_proxy_usdt=3733329, funding_indicative=0.000100, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=31488093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T19:14:59+00:00, last15m_closed_end=2026-11-08T19:15+00:00, prior8high=0.001846, depth_time=2026-11-08T19:15:07+00:00, book20_bid_proxy_usdt=11924, book20_ask_proxy_usdt=18607, funding_indicative=-0.000801, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.24%, turnover=16295826. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
