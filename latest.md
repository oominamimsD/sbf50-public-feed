# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T12:15:39Z**
- feed_generated_utc: 2026-11-09T12:15:41+00:00
- source_sha256: `e988eec454eede9febb1a94d4faf8f3ff469f5eecd53c07e81bf8de31552739e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T12:15+00:00, close=74504.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001504|-23.21|29.11|-21.20|6179559|0.67|
|JCT_USDT|0.008576|-12.79|72.24|-10.78|65646644|1.17|
|AKE_USDT|0.004791|-10.56|-47.69|-8.55|9248740|6.26|
|ASTER_USDT|0.635800|-6.47|-9.09|-4.46|5599760|1.57|
|XRP_USDT|1.086800|-5.96|-13.04|-3.95|277373965|1.84|
|ETH_USDT|2116.860000|-5.54|-6.57|-3.53|1560961408|0.05|
|HYPE_USDT|73.333000|-5.29|-16.37|-3.28|48848280|0.14|
|ZEC_USDT|1211.880000|-4.62|-2.10|-2.61|2290116216|0.08|
|NEAR_USDT|3.531000|-4.59|-18.47|-2.58|46022943|5.66|
|TRUMPOFFICIAL_USDT|1.139000|-4.20|-33.62|-2.19|6347255|8.78|
|HOT_USDT|0.000413|-3.86|14.84|-1.85|7709973|2.42|
|SOL_USDT|86.350000|-3.71|-8.87|-1.70|730098911|1.16|
|XLM_USDT|0.146350|-3.21|-13.07|-1.20|27702789|0.68|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004791|0.004949|0.004834|3.20|Y|N/N|N/Y|Y|N|
|ASTER_USDT|0.635800|0.623900|0.635700|0.32|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2116.860000|2098.500000|2116.700000|0.53|N|Y/Y|Y/Y|Y|N|
|HOT_USDT|0.000413|0.000414|0.000413|0.53|N|Y/N|N/N|Y|N|
|HYPE_USDT|73.333000|72.747000|73.333000|1.01|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008576|0.008306|0.008584|0.58|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.531000|3.480000|3.531000|0.50|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001504|0.001495|0.001504|1.42|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.350000|85.770000|86.350000|0.46|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.139000|1.124000|1.139000|1.24|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.146350|0.144930|0.146320|1.31|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.086800|1.076200|1.086400|0.82|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1211.880000|1192.400000|1212.230000|1.01|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T12:15:01+00:00, last15m_closed_end=2026-11-09T12:15+00:00, prior8high=0.005718, depth_time=2026-11-09T12:15:12+00:00, book20_bid_proxy_usdt=11810, book20_ask_proxy_usdt=12328, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.56%, turnover=9248740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T12:15:01+00:00, last15m_closed_end=2026-11-09T12:15+00:00, prior8high=0.633800, depth_time=2026-11-09T12:15:15+00:00, book20_bid_proxy_usdt=603789, book20_ask_proxy_usdt=845090, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.47%, turnover=5599760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T12:15:01+00:00, last15m_closed_end=2026-11-09T12:15+00:00, prior8high=2132.860000, depth_time=2026-11-09T12:15:20+00:00, book20_bid_proxy_usdt=2275096, book20_ask_proxy_usdt=4353210, funding_indicative=-0.000020, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.54%, turnover=1560961408. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-09T12:15:01+00:00, last15m_closed_end=2026-11-09T12:15+00:00, prior8high=0.000445, depth_time=2026-11-09T12:15:33+00:00, book20_bid_proxy_usdt=108134, book20_ask_proxy_usdt=121597, funding_indicative=-0.001407, next_funding_utc=2026-11-09T13:00:00+00:00, funding_cycle_h=1, 24h_change=-3.86%, turnover=7709973. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T12:15:01+00:00, last15m_closed_end=2026-11-09T12:15+00:00, prior8high=74.029000, depth_time=2026-11-09T12:15:23+00:00, book20_bid_proxy_usdt=49677, book20_ask_proxy_usdt=162993, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.29%, turnover=48848280. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T12:15:01+00:00, last15m_closed_end=2026-11-09T12:15+00:00, prior8high=0.009430, depth_time=2026-11-09T12:15:10+00:00, book20_bid_proxy_usdt=71781, book20_ask_proxy_usdt=74605, funding_indicative=0.001307, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.79%, turnover=65646644. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T12:15:01+00:00, last15m_closed_end=2026-11-09T12:15+00:00, prior8high=3.570000, depth_time=2026-11-09T12:15:28+00:00, book20_bid_proxy_usdt=2358951, book20_ask_proxy_usdt=2904524, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.59%, turnover=46022943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T12:15:01+00:00, last15m_closed_end=2026-11-09T12:15+00:00, prior8high=0.001571, depth_time=2026-11-09T12:15:07+00:00, book20_bid_proxy_usdt=24267, book20_ask_proxy_usdt=31837, funding_indicative=0.000039, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.21%, turnover=6179559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T12:15:01+00:00, last15m_closed_end=2026-11-09T12:15+00:00, prior8high=87.140000, depth_time=2026-11-09T12:15:35+00:00, book20_bid_proxy_usdt=13007574, book20_ask_proxy_usdt=12660620, funding_indicative=0.000020, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.71%, turnover=730098911. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T12:15:01+00:00, last15m_closed_end=2026-11-09T12:15+00:00, prior8high=1.144000, depth_time=2026-11-09T12:15:31+00:00, book20_bid_proxy_usdt=3154742, book20_ask_proxy_usdt=2295963, funding_indicative=0.000001, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.20%, turnover=6347255. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-09T12:15:01+00:00, last15m_closed_end=2026-11-09T12:15+00:00, prior8high=0.146930, depth_time=2026-11-09T12:15:37+00:00, book20_bid_proxy_usdt=68974, book20_ask_proxy_usdt=170286, funding_indicative=-0.000019, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=27702789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T12:15:01+00:00, last15m_closed_end=2026-11-09T12:15+00:00, prior8high=1.093100, depth_time=2026-11-09T12:15:17+00:00, book20_bid_proxy_usdt=2221011, book20_ask_proxy_usdt=3314738, funding_indicative=0.000096, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.96%, turnover=277373965. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T12:15:01+00:00, last15m_closed_end=2026-11-09T12:15+00:00, prior8high=1225.880000, depth_time=2026-11-09T12:15:25+00:00, book20_bid_proxy_usdt=166908, book20_ask_proxy_usdt=600249, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.62%, turnover=2290116216. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
