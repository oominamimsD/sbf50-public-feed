# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T14:45:23Z**
- feed_generated_utc: 2026-10-26T14:45:26+00:00
- source_sha256: `5d4a328ccf0437f5f74f8f6707e03492831f50f7ea5ee66e5c8e8da88df22d2d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1186; contracts: 1178; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T14:45+00:00, close=80032.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T14:00+00:00, close=79668.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.027730|-27.86|127.29|-27.16|11847268|7.21|
|BTW_USDT|1.268500|-23.53|-44.97|-22.83|12223522|3.94|
|APR_USDT|0.032380|-21.61|18.86|-20.91|6030260|3.09|
|WLD_USDT|0.443100|-2.95|-6.97|-2.25|62753117|2.26|
|LIT_USDT|3.098900|-2.50|5.75|-1.80|5248328|0.32|
|XMR_USDT|594.040000|-2.17|1.98|-1.47|5571284|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.032380|0.031070|0.032380|2.49|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.268500|1.279100|1.273600|3.89|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.027730|0.027330|0.027730|0.75|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.098900|3.039700|3.098900|1.87|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.443100|0.435800|0.443100|1.44|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|594.040000|590.710000|594.040000|0.63|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T14:45:00+00:00, last15m_closed_end=2026-10-26T14:45+00:00, prior8high=0.037130, depth_time=2026-10-26T14:45:14+00:00, book20_bid_proxy_usdt=54092, book20_ask_proxy_usdt=49834, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.61%, turnover=6030260. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T14:45:01+00:00, last15m_closed_end=2026-10-26T14:45+00:00, prior8high=1.462300, depth_time=2026-10-26T14:45:12+00:00, book20_bid_proxy_usdt=21655, book20_ask_proxy_usdt=13803, funding_indicative=-0.018116, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.53%, turnover=12223522. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T14:45:00+00:00, last15m_closed_end=2026-10-26T14:45+00:00, prior8high=0.029430, depth_time=2026-10-26T14:45:09+00:00, book20_bid_proxy_usdt=66812, book20_ask_proxy_usdt=106552, funding_indicative=-0.000997, next_funding_utc=2026-10-26T15:00:00+00:00, funding_cycle_h=1, 24h_change=-27.86%, turnover=11847268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T14:45:01+00:00, last15m_closed_end=2026-10-26T14:45+00:00, prior8high=3.115900, depth_time=2026-10-26T14:45:19+00:00, book20_bid_proxy_usdt=16636, book20_ask_proxy_usdt=16478, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=5248328. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T14:45:01+00:00, last15m_closed_end=2026-10-26T14:45+00:00, prior8high=0.444400, depth_time=2026-10-26T14:45:17+00:00, book20_bid_proxy_usdt=2311908, book20_ask_proxy_usdt=3082001, funding_indicative=-0.000148, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.95%, turnover=62753117. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T14:45:01+00:00, last15m_closed_end=2026-10-26T14:45+00:00, prior8high=594.690000, depth_time=2026-10-26T14:45:20+00:00, book20_bid_proxy_usdt=19191, book20_ask_proxy_usdt=26245, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=5571284. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
