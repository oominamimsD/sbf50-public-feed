# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T18:45:10Z**
- feed_generated_utc: 2026-10-15T18:45:11+00:00
- source_sha256: `fd3ba47f01ad5d5efd5504196e3c1bfbc6555e60030b8cf4dc55dbaa0411bd6d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T18:45+00:00, close=82290, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T18:00+00:00, close=82393.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T16:00+00:00, close=82375.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.050940|-4.42|53.01|-4.33|11037413|1.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|WAL_USDT|0.050940|0.050240|0.050940|0.71|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- WAL_USDT: quote_utc=2026-10-15T18:45:01+00:00, last15m_closed_end=2026-10-15T18:45+00:00, prior8high=0.051980, depth_time=2026-10-15T18:45:08+00:00, book20_bid_proxy_usdt=113514, book20_ask_proxy_usdt=160860, funding_indicative=-0.000385, next_funding_utc=2026-10-15T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.42%, turnover=11037413. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
