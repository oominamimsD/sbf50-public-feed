# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T11:15:41Z**
- feed_generated_utc: 2026-11-10T11:15:43+00:00
- source_sha256: `d22e1d5f15572be4646250745d7c840964c6d563a8e132811efaf4a59f59796e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T11:15+00:00, close=74337.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T11:00+00:00, close=74200.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002472|-49.52|-55.07|-47.98|13691703|4.05|
|JCT_USDT|0.005985|-40.92|38.63|-39.38|24646204|3.35|
|ON_USDT|0.127100|-15.04|-25.01|-13.50|5389237|7.87|
|ARB_USDT|0.163770|-11.01|2.78|-9.47|37828846|0.61|
|XMR_USDT|546.950000|-9.42|-9.63|-7.88|5977489|0.18|
|AVAX_USDT|8.314000|-7.51|-2.19|-5.97|51224454|1.20|
|QNT_USDT|187.170000|-6.43|-7.54|-4.89|33652410|1.60|
|AAVE_USDT|124.980000|-6.27|-4.27|-4.73|11415917|0.80|
|ZEC_USDT|1153.020000|-5.93|-8.05|-4.39|2273458123|0.09|
|PUMPFUN_USDT|0.003513|-4.58|-14.40|-3.04|7691966|2.85|
|DOT_USDT|0.853600|-4.18|-8.61|-2.64|8133765|1.17|
|SUI_USDT|0.834800|-3.74|-5.65|-2.20|35266986|1.20|
|DASH_USDT|45.860000|-3.69|-2.83|-2.15|10130266|4.36|
|SOL_USDT|84.780000|-3.53|-9.33|-1.99|664634102|1.18|
|HYPE_USDT|73.815000|-3.27|-13.88|-1.73|46452186|0.14|
|LINK_USDT|10.471000|-2.91|-6.79|-1.37|106711025|0.95|
|HBAR_USDT|0.066520|-2.84|-5.60|-1.30|9548400|1.50|
|XRP_USDT|1.082800|-2.79|-13.26|-1.25|274289392|0.92|
|WLD_USDT|0.317400|-2.60|-16.73|-1.06|27139441|3.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|124.980000|124.140000|124.980000|1.52|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002472|0.002406|0.002472|0.67|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.163770|0.164460|0.163770|1.53|Y|Y/Y|Y/N|Y|N|
|AVAX_USDT|8.314000|8.276000|8.314000|2.84|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.860000|45.440000|45.860000|1.76|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.853600|0.845000|0.853600|1.92|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.815000|73.568000|73.815000|2.21|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005985|0.005322|0.005985|0.60|N|Y/Y|Y/N|Y|N|
|ON_USDT|0.127100|0.122700|0.127100|0.49|N|Y/Y|N/Y|Y|N|
|PUMPFUN_USDT|0.003513|0.003499|0.003513|5.69|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|187.170000|186.370000|187.170000|1.76|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|84.780000|84.300000|84.780000|0.84|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.834800|0.831400|0.834800|0.71|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|546.950000|539.060000|546.950000|2.49|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1153.020000|1131.050000|1153.210000|1.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T11:15:00+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=125.840000, depth_time=2026-11-10T11:15:24+00:00, book20_bid_proxy_usdt=353676, book20_ask_proxy_usdt=327595, funding_indicative=0.000060, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.27%, turnover=11415917. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T11:14:59+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=0.002533, depth_time=2026-11-10T11:15:06+00:00, book20_bid_proxy_usdt=83177, book20_ask_proxy_usdt=57311, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-49.52%, turnover=13691703. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T11:14:59+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=0.169380, depth_time=2026-11-10T11:15:13+00:00, book20_bid_proxy_usdt=80138, book20_ask_proxy_usdt=100816, funding_indicative=-0.000213, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.01%, turnover=37828846. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T11:14:59+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=8.467000, depth_time=2026-11-10T11:15:19+00:00, book20_bid_proxy_usdt=723872, book20_ask_proxy_usdt=694840, funding_indicative=0.000009, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.51%, turnover=51224454. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T11:15:00+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=46.340000, depth_time=2026-11-10T11:15:35+00:00, book20_bid_proxy_usdt=687428, book20_ask_proxy_usdt=679985, funding_indicative=-0.000008, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=10130266. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T11:15:00+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=0.855200, depth_time=2026-11-10T11:15:30+00:00, book20_bid_proxy_usdt=666817, book20_ask_proxy_usdt=655480, funding_indicative=-0.000049, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.18%, turnover=8133765. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T11:14:59+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=74.581000, depth_time=2026-11-10T11:15:38+00:00, book20_bid_proxy_usdt=62972, book20_ask_proxy_usdt=33182, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.27%, turnover=46452186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T11:14:59+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=0.006657, depth_time=2026-11-10T11:15:09+00:00, book20_bid_proxy_usdt=44818, book20_ask_proxy_usdt=41327, funding_indicative=0.000320, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-40.92%, turnover=24646204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ON_USDT: quote_utc=2026-11-10T11:14:59+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=0.175000, depth_time=2026-11-10T11:15:12+00:00, book20_bid_proxy_usdt=129748, book20_ask_proxy_usdt=162425, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-15.04%, turnover=5389237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T11:15:00+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=0.003552, depth_time=2026-11-10T11:15:29+00:00, book20_bid_proxy_usdt=2906038, book20_ask_proxy_usdt=2765665, funding_indicative=-0.000016, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.58%, turnover=7691966. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T11:15:00+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=189.740000, depth_time=2026-11-10T11:15:22+00:00, book20_bid_proxy_usdt=67287, book20_ask_proxy_usdt=113615, funding_indicative=-0.000091, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.43%, turnover=33652410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T11:14:59+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=85.850000, depth_time=2026-11-10T11:15:38+00:00, book20_bid_proxy_usdt=11653692, book20_ask_proxy_usdt=21497213, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.53%, turnover=664634102. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T11:14:59+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=0.845100, depth_time=2026-11-10T11:15:34+00:00, book20_bid_proxy_usdt=1069206, book20_ask_proxy_usdt=2065072, funding_indicative=0.000075, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=35266986. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T11:15:00+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=562.000000, depth_time=2026-11-10T11:15:17+00:00, book20_bid_proxy_usdt=7136, book20_ask_proxy_usdt=11222, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.42%, turnover=5977489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T11:14:59+00:00, last15m_closed_end=2026-11-10T11:15+00:00, prior8high=1148.620000, depth_time=2026-11-10T11:15:27+00:00, book20_bid_proxy_usdt=209940, book20_ask_proxy_usdt=207924, funding_indicative=0.000083, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.93%, turnover=2273458123. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
