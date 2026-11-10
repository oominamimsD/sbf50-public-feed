# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T13:15:42Z**
- feed_generated_utc: 2026-11-10T13:15:44+00:00
- source_sha256: `cb7b618e70e2e718563eef7ce3439ef98c9445d2ed2a49f40df8ed39a7745f7b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T13:15+00:00, close=74360.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T13:00+00:00, close=74359, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002447|-50.03|-55.52|-48.53|12954683|4.09|
|JCT_USDT|0.006363|-37.19|47.39|-35.69|24200088|1.57|
|ARB_USDT|0.164860|-10.42|3.47|-8.92|37373186|0.61|
|ANTHROPIC_USDT|1300.120000|-9.00|-22.55|-7.50|6883279|2.38|
|XMR_USDT|550.730000|-8.79|-9.01|-7.29|6062123|0.18|
|AVAX_USDT|8.387000|-6.70|-1.34|-5.20|43734368|1.20|
|QNT_USDT|187.330000|-6.35|-7.46|-4.85|32598959|1.07|
|AAVE_USDT|125.400000|-5.96|-3.95|-4.46|9922087|0.80|
|ZEC_USDT|1153.810000|-5.86|-7.99|-4.36|2207360993|0.09|
|DOT_USDT|0.854500|-4.08|-8.52|-2.58|7942382|1.17|
|SUI_USDT|0.832500|-4.01|-5.91|-2.51|34308073|2.40|
|PUMPFUN_USDT|0.003548|-3.63|-13.54|-2.13|7257243|2.82|
|HYPE_USDT|73.602000|-3.55|-14.12|-2.05|44358425|0.14|
|SOL_USDT|84.850000|-3.45|-9.26|-1.95|630278332|1.18|
|XLM_USDT|0.144990|-3.11|-13.49|-1.61|23802763|0.69|
|XRP_USDT|1.080700|-2.98|-13.43|-1.48|263946340|0.93|
|WLD_USDT|0.316200|-2.97|-17.05|-1.47|25767621|3.16|
|ADA_USDT|0.177200|-2.85|-6.63|-1.35|20270498|5.64|
|HBAR_USDT|0.066720|-2.55|-5.32|-1.05|9065278|1.50|
|LINK_USDT|10.510000|-2.54|-6.44|-1.04|99318453|0.95|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.400000|124.180000|125.400000|1.54|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002447|0.002353|0.002447|1.79|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1300.120000|1247.900000|1300.120000|1.30|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164860|0.161170|0.164860|0.81|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.387000|8.255000|8.349000|1.25|N|Y/Y|Y/N|Y|N|
|DOT_USDT|0.854500|0.847900|0.854500|0.72|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.602000|73.342000|73.602000|0.92|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006363|0.005597|0.006367|0.58|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003548|0.003485|0.003545|1.22|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|187.330000|185.640000|187.330000|1.24|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|84.850000|84.170000|84.850000|0.44|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.832500|0.827600|0.832500|0.95|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.144990|0.145180|0.144990|1.38|Y|Y/Y|Y/Y|Y|Y|
|XMR_USDT|550.730000|546.050000|550.730000|0.49|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1153.810000|1139.250000|1153.810000|0.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=125.720000, depth_time=2026-11-10T13:15:22+00:00, book20_bid_proxy_usdt=389932, book20_ask_proxy_usdt=303614, funding_indicative=0.000066, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.96%, turnover=9922087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=0.002546, depth_time=2026-11-10T13:15:05+00:00, book20_bid_proxy_usdt=76588, book20_ask_proxy_usdt=107252, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-50.03%, turnover=12954683. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=1356.200000, depth_time=2026-11-10T13:15:15+00:00, book20_bid_proxy_usdt=26197, book20_ask_proxy_usdt=13695, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.00%, turnover=6883279. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=0.164750, depth_time=2026-11-10T13:15:11+00:00, book20_bid_proxy_usdt=98429, book20_ask_proxy_usdt=91951, funding_indicative=-0.000233, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.42%, turnover=37373186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=8.362000, depth_time=2026-11-10T13:15:19+00:00, book20_bid_proxy_usdt=675030, book20_ask_proxy_usdt=622836, funding_indicative=-0.000039, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.70%, turnover=43734368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=0.858100, depth_time=2026-11-10T13:15:29+00:00, book20_bid_proxy_usdt=923984, book20_ask_proxy_usdt=587109, funding_indicative=0.000045, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.08%, turnover=7942382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=73.962000, depth_time=2026-11-10T13:15:35+00:00, book20_bid_proxy_usdt=48517, book20_ask_proxy_usdt=84582, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.55%, turnover=44358425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=0.006495, depth_time=2026-11-10T13:15:09+00:00, book20_bid_proxy_usdt=29310, book20_ask_proxy_usdt=27569, funding_indicative=0.000154, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-37.19%, turnover=24200088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=0.003546, depth_time=2026-11-10T13:15:34+00:00, book20_bid_proxy_usdt=2724556, book20_ask_proxy_usdt=3107073, funding_indicative=-0.000036, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.63%, turnover=7257243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=188.280000, depth_time=2026-11-10T13:15:21+00:00, book20_bid_proxy_usdt=104543, book20_ask_proxy_usdt=48612, funding_indicative=-0.000073, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.35%, turnover=32598959. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=84.980000, depth_time=2026-11-10T13:15:38+00:00, book20_bid_proxy_usdt=16042876, book20_ask_proxy_usdt=16447214, funding_indicative=0.000095, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=630278332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=0.836100, depth_time=2026-11-10T13:15:31+00:00, book20_bid_proxy_usdt=1657978, book20_ask_proxy_usdt=1042664, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.01%, turnover=34308073. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=0.146500, depth_time=2026-11-10T13:15:41+00:00, book20_bid_proxy_usdt=179577, book20_ask_proxy_usdt=149579, funding_indicative=0.000072, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=23802763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=555.580000, depth_time=2026-11-10T13:15:16+00:00, book20_bid_proxy_usdt=8860, book20_ask_proxy_usdt=12714, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.79%, turnover=6062123. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T13:14:59+00:00, last15m_closed_end=2026-11-10T13:15+00:00, prior8high=1158.860000, depth_time=2026-11-10T13:15:26+00:00, book20_bid_proxy_usdt=165262, book20_ask_proxy_usdt=253967, funding_indicative=0.000062, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.86%, turnover=2207360993. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
