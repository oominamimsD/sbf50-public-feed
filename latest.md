# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T14:45:41Z**
- feed_generated_utc: 2026-11-10T14:45:43+00:00
- source_sha256: `d221e590bab601a42dc179743e5a8f2fb0724efa748dd19be078a3e316d2f965`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T14:45+00:00, close=74277.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T14:00+00:00, close=73714.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002695|-44.96|-51.01|-43.35|13639175|3.71|
|JCT_USDT|0.007000|-30.90|62.14|-29.29|25168726|5.68|
|ARB_USDT|0.165450|-10.10|3.84|-8.49|38282684|0.60|
|ANTHROPIC_USDT|1290.870000|-9.64|-23.10|-8.03|7623152|2.48|
|XMR_USDT|551.020000|-8.74|-8.96|-7.13|6368758|0.91|
|QNT_USDT|183.310000|-8.36|-9.45|-6.75|36407941|6.55|
|AAVE_USDT|124.780000|-6.42|-4.42|-4.81|10455313|0.80|
|AVAX_USDT|8.414000|-6.40|-1.02|-4.79|41298587|1.19|
|XRP_USDT|1.064900|-4.39|-14.69|-2.78|292190664|0.94|
|FILECOIN_USDT|0.756200|-4.14|-12.80|-2.53|5166588|1.32|
|PUMPFUN_USDT|0.003530|-4.12|-13.98|-2.51|8235879|2.83|
|SOL_USDT|84.440000|-3.92|-9.69|-2.31|704998960|1.18|
|HYPE_USDT|73.359000|-3.87|-14.41|-2.26|48024793|0.14|
|DOT_USDT|0.858100|-3.68|-8.13|-2.07|8274429|1.17|
|XLM_USDT|0.145310|-2.90|-13.29|-1.29|25100665|2.06|
|ADA_USDT|0.177100|-2.90|-6.69|-1.29|23012815|5.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|124.780000|122.640000|124.780000|4.34|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002695|0.002383|0.002695|1.65|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1290.870000|1274.190000|1290.870000|0.44|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.165450|0.161200|0.165450|3.55|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.414000|8.228000|8.414000|2.67|N|Y/Y|Y/N|Y|N|
|DOT_USDT|0.858100|0.838600|0.858100|1.42|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.756200|0.746800|0.756200|1.52|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.359000|72.598000|73.359000|7.01|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.007000|0.005860|0.007030|3.74|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003530|0.003428|0.003530|3.79|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|183.310000|178.810000|183.200000|2.84|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|84.440000|82.420000|84.440000|5.19|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.145310|0.143500|0.145300|1.72|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|551.020000|544.080000|550.990000|1.46|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.064900|1.048300|1.064900|2.64|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=125.920000, depth_time=2026-11-10T14:45:22+00:00, book20_bid_proxy_usdt=293295, book20_ask_proxy_usdt=288768, funding_indicative=0.000044, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.42%, turnover=10455313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=0.002815, depth_time=2026-11-10T14:45:07+00:00, book20_bid_proxy_usdt=34132, book20_ask_proxy_usdt=33545, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-44.96%, turnover=13639175. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=1309.180000, depth_time=2026-11-10T14:45:14+00:00, book20_bid_proxy_usdt=12554, book20_ask_proxy_usdt=16700, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.64%, turnover=7623152. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=0.166050, depth_time=2026-11-10T14:45:12+00:00, book20_bid_proxy_usdt=85912, book20_ask_proxy_usdt=44025, funding_indicative=-0.000137, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.10%, turnover=38282684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=8.412000, depth_time=2026-11-10T14:45:23+00:00, book20_bid_proxy_usdt=742612, book20_ask_proxy_usdt=506532, funding_indicative=-0.000025, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.40%, turnover=41298587. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=0.860100, depth_time=2026-11-10T14:45:36+00:00, book20_bid_proxy_usdt=529412, book20_ask_proxy_usdt=331488, funding_indicative=0.000044, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.68%, turnover=8274429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-11-10T14:45:00+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=0.771800, depth_time=2026-11-10T14:45:28+00:00, book20_bid_proxy_usdt=1919712, book20_ask_proxy_usdt=1495840, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.14%, turnover=5166588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=74.000000, depth_time=2026-11-10T14:45:36+00:00, book20_bid_proxy_usdt=69603, book20_ask_proxy_usdt=36147, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.87%, turnover=48024793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=0.007891, depth_time=2026-11-10T14:45:09+00:00, book20_bid_proxy_usdt=10213, book20_ask_proxy_usdt=8583, funding_indicative=0.000199, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-30.90%, turnover=25168726. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=0.003552, depth_time=2026-11-10T14:45:30+00:00, book20_bid_proxy_usdt=2734190, book20_ask_proxy_usdt=3389096, funding_indicative=-0.000006, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.12%, turnover=8235879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=188.280000, depth_time=2026-11-10T14:45:18+00:00, book20_bid_proxy_usdt=31041, book20_ask_proxy_usdt=61065, funding_indicative=-0.000088, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.36%, turnover=36407941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=85.210000, depth_time=2026-11-10T14:45:34+00:00, book20_bid_proxy_usdt=15609368, book20_ask_proxy_usdt=15380903, funding_indicative=0.000045, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.92%, turnover=704998960. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=0.146080, depth_time=2026-11-10T14:45:39+00:00, book20_bid_proxy_usdt=158845, book20_ask_proxy_usdt=70778, funding_indicative=0.000036, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=25100665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=555.790000, depth_time=2026-11-10T14:45:17+00:00, book20_bid_proxy_usdt=15822, book20_ask_proxy_usdt=14463, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.74%, turnover=6368758. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-10T14:44:59+00:00, last15m_closed_end=2026-11-10T14:45+00:00, prior8high=1.082900, depth_time=2026-11-10T14:45:27+00:00, book20_bid_proxy_usdt=3181244, book20_ask_proxy_usdt=3326083, funding_indicative=0.000076, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.39%, turnover=292190664. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
