# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T14:15:42Z**
- feed_generated_utc: 2026-11-10T14:15:44+00:00
- source_sha256: `7d747f9299ddeaa4995fa97783151513d6a1b15cae39f025a96c2b74e7facdb0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T14:15+00:00, close=73910.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T14:00+00:00, close=73714.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002476|-49.43|-54.99|-47.33|13219148|4.04|
|JCT_USDT|0.007101|-29.90|64.48|-27.80|23810474|5.63|
|ARB_USDT|0.164960|-10.36|3.53|-8.26|37132366|1.21|
|ANTHROPIC_USDT|1282.170000|-10.25|-23.62|-8.15|7534382|1.87|
|XMR_USDT|550.140000|-8.89|-9.11|-6.79|6264683|0.18|
|QNT_USDT|182.380000|-8.82|-9.91|-6.72|34616597|0.55|
|AVAX_USDT|8.318000|-7.47|-2.15|-5.37|40290109|1.20|
|AAVE_USDT|125.050000|-6.22|-4.22|-4.12|10059947|0.80|
|PUMPFUN_USDT|0.003498|-4.99|-14.76|-2.89|7904286|2.86|
|XRP_USDT|1.061600|-4.69|-14.96|-2.59|279218198|0.94|
|SOL_USDT|84.110000|-4.30|-10.05|-2.20|672800656|1.19|
|SUI_USDT|0.830500|-4.24|-6.13|-2.14|36862536|1.20|
|DOT_USDT|0.854000|-4.14|-8.57|-2.04|8143745|1.17|
|HYPE_USDT|73.214000|-4.06|-14.58|-1.96|45240031|0.14|
|FILECOIN_USDT|0.757000|-4.04|-12.71|-1.94|5032230|1.32|
|WLD_USDT|0.313800|-3.71|-17.68|-1.61|26958795|3.19|
|ETH_USDT|2068.130000|-3.66|-8.98|-1.56|1380649765|0.05|
|XLM_USDT|0.144180|-3.65|-13.97|-1.55|24458942|0.69|
|LINK_USDT|10.404000|-3.53|-7.38|-1.43|102214158|1.92|
|ADA_USDT|0.176100|-3.45|-7.21|-1.35|22111885|5.68|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.050000|122.640000|125.050000|0.75|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002476|0.002383|0.002476|1.63|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1282.170000|1274.190000|1282.170000|1.18|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164960|0.161170|0.164960|1.34|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.318000|8.228000|8.318000|0.71|N|Y/Y|Y/N|Y|N|
|DOT_USDT|0.854000|0.838600|0.854000|0.60|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.757000|0.746800|0.757000|0.94|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.214000|72.730000|73.214000|0.83|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.007101|0.005597|0.007101|2.19|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003498|0.003428|0.003497|0.52|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|182.380000|178.810000|182.380000|1.38|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|84.110000|82.420000|84.110000|0.63|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.830500|0.814500|0.830500|2.34|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|550.140000|544.080000|550.140000|0.30|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.061600|1.048300|1.061600|1.27|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=125.920000, depth_time=2026-11-10T14:15:23+00:00, book20_bid_proxy_usdt=353853, book20_ask_proxy_usdt=300744, funding_indicative=0.000058, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.22%, turnover=10059947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=0.002530, depth_time=2026-11-10T14:15:07+00:00, book20_bid_proxy_usdt=58045, book20_ask_proxy_usdt=67076, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-49.43%, turnover=13219148. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=1309.180000, depth_time=2026-11-10T14:15:14+00:00, book20_bid_proxy_usdt=6176, book20_ask_proxy_usdt=11346, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.25%, turnover=7534382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=0.165950, depth_time=2026-11-10T14:15:12+00:00, book20_bid_proxy_usdt=127963, book20_ask_proxy_usdt=67577, funding_indicative=-0.000171, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.36%, turnover=37132366. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=8.412000, depth_time=2026-11-10T14:15:22+00:00, book20_bid_proxy_usdt=642368, book20_ask_proxy_usdt=857938, funding_indicative=-0.000046, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.47%, turnover=40290109. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=0.860100, depth_time=2026-11-10T14:15:34+00:00, book20_bid_proxy_usdt=801861, book20_ask_proxy_usdt=404540, funding_indicative=0.000055, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.14%, turnover=8143745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-11-10T14:15:00+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=0.772800, depth_time=2026-11-10T14:15:42+00:00, book20_bid_proxy_usdt=1434816, book20_ask_proxy_usdt=1215668, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.04%, turnover=5032230. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=74.000000, depth_time=2026-11-10T14:15:39+00:00, book20_bid_proxy_usdt=76368, book20_ask_proxy_usdt=66976, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.06%, turnover=45240031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=0.007426, depth_time=2026-11-10T14:15:09+00:00, book20_bid_proxy_usdt=57097, book20_ask_proxy_usdt=23733, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-29.90%, turnover=23810474. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=0.003552, depth_time=2026-11-10T14:15:26+00:00, book20_bid_proxy_usdt=2631741, book20_ask_proxy_usdt=2308930, funding_indicative=-0.000018, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.99%, turnover=7904286. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=188.280000, depth_time=2026-11-10T14:15:19+00:00, book20_bid_proxy_usdt=28704, book20_ask_proxy_usdt=88099, funding_indicative=-0.000058, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.82%, turnover=34616597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=85.210000, depth_time=2026-11-10T14:15:32+00:00, book20_bid_proxy_usdt=21444563, book20_ask_proxy_usdt=16439712, funding_indicative=0.000056, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.30%, turnover=672800656. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=0.835000, depth_time=2026-11-10T14:15:34+00:00, book20_bid_proxy_usdt=1356354, book20_ask_proxy_usdt=1326226, funding_indicative=0.000058, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.24%, turnover=36862536. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=555.790000, depth_time=2026-11-10T14:15:13+00:00, book20_bid_proxy_usdt=8166, book20_ask_proxy_usdt=8213, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.89%, turnover=6264683. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-10T14:14:59+00:00, last15m_closed_end=2026-11-10T14:15+00:00, prior8high=1.082900, depth_time=2026-11-10T14:15:29+00:00, book20_bid_proxy_usdt=5440651, book20_ask_proxy_usdt=4247598, funding_indicative=0.000083, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.69%, turnover=279218198. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
