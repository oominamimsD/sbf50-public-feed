# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T16:15:10Z**
- feed_generated_utc: 2026-11-08T16:15:11+00:00
- source_sha256: `e30164e47ece1fe6f6d68640c37d9923f1ea104f9b76f274ae5bb43769453270`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T16:15+00:00, close=76000, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.029853|-3.26|51.73|-3.22|14240444|4.68|
|ONE_USDT|0.001935|-1.14|66.20|-1.10|21135694|0.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IDOL_USDT|0.029853|0.030120|0.029854|1.56|Y|Y/Y|N/N|Y|N|
|ONE_USDT|0.001935|0.001818|0.001938|0.80|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- IDOL_USDT: quote_utc=2026-11-08T16:14:59+00:00, last15m_closed_end=2026-11-08T16:15+00:00, prior8high=0.031336, depth_time=2026-11-08T16:15:05+00:00, book20_bid_proxy_usdt=8028, book20_ask_proxy_usdt=37149, funding_indicative=0.000955, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.26%, turnover=14240444. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T16:14:59+00:00, last15m_closed_end=2026-11-08T16:15+00:00, prior8high=0.001987, depth_time=2026-11-08T16:15:09+00:00, book20_bid_proxy_usdt=12782, book20_ask_proxy_usdt=10470, funding_indicative=-0.001526, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=21135694. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
