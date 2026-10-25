# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T23:15:17Z**
- feed_generated_utc: 2026-10-25T23:15:23+00:00
- source_sha256: `134f2ca966c32f8dd82e8644c66cd3a77fbc18f4b659319bf361d6618b9f16e7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.11 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T23:15+00:00, close=80427.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T23:00+00:00, close=80429.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.006169|-11.51|234.72|-11.29|10054699|1.62|
|XMR_USDT|593.850000|-2.20|1.94|-1.98|6641837|0.17|
|IRYS_USDT|0.037710|-1.89|209.09|-1.67|19965052|2.65|
|PEPE_USDT|0.000004|-1.50|12.32|-1.28|73762176|0.23|
|DASH_USDT|51.620000|-1.50|7.81|-1.28|13792146|1.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.620000|51.310000|51.620000|0.39|N|Y/Y|N/N|Y|N|
|IRYS_USDT|0.037710|0.035650|0.037710|2.30|N|N/Y|Y/Y|Y|N|
|JCT_USDT|0.006169|0.006105|0.006168|3.73|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.76|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|593.850000|593.330000|593.850000|1.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-25T23:15:02+00:00, last15m_closed_end=2026-10-25T23:15+00:00, prior8high=51.970000, depth_time=2026-10-25T23:15:15+00:00, book20_bid_proxy_usdt=415156, book20_ask_proxy_usdt=599221, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=13792146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T23:15:01+00:00, last15m_closed_end=2026-10-25T23:15+00:00, prior8high=0.039720, depth_time=2026-10-25T23:15:12+00:00, book20_bid_proxy_usdt=30933, book20_ask_proxy_usdt=28246, funding_indicative=-0.000326, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=1, 24h_change=-1.89%, turnover=19965052. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-25T23:15:01+00:00, last15m_closed_end=2026-10-25T23:15+00:00, prior8high=0.006991, depth_time=2026-10-25T23:15:07+00:00, book20_bid_proxy_usdt=45594, book20_ask_proxy_usdt=31281, funding_indicative=0.000112, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.51%, turnover=10054699. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-25T23:15:02+00:00, last15m_closed_end=2026-10-25T23:15+00:00, prior8high=0.000004, depth_time=2026-10-25T23:15:14+00:00, book20_bid_proxy_usdt=53004, book20_ask_proxy_usdt=48979, funding_indicative=0.000026, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=73762176. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T23:15:01+00:00, last15m_closed_end=2026-10-25T23:15+00:00, prior8high=602.000000, depth_time=2026-10-25T23:15:10+00:00, book20_bid_proxy_usdt=14659, book20_ask_proxy_usdt=32055, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=6641837. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
