# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T12:15:43Z**
- feed_generated_utc: 2026-11-10T12:15:44+00:00
- source_sha256: `9ada547f74fedf1f6ffa191bd3a679132189332264718edb1fd7be901b2cba24`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T12:15+00:00, close=74329.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002496|-49.03|-54.63|-47.48|13628939|4.01|
|JCT_USDT|0.006115|-39.64|41.64|-38.09|24189354|1.64|
|ARB_USDT|0.162560|-11.67|2.02|-10.12|38381240|0.61|
|ANTHROPIC_USDT|1292.560000|-9.53|-23.00|-7.98|6513098|2.01|
|XMR_USDT|553.060000|-8.41|-8.62|-6.86|6061067|0.18|
|AVAX_USDT|8.316000|-7.49|-2.17|-5.94|51633814|1.20|
|QNT_USDT|186.520000|-6.75|-7.86|-5.20|32908955|1.61|
|AAVE_USDT|124.480000|-6.65|-4.65|-5.10|10691496|1.61|
|ZEC_USDT|1148.130000|-6.33|-8.44|-4.78|2239783379|0.09|
|PUMPFUN_USDT|0.003529|-4.15|-14.01|-2.60|7518884|2.83|
|SUI_USDT|0.833100|-3.94|-5.84|-2.39|35141735|1.20|
|DOT_USDT|0.855800|-3.93|-8.38|-2.38|8347900|1.17|
|SOL_USDT|84.750000|-3.57|-9.36|-2.02|639113976|1.18|
|HYPE_USDT|73.587000|-3.57|-14.14|-2.02|45135032|0.14|
|DASH_USDT|46.080000|-3.23|-2.37|-1.68|9771465|2.17|
|XRP_USDT|1.079800|-3.06|-13.50|-1.51|269108876|0.93|
|LINK_USDT|10.458000|-3.03|-6.90|-1.48|104016113|1.91|
|WLD_USDT|0.316300|-2.94|-17.02|-1.39|26830136|3.16|
|HBAR_USDT|0.066600|-2.73|-5.49|-1.18|9435828|1.50|
|ETH_USDT|2091.580000|-2.56|-7.95|-1.01|1218486879|0.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|124.480000|124.140000|124.480000|0.15|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002496|0.002353|0.002493|3.14|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1292.560000|1247.900000|1292.640000|4.10|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.162560|0.161610|0.162560|0.60|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.316000|8.255000|8.317000|1.29|N|Y/Y|Y/N|Y|N|
|DASH_USDT|46.080000|45.400000|46.080000|1.92|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.855800|0.845000|0.855800|1.72|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.587000|73.342000|73.587000|0.42|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006115|0.005322|0.006123|0.40|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003529|0.003485|0.003529|0.96|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|186.520000|185.640000|186.520000|0.37|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|84.750000|84.170000|84.750000|0.59|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.833100|0.827600|0.833100|0.43|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|553.060000|539.060000|553.060000|0.49|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1148.130000|1131.050000|1147.670000|0.62|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=125.650000, depth_time=2026-11-10T12:15:21+00:00, book20_bid_proxy_usdt=353316, book20_ask_proxy_usdt=333608, funding_indicative=0.000066, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.65%, turnover=10691496. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=0.002546, depth_time=2026-11-10T12:15:07+00:00, book20_bid_proxy_usdt=77169, book20_ask_proxy_usdt=44024, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-49.03%, turnover=13628939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=1386.950000, depth_time=2026-11-10T12:15:14+00:00, book20_bid_proxy_usdt=11515, book20_ask_proxy_usdt=14891, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.53%, turnover=6513098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=0.167610, depth_time=2026-11-10T12:15:10+00:00, book20_bid_proxy_usdt=93842, book20_ask_proxy_usdt=90388, funding_indicative=-0.000227, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.67%, turnover=38381240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=8.412000, depth_time=2026-11-10T12:15:20+00:00, book20_bid_proxy_usdt=786780, book20_ask_proxy_usdt=921036, funding_indicative=-0.000013, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.49%, turnover=51633814. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=46.280000, depth_time=2026-11-10T12:15:40+00:00, book20_bid_proxy_usdt=326520, book20_ask_proxy_usdt=552907, funding_indicative=0.000015, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=9771465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=0.855800, depth_time=2026-11-10T12:15:35+00:00, book20_bid_proxy_usdt=453104, book20_ask_proxy_usdt=653002, funding_indicative=0.000046, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.93%, turnover=8347900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=74.537000, depth_time=2026-11-10T12:15:40+00:00, book20_bid_proxy_usdt=97200, book20_ask_proxy_usdt=73005, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.57%, turnover=45135032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=0.006488, depth_time=2026-11-10T12:15:09+00:00, book20_bid_proxy_usdt=38481, book20_ask_proxy_usdt=45716, funding_indicative=0.000307, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-39.64%, turnover=24189354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=0.003551, depth_time=2026-11-10T12:15:30+00:00, book20_bid_proxy_usdt=3068590, book20_ask_proxy_usdt=3389062, funding_indicative=-0.000026, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.15%, turnover=7518884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=189.430000, depth_time=2026-11-10T12:15:17+00:00, book20_bid_proxy_usdt=65620, book20_ask_proxy_usdt=115923, funding_indicative=-0.000077, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.75%, turnover=32908955. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=85.640000, depth_time=2026-11-10T12:15:37+00:00, book20_bid_proxy_usdt=12016274, book20_ask_proxy_usdt=18795719, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.57%, turnover=639113976. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=0.841900, depth_time=2026-11-10T12:15:32+00:00, book20_bid_proxy_usdt=1124994, book20_ask_proxy_usdt=1814664, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.94%, turnover=35141735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=552.690000, depth_time=2026-11-10T12:15:12+00:00, book20_bid_proxy_usdt=30665, book20_ask_proxy_usdt=20504, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.41%, turnover=6061067. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T12:15:02+00:00, last15m_closed_end=2026-11-10T12:15+00:00, prior8high=1154.630000, depth_time=2026-11-10T12:15:28+00:00, book20_bid_proxy_usdt=740503, book20_ask_proxy_usdt=229224, funding_indicative=0.000078, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.33%, turnover=2239783379. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
