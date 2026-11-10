# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T14:00:45Z**
- feed_generated_utc: 2026-11-10T14:00:47+00:00
- source_sha256: `d822698c94537d11e80205fbc7fedab84dc8743d71813294d41e4fd1c9fa5a2a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T14:00+00:00, close=73714.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T14:00+00:00, close=73714.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002423|-49.00|-55.96|-46.64|13109938|4.12|
|JCT_USDT|0.007400|-32.56|71.41|-30.20|23317076|2.70|
|ANTHROPIC_USDT|1281.120000|-10.33|-23.68|-7.97|7436966|2.03|
|ARB_USDT|0.164300|-8.87|3.11|-6.51|36786997|0.61|
|QNT_USDT|182.770000|-8.58|-9.72|-6.22|34092923|4.92|
|XMR_USDT|552.400000|-8.09|-8.73|-5.73|6247088|1.99|
|AVAX_USDT|8.291000|-7.77|-2.47|-5.41|40088954|1.21|
|AAVE_USDT|125.220000|-5.50|-4.09|-3.14|10013296|0.80|
|ZEC_USDT|1163.430000|-5.08|-7.22|-2.72|2235779026|0.43|
|PUMPFUN_USDT|0.003505|-4.67|-14.59|-2.31|7867301|2.85|
|XRP_USDT|1.064500|-4.43|-14.73|-2.07|275515285|0.94|
|SOL_USDT|84.080000|-4.33|-10.08|-1.97|669718750|1.19|
|ETH_USDT|2064.810000|-3.81|-9.13|-1.45|1369296791|0.05|
|DOT_USDT|0.852400|-3.77|-8.74|-1.41|8097935|1.17|
|HYPE_USDT|73.240000|-3.64|-14.55|-1.28|45001915|0.14|
|SUI_USDT|0.830000|-3.39|-6.19|-1.03|36157940|1.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.220000|122.640000|125.220000|1.34|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002423|0.002353|0.002424|1.03|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1281.120000|1247.900000|1281.230000|3.05|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164300|0.161170|0.164300|1.33|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.291000|8.228000|8.299000|3.77|N|Y/Y|Y/N|Y|N|
|DOT_USDT|0.852400|0.838600|0.852400|1.51|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2064.810000|2030.110000|2064.830000|2.54|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.240000|72.730000|73.240000|1.47|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.007400|0.005597|0.007400|3.00|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003505|0.003428|0.003505|2.72|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|182.770000|178.810000|182.770000|2.16|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|84.080000|82.420000|84.080000|2.20|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|552.400000|544.080000|552.400000|0.54|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.064500|1.048300|1.064800|1.40|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1163.430000|1132.440000|1163.860000|2.38|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T14:00:01+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=125.920000, depth_time=2026-11-10T14:00:22+00:00, book20_bid_proxy_usdt=325948, book20_ask_proxy_usdt=283323, funding_indicative=0.000063, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.50%, turnover=10013296. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T14:00:01+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=0.002546, depth_time=2026-11-10T14:00:07+00:00, book20_bid_proxy_usdt=116538, book20_ask_proxy_usdt=80808, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-49.00%, turnover=13109938. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T14:00:01+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=1309.180000, depth_time=2026-11-10T14:00:11+00:00, book20_bid_proxy_usdt=12511, book20_ask_proxy_usdt=23240, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.33%, turnover=7436966. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T14:00:01+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=0.165950, depth_time=2026-11-10T14:00:12+00:00, book20_bid_proxy_usdt=64884, book20_ask_proxy_usdt=90265, funding_indicative=-0.000194, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.87%, turnover=36786997. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T14:00:01+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=8.412000, depth_time=2026-11-10T14:00:20+00:00, book20_bid_proxy_usdt=712296, book20_ask_proxy_usdt=680736, funding_indicative=-0.000063, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.77%, turnover=40088954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T14:00:01+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=0.860100, depth_time=2026-11-10T14:00:41+00:00, book20_bid_proxy_usdt=234932, book20_ask_proxy_usdt=440183, funding_indicative=0.000066, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.77%, turnover=8097935. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-10T14:00:00+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=2103.900000, depth_time=2026-11-10T14:00:37+00:00, book20_bid_proxy_usdt=3676053, book20_ask_proxy_usdt=2195537, funding_indicative=0.000025, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.81%, turnover=1369296791. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T14:00:01+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=74.000000, depth_time=2026-11-10T14:00:44+00:00, book20_bid_proxy_usdt=27868, book20_ask_proxy_usdt=48097, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.64%, turnover=45001915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T14:00:01+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=0.006588, depth_time=2026-11-10T14:00:09+00:00, book20_bid_proxy_usdt=22908, book20_ask_proxy_usdt=25939, funding_indicative=0.000057, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-32.56%, turnover=23317076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T14:00:01+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=0.003552, depth_time=2026-11-10T14:00:29+00:00, book20_bid_proxy_usdt=3629470, book20_ask_proxy_usdt=2763537, funding_indicative=-0.000028, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.67%, turnover=7867301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T14:00:01+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=188.280000, depth_time=2026-11-10T14:00:16+00:00, book20_bid_proxy_usdt=69415, book20_ask_proxy_usdt=81063, funding_indicative=-0.000064, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.58%, turnover=34092923. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T14:00:00+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=85.210000, depth_time=2026-11-10T14:00:35+00:00, book20_bid_proxy_usdt=15771278, book20_ask_proxy_usdt=16779633, funding_indicative=0.000067, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.33%, turnover=669718750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T14:00:01+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=555.790000, depth_time=2026-11-10T14:00:15+00:00, book20_bid_proxy_usdt=12749, book20_ask_proxy_usdt=9392, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.09%, turnover=6247088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-10T14:00:00+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=1.082900, depth_time=2026-11-10T14:00:32+00:00, book20_bid_proxy_usdt=3220864, book20_ask_proxy_usdt=3169323, funding_indicative=0.000094, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.43%, turnover=275515285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T14:00:01+00:00, last15m_closed_end=2026-11-10T14:00+00:00, prior8high=1162.010000, depth_time=2026-11-10T14:00:27+00:00, book20_bid_proxy_usdt=212902, book20_ask_proxy_usdt=80779, funding_indicative=0.000053, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.08%, turnover=2235779026. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
