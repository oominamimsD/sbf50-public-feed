# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T19:00:12Z**
- feed_generated_utc: 2026-10-28T19:00:15+00:00
- source_sha256: `ea9a7fc430a842c144c12f35999ad3992a7abf6ff5d927bbfe1861a83f39d588`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T19:00+00:00, close=80980.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T19:00+00:00, close=80980.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|284.970000|-3.02|-1.62|-3.57|5321024|3.16|
|AIN_USDT|0.142350|-2.29|255.43|-2.84|7528445|2.81|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.142350|0.142100|0.142350|0.61|N|Y/Y|N/N|N|N|
|BCH_USDT|284.970000|282.710000|284.970000|1.39|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-10-28T19:00:03+00:00, last15m_closed_end=2026-10-28T19:00+00:00, prior8high=0.148560, depth_time=2026-10-28T19:00:11+00:00, book20_bid_proxy_usdt=6953, book20_ask_proxy_usdt=20424, funding_indicative=0.000722, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.29%, turnover=7528445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-28T19:00:04+00:00, last15m_closed_end=2026-10-28T19:00+00:00, prior8high=289.560000, depth_time=2026-10-28T19:00:08+00:00, book20_bid_proxy_usdt=63705, book20_ask_proxy_usdt=51597, funding_indicative=0.000024, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.02%, turnover=5321024. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
