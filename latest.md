# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-22T23:15:42Z**
- feed_generated_utc: 2026-10-22T23:15:45+00:00
- source_sha256: `0345254a3794f79478770130ca89d501ee5581765fcecbfb53aa9daf5a10b06f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-22T23:15+00:00, close=81339.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-22T23:00+00:00, close=81314.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-22T20:00+00:00, close=81462.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.423500|-5.27|10.74|-4.90|14875958|0.29|
|ARB_USDT|0.178200|-2.96|-6.18|-2.59|32899739|1.68|
|PUMPFUN_USDT|0.004548|-2.79|0.48|-2.42|36884048|2.20|
|APT_USDT|0.751500|-2.68|-9.09|-2.31|9013806|1.33|
|XPL_USDT|0.075510|-2.56|-10.89|-2.19|5662533|1.32|
|STRK_USDT|0.052970|-2.55|-45.02|-2.18|13628542|1.89|
|QNT_USDT|186.490000|-2.21|-10.30|-1.84|59827554|0.54|
|XMR_USDT|600.000000|-2.10|10.30|-1.73|26861470|0.17|
|EIGEN_USDT|0.217000|-1.98|-12.50|-1.61|6057016|4.61|
|PHA_USDT|0.060840|-1.95|20.42|-1.58|8404515|8.22|
|SEI_USDT|0.056950|-1.92|-7.33|-1.55|10764518|1.76|
|TIA_USDT|0.557800|-1.86|-7.41|-1.49|23845801|1.79|
|OP_USDT|0.117770|-1.73|-15.19|-1.36|6973566|0.85|
|ZEC_USDT|1212.980000|-1.72|2.81|-1.35|1856581400|0.08|
|NEAR_USDT|4.869000|-1.51|-4.88|-1.14|148822779|2.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.751500|0.753600|0.751500|4.83|Y|Y/Y|Y/Y|Y|Y|
|ARB_USDT|0.178200|0.178400|0.178250|1.53|Y|Y/Y|Y/Y|Y|Y|
|EIGEN_USDT|0.217000|0.216900|0.217000|0.08|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.423500|3.378800|3.423500|2.05|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.869000|4.848000|4.869000|0.34|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.117770|0.117600|0.117770|1.40|N|Y/Y|Y/Y|Y|N|
|PHA_USDT|0.060840|0.060580|0.060840|0.34|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004548|0.004525|0.004548|0.57|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|186.490000|186.130000|186.490000|0.96|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.056950|0.056980|0.056950|0.79|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052970|0.052550|0.052970|1.27|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.557800|0.556100|0.557800|1.04|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|600.000000|586.430000|600.000000|1.25|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.075510|0.075400|0.075510|5.55|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1212.980000|1203.410000|1212.980000|0.58|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=0.764700, depth_time=2026-10-22T23:15:14+00:00, book20_bid_proxy_usdt=210248, book20_ask_proxy_usdt=146414, funding_indicative=-0.000052, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.68%, turnover=9013806. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=0.182560, depth_time=2026-10-22T23:15:08+00:00, book20_bid_proxy_usdt=94210, book20_ask_proxy_usdt=82492, funding_indicative=-0.000137, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=32899739. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=0.220100, depth_time=2026-10-22T23:15:26+00:00, book20_bid_proxy_usdt=846968, book20_ask_proxy_usdt=563810, funding_indicative=-0.000002, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.98%, turnover=6057016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=3.594800, depth_time=2026-10-22T23:15:06+00:00, book20_bid_proxy_usdt=35878, book20_ask_proxy_usdt=18925, funding_indicative=0.000050, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.27%, turnover=14875958. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=4.941000, depth_time=2026-10-22T23:15:41+00:00, book20_bid_proxy_usdt=2917672, book20_ask_proxy_usdt=2756702, funding_indicative=0.000055, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=148822779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=0.119290, depth_time=2026-10-22T23:15:36+00:00, book20_bid_proxy_usdt=168380, book20_ask_proxy_usdt=130090, funding_indicative=-0.000181, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=6973566. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=0.062290, depth_time=2026-10-22T23:15:29+00:00, book20_bid_proxy_usdt=79513, book20_ask_proxy_usdt=96125, funding_indicative=-0.000478, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=8404515. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=0.004685, depth_time=2026-10-22T23:15:12+00:00, book20_bid_proxy_usdt=1940289, book20_ask_proxy_usdt=2118191, funding_indicative=0.000016, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=36884048. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=190.190000, depth_time=2026-10-22T23:15:21+00:00, book20_bid_proxy_usdt=71627, book20_ask_proxy_usdt=85639, funding_indicative=-0.000161, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=59827554. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=0.057790, depth_time=2026-10-22T23:15:27+00:00, book20_bid_proxy_usdt=523985, book20_ask_proxy_usdt=269486, funding_indicative=-0.000015, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=10764518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=0.053720, depth_time=2026-10-22T23:15:19+00:00, book20_bid_proxy_usdt=569498, book20_ask_proxy_usdt=708085, funding_indicative=0.000037, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.55%, turnover=13628542. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=0.566700, depth_time=2026-10-22T23:15:33+00:00, book20_bid_proxy_usdt=319644, book20_ask_proxy_usdt=311094, funding_indicative=-0.000006, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=23845801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=602.970000, depth_time=2026-10-22T23:15:23+00:00, book20_bid_proxy_usdt=13727, book20_ask_proxy_usdt=10298, funding_indicative=0.000100, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=26861470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=0.076450, depth_time=2026-10-22T23:15:16+00:00, book20_bid_proxy_usdt=660604, book20_ask_proxy_usdt=578354, funding_indicative=0.000001, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=5662533. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-22T23:15:00+00:00, last15m_closed_end=2026-10-22T23:15+00:00, prior8high=1225.760000, depth_time=2026-10-22T23:15:39+00:00, book20_bid_proxy_usdt=91740, book20_ask_proxy_usdt=340435, funding_indicative=0.000063, next_funding_utc=2026-10-23T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=1856581400. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
