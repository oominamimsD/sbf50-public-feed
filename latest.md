# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T03:45:16Z**
- feed_generated_utc: 2026-10-14T03:45:17+00:00
- source_sha256: `a7eb6ca11e371f40effa6221601286fbf057d9e13700f8d9f5c645d3bd9d5fe9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T03:45+00:00, close=83785.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T03:00+00:00, close=83609.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.083540|-3.89|60.06|-4.36|30190661|4.79|
|W_USDT|0.016286|-3.07|12.22|-3.54|7241057|0.61|
|OGN_USDT|0.034210|-2.81|52.65|-3.28|5035844|2.92|
|MAGIC_USDT|0.115480|-2.67|69.52|-3.14|6068022|0.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.115480|0.115000|0.115480|0.57|N|Y/Y|N/N|N|N|
|OGN_USDT|0.034210|0.033730|0.034210|1.13|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.083540|0.083660|0.083540|0.26|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016286|0.016278|0.016286|0.49|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T03:44:59+00:00, last15m_closed_end=2026-10-14T03:45+00:00, prior8high=0.120090, depth_time=2026-10-14T03:45:15+00:00, book20_bid_proxy_usdt=193561, book20_ask_proxy_usdt=183024, funding_indicative=-0.000158, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=6068022. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-14T03:44:59+00:00, last15m_closed_end=2026-10-14T03:45+00:00, prior8high=0.034730, depth_time=2026-10-14T03:45:12+00:00, book20_bid_proxy_usdt=119771, book20_ask_proxy_usdt=137011, funding_indicative=-0.000336, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=5035844. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T03:44:59+00:00, last15m_closed_end=2026-10-14T03:45+00:00, prior8high=0.086310, depth_time=2026-10-14T03:45:07+00:00, book20_bid_proxy_usdt=167565, book20_ask_proxy_usdt=217329, funding_indicative=0.000027, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.89%, turnover=30190661. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T03:44:59+00:00, last15m_closed_end=2026-10-14T03:45+00:00, prior8high=0.016979, depth_time=2026-10-14T03:45:07+00:00, book20_bid_proxy_usdt=37366, book20_ask_proxy_usdt=44372, funding_indicative=-0.000231, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=7241057. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
