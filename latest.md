# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T18:15:17Z**
- feed_generated_utc: 2026-11-09T18:15:18+00:00
- source_sha256: `0746cafc7403dd2a4e37ad0b84a73f33c2c0db27185e2ce2f5c237b123dab605`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T18:15+00:00, close=74740.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T18:00+00:00, close=74755.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T16:00+00:00, close=75500.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1165.710000|-4.89|-7.04|-3.89|2436546533|0.09|
|ONE_USDT|0.001445|-2.27|29.50|-1.27|5091652|0.69|
|XRP_USDT|1.089300|-2.20|-12.74|-1.20|305045381|1.84|
|QNT_USDT|195.830000|-2.10|-3.26|-1.10|43605947|0.51|
|TRUMPOFFICIAL_USDT|1.119000|-2.01|-31.60|-1.01|5775541|8.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ONE_USDT|0.001445|0.001445|0.001445|0.15|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.830000|193.980000|195.830000|1.37|N|Y/Y|N/N|Y|N|
|TRUMPOFFICIAL_USDT|1.119000|1.113000|1.119000|0.99|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.089300|1.090500|1.089500|1.42|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1165.710000|1163.250000|1166.190000|0.73|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ONE_USDT: quote_utc=2026-11-09T18:15:01+00:00, last15m_closed_end=2026-11-09T18:15+00:00, prior8high=0.001511, depth_time=2026-11-09T18:15:09+00:00, book20_bid_proxy_usdt=19346, book20_ask_proxy_usdt=26577, funding_indicative=-0.000572, next_funding_utc=2026-11-09T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=5091652. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-09T18:15:02+00:00, last15m_closed_end=2026-11-09T18:15+00:00, prior8high=200.320000, depth_time=2026-11-09T18:15:12+00:00, book20_bid_proxy_usdt=69992, book20_ask_proxy_usdt=34795, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=43605947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T18:15:02+00:00, last15m_closed_end=2026-11-09T18:15+00:00, prior8high=1.142000, depth_time=2026-11-09T18:15:16+00:00, book20_bid_proxy_usdt=3285157, book20_ask_proxy_usdt=2893769, funding_indicative=-0.000197, next_funding_utc=2026-11-09T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=5775541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T18:15:01+00:00, last15m_closed_end=2026-11-09T18:15+00:00, prior8high=1.114000, depth_time=2026-11-09T18:15:11+00:00, book20_bid_proxy_usdt=4992751, book20_ask_proxy_usdt=3406120, funding_indicative=0.000056, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=305045381. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T18:15:01+00:00, last15m_closed_end=2026-11-09T18:15+00:00, prior8high=1226.510000, depth_time=2026-11-09T18:15:07+00:00, book20_bid_proxy_usdt=277444, book20_ask_proxy_usdt=142266, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.89%, turnover=2436546533. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
