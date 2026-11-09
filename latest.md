# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T06:45:41Z**
- feed_generated_utc: 2026-11-09T06:45:43+00:00
- source_sha256: `9a64ed965053ae554cba17cf85d505626ca80f29d80009a6ce4228c3897b9164`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T06:45+00:00, close=74101.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T06:00+00:00, close=74440.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001626|-16.96|39.61|-14.42|9779479|0.61|
|AKE_USDT|0.004626|-13.64|-49.49|-11.10|11346352|6.48|
|JCT_USDT|0.008640|-12.14|73.52|-9.60|69764821|5.79|
|ASTER_USDT|0.632300|-6.98|-9.59|-4.44|5380266|1.58|
|ETH_USDT|2107.320000|-5.96|-6.99|-3.42|1306376435|0.05|
|XRP_USDT|1.087800|-5.88|-12.96|-3.34|249592039|0.92|
|TAO_USDT|214.250000|-5.21|-8.76|-2.67|35037196|1.40|
|PUMPFUN_USDT|0.003547|-5.08|-15.90|-2.54|9709367|2.82|
|HYPE_USDT|74.091000|-4.31|-15.50|-1.77|40894433|0.14|
|ZEC_USDT|1216.250000|-4.28|-1.74|-1.74|2109109090|0.25|
|AVAX_USDT|7.887000|-4.27|-10.02|-1.73|16694290|2.54|
|XLM_USDT|0.144950|-4.13|-13.90|-1.59|26028790|0.69|
|SOL_USDT|86.000000|-4.10|-9.24|-1.56|585832009|1.16|
|ADA_USDT|0.173300|-4.09|-10.20|-1.55|18991793|5.77|
|DOGE_USDT|0.068510|-3.96|-9.42|-1.42|66652615|1.46|
|NEAR_USDT|3.556000|-3.91|-17.89|-1.37|40470560|2.81|
|SUI_USDT|0.819100|-3.81|-9.02|-1.27|48988163|1.22|
|LINK_USDT|10.335000|-3.77|-11.02|-1.23|80439958|1.94|
|LIT_USDT|3.077200|-3.63|-4.73|-1.09|14018176|0.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.173300|0.173400|0.173300|1.21|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.004626|0.004549|0.004629|0.98|N|Y/Y|Y/N|Y|N|
|ASTER_USDT|0.632300|0.634000|0.632500|4.56|Y|Y/Y|Y/Y|Y|Y|
|AVAX_USDT|7.887000|7.877000|7.888000|1.08|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.068510|0.068650|0.068510|4.33|Y|Y/Y|Y/Y|Y|Y|
|ETH_USDT|2107.320000|2118.220000|2106.810000|3.88|Y|Y/Y|Y/Y|Y|Y|
|HYPE_USDT|74.091000|73.785000|74.091000|0.98|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008640|0.008120|0.008620|0.72|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001626|0.001615|0.001626|1.62|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003547|0.003528|0.003547|2.71|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.000000|86.050000|86.010000|0.80|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|214.250000|214.310000|214.250000|2.93|Y|Y/Y|Y/Y|Y|Y|
|XLM_USDT|0.144950|0.145040|0.144950|1.83|Y|Y/Y|Y/Y|Y|Y|
|XRP_USDT|1.087800|1.091900|1.087800|2.23|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1216.250000|1209.850000|1215.840000|1.19|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=0.177300, depth_time=2026-11-09T06:45:38+00:00, book20_bid_proxy_usdt=11878607, book20_ask_proxy_usdt=10504005, funding_indicative=0.000042, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.09%, turnover=18991793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=0.004787, depth_time=2026-11-09T06:45:08+00:00, book20_bid_proxy_usdt=62085, book20_ask_proxy_usdt=28987, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.64%, turnover=11346352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=0.641100, depth_time=2026-11-09T06:45:11+00:00, book20_bid_proxy_usdt=532032, book20_ask_proxy_usdt=752842, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.98%, turnover=5380266. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=8.050000, depth_time=2026-11-09T06:45:31+00:00, book20_bid_proxy_usdt=1005799, book20_ask_proxy_usdt=1840761, funding_indicative=0.000072, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.27%, turnover=16694290. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=0.069900, depth_time=2026-11-09T06:45:40+00:00, book20_bid_proxy_usdt=3290012, book20_ask_proxy_usdt=2302128, funding_indicative=0.000008, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.96%, turnover=66652615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=2145.110000, depth_time=2026-11-09T06:45:17+00:00, book20_bid_proxy_usdt=1702824, book20_ask_proxy_usdt=6828109, funding_indicative=-0.000031, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.96%, turnover=1306376435. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=75.000000, depth_time=2026-11-09T06:45:26+00:00, book20_bid_proxy_usdt=79108, book20_ask_proxy_usdt=51562, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.31%, turnover=40894433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=0.010737, depth_time=2026-11-09T06:45:12+00:00, book20_bid_proxy_usdt=31116, book20_ask_proxy_usdt=22012, funding_indicative=0.001494, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.14%, turnover=69764821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=0.001670, depth_time=2026-11-09T06:45:07+00:00, book20_bid_proxy_usdt=8862, book20_ask_proxy_usdt=10296, funding_indicative=-0.000137, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.96%, turnover=9779479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=0.003607, depth_time=2026-11-09T06:45:21+00:00, book20_bid_proxy_usdt=2975220, book20_ask_proxy_usdt=2447066, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.08%, turnover=9709367. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=87.830000, depth_time=2026-11-09T06:45:35+00:00, book20_bid_proxy_usdt=11844827, book20_ask_proxy_usdt=14461746, funding_indicative=-0.000085, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.10%, turnover=585832009. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=218.700000, depth_time=2026-11-09T06:45:21+00:00, book20_bid_proxy_usdt=147214, book20_ask_proxy_usdt=115974, funding_indicative=0.000048, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.21%, turnover=35037196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=0.147940, depth_time=2026-11-09T06:45:33+00:00, book20_bid_proxy_usdt=124256, book20_ask_proxy_usdt=139870, funding_indicative=0.000055, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.13%, turnover=26028790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=1.111600, depth_time=2026-11-09T06:45:19+00:00, book20_bid_proxy_usdt=2785682, book20_ask_proxy_usdt=4403036, funding_indicative=0.000007, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.88%, turnover=249592039. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T06:45:02+00:00, last15m_closed_end=2026-11-09T06:45+00:00, prior8high=1241.630000, depth_time=2026-11-09T06:45:28+00:00, book20_bid_proxy_usdt=861951, book20_ask_proxy_usdt=438066, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.28%, turnover=2109109090. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
