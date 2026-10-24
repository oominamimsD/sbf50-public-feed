# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T21:15:18Z**
- feed_generated_utc: 2026-10-24T21:15:21+00:00
- source_sha256: `33d3915ea2c964560cda03aa4f4d407ee8563f9c9738a394f3a848698b5c70e5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T21:15+00:00, close=80312, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-24T21:00+00:00, close=80489.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T20:00+00:00, close=80455.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.056820|-15.69|83.58|-16.37|12558159|1.76|
|BIRB_USDT|0.091430|-6.37|88.43|-7.05|11750357|4.38|
|IRYS_USDT|0.044840|-2.62|251.41|-3.30|37983372|4.46|
|STRK_USDT|0.046320|-0.87|-29.97|-1.55|9092030|2.16|
|DOT_USDT|1.033900|-0.50|-7.47|-1.18|12295401|0.97|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.091430|0.090420|0.091430|0.48|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.033900|1.037100|1.033900|2.36|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.044840|0.042300|0.044840|0.60|N|Y/Y|Y/N|Y|N|
|ORDER_USDT|0.056820|0.057430|0.056780|0.71|N|N/N|N/N|Y|N|
|STRK_USDT|0.046320|0.046640|0.046320|4.12|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-24T21:15:01+00:00, last15m_closed_end=2026-10-24T21:15+00:00, prior8high=0.094490, depth_time=2026-10-24T21:15:10+00:00, book20_bid_proxy_usdt=27491, book20_ask_proxy_usdt=26634, funding_indicative=-0.008146, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.37%, turnover=11750357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T21:15:01+00:00, last15m_closed_end=2026-10-24T21:15+00:00, prior8high=1.047500, depth_time=2026-10-24T21:15:17+00:00, book20_bid_proxy_usdt=309747, book20_ask_proxy_usdt=287412, funding_indicative=-0.000094, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.50%, turnover=12295401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-24T21:15:01+00:00, last15m_closed_end=2026-10-24T21:15+00:00, prior8high=0.045710, depth_time=2026-10-24T21:15:13+00:00, book20_bid_proxy_usdt=52735, book20_ask_proxy_usdt=45059, funding_indicative=0.000012, next_funding_utc=2026-10-24T22:00:00+00:00, funding_cycle_h=1, 24h_change=-2.62%, turnover=37983372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-24T21:15:01+00:00, last15m_closed_end=2026-10-24T21:15+00:00, prior8high=0.064800, depth_time=2026-10-24T21:15:08+00:00, book20_bid_proxy_usdt=76101, book20_ask_proxy_usdt=76881, funding_indicative=-0.001366, next_funding_utc=2026-10-24T22:00:00+00:00, funding_cycle_h=1, 24h_change=-15.69%, turnover=12558159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-24T21:15:01+00:00, last15m_closed_end=2026-10-24T21:15+00:00, prior8high=0.047580, depth_time=2026-10-24T21:15:15+00:00, book20_bid_proxy_usdt=836847, book20_ask_proxy_usdt=861461, funding_indicative=0.000019, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.87%, turnover=9092030. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
