# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T23:45:21Z**
- feed_generated_utc: 2026-10-25T23:45:24+00:00
- source_sha256: `8f915ca1e370244f0c94391e6377e7703218fec61c16c215c9139d59c36e6e93`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T23:45+00:00, close=80027.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T23:00+00:00, close=80429.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.006134|-12.01|232.82|-11.29|10229581|1.63|
|USELESS_USDT|0.167460|-2.96|18.39|-2.24|5106184|1.19|
|XMR_USDT|590.490000|-2.76|1.37|-2.04|6845672|3.05|
|PEPE_USDT|0.000004|-2.39|11.31|-1.67|76861366|0.23|
|T_USDT|0.005270|-2.09|12.07|-1.37|8621677|5.69|
|DASH_USDT|51.480000|-1.77|7.51|-1.05|14111356|1.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.480000|51.260000|51.480000|1.74|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.006134|0.006081|0.006123|2.16|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.73|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.005270|0.005155|0.005270|0.72|N|Y/Y|N/N|Y|N|
|USELESS_USDT|0.167460|0.167220|0.167460|4.23|N|Y/Y|N/N|Y|N|
|XMR_USDT|590.490000|592.340000|590.490000|2.45|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-25T23:45:01+00:00, last15m_closed_end=2026-10-25T23:45+00:00, prior8high=51.970000, depth_time=2026-10-25T23:45:20+00:00, book20_bid_proxy_usdt=805477, book20_ask_proxy_usdt=542942, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=14111356. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-25T23:45:00+00:00, last15m_closed_end=2026-10-25T23:45+00:00, prior8high=0.006991, depth_time=2026-10-25T23:45:07+00:00, book20_bid_proxy_usdt=42253, book20_ask_proxy_usdt=25035, funding_indicative=0.000058, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.01%, turnover=10229581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-25T23:45:00+00:00, last15m_closed_end=2026-10-25T23:45+00:00, prior8high=0.000004, depth_time=2026-10-25T23:45:15+00:00, book20_bid_proxy_usdt=59151, book20_ask_proxy_usdt=72288, funding_indicative=0.000038, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=76861366. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-25T23:45:00+00:00, last15m_closed_end=2026-10-25T23:45+00:00, prior8high=0.005411, depth_time=2026-10-25T23:45:17+00:00, book20_bid_proxy_usdt=68095, book20_ask_proxy_usdt=53895, funding_indicative=-0.005172, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=1, 24h_change=-2.09%, turnover=8621677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T23:45:01+00:00, last15m_closed_end=2026-10-25T23:45+00:00, prior8high=0.171640, depth_time=2026-10-25T23:45:09+00:00, book20_bid_proxy_usdt=15758, book20_ask_proxy_usdt=16831, funding_indicative=0.000050, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.96%, turnover=5106184. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-25T23:45:00+00:00, last15m_closed_end=2026-10-25T23:45+00:00, prior8high=601.720000, depth_time=2026-10-25T23:45:09+00:00, book20_bid_proxy_usdt=14676, book20_ask_proxy_usdt=58378, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=6845672. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
