# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T09:45:15Z**
- feed_generated_utc: 2026-11-06T09:45:16+00:00
- source_sha256: `04dcca42228256b7a629031db9b136af7e195133e76f42e7a8cb44cdf8728447`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T09:45+00:00, close=76089.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T09:00+00:00, close=75643, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|267.860000|-4.03|-7.08|-4.13|7555186|2.61|
|XRP_USDT|1.198000|-3.74|-8.51|-3.84|481252048|0.83|
|XPL_USDT|0.057570|-1.72|-27.06|-1.82|12196521|3.47|
|QNT_USDT|188.930000|-1.50|-4.93|-1.60|36734268|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|267.860000|261.500000|267.860000|0.71|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.930000|187.280000|188.930000|0.88|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057570|0.056650|0.057570|0.38|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.198000|1.177100|1.198000|1.28|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T09:45:01+00:00, last15m_closed_end=2026-11-06T09:45+00:00, prior8high=269.100000, depth_time=2026-11-06T09:45:05+00:00, book20_bid_proxy_usdt=54148, book20_ask_proxy_usdt=45948, funding_indicative=-0.000026, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.03%, turnover=7555186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T09:45:01+00:00, last15m_closed_end=2026-11-06T09:45+00:00, prior8high=190.420000, depth_time=2026-11-06T09:45:13+00:00, book20_bid_proxy_usdt=69084, book20_ask_proxy_usdt=108147, funding_indicative=0.000042, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=36734268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T09:45:01+00:00, last15m_closed_end=2026-11-06T09:45+00:00, prior8high=0.057950, depth_time=2026-11-06T09:45:11+00:00, book20_bid_proxy_usdt=436529, book20_ask_proxy_usdt=429294, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=12196521. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T09:45:01+00:00, last15m_closed_end=2026-11-06T09:45+00:00, prior8high=1.201000, depth_time=2026-11-06T09:45:09+00:00, book20_bid_proxy_usdt=3145390, book20_ask_proxy_usdt=4797692, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=481252048. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
