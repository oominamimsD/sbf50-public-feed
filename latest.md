# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T04:15:14Z**
- feed_generated_utc: 2026-10-16T04:15:16+00:00
- source_sha256: `279fb2b0dc3799a8db25920f5aca68d5a32718e19867265f97f2d90c3192603d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T04:15+00:00, close=82004, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEREBRO_USDT|0.041059|-19.95|49.53|-19.50|7021500|5.60|
|WAL_USDT|0.045420|-14.78|36.43|-14.33|5048701|2.20|
|ZKSYNC_USDT|0.016746|-5.06|50.57|-4.61|7807957|2.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|WAL_USDT|0.045420|0.044820|0.045420|0.69|N|Y/Y|Y/N|Y|N|
|ZEREBRO_USDT|0.041059|0.040318|0.041073|2.38|N|Y/N|N/N|Y|N|
|ZKSYNC_USDT|0.016746|0.016384|0.016755|1.11|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- WAL_USDT: quote_utc=2026-10-16T04:15:01+00:00, last15m_closed_end=2026-10-16T04:15+00:00, prior8high=0.047130, depth_time=2026-10-16T04:15:11+00:00, book20_bid_proxy_usdt=140640, book20_ask_proxy_usdt=201125, funding_indicative=-0.000530, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.78%, turnover=5048701. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T04:15:01+00:00, last15m_closed_end=2026-10-16T04:15+00:00, prior8high=0.059435, depth_time=2026-10-16T04:15:08+00:00, book20_bid_proxy_usdt=4995, book20_ask_proxy_usdt=14170, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.95%, turnover=7021500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZKSYNC_USDT: quote_utc=2026-10-16T04:15:01+00:00, last15m_closed_end=2026-10-16T04:15+00:00, prior8high=0.016793, depth_time=2026-10-16T04:15:13+00:00, book20_bid_proxy_usdt=11035, book20_ask_proxy_usdt=7840, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.06%, turnover=7807957. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
