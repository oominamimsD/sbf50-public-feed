# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T01:45:11Z**
- feed_generated_utc: 2026-10-16T01:45:13+00:00
- source_sha256: `bb7810f975424cba1e6901a0847573eb8cb9427e2e5b84389220c6eaa5dfef2d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T01:45+00:00, close=82138.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T01:00+00:00, close=82297.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T00:00+00:00, close=82195.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.047020|-11.78|41.24|-11.50|6684862|2.12|
|BTW_USDT|1.808100|-5.20|30.23|-4.92|22299625|1.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.808100|1.805400|1.808100|1.07|N|Y/Y|Y/Y|Y|N|
|WAL_USDT|0.047020|0.050210|0.047100|10.60|Y|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-16T01:45:02+00:00, last15m_closed_end=2026-10-16T01:45+00:00, prior8high=1.878400, depth_time=2026-10-16T01:45:09+00:00, book20_bid_proxy_usdt=21858, book20_ask_proxy_usdt=19000, funding_indicative=0.000050, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.20%, turnover=22299625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-16T01:45:02+00:00, last15m_closed_end=2026-10-16T01:45+00:00, prior8high=0.051850, depth_time=2026-10-16T01:45:08+00:00, book20_bid_proxy_usdt=79248, book20_ask_proxy_usdt=103787, funding_indicative=-0.000492, next_funding_utc=2026-10-16T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.78%, turnover=6684862. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
