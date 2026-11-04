# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T15:15:14Z**
- feed_generated_utc: 2026-11-04T15:15:16+00:00
- source_sha256: `4e3c5fdceceda1f38c2ed3bd4d461396c98a1fe8b148554160bf476f6fcfe5b3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T15:15+00:00, close=80824.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T15:00+00:00, close=79318.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.035740|-33.58|-24.78|-37.65|7016162|5.60|
|AKE_USDT|0.003332|-19.82|-84.22|-23.89|15089434|2.99|
|TRUMPOFFICIAL_USDT|1.461000|-9.14|-13.44|-13.21|14387142|6.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.035740|0.032840|0.035740|2.18|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.003332|0.002886|0.003332|2.43|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.461000|1.404000|1.461000|2.71|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T15:15:01+00:00, last15m_closed_end=2026-11-04T15:15+00:00, prior8high=0.037650, depth_time=2026-11-04T15:15:05+00:00, book20_bid_proxy_usdt=23244, book20_ask_proxy_usdt=25471, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-33.58%, turnover=7016162. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T15:15:01+00:00, last15m_closed_end=2026-11-04T15:15+00:00, prior8high=0.003329, depth_time=2026-11-04T15:15:10+00:00, book20_bid_proxy_usdt=20046, book20_ask_proxy_usdt=33110, funding_indicative=-0.000035, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-19.82%, turnover=15089434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T15:15:02+00:00, last15m_closed_end=2026-11-04T15:15+00:00, prior8high=1.443000, depth_time=2026-11-04T15:15:13+00:00, book20_bid_proxy_usdt=1569141, book20_ask_proxy_usdt=1850796, funding_indicative=-0.000373, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.14%, turnover=14387142. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
