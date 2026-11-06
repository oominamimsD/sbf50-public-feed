# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T18:45:10Z**
- feed_generated_utc: 2026-11-06T18:45:11+00:00
- source_sha256: `8628582275af2d1cef3492e103d4f8d75ca1dc1e51e6b6023a9e738dd7130005`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T18:45+00:00, close=75854.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T18:00+00:00, close=75750.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T16:00+00:00, close=75832.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ANTHROPIC_USDT|1354.700000|-5.34|-19.19|-5.36|6454083|1.33|
|LIT_USDT|3.333300|-1.74|18.02|-1.76|12728092|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1354.700000|1326.270000|1354.700000|0.37|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.333300|3.314000|3.333300|0.50|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T18:45:00+00:00, last15m_closed_end=2026-11-06T18:45+00:00, prior8high=1407.840000, depth_time=2026-11-06T18:45:07+00:00, book20_bid_proxy_usdt=22501, book20_ask_proxy_usdt=18979, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.34%, turnover=6454083. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T18:45:00+00:00, last15m_closed_end=2026-11-06T18:45+00:00, prior8high=3.455000, depth_time=2026-11-06T18:45:09+00:00, book20_bid_proxy_usdt=22552, book20_ask_proxy_usdt=33231, funding_indicative=0.000041, next_funding_utc=2026-11-06T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=12728092. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
