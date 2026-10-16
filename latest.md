# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T04:30:15Z**
- feed_generated_utc: 2026-10-16T04:30:17+00:00
- source_sha256: `03c66541af8c15fa74dab0e30108781ac7b30e60c4db9abf53cf796610bae860`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T04:30+00:00, close=82058, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEREBRO_USDT|0.039465|-23.06|43.73|-22.68|7070265|7.11|
|WAL_USDT|0.045880|-13.92|37.81|-13.54|5060618|2.18|
|ZKSYNC_USDT|0.016892|-4.23|51.89|-3.85|7811059|2.37|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|WAL_USDT|0.045880|0.044820|0.045900|1.04|N|Y/Y|Y/N|Y|N|
|ZEREBRO_USDT|0.039465|0.040115|0.039465|2.60|Y|Y/N|N/N|Y|N|
|ZKSYNC_USDT|0.016892|0.016384|0.016892|0.22|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- WAL_USDT: quote_utc=2026-10-16T04:30:00+00:00, last15m_closed_end=2026-10-16T04:30+00:00, prior8high=0.047030, depth_time=2026-10-16T04:30:11+00:00, book20_bid_proxy_usdt=137181, book20_ask_proxy_usdt=144170, funding_indicative=-0.000544, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.92%, turnover=5060618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T04:30:00+00:00, last15m_closed_end=2026-10-16T04:30+00:00, prior8high=0.059435, depth_time=2026-10-16T04:30:09+00:00, book20_bid_proxy_usdt=14457, book20_ask_proxy_usdt=12989, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-23.06%, turnover=7070265. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZKSYNC_USDT: quote_utc=2026-10-16T04:30:01+00:00, last15m_closed_end=2026-10-16T04:30+00:00, prior8high=0.016855, depth_time=2026-10-16T04:30:14+00:00, book20_bid_proxy_usdt=18062, book20_ask_proxy_usdt=4913, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.23%, turnover=7811059. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
