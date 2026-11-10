# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T19:00:39Z**
- feed_generated_utc: 2026-11-10T19:00:40+00:00
- source_sha256: `e2f783d81ee0717b140dee536b00d2acc3fe0ce94f6d419cf7bf582e3a2afb07`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T19:00+00:00, close=73455.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T19:00+00:00, close=73455.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005095|-15.49|21.94|-15.83|21455016|1.96|
|PIEVERSE_USDT|1.824800|-9.93|55.24|-10.27|7926850|2.74|
|DASH_USDT|43.480000|-6.59|-5.76|-6.93|13205823|2.30|
|UNI_USDT|6.689000|-5.32|-9.03|-5.66|28214309|1.50|
|ZEC_USDT|1036.880000|-5.16|-13.86|-5.50|2290070510|0.19|
|ONDO_USDT|0.362000|-4.76|-6.98|-5.10|14823961|2.76|
|PUMPFUN_USDT|0.003461|-2.86|-18.88|-3.20|9500956|2.89|
|DOGE_USDT|0.067410|-2.85|-10.69|-3.19|87374854|1.48|
|DOT_USDT|0.840100|-2.59|-10.87|-2.93|8639104|1.19|
|SUI_USDT|0.816900|-2.55|-9.06|-2.89|41515515|1.23|
|AVAX_USDT|8.255000|-1.46|-3.72|-1.80|31690630|1.21|
|AAVE_USDT|123.320000|-1.33|-3.99|-1.67|11414717|1.62|
|ARB_USDT|0.159500|-1.16|-0.23|-1.50|34013059|1.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|123.320000|120.940000|123.320000|0.61|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159500|0.155570|0.159480|0.64|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.255000|8.139000|8.255000|0.37|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.480000|42.350000|43.480000|0.17|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.067410|0.066560|0.067410|0.94|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.840100|0.829500|0.840100|0.53|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005095|0.005014|0.005095|0.32|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.362000|0.355900|0.362000|0.35|N|Y/Y|Y/N|Y|N|
|PIEVERSE_USDT|1.824800|1.808000|1.824100|1.03|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003461|0.003341|0.003461|1.35|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.816900|0.802700|0.816900|0.52|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.689000|6.608000|6.689000|0.71|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1036.880000|993.710000|1037.340000|0.56|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T19:00:02+00:00, last15m_closed_end=2026-11-10T19:00+00:00, prior8high=124.190000, depth_time=2026-11-10T19:00:33+00:00, book20_bid_proxy_usdt=396465, book20_ask_proxy_usdt=297584, funding_indicative=-0.000004, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=11414717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T19:00:02+00:00, last15m_closed_end=2026-11-10T19:00+00:00, prior8high=0.160280, depth_time=2026-11-10T19:00:37+00:00, book20_bid_proxy_usdt=90898, book20_ask_proxy_usdt=93906, funding_indicative=-0.000188, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=34013059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T19:00:02+00:00, last15m_closed_end=2026-11-10T19:00+00:00, prior8high=8.322000, depth_time=2026-11-10T19:00:31+00:00, book20_bid_proxy_usdt=835240, book20_ask_proxy_usdt=858917, funding_indicative=-0.000035, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=31690630. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T19:00:03+00:00, last15m_closed_end=2026-11-10T19:00+00:00, prior8high=44.020000, depth_time=2026-11-10T19:00:10+00:00, book20_bid_proxy_usdt=778107, book20_ask_proxy_usdt=666081, funding_indicative=-0.000135, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-6.59%, turnover=13205823. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-10T19:00:02+00:00, last15m_closed_end=2026-11-10T19:00+00:00, prior8high=0.067540, depth_time=2026-11-10T19:00:24+00:00, book20_bid_proxy_usdt=3834046, book20_ask_proxy_usdt=5314237, funding_indicative=-0.000086, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=87374854. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T19:00:02+00:00, last15m_closed_end=2026-11-10T19:00+00:00, prior8high=0.845000, depth_time=2026-11-10T19:00:25+00:00, book20_bid_proxy_usdt=614029, book20_ask_proxy_usdt=826908, funding_indicative=-0.000108, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.59%, turnover=8639104. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T19:00:02+00:00, last15m_closed_end=2026-11-10T19:00+00:00, prior8high=0.005462, depth_time=2026-11-10T19:00:07+00:00, book20_bid_proxy_usdt=52686, book20_ask_proxy_usdt=39348, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-15.49%, turnover=21455016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T19:00:02+00:00, last15m_closed_end=2026-11-10T19:00+00:00, prior8high=0.364800, depth_time=2026-11-10T19:00:20+00:00, book20_bid_proxy_usdt=2123758, book20_ask_proxy_usdt=2791945, funding_indicative=-0.000014, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.76%, turnover=14823961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T19:00:02+00:00, last15m_closed_end=2026-11-10T19:00+00:00, prior8high=1.887200, depth_time=2026-11-10T19:00:10+00:00, book20_bid_proxy_usdt=13264, book20_ask_proxy_usdt=20250, funding_indicative=0.000108, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.93%, turnover=7926850. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T19:00:03+00:00, last15m_closed_end=2026-11-10T19:00+00:00, prior8high=0.003476, depth_time=2026-11-10T19:00:21+00:00, book20_bid_proxy_usdt=2315153, book20_ask_proxy_usdt=2357551, funding_indicative=0.000002, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=9500956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T19:00:02+00:00, last15m_closed_end=2026-11-10T19:00+00:00, prior8high=0.819300, depth_time=2026-11-10T19:00:30+00:00, book20_bid_proxy_usdt=1622957, book20_ask_proxy_usdt=1468001, funding_indicative=-0.000079, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.55%, turnover=41515515. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T19:00:02+00:00, last15m_closed_end=2026-11-10T19:00+00:00, prior8high=6.745000, depth_time=2026-11-10T19:00:14+00:00, book20_bid_proxy_usdt=2459582, book20_ask_proxy_usdt=2625509, funding_indicative=-0.000023, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.32%, turnover=28214309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T19:00:02+00:00, last15m_closed_end=2026-11-10T19:00+00:00, prior8high=1045.180000, depth_time=2026-11-10T19:00:17+00:00, book20_bid_proxy_usdt=123448, book20_ask_proxy_usdt=239627, funding_indicative=-0.000038, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.16%, turnover=2290070510. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
