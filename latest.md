# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T02:45:14Z**
- feed_generated_utc: 2026-10-14T02:45:15+00:00
- source_sha256: `438c510c4398d0407c4b8a2f187deb955fefb02c357e4ad3b5c97bee2e720da4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T02:45+00:00, close=83358.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T02:00+00:00, close=83281.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|OGN_USDT|0.033810|-3.94|50.87|-3.90|5041126|2.96|
|STRK_USDT|0.084690|-2.57|62.27|-2.53|31237257|1.18|
|MAGIC_USDT|0.116160|-2.09|70.52|-2.05|7397626|0.86|
|W_USDT|0.016468|-1.99|13.47|-1.95|7859675|1.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.116160|0.115320|0.116040|1.19|N|Y/Y|N/N|N|N|
|OGN_USDT|0.033810|0.034060|0.033810|2.81|Y|Y/Y|Y/N|N|N|
|STRK_USDT|0.084690|0.084230|0.084690|0.26|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016468|0.016574|0.016479|1.37|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T02:45:02+00:00, last15m_closed_end=2026-10-14T02:45+00:00, prior8high=0.122210, depth_time=2026-10-14T02:45:11+00:00, book20_bid_proxy_usdt=177594, book20_ask_proxy_usdt=173178, funding_indicative=-0.000104, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=7397626. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-14T02:45:02+00:00, last15m_closed_end=2026-10-14T02:45+00:00, prior8high=0.034960, depth_time=2026-10-14T02:45:06+00:00, book20_bid_proxy_usdt=139848, book20_ask_proxy_usdt=134567, funding_indicative=-0.000184, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.94%, turnover=5041126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T02:45:02+00:00, last15m_closed_end=2026-10-14T02:45+00:00, prior8high=0.086530, depth_time=2026-10-14T02:45:09+00:00, book20_bid_proxy_usdt=238003, book20_ask_proxy_usdt=466628, funding_indicative=0.000017, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=31237257. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T02:45:02+00:00, last15m_closed_end=2026-10-14T02:45+00:00, prior8high=0.017269, depth_time=2026-10-14T02:45:12+00:00, book20_bid_proxy_usdt=17834, book20_ask_proxy_usdt=66831, funding_indicative=-0.000366, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=7859675. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
