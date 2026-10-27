# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T04:30:38Z**
- feed_generated_utc: 2026-10-27T04:30:42+00:00
- source_sha256: `28bf499507e399632807afa249c29eb576b24b83b859bc31296e37c5df0c776a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T04:30+00:00, close=79708.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|200.890000|-4.46|2.65|-3.60|124516222|0.50|
|PUMPFUN_USDT|0.004145|-4.22|-6.97|-3.36|21153501|2.41|
|NEAR_USDT|4.421000|-3.32|-9.84|-2.46|101439520|2.26|
|AAVE_USDT|132.280000|-3.25|-10.14|-2.39|24997696|0.76|
|DOT_USDT|0.990200|-3.16|-13.65|-2.30|10832579|1.01|
|FET_USDT|0.171400|-2.94|-9.31|-2.08|6546360|5.83|
|ONDO_USDT|0.406500|-2.93|-6.03|-2.07|22592090|2.46|
|FILECOIN_USDT|0.895000|-2.79|-11.56|-1.93|6449009|1.12|
|AVAX_USDT|8.754000|-2.70|-8.45|-1.84|57686256|1.14|
|ICP_USDT|2.574000|-2.12|-9.77|-1.26|5025518|3.89|
|WLD_USDT|0.435600|-2.11|-13.96|-1.25|70522395|2.29|
|PENGU_USDT|0.007417|-2.07|-0.98|-1.21|5525617|1.35|
|ARB_USDT|0.166510|-2.04|-14.88|-1.18|20459003|0.60|
|TAO_USDT|248.340000|-2.03|-7.43|-1.17|46116008|1.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.280000|132.250000|132.280000|0.32|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166510|0.165910|0.166520|0.23|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.754000|8.758000|8.757000|1.00|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.990200|0.988500|0.990200|0.93|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.171400|0.170600|0.171400|0.88|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.895000|0.892600|0.895000|0.24|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.574000|2.562000|2.575000|0.14|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.421000|4.389000|4.420000|0.30|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.406500|0.404300|0.406500|0.45|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007417|0.007387|0.007417|0.35|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004145|0.004118|0.004145|0.79|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|200.890000|199.100000|200.780000|1.28|N|Y/Y|N/N|Y|N|
|TAO_USDT|248.340000|247.350000|248.340000|0.27|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.435600|0.433900|0.435600|0.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T04:30:03+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=134.430000, depth_time=2026-10-27T04:30:13+00:00, book20_bid_proxy_usdt=377129, book20_ask_proxy_usdt=312990, funding_indicative=0.000088, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=24997696. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T04:30:03+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=0.168300, depth_time=2026-10-27T04:30:35+00:00, book20_bid_proxy_usdt=90069, book20_ask_proxy_usdt=131048, funding_indicative=0.000000, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=20459003. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T04:30:03+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=8.887000, depth_time=2026-10-27T04:30:25+00:00, book20_bid_proxy_usdt=1964830, book20_ask_proxy_usdt=933642, funding_indicative=-0.000047, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=57686256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T04:30:03+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=0.999600, depth_time=2026-10-27T04:30:12+00:00, book20_bid_proxy_usdt=267784, book20_ask_proxy_usdt=495196, funding_indicative=-0.000127, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=10832579. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T04:30:03+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=0.173600, depth_time=2026-10-27T04:30:16+00:00, book20_bid_proxy_usdt=1881200, book20_ask_proxy_usdt=1196066, funding_indicative=0.000055, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=6546360. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T04:30:03+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=0.904300, depth_time=2026-10-27T04:30:24+00:00, book20_bid_proxy_usdt=1066878, book20_ask_proxy_usdt=1358347, funding_indicative=-0.000038, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=6449009. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T04:30:03+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=2.595000, depth_time=2026-10-27T04:30:29+00:00, book20_bid_proxy_usdt=1143433, book20_ask_proxy_usdt=1082718, funding_indicative=0.000057, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=5025518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T04:30:02+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=4.470000, depth_time=2026-10-27T04:30:11+00:00, book20_bid_proxy_usdt=4497838, book20_ask_proxy_usdt=4058345, funding_indicative=0.000044, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.32%, turnover=101439520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T04:30:02+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=0.409600, depth_time=2026-10-27T04:30:21+00:00, book20_bid_proxy_usdt=2144582, book20_ask_proxy_usdt=2430389, funding_indicative=0.000028, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=22592090. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T04:30:03+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=0.007483, depth_time=2026-10-27T04:30:32+00:00, book20_bid_proxy_usdt=285140, book20_ask_proxy_usdt=233868, funding_indicative=-0.000006, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=5525617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T04:30:03+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=0.004221, depth_time=2026-10-27T04:30:09+00:00, book20_bid_proxy_usdt=2205828, book20_ask_proxy_usdt=2296040, funding_indicative=0.000025, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.22%, turnover=21153501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T04:30:02+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=205.330000, depth_time=2026-10-27T04:30:08+00:00, book20_bid_proxy_usdt=37803, book20_ask_proxy_usdt=82463, funding_indicative=-0.000112, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.46%, turnover=124516222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T04:30:02+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=249.630000, depth_time=2026-10-27T04:30:37+00:00, book20_bid_proxy_usdt=115039, book20_ask_proxy_usdt=132719, funding_indicative=0.000030, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.03%, turnover=46116008. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T04:30:02+00:00, last15m_closed_end=2026-10-27T04:30+00:00, prior8high=0.440800, depth_time=2026-10-27T04:30:31+00:00, book20_bid_proxy_usdt=3995134, book20_ask_proxy_usdt=3297634, funding_indicative=-0.000199, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=70522395. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
