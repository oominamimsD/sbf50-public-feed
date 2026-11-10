# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T15:30:42Z**
- feed_generated_utc: 2026-11-10T15:30:43+00:00
- source_sha256: `0f5ab669e15947df7914bca3e929296eb421d98a65cc265e797a7c40d3761168`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T15:30+00:00, close=74051.1, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T15:00+00:00, close=74373.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005302|-47.66|22.81|-45.77|24042466|5.66|
|AKE_USDT|0.002710|-44.65|-50.74|-42.76|14229082|3.69|
|ARB_USDT|0.163760|-11.01|2.78|-9.12|39170321|0.61|
|ANTHROPIC_USDT|1303.100000|-8.79|-22.37|-6.90|7680966|2.61|
|QNT_USDT|183.210000|-8.41|-9.50|-6.52|37194663|0.55|
|XMR_USDT|553.830000|-8.28|-8.50|-6.39|6462579|1.99|
|AVAX_USDT|8.296000|-7.71|-2.41|-5.82|41075729|1.21|
|AAVE_USDT|125.150000|-6.14|-4.14|-4.25|10688154|3.20|
|ZEC_USDT|1159.350000|-5.41|-7.55|-3.52|2286396166|0.26|
|XRP_USDT|1.053700|-5.40|-15.59|-3.51|296772501|0.95|
|PUMPFUN_USDT|0.003489|-5.24|-14.98|-3.35|8190218|2.87|
|SOL_USDT|83.670000|-4.80|-10.52|-2.91|682555250|1.20|
|SUI_USDT|0.827200|-4.62|-6.50|-2.73|39078658|1.21|
|HYPE_USDT|73.080000|-4.23|-14.73|-2.34|41826657|0.14|
|ETH_USDT|2064.280000|-3.84|-9.15|-1.95|1472512820|0.10|
|ADA_USDT|0.175700|-3.67|-7.42|-1.78|21839060|5.69|
|DOT_USDT|0.858700|-3.61|-8.07|-1.72|8207425|1.17|
|LINK_USDT|10.424000|-3.34|-7.21|-1.45|102376726|0.96|
|HBAR_USDT|0.066410|-3.00|-5.76|-1.11|8900228|1.50|
|XLM_USDT|0.145210|-2.96|-13.35|-1.07|22967731|0.69|
|DOGE_USDT|0.068740|-2.92|-8.35|-1.03|67277891|1.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.150000|122.640000|125.150000|2.45|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002710|0.002383|0.002710|2.61|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1303.100000|1277.520000|1303.100000|0.93|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.163760|0.161200|0.163760|2.75|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.296000|8.228000|8.298000|1.69|N|Y/Y|Y/N|Y|N|
|ETH_USDT|2064.280000|2030.110000|2063.130000|2.04|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.080000|72.149000|73.080000|1.47|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005302|0.005696|0.005322|2.84|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.003489|0.003428|0.003489|2.20|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|183.210000|178.810000|183.210000|0.93|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|83.670000|82.420000|83.630000|1.55|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.827200|0.814500|0.827200|1.90|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|553.830000|544.080000|553.830000|0.93|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.053700|1.048300|1.053100|1.43|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1159.350000|1132.440000|1155.280000|1.55|N|N/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=126.540000, depth_time=2026-11-10T15:30:23+00:00, book20_bid_proxy_usdt=293040, book20_ask_proxy_usdt=284523, funding_indicative=0.000020, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.14%, turnover=10688154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=0.003146, depth_time=2026-11-10T15:30:09+00:00, book20_bid_proxy_usdt=30391, book20_ask_proxy_usdt=31360, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-44.65%, turnover=14229082. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=1308.210000, depth_time=2026-11-10T15:30:13+00:00, book20_bid_proxy_usdt=18546, book20_ask_proxy_usdt=19868, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.79%, turnover=7680966. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=0.166600, depth_time=2026-11-10T15:30:11+00:00, book20_bid_proxy_usdt=74022, book20_ask_proxy_usdt=38305, funding_indicative=-0.000121, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.01%, turnover=39170321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=8.452000, depth_time=2026-11-10T15:30:20+00:00, book20_bid_proxy_usdt=712638, book20_ask_proxy_usdt=563199, funding_indicative=-0.000021, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.71%, turnover=41075729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=2103.900000, depth_time=2026-11-10T15:30:41+00:00, book20_bid_proxy_usdt=4303925, book20_ask_proxy_usdt=2176705, funding_indicative=0.000010, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.84%, turnover=1472512820. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=74.288000, depth_time=2026-11-10T15:30:38+00:00, book20_bid_proxy_usdt=50678, book20_ask_proxy_usdt=40120, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.23%, turnover=41826657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=0.008172, depth_time=2026-11-10T15:30:06+00:00, book20_bid_proxy_usdt=28736, book20_ask_proxy_usdt=29354, funding_indicative=0.000398, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-47.66%, turnover=24042466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=0.003613, depth_time=2026-11-10T15:30:31+00:00, book20_bid_proxy_usdt=2749704, book20_ask_proxy_usdt=3241855, funding_indicative=0.000009, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.24%, turnover=8190218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=187.450000, depth_time=2026-11-10T15:30:13+00:00, book20_bid_proxy_usdt=51662, book20_ask_proxy_usdt=57230, funding_indicative=-0.000085, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.41%, turnover=37194663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=85.210000, depth_time=2026-11-10T15:30:34+00:00, book20_bid_proxy_usdt=11988961, book20_ask_proxy_usdt=15989982, funding_indicative=0.000026, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.80%, turnover=682555250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=0.846000, depth_time=2026-11-10T15:30:36+00:00, book20_bid_proxy_usdt=1433162, book20_ask_proxy_usdt=868506, funding_indicative=0.000000, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.62%, turnover=39078658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=558.160000, depth_time=2026-11-10T15:30:16+00:00, book20_bid_proxy_usdt=22692, book20_ask_proxy_usdt=12875, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.28%, turnover=6462579. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=1.082900, depth_time=2026-11-10T15:30:28+00:00, book20_bid_proxy_usdt=4124340, book20_ask_proxy_usdt=3963104, funding_indicative=0.000058, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.40%, turnover=296772501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T15:29:59+00:00, last15m_closed_end=2026-11-10T15:30+00:00, prior8high=1198.440000, depth_time=2026-11-10T15:30:26+00:00, book20_bid_proxy_usdt=72826, book20_ask_proxy_usdt=104601, funding_indicative=0.000027, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.41%, turnover=2286396166. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
