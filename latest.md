# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T04:45:12Z**
- feed_generated_utc: 2026-10-28T04:45:15+00:00
- source_sha256: `96a1a6b31b13fe0a9c93da4485e7f02c8c89e15c022d112f6d9855dd90cc13a6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T04:45+00:00, close=80964.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T04:00+00:00, close=81110.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.048853|-23.16|-60.20|-23.69|34899315|1.64|
|NIL_USDT|0.083020|-10.43|-6.57|-10.96|5939945|6.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.083020|0.082210|0.083020|0.36|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.048853|0.047916|0.048800|1.62|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-28T04:45:01+00:00, last15m_closed_end=2026-10-28T04:45+00:00, prior8high=0.085420, depth_time=2026-10-28T04:45:10+00:00, book20_bid_proxy_usdt=5828, book20_ask_proxy_usdt=11674, funding_indicative=-0.000090, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.43%, turnover=5939945. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T04:45:01+00:00, last15m_closed_end=2026-10-28T04:45+00:00, prior8high=0.055511, depth_time=2026-10-28T04:45:09+00:00, book20_bid_proxy_usdt=31403, book20_ask_proxy_usdt=28375, funding_indicative=-0.000013, next_funding_utc=2026-10-28T08:00:00+00:00, funding_cycle_h=4, 24h_change=-23.16%, turnover=34899315. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
