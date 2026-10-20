# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T17:00:21Z**
- feed_generated_utc: 2026-10-20T17:00:24+00:00
- source_sha256: `14199855c66c5f2471989281a25c59d3eece3eb65ef20f916f2192bbfb25000e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T17:00+00:00, close=82743.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T17:00+00:00, close=82743.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T16:00+00:00, close=82581.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.753100|-5.21|-10.21|-5.40|33955569|1.71|
|Q_USDT|0.123103|-4.59|199.32|-4.78|6820523|1.71|
|PHA_USDT|0.057720|-4.16|4.88|-4.35|20695368|5.20|
|STRK_USDT|0.055270|-3.72|-36.42|-3.91|17763966|1.81|
|ARB_USDT|0.189290|-3.69|2.51|-3.88|105300982|0.53|
|INJ_USDT|8.602000|-3.41|9.76|-3.60|44989038|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.189290|0.186140|0.189290|0.91|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.753100|1.750600|1.752700|0.52|N|Y/Y|Y/Y|N|N|
|INJ_USDT|8.602000|8.469000|8.603000|0.78|N|N/N|N/N|N|N|
|PHA_USDT|0.057720|0.057170|0.057720|0.41|N|Y/Y|N/N|N|N|
|Q_USDT|0.123103|0.121860|0.123103|0.23|N|Y/Y|N/N|N|N|
|STRK_USDT|0.055270|0.054760|0.055270|0.50|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-20T17:00:01+00:00, last15m_closed_end=2026-10-20T17:00+00:00, prior8high=0.197880, depth_time=2026-10-20T17:00:18+00:00, book20_bid_proxy_usdt=111084, book20_ask_proxy_usdt=62588, funding_indicative=-0.000098, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=105300982. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T17:00:01+00:00, last15m_closed_end=2026-10-20T17:00+00:00, prior8high=1.889700, depth_time=2026-10-20T17:00:08+00:00, book20_bid_proxy_usdt=6478, book20_ask_proxy_usdt=9994, funding_indicative=-0.003170, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.21%, turnover=33955569. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-20T17:00:01+00:00, last15m_closed_end=2026-10-20T17:00+00:00, prior8high=9.005000, depth_time=2026-10-20T17:00:21+00:00, book20_bid_proxy_usdt=191010, book20_ask_proxy_usdt=218823, funding_indicative=0.000142, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.41%, turnover=44989038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-20T17:00:01+00:00, last15m_closed_end=2026-10-20T17:00+00:00, prior8high=0.060430, depth_time=2026-10-20T17:00:13+00:00, book20_bid_proxy_usdt=53917, book20_ask_proxy_usdt=57718, funding_indicative=-0.000258, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.16%, turnover=20695368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T17:00:01+00:00, last15m_closed_end=2026-10-20T17:00+00:00, prior8high=0.131229, depth_time=2026-10-20T17:00:07+00:00, book20_bid_proxy_usdt=19791, book20_ask_proxy_usdt=17607, funding_indicative=0.000003, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.59%, turnover=6820523. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T17:00:01+00:00, last15m_closed_end=2026-10-20T17:00+00:00, prior8high=0.058150, depth_time=2026-10-20T17:00:15+00:00, book20_bid_proxy_usdt=614685, book20_ask_proxy_usdt=582835, funding_indicative=-0.000009, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.72%, turnover=17763966. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
