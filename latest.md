# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T21:45:35Z**
- feed_generated_utc: 2026-11-08T21:45:37+00:00
- source_sha256: `876de6faed554e7d9c9b6df659eb43511f3a062d313cd38e9578ff71e035f47c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T21:45+00:00, close=75565.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T21:00+00:00, close=75718.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001669|-14.78|43.28|-14.16|14576682|0.60|
|ZEC_USDT|1212.550000|-4.57|-2.04|-3.95|1542382935|1.57|
|NEAR_USDT|3.585000|-3.13|-17.22|-2.51|33093888|2.79|
|HYPE_USDT|75.419000|-2.59|-13.99|-1.97|24769080|0.13|
|DASH_USDT|46.600000|-2.53|-4.11|-1.91|13408993|2.15|
|TRUMPOFFICIAL_USDT|1.161000|-2.35|-32.34|-1.73|5147287|8.61|
|LIT_USDT|3.122300|-2.22|-3.33|-1.60|7900591|0.32|
|WLD_USDT|0.319600|-1.93|-19.23|-1.31|23493700|3.13|
|INJ_USDT|7.985000|-1.79|11.02|-1.17|16822839|1.25|
|ONDO_USDT|0.355700|-1.74|-12.47|-1.12|7739551|2.81|
|TAO_USDT|222.200000|-1.69|-5.38|-1.07|21464407|1.80|
|ARB_USDT|0.167120|-1.63|0.56|-1.01|18217836|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.167120|0.166560|0.167120|0.76|N|Y/Y|N/N|Y|N|
|DASH_USDT|46.600000|46.790000|46.600000|1.31|Y|N/N|N/N|Y|N|
|HYPE_USDT|75.419000|75.851000|75.404000|3.47|Y|Y/Y|Y/Y|Y|Y|
|INJ_USDT|7.985000|8.022000|7.985000|0.77|N|Y/Y|Y/N|Y|N|
|LIT_USDT|3.122300|3.111500|3.122300|10.40|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.585000|3.589000|3.585000|2.44|Y|Y/Y|Y/Y|Y|Y|
|ONDO_USDT|0.355700|0.355700|0.355700|2.82|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001669|0.001657|0.001669|0.96|N|Y/Y|N/N|Y|N|
|TAO_USDT|222.200000|222.550000|222.200000|0.82|N|Y/N|Y/N|Y|N|
|TRUMPOFFICIAL_USDT|1.161000|1.166000|1.161000|2.27|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.319600|0.319600|0.319700|0.88|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1212.550000|1225.210000|1212.670000|1.83|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-08T21:45:01+00:00, last15m_closed_end=2026-11-08T21:45+00:00, prior8high=0.167590, depth_time=2026-11-08T21:45:34+00:00, book20_bid_proxy_usdt=37050, book20_ask_proxy_usdt=92830, funding_indicative=0.000005, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=18217836. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-08T21:45:01+00:00, last15m_closed_end=2026-11-08T21:45+00:00, prior8high=47.690000, depth_time=2026-11-08T21:45:16+00:00, book20_bid_proxy_usdt=536716, book20_ask_proxy_usdt=500243, funding_indicative=0.000100, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=13408993. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-08T21:45:01+00:00, last15m_closed_end=2026-11-08T21:45+00:00, prior8high=77.158000, depth_time=2026-11-08T21:45:14+00:00, book20_bid_proxy_usdt=59341, book20_ask_proxy_usdt=167370, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=24769080. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-08T21:45:01+00:00, last15m_closed_end=2026-11-08T21:45+00:00, prior8high=8.145000, depth_time=2026-11-08T21:45:22+00:00, book20_bid_proxy_usdt=98213, book20_ask_proxy_usdt=129895, funding_indicative=-0.000051, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=16822839. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-08T21:45:01+00:00, last15m_closed_end=2026-11-08T21:45+00:00, prior8high=3.212800, depth_time=2026-11-08T21:45:22+00:00, book20_bid_proxy_usdt=31475, book20_ask_proxy_usdt=21689, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=7900591. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T21:45:01+00:00, last15m_closed_end=2026-11-08T21:45+00:00, prior8high=3.666000, depth_time=2026-11-08T21:45:12+00:00, book20_bid_proxy_usdt=3019437, book20_ask_proxy_usdt=2988027, funding_indicative=0.000100, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.13%, turnover=33093888. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T21:45:01+00:00, last15m_closed_end=2026-11-08T21:45+00:00, prior8high=0.361200, depth_time=2026-11-08T21:45:28+00:00, book20_bid_proxy_usdt=1279151, book20_ask_proxy_usdt=1430592, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=7739551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T21:45:01+00:00, last15m_closed_end=2026-11-08T21:45+00:00, prior8high=0.001798, depth_time=2026-11-08T21:45:07+00:00, book20_bid_proxy_usdt=11781, book20_ask_proxy_usdt=8594, funding_indicative=-0.000034, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-14.78%, turnover=14576682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-08T21:45:01+00:00, last15m_closed_end=2026-11-08T21:45+00:00, prior8high=225.170000, depth_time=2026-11-08T21:45:32+00:00, book20_bid_proxy_usdt=70989, book20_ask_proxy_usdt=85266, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.69%, turnover=21464407. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-08T21:45:01+00:00, last15m_closed_end=2026-11-08T21:45+00:00, prior8high=1.179000, depth_time=2026-11-08T21:45:19+00:00, book20_bid_proxy_usdt=2509501, book20_ask_proxy_usdt=2508246, funding_indicative=-0.000132, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=5147287. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T21:45:01+00:00, last15m_closed_end=2026-11-08T21:45+00:00, prior8high=0.324400, depth_time=2026-11-08T21:45:24+00:00, book20_bid_proxy_usdt=3369373, book20_ask_proxy_usdt=3087271, funding_indicative=-0.000063, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=23493700. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T21:45:01+00:00, last15m_closed_end=2026-11-08T21:45+00:00, prior8high=1268.660000, depth_time=2026-11-08T21:45:10+00:00, book20_bid_proxy_usdt=105886, book20_ask_proxy_usdt=180533, funding_indicative=0.000018, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.57%, turnover=1542382935. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
