# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T13:30:46Z**
- feed_generated_utc: 2026-11-10T13:30:48+00:00
- source_sha256: `3c74c8b51ef4cfb20dd42d6de97548aa5a2fb8388ad60fcc92e2d3aacb25a181`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T13:30+00:00, close=74379.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T13:00+00:00, close=74359, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002436|-50.25|-55.72|-48.74|13072525|4.10|
|JCT_USDT|0.006497|-35.87|50.49|-34.36|24318086|4.62|
|ARB_USDT|0.164990|-10.35|3.55|-8.84|37587659|0.61|
|XMR_USDT|549.750000|-8.95|-9.17|-7.44|6130729|2.18|
|ANTHROPIC_USDT|1302.770000|-8.81|-22.39|-7.30|7004322|0.08|
|AVAX_USDT|8.359000|-7.01|-1.67|-5.50|44201671|1.20|
|QNT_USDT|186.550000|-6.74|-7.85|-5.23|33021375|0.54|
|ZEC_USDT|1153.120000|-5.92|-8.05|-4.41|2226562540|4.16|
|AAVE_USDT|125.450000|-5.92|-3.91|-4.41|10009261|0.80|
|SUI_USDT|0.831700|-4.10|-6.00|-2.59|34545877|2.40|
|DOT_USDT|0.854700|-4.06|-8.50|-2.55|7965202|1.17|
|PUMPFUN_USDT|0.003534|-4.01|-13.88|-2.50|7319225|2.83|
|SOL_USDT|84.660000|-3.67|-9.46|-2.16|635572037|1.18|
|HYPE_USDT|73.690000|-3.43|-14.02|-1.92|44439395|1.76|
|XRP_USDT|1.079200|-3.11|-13.55|-1.60|267442922|0.93|
|XLM_USDT|0.145270|-2.92|-13.32|-1.41|24098545|0.69|
|WLD_USDT|0.316500|-2.88|-16.97|-1.37|26052029|3.16|
|ADA_USDT|0.177300|-2.79|-6.58|-1.28|20369991|5.64|
|DASH_USDT|46.290000|-2.79|-1.92|-1.28|9906803|2.16|
|HBAR_USDT|0.066660|-2.64|-5.40|-1.13|9085496|1.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.450000|124.180000|125.450000|1.47|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002436|0.002353|0.002434|1.96|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1302.770000|1247.900000|1302.770000|1.67|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164990|0.161170|0.164980|0.82|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.359000|8.255000|8.359000|1.73|N|Y/Y|Y/N|Y|N|
|DOT_USDT|0.854700|0.847900|0.854700|0.37|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.690000|73.342000|73.690000|0.28|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006497|0.005597|0.006497|0.53|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003534|0.003485|0.003534|0.78|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|186.550000|185.640000|186.550000|1.31|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|84.660000|84.170000|84.660000|1.22|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.831700|0.827600|0.831800|0.81|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|549.750000|546.050000|549.750000|1.95|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.079200|1.074300|1.079100|1.26|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1153.120000|1141.660000|1153.880000|1.29|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T13:30:00+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=125.920000, depth_time=2026-11-10T13:30:28+00:00, book20_bid_proxy_usdt=124141, book20_ask_proxy_usdt=143384, funding_indicative=0.000063, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.92%, turnover=10009261. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T13:29:59+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=0.002546, depth_time=2026-11-10T13:30:07+00:00, book20_bid_proxy_usdt=74668, book20_ask_proxy_usdt=60016, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-50.25%, turnover=13072525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T13:29:59+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=1344.530000, depth_time=2026-11-10T13:30:18+00:00, book20_bid_proxy_usdt=14756, book20_ask_proxy_usdt=22676, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.81%, turnover=7004322. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T13:29:59+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=0.165080, depth_time=2026-11-10T13:30:13+00:00, book20_bid_proxy_usdt=16391, book20_ask_proxy_usdt=13891, funding_indicative=-0.000230, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.35%, turnover=37587659. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T13:29:59+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=8.398000, depth_time=2026-11-10T13:30:21+00:00, book20_bid_proxy_usdt=395528, book20_ask_proxy_usdt=316621, funding_indicative=-0.000048, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.01%, turnover=44201671. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T13:30:00+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=0.858100, depth_time=2026-11-10T13:30:34+00:00, book20_bid_proxy_usdt=162543, book20_ask_proxy_usdt=181042, funding_indicative=0.000032, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.06%, turnover=7965202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T13:29:59+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=73.962000, depth_time=2026-11-10T13:30:42+00:00, book20_bid_proxy_usdt=41306, book20_ask_proxy_usdt=47951, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.43%, turnover=44439395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T13:29:59+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=0.006495, depth_time=2026-11-10T13:30:11+00:00, book20_bid_proxy_usdt=22084, book20_ask_proxy_usdt=6790, funding_indicative=0.000101, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-35.87%, turnover=24318086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T13:30:00+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=0.003552, depth_time=2026-11-10T13:30:36+00:00, book20_bid_proxy_usdt=804139, book20_ask_proxy_usdt=946345, funding_indicative=-0.000037, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.01%, turnover=7319225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T13:30:00+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=188.280000, depth_time=2026-11-10T13:30:23+00:00, book20_bid_proxy_usdt=29992, book20_ask_proxy_usdt=45132, funding_indicative=-0.000078, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.74%, turnover=33021375. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T13:29:59+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=84.980000, depth_time=2026-11-10T13:30:39+00:00, book20_bid_proxy_usdt=6361038, book20_ask_proxy_usdt=3673338, funding_indicative=0.000091, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.67%, turnover=635572037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T13:29:59+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=0.836100, depth_time=2026-11-10T13:30:31+00:00, book20_bid_proxy_usdt=23558, book20_ask_proxy_usdt=92842, funding_indicative=0.000099, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.10%, turnover=34545877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T13:30:00+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=555.790000, depth_time=2026-11-10T13:30:15+00:00, book20_bid_proxy_usdt=10624, book20_ask_proxy_usdt=27079, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.95%, turnover=6130729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-10T13:29:59+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=1.084600, depth_time=2026-11-10T13:30:45+00:00, book20_bid_proxy_usdt=183419, book20_ask_proxy_usdt=344114, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=267442922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T13:29:59+00:00, last15m_closed_end=2026-11-10T13:30+00:00, prior8high=1158.860000, depth_time=2026-11-10T13:30:26+00:00, book20_bid_proxy_usdt=997357, book20_ask_proxy_usdt=227228, funding_indicative=0.000055, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.92%, turnover=2226562540. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
