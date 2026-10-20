# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T02:45:14Z**
- feed_generated_utc: 2026-10-20T02:45:16+00:00
- source_sha256: `e00678d0b1becf5f0d734180e9d25efcabd764daf18fc0a4b89b3906eb7c10b1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T02:45+00:00, close=81603.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T02:00+00:00, close=81765.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.860500|-2.18|-17.71|-1.80|7735372|0.54|
|NEAR_USDT|4.812000|-1.87|-13.28|-1.49|171307577|2.08|
|SAND_USDT|0.058030|-1.87|-6.53|-1.49|9163477|1.72|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NEAR_USDT|4.812000|4.785000|4.812000|0.95|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.058030|0.057130|0.058030|0.17|N|Y/Y|N/Y|Y|N|
|ZRO_USDT|1.860500|1.833600|1.860500|2.01|N|Y/N|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- NEAR_USDT: quote_utc=2026-10-20T02:45:00+00:00, last15m_closed_end=2026-10-20T02:45+00:00, prior8high=4.885000, depth_time=2026-10-20T02:45:11+00:00, book20_bid_proxy_usdt=2354193, book20_ask_proxy_usdt=2172543, funding_indicative=0.000063, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=171307577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T02:45:00+00:00, last15m_closed_end=2026-10-20T02:45+00:00, prior8high=0.058880, depth_time=2026-10-20T02:45:10+00:00, book20_bid_proxy_usdt=693532, book20_ask_proxy_usdt=985797, funding_indicative=-0.002219, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=9163477. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T02:45:00+00:00, last15m_closed_end=2026-10-20T02:45+00:00, prior8high=1.895200, depth_time=2026-10-20T02:45:07+00:00, book20_bid_proxy_usdt=45949, book20_ask_proxy_usdt=70667, funding_indicative=0.000050, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.18%, turnover=7735372. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
