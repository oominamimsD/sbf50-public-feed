# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T12:15:25Z**
- feed_generated_utc: 2026-10-20T12:15:28+00:00
- source_sha256: `1366b1ea09d03e59da3b142da639dd394369d3cfea6c284d80de253d05baed5d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T12:15+00:00, close=81338, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.067953|-21.92|307.83|-21.23|8765594|0.88|
|NEAR_USDT|4.675000|-4.66|-15.75|-3.97|164838660|2.14|
|SAND_USDT|0.056660|-4.19|-8.74|-3.50|5344107|1.76|
|ARB_USDT|0.188400|-3.69|-0.03|-3.00|97191667|0.53|
|Q_USDT|0.122108|-3.07|296.57|-2.38|6789771|1.80|
|UNI_USDT|7.114000|-2.38|-4.09|-1.69|9667762|1.41|
|LTC_USDT|58.440000|-2.15|-7.17|-1.46|12961271|1.71|
|TAO_USDT|263.130000|-1.92|-8.08|-1.23|58005131|0.76|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.067953|0.066520|0.068049|0.74|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.188400|0.188340|0.188410|3.96|N|Y/Y|Y/N|Y|N|
|LTC_USDT|58.440000|58.250000|58.440000|1.14|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.675000|4.630000|4.675000|1.08|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.122108|0.110892|0.122156|4.17|N|N/Y|N/N|Y|N|
|SAND_USDT|0.056660|0.056510|0.056660|3.10|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.130000|262.210000|263.150000|2.94|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.114000|7.106000|7.114000|1.54|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T12:15:03+00:00, last15m_closed_end=2026-10-20T12:15+00:00, prior8high=0.071607, depth_time=2026-10-20T12:15:07+00:00, book20_bid_proxy_usdt=6178, book20_ask_proxy_usdt=9408, funding_indicative=0.000047, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.92%, turnover=8765594. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T12:15:03+00:00, last15m_closed_end=2026-10-20T12:15+00:00, prior8high=0.190320, depth_time=2026-10-20T12:15:15+00:00, book20_bid_proxy_usdt=58388, book20_ask_proxy_usdt=89623, funding_indicative=0.000099, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=97191667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-20T12:15:03+00:00, last15m_closed_end=2026-10-20T12:15+00:00, prior8high=59.150000, depth_time=2026-10-20T12:15:22+00:00, book20_bid_proxy_usdt=1682098, book20_ask_proxy_usdt=1458031, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=12961271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T12:15:03+00:00, last15m_closed_end=2026-10-20T12:15+00:00, prior8high=4.710000, depth_time=2026-10-20T12:15:10+00:00, book20_bid_proxy_usdt=3933386, book20_ask_proxy_usdt=3058516, funding_indicative=0.000047, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.66%, turnover=164838660. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T12:15:03+00:00, last15m_closed_end=2026-10-20T12:15+00:00, prior8high=0.133630, depth_time=2026-10-20T12:15:17+00:00, book20_bid_proxy_usdt=24262, book20_ask_proxy_usdt=15890, funding_indicative=0.000050, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=6789771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T12:15:03+00:00, last15m_closed_end=2026-10-20T12:15+00:00, prior8high=0.057080, depth_time=2026-10-20T12:15:10+00:00, book20_bid_proxy_usdt=1045676, book20_ask_proxy_usdt=1232169, funding_indicative=-0.001853, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.19%, turnover=5344107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T12:15:03+00:00, last15m_closed_end=2026-10-20T12:15+00:00, prior8high=264.440000, depth_time=2026-10-20T12:15:24+00:00, book20_bid_proxy_usdt=81533, book20_ask_proxy_usdt=103252, funding_indicative=0.000036, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=58005131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T12:15:03+00:00, last15m_closed_end=2026-10-20T12:15+00:00, prior8high=7.169000, depth_time=2026-10-20T12:15:18+00:00, book20_bid_proxy_usdt=2400770, book20_ask_proxy_usdt=2295082, funding_indicative=0.000047, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=9667762. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
