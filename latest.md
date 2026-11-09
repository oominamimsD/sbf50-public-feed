# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T19:45:10Z**
- feed_generated_utc: 2026-11-09T19:45:11+00:00
- source_sha256: `a9d17c1f74166076756b84b124ce3fc2a2615f641cea0f98d24b33cc725d2f96`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T19:45+00:00, close=75023.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T19:00+00:00, close=74675, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T16:00+00:00, close=75500.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1184.760000|-3.34|-5.52|-2.71|2497159249|0.42|
|BCH_USDT|239.380000|-1.74|-13.06|-1.11|5007159|1.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|239.380000|237.150000|239.380000|1.02|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1184.760000|1158.500000|1184.800000|1.19|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-09T19:44:59+00:00, last15m_closed_end=2026-11-09T19:45+00:00, prior8high=242.930000, depth_time=2026-11-09T19:45:09+00:00, book20_bid_proxy_usdt=54106, book20_ask_proxy_usdt=60409, funding_indicative=0.000058, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=5007159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T19:44:59+00:00, last15m_closed_end=2026-11-09T19:45+00:00, prior8high=1177.940000, depth_time=2026-11-09T19:45:07+00:00, book20_bid_proxy_usdt=66555, book20_ask_proxy_usdt=292474, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.34%, turnover=2497159249. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
