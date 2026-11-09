# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T06:30:44Z**
- feed_generated_utc: 2026-11-09T06:30:46+00:00
- source_sha256: `b3c3da8202b2bcfcc6ff2813c42360a08eaa436771f8338b49efbaf2e8eb7251`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T06:30+00:00, close=74268.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T06:00+00:00, close=74440.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001634|-16.56|40.28|-14.25|9722006|0.61|
|AKE_USDT|0.004602|-14.09|-49.75|-11.78|11281289|2.17|
|JCT_USDT|0.008831|-10.19|77.36|-7.88|69523658|4.53|
|ASTER_USDT|0.634100|-6.72|-9.33|-4.41|5243263|3.15|
|ETH_USDT|2118.770000|-5.45|-6.48|-3.14|1273835647|0.05|
|XRP_USDT|1.093000|-5.43|-12.55|-3.12|244673864|0.92|
|PUMPFUN_USDT|0.003543|-5.19|-16.00|-2.88|9520348|2.82|
|TAO_USDT|214.660000|-5.03|-8.59|-2.72|34217734|1.40|
|NEAR_USDT|3.541000|-4.32|-18.24|-2.01|40378804|2.82|
|AVAX_USDT|7.892000|-4.21|-9.97|-1.90|16632033|1.27|
|HYPE_USDT|74.222000|-4.14|-15.35|-1.83|40668650|0.14|
|XLM_USDT|0.145090|-4.04|-13.82|-1.73|25643435|1.38|
|ZEC_USDT|1219.810000|-4.00|-1.46|-1.69|2082288204|0.08|
|ADA_USDT|0.173700|-3.87|-10.00|-1.56|18870199|5.75|
|LIT_USDT|3.069900|-3.86|-4.95|-1.55|13934660|0.33|
|SOL_USDT|86.260000|-3.81|-8.97|-1.50|581374876|1.16|
|LINK_USDT|10.350000|-3.64|-10.89|-1.33|79413409|1.93|
|DOGE_USDT|0.068840|-3.50|-8.98|-1.19|65056200|1.45|
|ONDO_USDT|0.349900|-3.34|-13.90|-1.03|11776251|2.86|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.173700|0.174300|0.173700|2.32|Y|Y/Y|Y/Y|Y|Y|
|AKE_USDT|0.004602|0.004549|0.004601|1.25|N|Y/Y|Y/N|Y|N|
|ASTER_USDT|0.634100|0.636400|0.634100|1.91|Y|Y/Y|Y/Y|Y|Y|
|AVAX_USDT|7.892000|7.910000|7.892000|2.85|Y|Y/Y|Y/Y|Y|Y|
|ETH_USDT|2118.770000|2126.320000|2118.940000|2.28|Y|Y/Y|Y/Y|Y|Y|
|HYPE_USDT|74.222000|73.785000|74.222000|1.11|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008831|0.008120|0.008840|0.82|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.069900|3.074900|3.069900|0.26|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.541000|3.546000|3.541000|2.79|Y|Y/Y|Y/Y|Y|Y|
|ONE_USDT|0.001634|0.001615|0.001634|1.70|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003543|0.003538|0.003543|1.25|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|214.660000|215.110000|214.660000|2.81|Y|Y/Y|Y/Y|Y|Y|
|XLM_USDT|0.145090|0.145430|0.145080|1.83|Y|Y/Y|Y/Y|Y|Y|
|XRP_USDT|1.093000|1.091900|1.093000|1.73|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1219.810000|1213.580000|1219.620000|1.09|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=0.177300, depth_time=2026-11-09T06:30:40+00:00, book20_bid_proxy_usdt=10690189, book20_ask_proxy_usdt=9512027, funding_indicative=0.000047, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.87%, turnover=18870199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=0.004875, depth_time=2026-11-09T06:30:10+00:00, book20_bid_proxy_usdt=42079, book20_ask_proxy_usdt=39291, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.09%, turnover=11281289. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=0.641100, depth_time=2026-11-09T06:30:14+00:00, book20_bid_proxy_usdt=578057, book20_ask_proxy_usdt=579996, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.72%, turnover=5243263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=8.050000, depth_time=2026-11-09T06:30:30+00:00, book20_bid_proxy_usdt=966873, book20_ask_proxy_usdt=2258181, funding_indicative=0.000076, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.21%, turnover=16632033. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=2145.760000, depth_time=2026-11-09T06:30:17+00:00, book20_bid_proxy_usdt=2187520, book20_ask_proxy_usdt=3677165, funding_indicative=-0.000033, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.45%, turnover=1273835647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=75.000000, depth_time=2026-11-09T06:30:32+00:00, book20_bid_proxy_usdt=121558, book20_ask_proxy_usdt=95916, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.14%, turnover=40668650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=0.010737, depth_time=2026-11-09T06:30:12+00:00, book20_bid_proxy_usdt=22264, book20_ask_proxy_usdt=16373, funding_indicative=0.001589, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.19%, turnover=69523658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=3.128100, depth_time=2026-11-09T06:30:42+00:00, book20_bid_proxy_usdt=21655, book20_ask_proxy_usdt=24422, funding_indicative=-0.000042, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.86%, turnover=13934660. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=3.638000, depth_time=2026-11-09T06:30:28+00:00, book20_bid_proxy_usdt=1771142, book20_ask_proxy_usdt=2918610, funding_indicative=0.000100, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.32%, turnover=40378804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=0.001670, depth_time=2026-11-09T06:30:07+00:00, book20_bid_proxy_usdt=13104, book20_ask_proxy_usdt=8878, funding_indicative=-0.000093, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.56%, turnover=9722006. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=0.003607, depth_time=2026-11-09T06:30:23+00:00, book20_bid_proxy_usdt=2684606, book20_ask_proxy_usdt=2821610, funding_indicative=0.000047, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.19%, turnover=9520348. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=218.700000, depth_time=2026-11-09T06:30:25+00:00, book20_bid_proxy_usdt=111123, book20_ask_proxy_usdt=109734, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.03%, turnover=34217734. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=0.147940, depth_time=2026-11-09T06:30:35+00:00, book20_bid_proxy_usdt=173553, book20_ask_proxy_usdt=112967, funding_indicative=0.000058, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.04%, turnover=25643435. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=1.114500, depth_time=2026-11-09T06:30:20+00:00, book20_bid_proxy_usdt=2949677, book20_ask_proxy_usdt=3005961, funding_indicative=0.000002, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.43%, turnover=244673864. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T06:30:01+00:00, last15m_closed_end=2026-11-09T06:30+00:00, prior8high=1241.630000, depth_time=2026-11-09T06:30:38+00:00, book20_bid_proxy_usdt=274884, book20_ask_proxy_usdt=372483, funding_indicative=0.000041, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.00%, turnover=2082288204. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
