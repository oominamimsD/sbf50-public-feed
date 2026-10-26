# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T01:30:22Z**
- feed_generated_utc: 2026-10-26T01:30:25+00:00
- source_sha256: `f62e1a8ffb540a4513ffcab1076584d822b26548f971c52fbed88c101b83b4ce`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T01:30+00:00, close=79973.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T01:00+00:00, close=80135.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005793|-16.91|214.32|-16.12|10421292|1.73|
|T_USDT|0.004953|-7.98|5.33|-7.19|8020683|2.02|
|PEPE_USDT|0.000004|-2.82|10.82|-2.03|74126485|0.71|
|DASH_USDT|51.040000|-2.61|6.59|-1.82|13671682|1.96|
|BTW_USDT|1.617300|-2.50|-29.84|-1.71|12289756|1.24|
|WLD_USDT|0.446400|-2.23|-6.27|-1.44|73672609|2.24|
|XMR_USDT|594.990000|-2.02|2.14|-1.23|6597578|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.617300|1.606400|1.617300|1.00|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|51.040000|50.870000|51.110000|0.80|N|Y/Y|Y/N|Y|N|
|JCT_USDT|0.005793|0.005381|0.005779|1.39|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.67|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004953|0.004881|0.004953|1.27|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.446400|0.443500|0.446400|0.97|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|594.990000|589.580000|594.990000|1.42|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T01:30:02+00:00, last15m_closed_end=2026-10-26T01:30+00:00, prior8high=1.649100, depth_time=2026-10-26T01:30:16+00:00, book20_bid_proxy_usdt=27918, book20_ask_proxy_usdt=9856, funding_indicative=-0.007229, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=12289756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T01:30:02+00:00, last15m_closed_end=2026-10-26T01:30+00:00, prior8high=51.950000, depth_time=2026-10-26T01:30:13+00:00, book20_bid_proxy_usdt=734329, book20_ask_proxy_usdt=509946, funding_indicative=0.000085, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=13671682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T01:30:01+00:00, last15m_closed_end=2026-10-26T01:30+00:00, prior8high=0.006470, depth_time=2026-10-26T01:30:08+00:00, book20_bid_proxy_usdt=39798, book20_ask_proxy_usdt=37462, funding_indicative=0.000100, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-16.91%, turnover=10421292. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T01:30:02+00:00, last15m_closed_end=2026-10-26T01:30+00:00, prior8high=0.000004, depth_time=2026-10-26T01:30:12+00:00, book20_bid_proxy_usdt=50092, book20_ask_proxy_usdt=38800, funding_indicative=0.000082, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=74126485. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T01:30:01+00:00, last15m_closed_end=2026-10-26T01:30+00:00, prior8high=0.005323, depth_time=2026-10-26T01:30:09+00:00, book20_bid_proxy_usdt=71602, book20_ask_proxy_usdt=86428, funding_indicative=-0.002016, next_funding_utc=2026-10-26T02:00:00+00:00, funding_cycle_h=1, 24h_change=-7.98%, turnover=8020683. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T01:30:02+00:00, last15m_closed_end=2026-10-26T01:30+00:00, prior8high=0.452600, depth_time=2026-10-26T01:30:19+00:00, book20_bid_proxy_usdt=1800783, book20_ask_proxy_usdt=2341163, funding_indicative=0.000069, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=73672609. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T01:30:01+00:00, last15m_closed_end=2026-10-26T01:30+00:00, prior8high=596.220000, depth_time=2026-10-26T01:30:21+00:00, book20_bid_proxy_usdt=27682, book20_ask_proxy_usdt=12751, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.02%, turnover=6597578. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
