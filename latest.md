# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T07:00:41Z**
- feed_generated_utc: 2026-11-09T07:00:42+00:00
- source_sha256: `43f4c89823e25b64fddaa2c05dc5bce396e9a6bd28f7c1a411c822c3693ce815`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T07:00+00:00, close=74275.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T07:00+00:00, close=74275.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T04:00+00:00, close=74818.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001623|-17.13|39.33|-14.82|9806843|0.62|
|AKE_USDT|0.004555|-14.97|-50.27|-12.66|11405343|4.39|
|ASTER_USDT|0.632800|-6.91|-9.52|-4.60|5453811|1.58|
|ETH_USDT|2112.490000|-5.73|-6.76|-3.42|1336442879|0.05|
|JCT_USDT|0.009273|-5.70|86.24|-3.39|70259146|5.39|
|XRP_USDT|1.091200|-5.58|-12.69|-3.27|252923399|0.92|
|TAO_USDT|214.350000|-5.16|-8.72|-2.85|36010355|1.40|
|PUMPFUN_USDT|0.003546|-5.11|-15.93|-2.80|9737948|2.82|
|ZEC_USDT|1211.260000|-4.67|-2.15|-2.36|2143526670|0.08|
|LIT_USDT|3.045700|-4.62|-5.70|-2.31|14059044|0.33|
|NEAR_USDT|3.538000|-4.40|-18.30|-2.09|40755221|2.83|
|HYPE_USDT|74.091000|-4.31|-15.50|-2.00|41175035|0.14|
|AVAX_USDT|7.892000|-4.21|-9.97|-1.90|16906408|1.27|
|ADA_USDT|0.173200|-4.15|-10.25|-1.84|19185338|5.77|
|SOL_USDT|86.020000|-4.08|-9.22|-1.77|599070233|1.16|
|XLM_USDT|0.145130|-4.02|-13.79|-1.71|26411896|0.69|
|DOGE_USDT|0.068700|-3.70|-9.17|-1.39|67748823|1.46|
|LINK_USDT|10.345000|-3.68|-10.93|-1.37|81790989|0.97|
|UNI_USDT|6.754000|-3.55|-6.91|-1.24|29608750|1.48|
|DOT_USDT|0.861000|-3.35|-9.08|-1.04|9411828|2.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.173200|0.172900|0.173200|1.91|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.004555|0.004549|0.004555|0.88|N|Y/Y|Y/N|Y|N|
|ASTER_USDT|0.632800|0.628000|0.632800|2.04|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|7.892000|7.877000|7.893000|2.65|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2112.490000|2105.180000|2112.490000|3.59|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|74.091000|73.785000|74.091000|1.23|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009273|0.008120|0.009273|1.42|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.045700|3.055600|3.046200|0.35|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.538000|3.530000|3.538000|1.28|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001623|0.001613|0.001623|0.76|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003546|0.003528|0.003546|0.41|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.020000|85.860000|86.020000|2.73|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|214.350000|213.930000|214.350000|3.41|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.091200|1.085500|1.091300|1.52|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1211.260000|1209.850000|1211.080000|1.54|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=0.176600, depth_time=2026-11-09T07:00:37+00:00, book20_bid_proxy_usdt=11128407, book20_ask_proxy_usdt=9298191, funding_indicative=0.000047, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.15%, turnover=19185338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=0.004713, depth_time=2026-11-09T07:00:08+00:00, book20_bid_proxy_usdt=46943, book20_ask_proxy_usdt=60582, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.97%, turnover=11405343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=0.641100, depth_time=2026-11-09T07:00:10+00:00, book20_bid_proxy_usdt=926132, book20_ask_proxy_usdt=618432, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.91%, turnover=5453811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=8.015000, depth_time=2026-11-09T07:00:34+00:00, book20_bid_proxy_usdt=1492850, book20_ask_proxy_usdt=1025996, funding_indicative=0.000071, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.21%, turnover=16906408. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=2140.400000, depth_time=2026-11-09T07:00:13+00:00, book20_bid_proxy_usdt=1985938, book20_ask_proxy_usdt=10828033, funding_indicative=-0.000029, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.73%, turnover=1336442879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=74.624000, depth_time=2026-11-09T07:00:32+00:00, book20_bid_proxy_usdt=112764, book20_ask_proxy_usdt=65282, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.31%, turnover=41175035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=0.010737, depth_time=2026-11-09T07:00:16+00:00, book20_bid_proxy_usdt=29066, book20_ask_proxy_usdt=43788, funding_indicative=0.001472, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.70%, turnover=70259146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=3.128100, depth_time=2026-11-09T07:00:27+00:00, book20_bid_proxy_usdt=28638, book20_ask_proxy_usdt=32566, funding_indicative=-0.000043, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.62%, turnover=14059044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=3.622000, depth_time=2026-11-09T07:00:29+00:00, book20_bid_proxy_usdt=1732636, book20_ask_proxy_usdt=2080730, funding_indicative=0.000100, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.40%, turnover=40755221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=0.001670, depth_time=2026-11-09T07:00:06+00:00, book20_bid_proxy_usdt=9952, book20_ask_proxy_usdt=9919, funding_indicative=-0.000148, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-17.13%, turnover=9806843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=0.003596, depth_time=2026-11-09T07:00:23+00:00, book20_bid_proxy_usdt=2528162, book20_ask_proxy_usdt=2242546, funding_indicative=0.000044, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.11%, turnover=9737948. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=87.550000, depth_time=2026-11-09T07:00:40+00:00, book20_bid_proxy_usdt=14507198, book20_ask_proxy_usdt=11495394, funding_indicative=-0.000077, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.08%, turnover=599070233. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=218.100000, depth_time=2026-11-09T07:00:20+00:00, book20_bid_proxy_usdt=90490, book20_ask_proxy_usdt=106164, funding_indicative=0.000050, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.16%, turnover=36010355. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=1.107600, depth_time=2026-11-09T07:00:18+00:00, book20_bid_proxy_usdt=2763190, book20_ask_proxy_usdt=3213578, funding_indicative=0.000021, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.58%, turnover=252923399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T06:59:59+00:00, last15m_closed_end=2026-11-09T07:00+00:00, prior8high=1236.620000, depth_time=2026-11-09T07:00:25+00:00, book20_bid_proxy_usdt=576790, book20_ask_proxy_usdt=108555, funding_indicative=0.000072, next_funding_utc=2026-11-09T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.67%, turnover=2143526670. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
