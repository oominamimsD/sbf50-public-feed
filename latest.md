# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T06:00:41Z**
- feed_generated_utc: 2026-11-09T06:00:42+00:00
- source_sha256: `d39beb5a20d9f33f767554eb83e469355ef2e36a704c61245a6c4f2b147b4149`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T06:00+00:00, close=74440.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T06:00+00:00, close=74440.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001625|-17.00|39.54|-14.90|10172188|0.61|
|AKE_USDT|0.004604|-14.05|-49.73|-11.95|11531853|4.35|
|JCT_USDT|0.009168|-6.77|84.13|-4.67|69128396|2.18|
|ASTER_USDT|0.637400|-6.23|-8.86|-4.13|5206351|3.14|
|XRP_USDT|1.093900|-5.35|-12.48|-3.25|240331677|0.91|
|PUMPFUN_USDT|0.003544|-5.16|-15.97|-3.06|9432742|2.82|
|ETH_USDT|2127.800000|-5.05|-6.09|-2.95|1254961383|0.05|
|HYPE_USDT|73.893000|-4.56|-15.73|-2.46|40421787|0.14|
|TAO_USDT|215.900000|-4.48|-8.06|-2.38|33155520|1.39|
|TRUMPOFFICIAL_USDT|1.138000|-4.28|-33.68|-2.18|6883797|8.78|
|NEAR_USDT|3.552000|-4.02|-17.98|-1.92|40003725|2.81|
|ZEC_USDT|1219.990000|-3.98|-1.44|-1.88|2082086833|0.08|
|AVAX_USDT|7.928000|-3.77|-9.55|-1.67|16583760|1.26|
|XLM_USDT|0.145750|-3.61|-13.42|-1.51|25194920|0.69|
|SOL_USDT|86.570000|-3.46|-8.64|-1.36|565150529|1.16|
|ADA_USDT|0.174700|-3.32|-9.48|-1.22|18665939|5.72|
|DOT_USDT|0.862800|-3.15|-8.89|-1.05|7758635|2.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004604|0.004549|0.004604|1.21|N|Y/Y|Y/N|Y|N|
|ASTER_USDT|0.637400|0.637000|0.637400|1.29|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|7.928000|7.939000|7.928000|1.44|Y|Y/Y|Y/Y|Y|Y|
|ETH_USDT|2127.800000|2126.320000|2127.800000|0.73|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.893000|74.125000|73.893000|1.24|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009168|0.007861|0.009174|0.73|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.552000|3.559000|3.552000|0.71|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001625|0.001620|0.001625|1.59|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003544|0.003538|0.003544|0.21|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.570000|86.710000|86.570000|0.49|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|215.900000|215.910000|215.900000|0.97|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.138000|1.138000|1.138000|0.10|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.145750|0.145960|0.145750|1.43|Y|Y/Y|Y/Y|Y|Y|
|XRP_USDT|1.093900|1.095800|1.093900|1.83|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1219.990000|1222.260000|1219.980000|1.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=0.004912, depth_time=2026-11-09T06:00:08+00:00, book20_bid_proxy_usdt=57854, book20_ask_proxy_usdt=34454, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.05%, turnover=11531853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=0.643200, depth_time=2026-11-09T06:00:09+00:00, book20_bid_proxy_usdt=534927, book20_ask_proxy_usdt=737818, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.23%, turnover=5206351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=8.059000, depth_time=2026-11-09T06:00:34+00:00, book20_bid_proxy_usdt=943165, book20_ask_proxy_usdt=2302994, funding_indicative=0.000074, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.77%, turnover=16583760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=2145.900000, depth_time=2026-11-09T06:00:19+00:00, book20_bid_proxy_usdt=4702638, book20_ask_proxy_usdt=2715954, funding_indicative=-0.000040, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.05%, turnover=1254961383. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=75.000000, depth_time=2026-11-09T06:00:21+00:00, book20_bid_proxy_usdt=85270, book20_ask_proxy_usdt=82906, funding_indicative=0.000045, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.56%, turnover=40421787. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=0.010737, depth_time=2026-11-09T06:00:11+00:00, book20_bid_proxy_usdt=20049, book20_ask_proxy_usdt=26941, funding_indicative=0.001657, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.77%, turnover=69128396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=3.638000, depth_time=2026-11-09T06:00:29+00:00, book20_bid_proxy_usdt=1987234, book20_ask_proxy_usdt=3203662, funding_indicative=0.000100, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.02%, turnover=40003725. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=0.001693, depth_time=2026-11-09T06:00:06+00:00, book20_bid_proxy_usdt=11181, book20_ask_proxy_usdt=12986, funding_indicative=-0.000107, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-17.00%, turnover=10172188. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=0.003638, depth_time=2026-11-09T06:00:16+00:00, book20_bid_proxy_usdt=2417968, book20_ask_proxy_usdt=2821338, funding_indicative=0.000049, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.16%, turnover=9432742. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=87.830000, depth_time=2026-11-09T06:00:39+00:00, book20_bid_proxy_usdt=14431058, book20_ask_proxy_usdt=14649019, funding_indicative=-0.000092, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.46%, turnover=565150529. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=218.700000, depth_time=2026-11-09T06:00:24+00:00, book20_bid_proxy_usdt=229235, book20_ask_proxy_usdt=122623, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.48%, turnover=33155520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=1.155000, depth_time=2026-11-09T06:00:22+00:00, book20_bid_proxy_usdt=2557675, book20_ask_proxy_usdt=2718701, funding_indicative=-0.000034, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.28%, turnover=6883797. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=0.147940, depth_time=2026-11-09T06:00:37+00:00, book20_bid_proxy_usdt=83377, book20_ask_proxy_usdt=149938, funding_indicative=0.000049, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.61%, turnover=25194920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=1.115600, depth_time=2026-11-09T06:00:15+00:00, book20_bid_proxy_usdt=3087992, book20_ask_proxy_usdt=3568000, funding_indicative=-0.000007, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.35%, turnover=240331677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T05:59:59+00:00, last15m_closed_end=2026-11-09T06:00+00:00, prior8high=1241.630000, depth_time=2026-11-09T06:00:32+00:00, book20_bid_proxy_usdt=659706, book20_ask_proxy_usdt=662758, funding_indicative=0.000038, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.98%, turnover=2082086833. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
