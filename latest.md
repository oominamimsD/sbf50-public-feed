# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T02:15:48Z**
- feed_generated_utc: 2026-11-04T02:15:50+00:00
- source_sha256: `5a836c83fb3835f90eb1812c1320f949a5875eac529dca8df02cc04b95e263d0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T02:15+00:00, close=76942.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T02:00+00:00, close=77014.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-04T00:00+00:00, close=77441.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.040360|-24.99|-15.06|-24.05|12696795|2.48|
|HOT_USDT|0.000478|-11.18|38.44|-10.24|7948189|2.09|
|AKE_USDT|0.003725|-10.37|-82.36|-9.43|12653002|2.69|
|TRUMPOFFICIAL_USDT|1.514000|-5.84|-10.30|-4.90|7100884|6.61|
|STRK_USDT|0.041820|-5.23|-9.32|-4.29|5635394|2.39|
|HYPE_USDT|83.041000|-4.93|4.51|-3.99|70770275|0.12|
|XPL_USDT|0.061330|-4.24|-16.91|-3.30|7300401|1.63|
|XLM_USDT|0.159900|-2.96|-5.50|-2.02|34464717|0.62|
|QNT_USDT|189.820000|-2.86|-4.07|-1.92|60141109|0.53|
|LINK_USDT|10.856000|-2.67|-5.19|-1.73|172957384|0.92|
|OP_USDT|0.107530|-2.62|-3.40|-1.68|9179525|0.93|
|AAVE_USDT|125.440000|-2.34|-5.44|-1.40|21996746|0.80|
|TAO_USDT|222.360000|-2.26|-11.47|-1.32|33365035|1.35|
|DASH_USDT|45.110000|-2.23|-16.72|-1.29|11500202|2.22|
|HBAR_USDT|0.068560|-2.09|-9.93|-1.15|6192418|1.46|
|NEAR_USDT|3.779000|-2.07|-17.16|-1.13|67030629|5.29|
|XRP_USDT|1.254300|-2.06|-5.02|-1.12|283171533|0.80|
|PEPE_USDT|0.000005|-2.03|8.78|-1.09|97420876|0.21|
|SOL_USDT|91.840000|-2.00|-8.99|-1.06|490796651|1.09|
|DOGE_USDT|0.073990|-1.97|-5.32|-1.03|74254062|1.35|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|125.440000|124.550000|125.430000|4.54|N|Y/Y|Y/Y|Y|N|
|AGT_USDT|0.040360|0.039920|0.040360|0.46|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.003725|0.003714|0.003719|0.80|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|45.110000|44.790000|45.110000|0.89|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.068560|0.068160|0.068560|1.18|N|Y/Y|Y/Y|Y|N|
|HOT_USDT|0.000478|0.000473|0.000478|0.50|N|Y/N|N/N|Y|N|
|HYPE_USDT|83.041000|81.750000|83.041000|0.61|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.856000|10.794000|10.855000|1.68|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.107530|0.106760|0.107490|1.52|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.820000|188.930000|189.820000|1.22|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.041820|0.041450|0.041800|0.48|N|Y/Y|Y/N|Y|N|
|TAO_USDT|222.360000|220.580000|222.360000|1.05|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.514000|1.495000|1.514000|3.33|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.159900|0.158870|0.159900|0.99|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.061330|0.060580|0.061350|0.63|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=127.550000, depth_time=2026-11-04T02:15:37+00:00, book20_bid_proxy_usdt=341465, book20_ask_proxy_usdt=229136, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=21996746. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AGT_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=0.044580, depth_time=2026-11-04T02:15:09+00:00, book20_bid_proxy_usdt=30019, book20_ask_proxy_usdt=28501, funding_indicative=0.000243, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-24.99%, turnover=12696795. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=0.003990, depth_time=2026-11-04T02:15:13+00:00, book20_bid_proxy_usdt=55072, book20_ask_proxy_usdt=88528, funding_indicative=-0.000462, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.37%, turnover=12653002. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=46.290000, depth_time=2026-11-04T02:15:40+00:00, book20_bid_proxy_usdt=493234, book20_ask_proxy_usdt=640478, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=11500202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=0.069740, depth_time=2026-11-04T02:15:47+00:00, book20_bid_proxy_usdt=1305094, book20_ask_proxy_usdt=1165580, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=6192418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=0.000559, depth_time=2026-11-04T02:15:11+00:00, book20_bid_proxy_usdt=81731, book20_ask_proxy_usdt=53541, funding_indicative=-0.000408, next_funding_utc=2026-11-04T03:00:00+00:00, funding_cycle_h=1, 24h_change=-11.18%, turnover=7948189. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=85.442000, depth_time=2026-11-04T02:15:22+00:00, book20_bid_proxy_usdt=162415, book20_ask_proxy_usdt=155865, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=70770275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=11.041000, depth_time=2026-11-04T02:15:33+00:00, book20_bid_proxy_usdt=417750, book20_ask_proxy_usdt=439558, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=172957384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=0.109600, depth_time=2026-11-04T02:15:35+00:00, book20_bid_proxy_usdt=95293, book20_ask_proxy_usdt=96542, funding_indicative=0.000092, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=9179525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=193.440000, depth_time=2026-11-04T02:15:30+00:00, book20_bid_proxy_usdt=74559, book20_ask_proxy_usdt=37080, funding_indicative=-0.000055, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=60141109. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=0.042390, depth_time=2026-11-04T02:15:20+00:00, book20_bid_proxy_usdt=352755, book20_ask_proxy_usdt=291260, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.23%, turnover=5635394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=226.370000, depth_time=2026-11-04T02:15:41+00:00, book20_bid_proxy_usdt=142816, book20_ask_proxy_usdt=266297, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=33365035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=1.589000, depth_time=2026-11-04T02:15:14+00:00, book20_bid_proxy_usdt=2675681, book20_ask_proxy_usdt=1898992, funding_indicative=-0.000078, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.84%, turnover=7100884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=0.162470, depth_time=2026-11-04T02:15:24+00:00, book20_bid_proxy_usdt=129207, book20_ask_proxy_usdt=170012, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=34464717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-04T02:15:02+00:00, last15m_closed_end=2026-11-04T02:15+00:00, prior8high=0.063330, depth_time=2026-11-04T02:15:25+00:00, book20_bid_proxy_usdt=423877, book20_ask_proxy_usdt=431964, funding_indicative=0.000027, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.24%, turnover=7300401. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
