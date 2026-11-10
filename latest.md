# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T22:00:42Z**
- feed_generated_utc: 2026-11-10T22:00:43+00:00
- source_sha256: `ab946b190b0b5ce338a43dde4e4bff2ae99f7422f282fadc54e1cfa17f4ff451`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T22:00+00:00, close=73819.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T22:00+00:00, close=73819.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.209680|-16.44|55.91|-17.34|49205391|2.87|
|JCT_USDT|0.005264|-12.68|25.99|-13.58|19636863|3.80|
|PIEVERSE_USDT|1.847200|-10.05|57.15|-10.95|5713324|2.17|
|PEPE_USDT|0.000005|-5.21|7.65|-6.11|71122733|0.19|
|DASH_USDT|43.270000|-4.14|-6.22|-5.04|13848425|2.31|
|ARB_USDT|0.159800|-3.18|-0.05|-4.08|33469260|0.63|
|ZEC_USDT|1058.950000|-3.14|-12.03|-4.04|2211681553|0.09|
|WLD_USDT|0.309200|-2.73|-16.90|-3.63|29279024|3.23|
|JUP_USDT|0.250000|-2.45|0.36|-3.35|5479220|4.00|
|DOT_USDT|0.843000|-2.26|-10.56|-3.16|8532465|1.19|
|DOGE_USDT|0.067980|-2.03|-9.93|-2.93|89827029|1.47|
|ADA_USDT|0.174000|-1.86|-8.85|-2.76|22328032|5.74|
|VVV_USDT|19.453000|-1.83|-13.00|-2.73|5215250|0.51|
|UNI_USDT|6.729000|-1.47|-8.48|-2.37|30350567|1.49|
|SOL_USDT|83.350000|-1.13|-11.06|-2.03|652978751|1.20|
|AVAX_USDT|8.310000|-0.81|-3.07|-1.71|27576831|1.20|
|SILVER_USDT|51.630000|-0.74|3.30|-1.64|267692249|1.94|
|ANTHROPIC_USDT|1308.150000|-0.71|-21.85|-1.61|8467707|1.30|
|QNT_USDT|181.980000|-0.60|-6.87|-1.50|47319692|1.10|
|XAU_USDT|4039.160000|-0.19|2.38|-1.09|509239855|0.03|
|XAUT_USDT|4021.690000|-0.18|2.34|-1.08|112343045|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.174000|0.172800|0.174000|0.25|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159800|0.158120|0.159810|1.04|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.270000|42.550000|43.240000|1.39|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.067980|0.067170|0.067980|0.21|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.843000|0.831500|0.843000|0.58|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.209680|0.202000|0.215160|1.01|N|Y/N|N/N|Y|N|
|JCT_USDT|0.005264|0.005110|0.005264|0.39|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.250000|0.250600|0.250000|0.65|N|Y/N|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.52|N|N/Y|N/N|Y|N|
|PIEVERSE_USDT|1.847200|1.782100|1.847200|0.39|N|Y/Y|N/N|Y|N|
|SOL_USDT|83.350000|82.560000|83.330000|0.39|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.729000|6.659000|6.727000|0.57|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.453000|19.037000|19.453000|0.72|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.309200|0.304700|0.309200|1.07|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1058.950000|1025.010000|1058.510000|0.82|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=0.175300, depth_time=2026-11-10T22:00:33+00:00, book20_bid_proxy_usdt=9034068, book20_ask_proxy_usdt=10895408, funding_indicative=-0.000054, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=22328032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=0.160720, depth_time=2026-11-10T22:00:18+00:00, book20_bid_proxy_usdt=65397, book20_ask_proxy_usdt=124926, funding_indicative=-0.000231, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.18%, turnover=33469260. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=43.220000, depth_time=2026-11-10T22:00:16+00:00, book20_bid_proxy_usdt=824857, book20_ask_proxy_usdt=705870, funding_indicative=-0.000209, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.14%, turnover=13848425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=0.068070, depth_time=2026-11-10T22:00:30+00:00, book20_bid_proxy_usdt=3758320, book20_ask_proxy_usdt=5462368, funding_indicative=-0.000054, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=89827029. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=0.842400, depth_time=2026-11-10T22:00:26+00:00, book20_bid_proxy_usdt=659298, book20_ask_proxy_usdt=757168, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=8532465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=0.282000, depth_time=2026-11-10T22:00:07+00:00, book20_bid_proxy_usdt=19122, book20_ask_proxy_usdt=14266, funding_indicative=-0.020000, next_funding_utc=2026-11-10T23:00:00+00:00, funding_cycle_h=1, 24h_change=-16.44%, turnover=49205391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=0.005437, depth_time=2026-11-10T22:00:08+00:00, book20_bid_proxy_usdt=46435, book20_ask_proxy_usdt=45828, funding_indicative=0.000481, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.68%, turnover=19636863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=0.257600, depth_time=2026-11-10T22:00:25+00:00, book20_bid_proxy_usdt=520168, book20_ask_proxy_usdt=375736, funding_indicative=-0.000044, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.45%, turnover=5479220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=0.000005, depth_time=2026-11-10T22:00:13+00:00, book20_bid_proxy_usdt=22424, book20_ask_proxy_usdt=22590, funding_indicative=0.000049, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.21%, turnover=71122733. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=1.849200, depth_time=2026-11-10T22:00:11+00:00, book20_bid_proxy_usdt=28282, book20_ask_proxy_usdt=15770, funding_indicative=0.000139, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.05%, turnover=5713324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=83.640000, depth_time=2026-11-10T22:00:41+00:00, book20_bid_proxy_usdt=17481788, book20_ask_proxy_usdt=14623816, funding_indicative=0.000016, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=652978751. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=6.774000, depth_time=2026-11-10T22:00:37+00:00, book20_bid_proxy_usdt=2504816, book20_ask_proxy_usdt=3087514, funding_indicative=-0.000026, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.47%, turnover=30350567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=19.455000, depth_time=2026-11-10T22:00:36+00:00, book20_bid_proxy_usdt=68896, book20_ask_proxy_usdt=18690, funding_indicative=0.000037, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.83%, turnover=5215250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=0.310100, depth_time=2026-11-10T22:00:21+00:00, book20_bid_proxy_usdt=5160322, book20_ask_proxy_usdt=4722983, funding_indicative=-0.000014, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=29279024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T22:00:02+00:00, last15m_closed_end=2026-11-10T22:00+00:00, prior8high=1067.490000, depth_time=2026-11-10T22:00:20+00:00, book20_bid_proxy_usdt=157805, book20_ask_proxy_usdt=376557, funding_indicative=0.000010, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.14%, turnover=2211681553. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
