# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T17:30:17Z**
- feed_generated_utc: 2026-10-21T17:30:20+00:00
- source_sha256: `dd541530f58d9edd6e6c876986cd9d81f06d772ed1fd4ca12ff0847af1684a2f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T17:30+00:00, close=84524, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T17:00+00:00, close=84506.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BR_USDT|0.518990|-4.16|27.28|-4.18|15908392|0.39|
|JCT_USDT|0.004103|-3.48|95.28|-3.50|16680924|9.75|
|AKE_USDT|0.026051|-2.39|0.65|-2.41|10009345|3.46|
|INJ_USDT|8.619000|-1.58|12.82|-1.60|55921165|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.026051|0.025666|0.026051|0.21|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.518990|0.521390|0.518990|0.96|N|Y/Y|Y/Y|N|N|
|INJ_USDT|8.619000|8.577000|8.619000|1.29|N|Y/Y|N/N|N|N|
|JCT_USDT|0.004103|0.004016|0.004103|0.33|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T17:30:00+00:00, last15m_closed_end=2026-10-21T17:30+00:00, prior8high=0.027572, depth_time=2026-10-21T17:30:14+00:00, book20_bid_proxy_usdt=11180, book20_ask_proxy_usdt=20396, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.39%, turnover=10009345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T17:30:00+00:00, last15m_closed_end=2026-10-21T17:30+00:00, prior8high=0.561210, depth_time=2026-10-21T17:30:09+00:00, book20_bid_proxy_usdt=3352, book20_ask_proxy_usdt=3071, funding_indicative=-0.000141, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.16%, turnover=15908392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T17:30:00+00:00, last15m_closed_end=2026-10-21T17:30+00:00, prior8high=8.808000, depth_time=2026-10-21T17:30:16+00:00, book20_bid_proxy_usdt=229134, book20_ask_proxy_usdt=232985, funding_indicative=0.000022, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=55921165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-21T17:30:00+00:00, last15m_closed_end=2026-10-21T17:30+00:00, prior8high=0.004408, depth_time=2026-10-21T17:30:12+00:00, book20_bid_proxy_usdt=46112, book20_ask_proxy_usdt=49047, funding_indicative=0.000051, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.48%, turnover=16680924. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
