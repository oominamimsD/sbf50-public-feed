# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T17:00:13Z**
- feed_generated_utc: 2026-11-06T17:00:14+00:00
- source_sha256: `172185439182f5cb7971e9ff1f6a7b9b3c053cde5ae50b8bbfd6c7439892a9de`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T17:00+00:00, close=75978.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T17:00+00:00, close=75978.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T16:00+00:00, close=75832.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.003020|-14.61|-47.34|-15.22|5410300|3.33|
|ANTHROPIC_USDT|1379.330000|-5.10|-17.72|-5.71|5700411|0.87|
|BLESS_USDT|0.008008|-0.66|-18.70|-1.27|6325508|1.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1379.330000|1397.510000|1379.330000|1.31|Y|Y/Y|Y/Y|Y|Y|
|BLESS_USDT|0.008008|0.007722|0.008008|0.20|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.003020|0.002764|0.003023|0.69|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T17:00:00+00:00, last15m_closed_end=2026-11-06T17:00+00:00, prior8high=1468.440000, depth_time=2026-11-06T17:00:10+00:00, book20_bid_proxy_usdt=10716, book20_ask_proxy_usdt=29902, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.10%, turnover=5700411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-06T17:00:00+00:00, last15m_closed_end=2026-11-06T17:00+00:00, prior8high=0.008227, depth_time=2026-11-06T17:00:12+00:00, book20_bid_proxy_usdt=16274, book20_ask_proxy_usdt=16118, funding_indicative=0.000050, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.66%, turnover=6325508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-06T17:00:00+00:00, last15m_closed_end=2026-11-06T17:00+00:00, prior8high=0.003722, depth_time=2026-11-06T17:00:07+00:00, book20_bid_proxy_usdt=38112, book20_ask_proxy_usdt=54660, funding_indicative=0.000050, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-14.61%, turnover=5410300. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
