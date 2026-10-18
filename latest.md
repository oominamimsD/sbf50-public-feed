# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T17:45:13Z**
- feed_generated_utc: 2026-10-18T17:45:15+00:00
- source_sha256: `3aefcdf740b7e76e7bc42135584bc0b0d21987d446d1edfd14979abc638ec974`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T17:45+00:00, close=81113.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T17:00+00:00, close=81040.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.059760|-2.92|-49.89|-2.90|15208710|1.67|
|BAT_USDT|0.170990|-2.50|2.61|-2.48|10038101|2.34|
|PUMPFUN_USDT|0.004128|-1.59|-28.51|-1.57|29978178|2.42|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.170990|0.171200|0.170990|0.44|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004128|0.004108|0.004128|0.80|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.059760|0.060020|0.059760|2.11|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-18T17:44:59+00:00, last15m_closed_end=2026-10-18T17:45+00:00, prior8high=0.177360, depth_time=2026-10-18T17:45:09+00:00, book20_bid_proxy_usdt=17798, book20_ask_proxy_usdt=27051, funding_indicative=-0.000002, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=10038101. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T17:44:58+00:00, last15m_closed_end=2026-10-18T17:45+00:00, prior8high=0.004211, depth_time=2026-10-18T17:45:12+00:00, book20_bid_proxy_usdt=1505696, book20_ask_proxy_usdt=2254167, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.59%, turnover=29978178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T17:44:58+00:00, last15m_closed_end=2026-10-18T17:45+00:00, prior8high=0.062250, depth_time=2026-10-18T17:45:07+00:00, book20_bid_proxy_usdt=498048, book20_ask_proxy_usdt=404784, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.92%, turnover=15208710. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
