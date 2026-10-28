# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T02:00:14Z**
- feed_generated_utc: 2026-10-28T02:00:17+00:00
- source_sha256: `bfcd6778fd9bb7185f55fe905b327ecba21976d98604a6feaf759c9b417169e3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T02:00+00:00, close=80912.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T02:00+00:00, close=80912.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T00:00+00:00, close=80868.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.023016|-22.15|-25.97|-22.62|5642938|0.87|
|Q_USDT|0.054702|-17.10|-55.43|-17.57|38268393|0.18|
|NIL_USDT|0.085960|-5.50|-3.26|-5.97|5806841|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.023016|0.021437|0.023016|1.79|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.085960|0.085040|0.085960|0.90|N|Y/Y|N/N|N|N|
|Q_USDT|0.054702|0.052383|0.054702|0.59|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T02:00:01+00:00, last15m_closed_end=2026-10-28T02:00+00:00, prior8high=0.023654, depth_time=2026-10-28T02:00:09+00:00, book20_bid_proxy_usdt=2320, book20_ask_proxy_usdt=3494, funding_indicative=0.000050, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-22.15%, turnover=5642938. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-28T02:00:01+00:00, last15m_closed_end=2026-10-28T02:00+00:00, prior8high=0.092100, depth_time=2026-10-28T02:00:14+00:00, book20_bid_proxy_usdt=3634, book20_ask_proxy_usdt=8039, funding_indicative=-0.000267, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.50%, turnover=5806841. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T02:00:01+00:00, last15m_closed_end=2026-10-28T02:00+00:00, prior8high=0.055141, depth_time=2026-10-28T02:00:11+00:00, book20_bid_proxy_usdt=28758, book20_ask_proxy_usdt=27818, funding_indicative=-0.000155, next_funding_utc=2026-10-28T04:00:00+00:00, funding_cycle_h=4, 24h_change=-17.10%, turnover=38268393. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
