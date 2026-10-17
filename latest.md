# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T16:45:11Z**
- feed_generated_utc: 2026-10-17T16:45:12+00:00
- source_sha256: `55198fd6c63469b360fd41e6b694217594db912f98700a12ba9dc6e38e4a3739`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T16:45+00:00, close=81269.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T16:00+00:00, close=81315.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T16:00+00:00, close=81315.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.258200|-5.10|UNKNOWN|-5.05|8660719|7.74|
|PUMPFUN_USDT|0.004346|-1.49|-24.08|-1.44|42979462|2.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DNA_USDT|0.258200|0.254400|0.258200|0.74|N|Y/Y|?|Y|N|
|PUMPFUN_USDT|0.004346|0.004361|0.004349|6.48|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- DNA_USDT: quote_utc=2026-10-17T16:45:01+00:00, last15m_closed_end=2026-10-17T16:45+00:00, prior8high=0.276900, depth_time=2026-10-17T16:45:06+00:00, book20_bid_proxy_usdt=91653, book20_ask_proxy_usdt=75667, funding_indicative=-0.001295, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.10%, turnover=8660719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-17T16:45:01+00:00, last15m_closed_end=2026-10-17T16:45+00:00, prior8high=0.004547, depth_time=2026-10-17T16:45:10+00:00, book20_bid_proxy_usdt=1185313, book20_ask_proxy_usdt=1099764, funding_indicative=0.000050, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.49%, turnover=42979462. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
