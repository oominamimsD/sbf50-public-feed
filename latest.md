# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T18:30:16Z**
- feed_generated_utc: 2026-11-05T18:30:17+00:00
- source_sha256: `0e6b7daeaf7fcec4f34c7d3ff77c07323b34c604d4106db419d204e7f74a0a18`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T18:30+00:00, close=76140, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T18:00+00:00, close=75920.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T16:00+00:00, close=76013.2, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FLUID_USDT|2.398000|-5.29|16.18|-5.46|8889688|8.35|
|BCH_USDT|274.040000|-1.82|-4.93|-1.99|10153756|2.55|
|ONDO_USDT|0.368200|-1.15|-14.33|-1.32|29426978|2.72|
|TRUMPOFFICIAL_USDT|1.156000|-0.94|-33.10|-1.11|29965481|8.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|274.040000|272.300000|274.040000|0.36|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.398000|2.364000|2.398000|0.32|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.368200|0.359500|0.368200|0.47|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.156000|1.112000|1.156000|1.08|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-05T18:29:59+00:00, last15m_closed_end=2026-11-05T18:30+00:00, prior8high=284.120000, depth_time=2026-11-05T18:30:09+00:00, book20_bid_proxy_usdt=44700, book20_ask_proxy_usdt=65047, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=10153756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T18:29:58+00:00, last15m_closed_end=2026-11-05T18:30+00:00, prior8high=2.611000, depth_time=2026-11-05T18:30:05+00:00, book20_bid_proxy_usdt=201674, book20_ask_proxy_usdt=184564, funding_indicative=0.000247, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.29%, turnover=8889688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-05T18:29:59+00:00, last15m_closed_end=2026-11-05T18:30+00:00, prior8high=0.379600, depth_time=2026-11-05T18:30:11+00:00, book20_bid_proxy_usdt=1636103, book20_ask_proxy_usdt=1947025, funding_indicative=0.000000, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.15%, turnover=29426978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T18:29:59+00:00, last15m_closed_end=2026-11-05T18:30+00:00, prior8high=1.204000, depth_time=2026-11-05T18:30:14+00:00, book20_bid_proxy_usdt=1418344, book20_ask_proxy_usdt=876317, funding_indicative=-0.000051, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.94%, turnover=29965481. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
