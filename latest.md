# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T09:30:48Z**
- feed_generated_utc: 2026-11-05T09:30:51+00:00
- source_sha256: `0a0d0f3d7f72bac04b3d3fbad9341175f15c4ac5a7d65d231e43aeef3d30db85`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T09:30+00:00, close=80315, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T09:00+00:00, close=80496.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T08:00+00:00, close=80362.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002196|-21.85|-89.07|-21.90|16758786|9.10|
|TRUMPOFFICIAL_USDT|1.269000|-10.88|-25.74|-10.93|25725762|7.88|
|BTW_USDT|1.024900|-6.74|-41.02|-6.79|5255528|2.93|
|ZRO_USDT|1.789300|-4.04|4.51|-4.09|7527116|0.56|
|FARTCOIN_USDT|0.125160|-3.80|-4.45|-3.85|16417704|3.20|
|WLD_USDT|0.377500|-3.72|-12.77|-3.77|62787903|2.65|
|PEPE_USDT|0.000005|-3.16|3.27|-3.21|124932185|0.20|
|NEAR_USDT|4.019000|-3.01|-13.17|-3.06|73602764|2.49|
|HYPE_USDT|83.454000|-2.85|4.50|-2.90|79279255|0.12|
|FET_USDT|0.159100|-2.57|-12.43|-2.62|7380919|6.28|
|PENGU_USDT|0.007254|-2.52|-6.47|-2.57|6726644|1.38|
|ENA_USDT|0.181440|-2.33|-7.51|-2.38|92503499|0.55|
|SEI_USDT|0.049100|-2.21|-7.09|-2.26|5949264|2.04|
|AVAX_USDT|8.752000|-2.17|-1.51|-2.22|22126609|1.14|
|DOT_USDT|0.957600|-1.17|-4.58|-1.22|12114931|1.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002196|0.002431|0.002196|7.22|Y|Y/Y|Y/Y|N|Y|
|AVAX_USDT|8.752000|8.721000|8.752000|2.62|N|N/N|N/N|N|N|
|BTW_USDT|1.024900|1.024000|1.025400|1.84|N|Y/Y|Y/Y|N|N|
|DOT_USDT|0.957600|0.941500|0.957600|2.82|N|N/Y|Y/N|N|N|
|ENA_USDT|0.181440|0.178620|0.181510|0.68|N|N/N|N/N|N|N|
|FARTCOIN_USDT|0.125160|0.123350|0.125260|0.30|N|N/N|N/N|N|N|
|FET_USDT|0.159100|0.158800|0.159100|2.76|N|Y/Y|N/N|N|N|
|HYPE_USDT|83.454000|83.126000|83.454000|1.73|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|4.019000|4.005000|4.019000|1.23|N|N/N|Y/Y|N|N|
|PENGU_USDT|0.007254|0.007163|0.007253|0.48|N|N/Y|Y/N|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.65|N|N/Y|N/N|N|N|
|SEI_USDT|0.049100|0.048400|0.049100|0.93|N|N/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.269000|1.246000|1.269000|1.98|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.377500|0.373100|0.377500|1.00|N|N/Y|Y/Y|N|N|
|ZRO_USDT|1.789300|1.790700|1.789300|4.63|Y|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=0.002757, depth_time=2026-11-05T09:30:07+00:00, book20_bid_proxy_usdt=35856, book20_ask_proxy_usdt=38094, funding_indicative=-0.000542, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.85%, turnover=16758786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=8.808000, depth_time=2026-11-05T09:30:43+00:00, book20_bid_proxy_usdt=1480546, book20_ask_proxy_usdt=1105723, funding_indicative=0.000077, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=22126609. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=1.060000, depth_time=2026-11-05T09:30:13+00:00, book20_bid_proxy_usdt=14554, book20_ask_proxy_usdt=24030, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.74%, turnover=5255528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=0.960100, depth_time=2026-11-05T09:30:46+00:00, book20_bid_proxy_usdt=578212, book20_ask_proxy_usdt=630428, funding_indicative=-0.000034, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=12114931. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=0.181970, depth_time=2026-11-05T09:30:38+00:00, book20_bid_proxy_usdt=117135, book20_ask_proxy_usdt=188416, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=92503499. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=0.125790, depth_time=2026-11-05T09:30:18+00:00, book20_bid_proxy_usdt=65428, book20_ask_proxy_usdt=69935, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.80%, turnover=16417704. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=0.160700, depth_time=2026-11-05T09:30:31+00:00, book20_bid_proxy_usdt=2050304, book20_ask_proxy_usdt=1087416, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.57%, turnover=7380919. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=84.033000, depth_time=2026-11-05T09:30:29+00:00, book20_bid_proxy_usdt=63891, book20_ask_proxy_usdt=175540, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.85%, turnover=79279255. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=4.051000, depth_time=2026-11-05T09:30:27+00:00, book20_bid_proxy_usdt=5719781, book20_ask_proxy_usdt=4537486, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.01%, turnover=73602764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=0.007286, depth_time=2026-11-05T09:30:34+00:00, book20_bid_proxy_usdt=198106, book20_ask_proxy_usdt=215112, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=6726644. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=0.000005, depth_time=2026-11-05T09:30:24+00:00, book20_bid_proxy_usdt=43697, book20_ask_proxy_usdt=32012, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=124932185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=0.049230, depth_time=2026-11-05T09:30:41+00:00, book20_bid_proxy_usdt=360634, book20_ask_proxy_usdt=362759, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=5949264. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=1.268000, depth_time=2026-11-05T09:30:09+00:00, book20_bid_proxy_usdt=1399101, book20_ask_proxy_usdt=1236631, funding_indicative=-0.000359, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.88%, turnover=25725762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=0.382100, depth_time=2026-11-05T09:30:21+00:00, book20_bid_proxy_usdt=3274880, book20_ask_proxy_usdt=2502534, funding_indicative=-0.000260, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=62787903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T09:30:01+00:00, last15m_closed_end=2026-11-05T09:30+00:00, prior8high=1.822000, depth_time=2026-11-05T09:30:15+00:00, book20_bid_proxy_usdt=29925, book20_ask_proxy_usdt=19884, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.04%, turnover=7527116. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
