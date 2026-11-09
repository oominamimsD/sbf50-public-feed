# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T09:15:38Z**
- feed_generated_utc: 2026-11-09T09:15:40+00:00
- source_sha256: `f559ff22d3edb01f486b02f0b81f0e20103e7a59a9531201e208d553ecda6f3d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T09:15+00:00, close=74410.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T09:00+00:00, close=74524.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001568|-19.89|34.68|-17.75|8081275|0.64|
|AKE_USDT|0.004391|-18.03|-52.06|-15.89|9495712|6.83|
|ASTER_USDT|0.632800|-6.91|-9.52|-4.77|5409970|1.58|
|ETH_USDT|2116.920000|-5.54|-6.57|-3.40|1480140994|0.05|
|XRP_USDT|1.094300|-5.32|-12.44|-3.18|260626629|0.91|
|HYPE_USDT|73.591000|-4.95|-16.07|-2.81|46498821|0.14|
|JCT_USDT|0.009353|-4.89|87.84|-2.75|73033054|3.21|
|NEAR_USDT|3.534000|-4.51|-18.40|-2.37|43223771|2.83|
|PUMPFUN_USDT|0.003574|-4.36|-15.26|-2.22|10289510|2.80|
|TRUMPOFFICIAL_USDT|1.139000|-4.20|-33.62|-2.06|6791234|8.78|
|ZEC_USDT|1222.440000|-3.79|-1.24|-1.65|2256942880|0.08|
|UNI_USDT|6.756000|-3.52|-6.89|-1.38|28589830|1.48|
|XLM_USDT|0.146230|-3.29|-13.14|-1.15|27920029|0.68|
|SOL_USDT|86.760000|-3.25|-8.44|-1.11|681548398|1.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004391|0.004511|0.004390|3.02|Y|Y/Y|Y/Y|Y|Y|
|ASTER_USDT|0.632800|0.624700|0.632800|0.65|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2116.920000|2081.410000|2116.920000|1.26|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.591000|72.442000|73.591000|2.29|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009353|0.007376|0.009350|2.22|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.534000|3.460000|3.534000|3.38|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001568|0.001562|0.001568|1.46|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003574|0.003485|0.003574|1.85|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.760000|85.090000|86.760000|1.75|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.139000|1.122000|1.139000|1.93|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.756000|6.646000|6.756000|2.06|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.146230|0.143780|0.146230|0.85|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.094300|1.081600|1.094300|0.74|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1222.440000|1185.330000|1222.440000|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-09T09:14:59+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=0.004767, depth_time=2026-11-09T09:15:09+00:00, book20_bid_proxy_usdt=29686, book20_ask_proxy_usdt=51300, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.03%, turnover=9495712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T09:15:00+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=0.637200, depth_time=2026-11-09T09:15:10+00:00, book20_bid_proxy_usdt=493396, book20_ask_proxy_usdt=800981, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.91%, turnover=5409970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T09:14:59+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=2124.800000, depth_time=2026-11-09T09:15:13+00:00, book20_bid_proxy_usdt=10511064, book20_ask_proxy_usdt=2773801, funding_indicative=-0.000029, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.54%, turnover=1480140994. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T09:14:59+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=74.182000, depth_time=2026-11-09T09:15:17+00:00, book20_bid_proxy_usdt=96498, book20_ask_proxy_usdt=92117, funding_indicative=0.000040, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.95%, turnover=46498821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T09:14:59+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=0.009375, depth_time=2026-11-09T09:15:20+00:00, book20_bid_proxy_usdt=20398, book20_ask_proxy_usdt=15796, funding_indicative=0.001240, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.89%, turnover=73033054. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T09:14:59+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=3.564000, depth_time=2026-11-09T09:15:22+00:00, book20_bid_proxy_usdt=2255295, book20_ask_proxy_usdt=2124235, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.51%, turnover=43223771. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T09:14:59+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=0.001629, depth_time=2026-11-09T09:15:05+00:00, book20_bid_proxy_usdt=14854, book20_ask_proxy_usdt=11050, funding_indicative=-0.000074, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.89%, turnover=8081275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T09:15:00+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=0.003580, depth_time=2026-11-09T09:15:24+00:00, book20_bid_proxy_usdt=2302791, book20_ask_proxy_usdt=2533356, funding_indicative=0.000035, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.36%, turnover=10289510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T09:14:59+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=86.950000, depth_time=2026-11-09T09:15:37+00:00, book20_bid_proxy_usdt=17029771, book20_ask_proxy_usdt=13576060, funding_indicative=-0.000033, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=681548398. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T09:15:00+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=1.148000, depth_time=2026-11-09T09:15:26+00:00, book20_bid_proxy_usdt=2992787, book20_ask_proxy_usdt=2392717, funding_indicative=0.000029, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.20%, turnover=6791234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-09T09:15:00+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=6.768000, depth_time=2026-11-09T09:15:32+00:00, book20_bid_proxy_usdt=1670378, book20_ask_proxy_usdt=1951605, funding_indicative=0.000053, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.52%, turnover=28589830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-09T09:15:00+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=0.146430, depth_time=2026-11-09T09:15:35+00:00, book20_bid_proxy_usdt=79058, book20_ask_proxy_usdt=179990, funding_indicative=0.000031, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.29%, turnover=27920029. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T09:14:59+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=1.098500, depth_time=2026-11-09T09:15:15+00:00, book20_bid_proxy_usdt=2793955, book20_ask_proxy_usdt=3410130, funding_indicative=0.000064, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.32%, turnover=260626629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T09:14:59+00:00, last15m_closed_end=2026-11-09T09:15+00:00, prior8high=1231.460000, depth_time=2026-11-09T09:15:30+00:00, book20_bid_proxy_usdt=124925, book20_ask_proxy_usdt=287642, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.79%, turnover=2256942880. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
