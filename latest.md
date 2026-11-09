# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T22:45:10Z**
- feed_generated_utc: 2026-11-09T22:45:11+00:00
- source_sha256: `74d87a6fd464d0031f1cb62b3023de8d7e83fb96d840dde70ecbf31a9abf5e67`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T22:45+00:00, close=75250.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T22:00+00:00, close=75004.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1182.620000|-3.51|-5.69|-3.18|2515027225|0.09|
|DOT_USDT|0.863300|-3.09|-7.57|-2.76|11630016|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|0.863300|0.856000|0.863200|0.50|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1182.620000|1162.360000|1182.440000|1.01|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-11-09T22:45:03+00:00, last15m_closed_end=2026-11-09T22:45+00:00, prior8high=0.868000, depth_time=2026-11-09T22:45:09+00:00, book20_bid_proxy_usdt=790016, book20_ask_proxy_usdt=616089, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.09%, turnover=11630016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T22:45:03+00:00, last15m_closed_end=2026-11-09T22:45+00:00, prior8high=1178.740000, depth_time=2026-11-09T22:45:06+00:00, book20_bid_proxy_usdt=208093, book20_ask_proxy_usdt=189196, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.51%, turnover=2515027225. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
