# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T20:45:32Z**
- feed_generated_utc: 2026-10-26T20:45:36+00:00
- source_sha256: `dd20074d29fc95b3e734400f306eca427b7f27e43ca70d10d79798e5e3ad6c49`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T20:45+00:00, close=79808.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.025800|-6.45|110.09|-5.72|9573331|3.88|
|BTW_USDT|1.126300|-5.80|-35.71|-5.07|20728733|4.43|
|QNT_USDT|201.990000|-3.94|3.21|-3.21|120434419|1.98|
|LIT_USDT|3.011600|-3.42|-0.66|-2.69|5169278|0.33|
|PUMPFUN_USDT|0.004202|-2.91|-5.70|-2.18|22195093|4.76|
|NEAR_USDT|4.463000|-2.40|-8.99|-1.67|118252102|2.24|
|WLD_USDT|0.435800|-2.06|-13.92|-1.33|72825162|2.29|
|FILECOIN_USDT|0.901800|-2.05|-10.88|-1.32|6083569|1.11|
|DOT_USDT|1.001800|-2.03|-12.64|-1.30|10458044|1.00|
|FET_USDT|0.173200|-1.92|-8.35|-1.19|5994397|5.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.126300|1.103200|1.126300|0.43|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.001800|0.999500|1.001800|0.65|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.173200|0.173300|0.173200|1.30|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.901800|0.904100|0.901800|1.56|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.025800|0.025780|0.025800|1.84|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.011600|3.018600|3.011600|1.49|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.463000|4.442000|4.463000|0.21|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004202|0.004209|0.004202|0.22|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|201.990000|201.780000|201.990000|0.62|N|N/N|N/N|Y|N|
|WLD_USDT|0.435800|0.435200|0.435800|0.39|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T20:45:00+00:00, last15m_closed_end=2026-10-26T20:45+00:00, prior8high=1.260500, depth_time=2026-10-26T20:45:11+00:00, book20_bid_proxy_usdt=11976, book20_ask_proxy_usdt=10296, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.80%, turnover=20728733. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T20:45:00+00:00, last15m_closed_end=2026-10-26T20:45+00:00, prior8high=1.012900, depth_time=2026-10-26T20:45:29+00:00, book20_bid_proxy_usdt=396830, book20_ask_proxy_usdt=419016, funding_indicative=0.000007, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=10458044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-26T20:45:00+00:00, last15m_closed_end=2026-10-26T20:45+00:00, prior8high=0.175200, depth_time=2026-10-26T20:45:30+00:00, book20_bid_proxy_usdt=2086260, book20_ask_proxy_usdt=1188764, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=5994397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T20:45:00+00:00, last15m_closed_end=2026-10-26T20:45+00:00, prior8high=0.914300, depth_time=2026-10-26T20:45:24+00:00, book20_bid_proxy_usdt=1000848, book20_ask_proxy_usdt=1201679, funding_indicative=0.000074, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=6083569. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T20:45:00+00:00, last15m_closed_end=2026-10-26T20:45+00:00, prior8high=0.026670, depth_time=2026-10-26T20:45:08+00:00, book20_bid_proxy_usdt=79157, book20_ask_proxy_usdt=84578, funding_indicative=-0.000688, next_funding_utc=2026-10-26T21:00:00+00:00, funding_cycle_h=1, 24h_change=-6.45%, turnover=9573331. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T20:45:00+00:00, last15m_closed_end=2026-10-26T20:45+00:00, prior8high=3.080700, depth_time=2026-10-26T20:45:16+00:00, book20_bid_proxy_usdt=20994, book20_ask_proxy_usdt=23472, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.42%, turnover=5169278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T20:45:00+00:00, last15m_closed_end=2026-10-26T20:45+00:00, prior8high=4.512000, depth_time=2026-10-26T20:45:21+00:00, book20_bid_proxy_usdt=4315445, book20_ask_proxy_usdt=2810362, funding_indicative=0.000073, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=118252102. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T20:45:00+00:00, last15m_closed_end=2026-10-26T20:45+00:00, prior8high=0.004278, depth_time=2026-10-26T20:45:18+00:00, book20_bid_proxy_usdt=2563656, book20_ask_proxy_usdt=1515374, funding_indicative=0.000026, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.91%, turnover=22195093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-26T20:45:00+00:00, last15m_closed_end=2026-10-26T20:45+00:00, prior8high=205.320000, depth_time=2026-10-26T20:45:13+00:00, book20_bid_proxy_usdt=90052, book20_ask_proxy_usdt=55435, funding_indicative=0.000060, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.94%, turnover=120434419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T20:45:00+00:00, last15m_closed_end=2026-10-26T20:45+00:00, prior8high=0.443100, depth_time=2026-10-26T20:45:24+00:00, book20_bid_proxy_usdt=2777265, book20_ask_proxy_usdt=2273524, funding_indicative=-0.000132, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.06%, turnover=72825162. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
