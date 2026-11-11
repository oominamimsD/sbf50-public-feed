# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T01:00:39Z**
- feed_generated_utc: 2026-11-11T01:00:41+00:00
- source_sha256: `7d3d24720d1755a9067e3f1b9aa6a5a2979147c852692c731448a1a54831c9e6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T01:00+00:00, close=73513.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T01:00+00:00, close=73513.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005127|-14.96|22.71|-15.41|18588549|3.90|
|PIEVERSE_USDT|1.827100|-11.03|55.44|-11.48|5083713|1.64|
|DASH_USDT|43.110000|-7.38|-6.56|-7.83|14015170|2.32|
|ZEC_USDT|1032.840000|-5.53|-14.20|-5.98|2134880158|0.10|
|UNI_USDT|6.693000|-5.26|-8.97|-5.71|33353141|1.49|
|ARB_USDT|0.161310|-2.27|0.89|-2.72|33337182|1.86|
|HYPE_USDT|71.952000|-2.25|-17.62|-2.70|40618645|0.14|
|VVV_USDT|19.385000|-2.17|-13.30|-2.62|5238397|1.55|
|DOT_USDT|0.843800|-2.16|-10.48|-2.61|8357988|1.19|
|LINK_USDT|10.324000|-1.76|-7.44|-2.21|88579166|0.97|
|SOL_USDT|83.100000|-1.43|-11.33|-1.88|653677068|1.20|
|XRP_USDT|1.051300|-1.30|-17.91|-1.75|295818504|0.95|
|QNT_USDT|181.220000|-1.02|-7.26|-1.47|45529178|3.31|
|AAVE_USDT|124.160000|-0.66|-3.33|-1.11|10258779|0.81|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|124.160000|123.220000|124.160000|0.99|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.161310|0.159830|0.161310|0.13|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.110000|42.400000|43.110000|0.04|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.843800|0.837800|0.843800|1.46|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|71.952000|71.970000|71.952000|0.97|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005127|0.004964|0.005127|1.69|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.324000|10.223000|10.324000|0.53|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.827100|1.808000|1.827100|0.35|N|Y/Y|N/N|Y|N|
|QNT_USDT|181.220000|180.050000|181.220000|1.27|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|83.100000|82.540000|83.100000|0.75|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.693000|6.611000|6.693000|4.71|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.385000|19.215000|19.385000|0.92|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.051300|1.049500|1.051300|0.40|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1032.840000|1030.550000|1032.710000|1.22|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=124.460000, depth_time=2026-11-11T01:00:36+00:00, book20_bid_proxy_usdt=315415, book20_ask_proxy_usdt=480291, funding_indicative=0.000061, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.66%, turnover=10258779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=0.161710, depth_time=2026-11-11T01:00:19+00:00, book20_bid_proxy_usdt=77044, book20_ask_proxy_usdt=62799, funding_indicative=-0.000162, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=33337182. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=43.660000, depth_time=2026-11-11T01:00:12+00:00, book20_bid_proxy_usdt=684205, book20_ask_proxy_usdt=551542, funding_indicative=-0.000206, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.38%, turnover=14015170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=0.848500, depth_time=2026-11-11T01:00:23+00:00, book20_bid_proxy_usdt=521244, book20_ask_proxy_usdt=778991, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=8357988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=72.523000, depth_time=2026-11-11T01:00:21+00:00, book20_bid_proxy_usdt=198492, book20_ask_proxy_usdt=101588, funding_indicative=0.000050, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=40618645. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=0.005318, depth_time=2026-11-11T01:00:07+00:00, book20_bid_proxy_usdt=55927, book20_ask_proxy_usdt=55948, funding_indicative=0.000393, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.96%, turnover=18588549. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=10.366000, depth_time=2026-11-11T01:00:27+00:00, book20_bid_proxy_usdt=436654, book20_ask_proxy_usdt=632704, funding_indicative=0.000025, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=88579166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=1.870000, depth_time=2026-11-11T01:00:08+00:00, book20_bid_proxy_usdt=19671, book20_ask_proxy_usdt=13518, funding_indicative=0.000050, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.03%, turnover=5083713. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=182.460000, depth_time=2026-11-11T01:00:35+00:00, book20_bid_proxy_usdt=40549, book20_ask_proxy_usdt=77531, funding_indicative=-0.000225, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=45529178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=83.600000, depth_time=2026-11-11T01:00:30+00:00, book20_bid_proxy_usdt=14060308, book20_ask_proxy_usdt=15353894, funding_indicative=0.000074, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=653677068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=6.740000, depth_time=2026-11-11T01:00:17+00:00, book20_bid_proxy_usdt=2211843, book20_ask_proxy_usdt=3466948, funding_indicative=-0.000001, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.26%, turnover=33353141. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=19.550000, depth_time=2026-11-11T01:00:20+00:00, book20_bid_proxy_usdt=42364, book20_ask_proxy_usdt=16734, funding_indicative=0.000050, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=5238397. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=1.060100, depth_time=2026-11-11T01:00:33+00:00, book20_bid_proxy_usdt=3646715, book20_ask_proxy_usdt=3094716, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=295818504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T01:00:00+00:00, last15m_closed_end=2026-11-11T01:00+00:00, prior8high=1055.500000, depth_time=2026-11-11T01:00:14+00:00, book20_bid_proxy_usdt=2157734, book20_ask_proxy_usdt=407719, funding_indicative=0.000060, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.53%, turnover=2134880158. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
