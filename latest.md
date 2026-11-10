# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T12:30:44Z**
- feed_generated_utc: 2026-11-10T12:30:45+00:00
- source_sha256: `536ab2ca37d06674689cfc2d989fc8d5f5b15ca40884a890a9fc8622884ea407`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T12:30+00:00, close=74232.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T12:00+00:00, close=74389.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002471|-49.54|-55.08|-47.87|13687694|4.05|
|JCT_USDT|0.005894|-41.82|36.52|-40.15|24399298|5.08|
|ON_USDT|0.112200|-25.00|-33.80|-23.33|5005734|8.91|
|ARB_USDT|0.162180|-11.87|1.78|-10.20|38541740|0.62|
|ANTHROPIC_USDT|1281.250000|-10.32|-23.67|-8.65|6623246|2.58|
|XMR_USDT|551.960000|-8.59|-8.81|-6.92|6064719|0.18|
|AVAX_USDT|8.323000|-7.41|-2.09|-5.74|52185551|1.20|
|AAVE_USDT|124.620000|-6.54|-4.54|-4.87|10736667|3.21|
|QNT_USDT|186.960000|-6.53|-7.65|-4.86|33092453|0.54|
|ZEC_USDT|1150.160000|-6.16|-8.28|-4.49|2255341485|0.09|
|SUI_USDT|0.833100|-3.94|-5.84|-2.27|35428861|1.20|
|DOT_USDT|0.857500|-3.74|-8.20|-2.07|8416251|1.17|
|PUMPFUN_USDT|0.003544|-3.74|-13.64|-2.07|7728130|2.82|
|SOL_USDT|84.720000|-3.60|-9.40|-1.93|642472872|1.18|
|HYPE_USDT|73.606000|-3.54|-14.12|-1.87|45410258|0.14|
|XRP_USDT|1.079500|-3.08|-13.52|-1.41|273135401|0.93|
|LINK_USDT|10.472000|-2.90|-6.78|-1.23|104664214|1.91|
|WLD_USDT|0.316600|-2.85|-16.94|-1.18|26948974|3.16|
|DASH_USDT|46.270000|-2.83|-1.97|-1.16|9851983|2.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|124.620000|124.140000|124.620000|0.77|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002471|0.002353|0.002471|0.92|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1281.250000|1247.900000|1281.270000|2.37|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.162180|0.161170|0.162180|0.51|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.323000|8.255000|8.323000|2.53|N|Y/Y|Y/N|Y|N|
|DOT_USDT|0.857500|0.845000|0.857500|1.26|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.606000|73.342000|73.606000|0.76|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005894|0.005322|0.005893|0.82|N|Y/Y|Y/Y|Y|N|
|ON_USDT|0.112200|0.113300|0.112200|1.28|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003544|0.003485|0.003544|3.34|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|186.960000|185.640000|186.960000|0.70|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|84.720000|84.170000|84.720000|0.57|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.833100|0.827600|0.833100|1.04|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|551.960000|539.060000|551.960000|0.08|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1150.160000|1131.050000|1150.160000|1.00|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=125.140000, depth_time=2026-11-10T12:30:21+00:00, book20_bid_proxy_usdt=346498, book20_ask_proxy_usdt=713827, funding_indicative=0.000070, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.54%, turnover=10736667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=0.002546, depth_time=2026-11-10T12:30:07+00:00, book20_bid_proxy_usdt=50184, book20_ask_proxy_usdt=90906, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-49.54%, turnover=13687694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=1386.130000, depth_time=2026-11-10T12:30:18+00:00, book20_bid_proxy_usdt=13086, book20_ask_proxy_usdt=49142, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.32%, turnover=6623246. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=0.166380, depth_time=2026-11-10T12:30:15+00:00, book20_bid_proxy_usdt=97142, book20_ask_proxy_usdt=81482, funding_indicative=-0.000234, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.87%, turnover=38541740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=8.353000, depth_time=2026-11-10T12:30:18+00:00, book20_bid_proxy_usdt=1803062, book20_ask_proxy_usdt=727722, funding_indicative=-0.000019, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.41%, turnover=52185551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=0.857100, depth_time=2026-11-10T12:30:35+00:00, book20_bid_proxy_usdt=578756, book20_ask_proxy_usdt=393939, funding_indicative=0.000044, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=8416251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=74.215000, depth_time=2026-11-10T12:30:41+00:00, book20_bid_proxy_usdt=178443, book20_ask_proxy_usdt=46147, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.54%, turnover=45410258. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=0.006488, depth_time=2026-11-10T12:30:10+00:00, book20_bid_proxy_usdt=30055, book20_ask_proxy_usdt=48602, funding_indicative=0.000264, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-41.82%, turnover=24399298. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ON_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=0.135800, depth_time=2026-11-10T12:30:13+00:00, book20_bid_proxy_usdt=127715, book20_ask_proxy_usdt=108108, funding_indicative=0.000050, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-25.00%, turnover=5005734. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=0.003531, depth_time=2026-11-10T12:30:36+00:00, book20_bid_proxy_usdt=3276377, book20_ask_proxy_usdt=2518779, funding_indicative=-0.000027, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.74%, turnover=7728130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=187.960000, depth_time=2026-11-10T12:30:28+00:00, book20_bid_proxy_usdt=71289, book20_ask_proxy_usdt=57518, funding_indicative=-0.000069, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.53%, turnover=33092453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=85.320000, depth_time=2026-11-10T12:30:39+00:00, book20_bid_proxy_usdt=14442131, book20_ask_proxy_usdt=13938744, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.60%, turnover=642472872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=0.837300, depth_time=2026-11-10T12:30:33+00:00, book20_bid_proxy_usdt=1922883, book20_ask_proxy_usdt=1484234, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.94%, turnover=35428861. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=553.110000, depth_time=2026-11-10T12:30:21+00:00, book20_bid_proxy_usdt=9775, book20_ask_proxy_usdt=13578, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.59%, turnover=6064719. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T12:30:00+00:00, last15m_closed_end=2026-11-10T12:30+00:00, prior8high=1154.630000, depth_time=2026-11-10T12:30:30+00:00, book20_bid_proxy_usdt=148378, book20_ask_proxy_usdt=228076, funding_indicative=0.000073, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.16%, turnover=2255341485. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
