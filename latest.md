# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T02:30:44Z**
- feed_generated_utc: 2026-10-17T02:30:46+00:00
- source_sha256: `c66319557ab1f90ec53ed4addae48607f44c88be9fa708e00f1ecd5520900939`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T02:30+00:00, close=81404.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T02:00+00:00, close=81511.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BR_USDT|0.368860|-21.46|-27.29|-21.54|11371014|7.86|
|ZRO_USDT|1.953900|-7.01|-4.07|-7.09|15824568|0.51|
|RIVER_USDT|1.076000|-4.44|-8.96|-4.52|5405752|9.29|
|ZEC_USDT|1144.090000|-3.69|-6.09|-3.77|1387982647|0.09|
|ARB_USDT|0.188510|-3.29|4.26|-3.37|31728288|0.53|
|TAO_USDT|273.800000|-2.43|-0.31|-2.51|80080921|1.10|
|STRK_USDT|0.072240|-2.31|-4.07|-2.39|21409885|1.39|
|FET_USDT|0.195000|-2.30|-10.13|-2.38|11490970|5.12|
|INJ_USDT|8.772000|-2.29|26.59|-2.37|113189273|1.14|
|APT_USDT|0.839300|-1.96|4.84|-2.04|12651861|1.19|
|AAVE_USDT|154.490000|-1.77|-9.03|-1.85|30862482|1.29|
|SUI_USDT|1.002600|-1.75|-5.20|-1.83|97516004|1.00|
|ENA_USDT|0.196640|-1.64|-8.78|-1.72|40743308|0.51|
|ONDO_USDT|0.450100|-1.53|-6.24|-1.61|28736047|2.22|
|ICP_USDT|2.993000|-1.48|-0.86|-1.56|8990181|3.34|
|AVAX_USDT|9.939000|-1.42|-2.48|-1.50|124453900|1.01|
|FARTCOIN_USDT|0.152590|-1.37|-6.59|-1.45|7148296|0.66|
|SEI_USDT|0.063640|-1.02|-2.81|-1.10|19102643|1.57|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.490000|153.940000|154.490000|1.92|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.839300|0.833600|0.839300|1.18|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.188510|0.188590|0.188510|2.01|Y|Y/Y|N/N|Y|N|
|BR_USDT|0.368860|0.372590|0.368860|0.94|N|Y/N|N/N|Y|N|
|ENA_USDT|0.196640|0.196360|0.196640|1.14|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.195000|0.194100|0.195000|2.83|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.993000|2.986000|2.993000|0.57|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.772000|8.619000|8.772000|0.55|N|N/Y|N/N|Y|N|
|ONDO_USDT|0.450100|0.448400|0.450100|0.61|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.076000|1.075000|1.076000|0.19|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.072240|0.071710|0.072240|4.06|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.002600|1.001200|1.002600|0.77|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|273.800000|273.080000|273.800000|0.82|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1144.090000|1141.130000|1144.090000|1.21|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.953900|1.938500|1.953900|0.34|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T02:30:00+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=155.480000, depth_time=2026-10-17T02:30:33+00:00, book20_bid_proxy_usdt=269661, book20_ask_proxy_usdt=325461, funding_indicative=0.000053, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=30862482. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T02:30:00+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=0.848700, depth_time=2026-10-17T02:30:29+00:00, book20_bid_proxy_usdt=122563, book20_ask_proxy_usdt=135806, funding_indicative=0.000048, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=12651861. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T02:29:59+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=0.191280, depth_time=2026-10-17T02:30:18+00:00, book20_bid_proxy_usdt=46568, book20_ask_proxy_usdt=66993, funding_indicative=-0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.29%, turnover=31728288. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-17T02:29:59+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=0.408840, depth_time=2026-10-17T02:30:09+00:00, book20_bid_proxy_usdt=2325, book20_ask_proxy_usdt=5110, funding_indicative=-0.004267, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-21.46%, turnover=11371014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T02:30:00+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=0.198780, depth_time=2026-10-17T02:30:37+00:00, book20_bid_proxy_usdt=203565, book20_ask_proxy_usdt=214728, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.64%, turnover=40743308. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T02:30:00+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=0.198200, depth_time=2026-10-17T02:30:25+00:00, book20_bid_proxy_usdt=2016833, book20_ask_proxy_usdt=1056389, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.30%, turnover=11490970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-17T02:30:00+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=3.023000, depth_time=2026-10-17T02:30:42+00:00, book20_bid_proxy_usdt=1094699, book20_ask_proxy_usdt=1250587, funding_indicative=0.000082, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=8990181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T02:29:59+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=8.886000, depth_time=2026-10-17T02:30:28+00:00, book20_bid_proxy_usdt=221061, book20_ask_proxy_usdt=255110, funding_indicative=0.000105, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.29%, turnover=113189273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-17T02:30:00+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=0.453800, depth_time=2026-10-17T02:30:40+00:00, book20_bid_proxy_usdt=1944950, book20_ask_proxy_usdt=2134646, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=28736047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T02:30:00+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=1.093000, depth_time=2026-10-17T02:30:07+00:00, book20_bid_proxy_usdt=491864, book20_ask_proxy_usdt=390259, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.44%, turnover=5405752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T02:30:00+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=0.074750, depth_time=2026-10-17T02:30:23+00:00, book20_bid_proxy_usdt=309208, book20_ask_proxy_usdt=289873, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=21409885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T02:29:59+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=1.014600, depth_time=2026-10-17T02:30:35+00:00, book20_bid_proxy_usdt=990428, book20_ask_proxy_usdt=1233525, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=97516004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T02:29:59+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=275.950000, depth_time=2026-10-17T02:30:20+00:00, book20_bid_proxy_usdt=99608, book20_ask_proxy_usdt=146712, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.43%, turnover=80080921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T02:29:59+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=1157.920000, depth_time=2026-10-17T02:30:16+00:00, book20_bid_proxy_usdt=489573, book20_ask_proxy_usdt=218834, funding_indicative=0.000078, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=1387982647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T02:29:59+00:00, last15m_closed_end=2026-10-17T02:30+00:00, prior8high=2.010300, depth_time=2026-10-17T02:30:10+00:00, book20_bid_proxy_usdt=68838, book20_ask_proxy_usdt=28701, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.01%, turnover=15824568. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
