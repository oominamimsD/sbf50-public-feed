# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T05:45:32Z**
- feed_generated_utc: 2026-10-26T05:45:35+00:00
- source_sha256: `40dfee91a88dfb03cd18c9a30073b7d3da68929c1e6191bb1fa5d264acc22d74`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T05:45+00:00, close=80200.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T05:00+00:00, close=80102.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T04:00+00:00, close=79565.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.033320|-13.31|173.11|-12.82|14318522|3.00|
|APR_USDT|0.036800|-10.91|35.09|-10.42|11578221|2.72|
|T_USDT|0.004821|-10.44|2.53|-9.95|5961727|4.15|
|XMR_USDT|589.650000|-2.89|1.22|-2.40|6844515|0.68|
|LIT_USDT|3.086400|-2.89|5.32|-2.40|6208928|0.32|
|WLD_USDT|0.443700|-2.82|-6.84|-2.33|74280441|2.25|
|DASH_USDT|51.100000|-2.49|6.72|-2.00|13566885|5.87|
|DOT_USDT|1.016100|-2.22|-4.98|-1.73|11207563|0.98|
|PUMPFUN_USDT|0.004217|-1.58|0.52|-1.09|17486438|2.37|
|STRK_USDT|0.045050|-1.50|-26.81|-1.01|9415066|2.22|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.036800|0.033880|0.036880|1.78|N|Y/Y|N/N|Y|N|
|DASH_USDT|51.100000|50.050000|51.100000|0.42|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.016100|1.011600|1.016300|0.52|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.033320|0.033760|0.033310|1.70|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|3.086400|3.000300|3.086400|1.21|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004217|0.004111|0.004217|0.37|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045050|0.044630|0.045050|2.50|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004821|0.004818|0.004824|1.71|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.443700|0.434800|0.443700|1.45|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|589.650000|588.910000|589.650000|0.17|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T05:45:02+00:00, last15m_closed_end=2026-10-26T05:45+00:00, prior8high=0.036500, depth_time=2026-10-26T05:45:10+00:00, book20_bid_proxy_usdt=58732, book20_ask_proxy_usdt=112225, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.91%, turnover=11578221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T05:45:02+00:00, last15m_closed_end=2026-10-26T05:45+00:00, prior8high=51.450000, depth_time=2026-10-26T05:45:20+00:00, book20_bid_proxy_usdt=640907, book20_ask_proxy_usdt=833186, funding_indicative=0.000075, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=13566885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T05:45:02+00:00, last15m_closed_end=2026-10-26T05:45+00:00, prior8high=1.024300, depth_time=2026-10-26T05:45:25+00:00, book20_bid_proxy_usdt=355385, book20_ask_proxy_usdt=276075, funding_indicative=-0.000011, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.22%, turnover=11207563. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T05:45:02+00:00, last15m_closed_end=2026-10-26T05:45+00:00, prior8high=0.038000, depth_time=2026-10-26T05:45:08+00:00, book20_bid_proxy_usdt=177874, book20_ask_proxy_usdt=74236, funding_indicative=-0.000398, next_funding_utc=2026-10-26T06:00:00+00:00, funding_cycle_h=1, 24h_change=-13.31%, turnover=14318522. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T05:45:02+00:00, last15m_closed_end=2026-10-26T05:45+00:00, prior8high=3.100900, depth_time=2026-10-26T05:45:18+00:00, book20_bid_proxy_usdt=18744, book20_ask_proxy_usdt=19064, funding_indicative=0.000050, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=6208928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T05:45:02+00:00, last15m_closed_end=2026-10-26T05:45+00:00, prior8high=0.004219, depth_time=2026-10-26T05:45:28+00:00, book20_bid_proxy_usdt=2260695, book20_ask_proxy_usdt=2545962, funding_indicative=0.000021, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.58%, turnover=17486438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T05:45:02+00:00, last15m_closed_end=2026-10-26T05:45+00:00, prior8high=0.045380, depth_time=2026-10-26T05:45:30+00:00, book20_bid_proxy_usdt=1109006, book20_ask_proxy_usdt=818343, funding_indicative=0.000046, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=9415066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T05:45:02+00:00, last15m_closed_end=2026-10-26T05:45+00:00, prior8high=0.004979, depth_time=2026-10-26T05:45:12+00:00, book20_bid_proxy_usdt=60977, book20_ask_proxy_usdt=61818, funding_indicative=-0.000759, next_funding_utc=2026-10-26T06:00:00+00:00, funding_cycle_h=1, 24h_change=-10.44%, turnover=5961727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T05:45:02+00:00, last15m_closed_end=2026-10-26T05:45+00:00, prior8high=0.446600, depth_time=2026-10-26T05:45:21+00:00, book20_bid_proxy_usdt=2845428, book20_ask_proxy_usdt=2125538, funding_indicative=-0.000005, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=74280441. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T05:45:02+00:00, last15m_closed_end=2026-10-26T05:45+00:00, prior8high=595.240000, depth_time=2026-10-26T05:45:11+00:00, book20_bid_proxy_usdt=32896, book20_ask_proxy_usdt=8442, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.89%, turnover=6844515. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
