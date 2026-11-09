# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T21:45:15Z**
- feed_generated_utc: 2026-11-09T21:45:16+00:00
- source_sha256: `b543369c309b82023a8af82d49b046d8dbb57900f512a839c608282214a92d18`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T21:45+00:00, close=74811.8, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T21:00+00:00, close=74845.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1166.010000|-4.87|-7.02|-3.96|2575537214|0.09|
|DOT_USDT|0.859700|-3.50|-7.96|-2.59|12630143|1.16|
|QNT_USDT|195.000000|-2.51|-3.67|-1.60|45289412|0.51|
|XRP_USDT|1.090600|-2.09|-12.64|-1.18|330251508|0.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|0.859700|0.859200|0.859700|0.55|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.000000|194.710000|195.010000|0.92|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.090600|1.087800|1.090600|0.84|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1166.010000|1162.360000|1166.150000|0.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-11-09T21:45:01+00:00, last15m_closed_end=2026-11-09T21:45+00:00, prior8high=0.874300, depth_time=2026-11-09T21:45:09+00:00, book20_bid_proxy_usdt=870729, book20_ask_proxy_usdt=830893, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.50%, turnover=12630143. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-09T21:45:01+00:00, last15m_closed_end=2026-11-09T21:45+00:00, prior8high=197.510000, depth_time=2026-11-09T21:45:12+00:00, book20_bid_proxy_usdt=53290, book20_ask_proxy_usdt=51772, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=45289412. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T21:45:01+00:00, last15m_closed_end=2026-11-09T21:45+00:00, prior8high=1.103100, depth_time=2026-11-09T21:45:13+00:00, book20_bid_proxy_usdt=3800211, book20_ask_proxy_usdt=4048393, funding_indicative=0.000082, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=330251508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T21:45:01+00:00, last15m_closed_end=2026-11-09T21:45+00:00, prior8high=1189.910000, depth_time=2026-11-09T21:45:07+00:00, book20_bid_proxy_usdt=176853, book20_ask_proxy_usdt=299287, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.87%, turnover=2575537214. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
