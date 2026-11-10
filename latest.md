# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T11:00:44Z**
- feed_generated_utc: 2026-11-10T11:00:47+00:00
- source_sha256: `01b0a44f689f641baec84e78776250f9378e7a9d72248bfc89b451780dfd7adb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T11:00+00:00, close=74200.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T11:00+00:00, close=74200.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002478|-47.84|-54.96|-46.12|13649242|4.04|
|JCT_USDT|0.005940|-41.36|37.59|-39.64|24500567|1.68|
|ON_USDT|0.132200|-11.63|-22.00|-9.91|5377024|7.57|
|ARB_USDT|0.164680|-10.51|3.35|-8.79|37394232|1.21|
|XMR_USDT|548.440000|-9.17|-9.39|-7.45|5857185|0.18|
|ZEC_USDT|1143.130000|-6.73|-8.84|-5.01|2256134467|0.09|
|QNT_USDT|186.910000|-6.51|-7.67|-4.79|33251831|1.07|
|AVAX_USDT|8.292000|-6.41|-2.45|-4.69|50662290|1.21|
|AAVE_USDT|124.830000|-6.38|-4.38|-4.66|11296229|0.80|
|PUMPFUN_USDT|0.003509|-4.56|-14.49|-2.84|7526413|2.85|
|DOT_USDT|0.850700|-3.96|-8.92|-2.24|8049225|1.18|
|SOL_USDT|84.430000|-3.93|-9.71|-2.21|658552292|1.18|
|DASH_USDT|45.580000|-3.65|-3.43|-1.93|10053408|2.19|
|HYPE_USDT|73.651000|-3.10|-14.07|-1.38|45775761|0.14|
|SUI_USDT|0.833300|-3.01|-5.82|-1.29|35072583|1.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|124.830000|124.140000|124.840000|1.05|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002478|0.002406|0.002478|0.37|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164680|0.164660|0.164750|0.68|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|8.292000|8.276000|8.292000|1.48|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.580000|45.440000|45.580000|0.40|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.850700|0.845000|0.850700|1.16|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.651000|73.603000|73.655000|0.66|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005940|0.005322|0.005921|0.53|N|Y/Y|Y/N|Y|N|
|ON_USDT|0.132200|0.122700|0.132300|0.36|N|Y/Y|N/Y|Y|N|
|PUMPFUN_USDT|0.003509|0.003499|0.003509|1.74|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|186.910000|186.370000|186.910000|0.90|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|84.430000|84.300000|84.430000|0.52|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.833300|0.831400|0.833300|1.21|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|548.440000|539.060000|548.400000|1.18|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1143.130000|1131.050000|1143.200000|0.57|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=126.020000, depth_time=2026-11-10T11:00:28+00:00, book20_bid_proxy_usdt=425987, book20_ask_proxy_usdt=347753, funding_indicative=0.000054, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.38%, turnover=11296229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=0.002533, depth_time=2026-11-10T11:00:04+00:00, book20_bid_proxy_usdt=88657, book20_ask_proxy_usdt=62782, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-47.84%, turnover=13649242. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=0.169380, depth_time=2026-11-10T11:00:13+00:00, book20_bid_proxy_usdt=49144, book20_ask_proxy_usdt=67770, funding_indicative=-0.000196, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.51%, turnover=37394232. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=8.489000, depth_time=2026-11-10T11:00:25+00:00, book20_bid_proxy_usdt=1128970, book20_ask_proxy_usdt=786619, funding_indicative=0.000012, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.41%, turnover=50662290. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T11:00:03+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=46.340000, depth_time=2026-11-10T11:00:38+00:00, book20_bid_proxy_usdt=830161, book20_ask_proxy_usdt=518731, funding_indicative=-0.000009, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.65%, turnover=10053408. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=0.856000, depth_time=2026-11-10T11:00:30+00:00, book20_bid_proxy_usdt=517618, book20_ask_proxy_usdt=589104, funding_indicative=-0.000078, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.96%, turnover=8049225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=74.581000, depth_time=2026-11-10T11:00:41+00:00, book20_bid_proxy_usdt=154584, book20_ask_proxy_usdt=76171, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.10%, turnover=45775761. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=0.006657, depth_time=2026-11-10T11:00:10+00:00, book20_bid_proxy_usdt=39323, book20_ask_proxy_usdt=41525, funding_indicative=0.000304, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-41.36%, turnover=24500567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ON_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=0.181700, depth_time=2026-11-10T11:00:12+00:00, book20_bid_proxy_usdt=70196, book20_ask_proxy_usdt=47977, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.63%, turnover=5377024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=0.003555, depth_time=2026-11-10T11:00:29+00:00, book20_bid_proxy_usdt=2791255, book20_ask_proxy_usdt=3305277, funding_indicative=-0.000006, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.56%, turnover=7526413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=189.740000, depth_time=2026-11-10T11:00:20+00:00, book20_bid_proxy_usdt=79961, book20_ask_proxy_usdt=39530, funding_indicative=-0.000104, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.51%, turnover=33251831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=85.900000, depth_time=2026-11-10T11:00:34+00:00, book20_bid_proxy_usdt=11790811, book20_ask_proxy_usdt=17317876, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.93%, turnover=658552292. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=0.845200, depth_time=2026-11-10T11:00:43+00:00, book20_bid_proxy_usdt=1890737, book20_ask_proxy_usdt=1539392, funding_indicative=0.000067, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.01%, turnover=35072583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=563.070000, depth_time=2026-11-10T11:00:17+00:00, book20_bid_proxy_usdt=58401, book20_ask_proxy_usdt=16117, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.17%, turnover=5857185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T11:00:02+00:00, last15m_closed_end=2026-11-10T11:00+00:00, prior8high=1147.840000, depth_time=2026-11-10T11:00:19+00:00, book20_bid_proxy_usdt=129507, book20_ask_proxy_usdt=233606, funding_indicative=0.000082, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.73%, turnover=2256134467. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
