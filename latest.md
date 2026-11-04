# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T01:30:43Z**
- feed_generated_utc: 2026-11-04T01:30:46+00:00
- source_sha256: `1e26ad0ba749c227cc48f36000b3961b0c2b39319978c20829d63488d748c3a3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T01:30+00:00, close=76942.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T01:00+00:00, close=77225.9, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T00:00+00:00, close=77441.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003844|-7.50|-81.80|-6.58|13472263|2.60|
|TRUMPOFFICIAL_USDT|1.510000|-6.09|-10.54|-5.17|6783582|6.62|
|STRK_USDT|0.041610|-5.71|-9.77|-4.79|5496719|2.40|
|HYPE_USDT|83.223000|-4.72|4.73|-3.80|68393667|1.08|
|XPL_USDT|0.061480|-4.01|-16.71|-3.09|7486777|1.63|
|XLM_USDT|0.159610|-3.14|-5.67|-2.22|34450213|1.25|
|QNT_USDT|189.750000|-2.90|-4.11|-1.98|60500091|1.05|
|LINK_USDT|10.844000|-2.77|-5.30|-1.85|169792420|1.84|
|OP_USDT|0.107390|-2.75|-3.53|-1.83|9111236|0.93|
|ARB_USDT|0.155510|-2.73|-7.70|-1.81|17240493|0.64|
|FARTCOIN_USDT|0.116320|-2.54|-10.71|-1.62|11370914|0.86|
|AVAX_USDT|8.359000|-2.50|-5.58|-1.58|19574604|1.20|
|TAO_USDT|222.020000|-2.41|-11.61|-1.49|33431174|1.35|
|DASH_USDT|45.040000|-2.38|-16.85|-1.46|10947712|2.22|
|AAVE_USDT|125.410000|-2.36|-5.47|-1.44|21912038|8.77|
|XRP_USDT|1.251400|-2.29|-5.24|-1.37|270989535|0.80|
|HBAR_USDT|0.068470|-2.22|-10.04|-1.30|5824775|2.92|
|ADA_USDT|0.186700|-2.20|-9.19|-1.28|21483393|5.36|
|NEAR_USDT|3.781000|-2.02|-17.11|-1.10|67743133|2.65|
|SOL_USDT|91.840000|-2.00|-8.99|-1.08|490568016|1.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.410000|124.670000|125.470000|1.67|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.003844|0.003787|0.003844|1.33|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.155510|0.154430|0.155510|1.56|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.359000|8.348000|8.359000|2.23|N|Y/Y|Y/N|Y|N|
|DASH_USDT|45.040000|44.790000|45.040000|1.10|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.116320|0.115500|0.116320|1.63|N|Y/N|Y/Y|Y|N|
|HYPE_USDT|83.223000|83.128000|83.295000|1.87|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.844000|10.794000|10.843000|2.57|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.107390|0.107070|0.107390|0.65|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.750000|188.930000|189.820000|0.81|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.041610|0.041520|0.041610|1.25|N|Y/Y|Y/N|Y|N|
|TAO_USDT|222.020000|221.120000|222.020000|1.34|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.510000|1.504000|1.510000|5.23|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.159610|0.158870|0.159700|1.45|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.061480|0.061250|0.061480|1.06|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=128.110000, depth_time=2026-11-04T01:30:41+00:00, book20_bid_proxy_usdt=229702, book20_ask_proxy_usdt=398286, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.36%, turnover=21912038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=0.004026, depth_time=2026-11-04T01:30:07+00:00, book20_bid_proxy_usdt=26059, book20_ask_proxy_usdt=34052, funding_indicative=-0.000644, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.50%, turnover=13472263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=0.159660, depth_time=2026-11-04T01:30:31+00:00, book20_bid_proxy_usdt=64360, book20_ask_proxy_usdt=73981, funding_indicative=0.000030, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=17240493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=8.594000, depth_time=2026-11-04T01:30:35+00:00, book20_bid_proxy_usdt=1482151, book20_ask_proxy_usdt=825820, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=19574604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=46.700000, depth_time=2026-11-04T01:30:39+00:00, book20_bid_proxy_usdt=692148, book20_ask_proxy_usdt=671953, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=10947712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=0.120280, depth_time=2026-11-04T01:30:33+00:00, book20_bid_proxy_usdt=60424, book20_ask_proxy_usdt=93822, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.54%, turnover=11370914. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=85.946000, depth_time=2026-11-04T01:30:16+00:00, book20_bid_proxy_usdt=38571, book20_ask_proxy_usdt=212480, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.72%, turnover=68393667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=11.152000, depth_time=2026-11-04T01:30:26+00:00, book20_bid_proxy_usdt=390276, book20_ask_proxy_usdt=394393, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.77%, turnover=169792420. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=0.110510, depth_time=2026-11-04T01:30:28+00:00, book20_bid_proxy_usdt=83777, book20_ask_proxy_usdt=87623, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=9111236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=193.440000, depth_time=2026-11-04T01:30:23+00:00, book20_bid_proxy_usdt=53136, book20_ask_proxy_usdt=85135, funding_indicative=-0.000039, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=60500091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=0.042850, depth_time=2026-11-04T01:30:12+00:00, book20_bid_proxy_usdt=375554, book20_ask_proxy_usdt=290811, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.71%, turnover=5496719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=227.970000, depth_time=2026-11-04T01:30:37+00:00, book20_bid_proxy_usdt=263672, book20_ask_proxy_usdt=305182, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.41%, turnover=33431174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=1.602000, depth_time=2026-11-04T01:30:10+00:00, book20_bid_proxy_usdt=1873055, book20_ask_proxy_usdt=1919514, funding_indicative=0.000000, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.09%, turnover=6783582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=0.163410, depth_time=2026-11-04T01:30:21+00:00, book20_bid_proxy_usdt=85249, book20_ask_proxy_usdt=212796, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.14%, turnover=34450213. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-04T01:30:03+00:00, last15m_closed_end=2026-11-04T01:30+00:00, prior8high=0.064100, depth_time=2026-11-04T01:30:19+00:00, book20_bid_proxy_usdt=367139, book20_ask_proxy_usdt=333893, funding_indicative=0.000043, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.01%, turnover=7486777. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
