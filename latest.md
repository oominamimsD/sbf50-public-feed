# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T21:00:31Z**
- feed_generated_utc: 2026-10-26T21:00:34+00:00
- source_sha256: `db0eaff38953b3b02c60a691755c3f3af1cc5f55d656afdc242c1d5c64bee5ab`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T21:00+00:00, close=79843, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T21:00+00:00, close=79843, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.026100|-5.36|112.54|-4.67|9607256|3.83|
|QNT_USDT|202.160000|-3.86|3.30|-3.17|121108072|1.98|
|BTW_USDT|1.151000|-3.73|-34.30|-3.04|20849563|3.47|
|LIT_USDT|3.009000|-3.50|-0.75|-2.81|5236051|0.33|
|PUMPFUN_USDT|0.004204|-2.86|-5.65|-2.17|22217076|2.38|
|FILECOIN_USDT|0.900800|-2.77|-10.98|-2.08|6108336|1.11|
|NEAR_USDT|4.453000|-2.62|-9.19|-1.93|118941432|2.25|
|WLD_USDT|0.435500|-2.13|-13.98|-1.44|73084668|2.30|
|PEPE_USDT|0.000004|-1.90|4.13|-1.21|85350712|0.23|
|DOT_USDT|1.004900|-1.73|-12.37|-1.04|10521524|0.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.151000|1.103200|1.151000|0.36|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.004900|0.999500|1.004900|0.51|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.900800|0.901000|0.900800|3.69|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.026100|0.025640|0.026100|0.86|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.009000|3.008700|3.009000|1.26|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.453000|4.442000|4.453000|0.62|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.56|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004204|0.004195|0.004204|0.09|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|202.160000|201.510000|202.160000|0.56|N|Y/N|N/N|Y|N|
|WLD_USDT|0.435500|0.435200|0.435500|0.33|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T20:59:59+00:00, last15m_closed_end=2026-10-26T21:00+00:00, prior8high=1.216600, depth_time=2026-10-26T21:00:13+00:00, book20_bid_proxy_usdt=13576, book20_ask_proxy_usdt=13828, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.73%, turnover=20849563. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T20:59:59+00:00, last15m_closed_end=2026-10-26T21:00+00:00, prior8high=1.012800, depth_time=2026-10-26T21:00:30+00:00, book20_bid_proxy_usdt=303562, book20_ask_proxy_usdt=279769, funding_indicative=-0.000012, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=10521524. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T21:00:00+00:00, last15m_closed_end=2026-10-26T21:00+00:00, prior8high=0.914300, depth_time=2026-10-26T21:00:16+00:00, book20_bid_proxy_usdt=1194911, book20_ask_proxy_usdt=1446621, funding_indicative=0.000081, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.77%, turnover=6108336. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T20:59:59+00:00, last15m_closed_end=2026-10-26T21:00+00:00, prior8high=0.026670, depth_time=2026-10-26T21:00:09+00:00, book20_bid_proxy_usdt=116070, book20_ask_proxy_usdt=116588, funding_indicative=-0.000604, next_funding_utc=2026-10-26T22:00:00+00:00, funding_cycle_h=1, 24h_change=-5.36%, turnover=9607256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T20:59:59+00:00, last15m_closed_end=2026-10-26T21:00+00:00, prior8high=3.080700, depth_time=2026-10-26T21:00:14+00:00, book20_bid_proxy_usdt=26307, book20_ask_proxy_usdt=24131, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.50%, turnover=5236051. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T20:59:59+00:00, last15m_closed_end=2026-10-26T21:00+00:00, prior8high=4.506000, depth_time=2026-10-26T21:00:23+00:00, book20_bid_proxy_usdt=3133210, book20_ask_proxy_usdt=5118582, funding_indicative=0.000074, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=118941432. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T20:59:59+00:00, last15m_closed_end=2026-10-26T21:00+00:00, prior8high=0.000004, depth_time=2026-10-26T21:00:27+00:00, book20_bid_proxy_usdt=58415, book20_ask_proxy_usdt=53723, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=85350712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T20:59:59+00:00, last15m_closed_end=2026-10-26T21:00+00:00, prior8high=0.004273, depth_time=2026-10-26T21:00:18+00:00, book20_bid_proxy_usdt=2502685, book20_ask_proxy_usdt=1875984, funding_indicative=0.000014, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=22217076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-26T20:59:59+00:00, last15m_closed_end=2026-10-26T21:00+00:00, prior8high=205.320000, depth_time=2026-10-26T21:00:11+00:00, book20_bid_proxy_usdt=67366, book20_ask_proxy_usdt=60128, funding_indicative=0.000065, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=121108072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T20:59:59+00:00, last15m_closed_end=2026-10-26T21:00+00:00, prior8high=0.443100, depth_time=2026-10-26T21:00:25+00:00, book20_bid_proxy_usdt=3289774, book20_ask_proxy_usdt=2950160, funding_indicative=-0.000126, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=73084668. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
