# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T21:15:12Z**
- feed_generated_utc: 2026-11-06T21:15:13+00:00
- source_sha256: `a6a1e7b966ab1ec6138ad391358f06317b7df831184f244f9fd619a165c8f8fb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T21:15+00:00, close=75873.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T21:00+00:00, close=75860, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.145200|-23.57|-45.33|-23.62|31600645|6.89|
|ANTHROPIC_USDT|1350.810000|-5.61|-19.42|-5.66|5954355|3.33|
|LIT_USDT|3.320700|-2.11|17.58|-2.16|10529345|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1350.810000|1316.030000|1348.690000|2.26|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.320700|3.268700|3.320700|0.18|N|Y/Y|Y/N|Y|N|
|UAI_USDT|0.145200|0.105200|0.145200|1.77|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T21:14:59+00:00, last15m_closed_end=2026-11-06T21:15+00:00, prior8high=1357.510000, depth_time=2026-11-06T21:15:09+00:00, book20_bid_proxy_usdt=19743, book20_ask_proxy_usdt=24491, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.61%, turnover=5954355. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T21:14:59+00:00, last15m_closed_end=2026-11-06T21:15+00:00, prior8high=3.343600, depth_time=2026-11-06T21:15:09+00:00, book20_bid_proxy_usdt=37593, book20_ask_proxy_usdt=24399, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=10529345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T21:14:59+00:00, last15m_closed_end=2026-11-06T21:15+00:00, prior8high=0.139800, depth_time=2026-11-06T21:15:06+00:00, book20_bid_proxy_usdt=123019, book20_ask_proxy_usdt=129331, funding_indicative=-0.000030, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-23.57%, turnover=31600645. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
