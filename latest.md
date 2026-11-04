# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T07:30:13Z**
- feed_generated_utc: 2026-11-04T07:30:14+00:00
- source_sha256: `2035f7184985b9a2822fda7e4c8f43f011610d8bd9fb8765a2a2816c6d0674e7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T07:30+00:00, close=78269.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T07:00+00:00, close=77970.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.038080|-29.23|-19.86|-30.00|10844493|5.25|
|AKE_USDT|0.003115|-25.04|-85.25|-25.81|12434538|3.21|
|TRUMPOFFICIAL_USDT|1.510000|-6.09|-10.54|-6.86|8899275|6.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.038080|0.036730|0.038080|1.05|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.003115|0.002979|0.003115|0.68|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.510000|1.501000|1.510000|0.40|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T07:29:59+00:00, last15m_closed_end=2026-11-04T07:30+00:00, prior8high=0.038670, depth_time=2026-11-04T07:30:07+00:00, book20_bid_proxy_usdt=28568, book20_ask_proxy_usdt=36450, funding_indicative=0.000115, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-29.23%, turnover=10844493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T07:30:00+00:00, last15m_closed_end=2026-11-04T07:30+00:00, prior8high=0.003323, depth_time=2026-11-04T07:30:09+00:00, book20_bid_proxy_usdt=69448, book20_ask_proxy_usdt=71151, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-25.04%, turnover=12434538. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T07:30:00+00:00, last15m_closed_end=2026-11-04T07:30+00:00, prior8high=1.536000, depth_time=2026-11-04T07:30:12+00:00, book20_bid_proxy_usdt=2479398, book20_ask_proxy_usdt=2218171, funding_indicative=-0.000077, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.09%, turnover=8899275. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
