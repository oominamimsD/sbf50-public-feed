# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T06:45:28Z**
- feed_generated_utc: 2026-11-10T06:45:30+00:00
- source_sha256: `57e3c362064be03e7952efa1ccf1ecfa0b6d53e69960f5ca8e51c084c2522c3b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T06:45+00:00, close=74678.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T06:00+00:00, close=74787.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002482|-49.31|-54.88|-48.23|15520407|4.03|
|JCT_USDT|0.006509|-35.75|50.77|-34.67|26235971|1.54|
|ARB_USDT|0.171490|-6.81|7.63|-5.73|34398099|0.58|
|ZEC_USDT|1151.480000|-6.05|-8.18|-4.97|2441102365|0.09|
|AAVE_USDT|126.000000|-5.51|-3.49|-4.43|13576533|2.38|
|QNT_USDT|190.830000|-4.60|-5.73|-3.52|35514432|0.52|
|DASH_USDT|45.770000|-3.88|-3.02|-2.80|13808870|4.37|
|DOT_USDT|0.859500|-3.52|-7.98|-2.44|10499171|1.16|
|SOL_USDT|86.040000|-2.10|-7.98|-1.02|675259567|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.000000|125.050000|125.940000|1.60|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002482|0.002443|0.002485|0.97|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.171490|0.170290|0.171430|0.73|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.770000|45.630000|45.770000|0.17|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.859500|0.848100|0.859600|0.30|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006509|0.006540|0.006509|1.11|N|Y/Y|N/N|Y|N|
|QNT_USDT|190.830000|189.670000|190.830000|0.40|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.040000|85.770000|86.040000|0.70|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1151.480000|1144.770000|1151.480000|0.72|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T06:45:01+00:00, last15m_closed_end=2026-11-10T06:45+00:00, prior8high=127.920000, depth_time=2026-11-10T06:45:17+00:00, book20_bid_proxy_usdt=314945, book20_ask_proxy_usdt=378416, funding_indicative=0.000039, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.51%, turnover=13576533. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T06:45:01+00:00, last15m_closed_end=2026-11-10T06:45+00:00, prior8high=0.002768, depth_time=2026-11-10T06:45:07+00:00, book20_bid_proxy_usdt=49532, book20_ask_proxy_usdt=64011, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-49.31%, turnover=15520407. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T06:45:01+00:00, last15m_closed_end=2026-11-10T06:45+00:00, prior8high=0.173110, depth_time=2026-11-10T06:45:08+00:00, book20_bid_proxy_usdt=73320, book20_ask_proxy_usdt=64783, funding_indicative=-0.000021, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.81%, turnover=34398099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T06:45:01+00:00, last15m_closed_end=2026-11-10T06:45+00:00, prior8high=46.350000, depth_time=2026-11-10T06:45:22+00:00, book20_bid_proxy_usdt=583817, book20_ask_proxy_usdt=543334, funding_indicative=0.000034, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.88%, turnover=13808870. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T06:45:01+00:00, last15m_closed_end=2026-11-10T06:45+00:00, prior8high=0.858800, depth_time=2026-11-10T06:45:22+00:00, book20_bid_proxy_usdt=452270, book20_ask_proxy_usdt=629166, funding_indicative=0.000036, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.52%, turnover=10499171. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T06:45:01+00:00, last15m_closed_end=2026-11-10T06:45+00:00, prior8high=0.008040, depth_time=2026-11-10T06:45:10+00:00, book20_bid_proxy_usdt=36435, book20_ask_proxy_usdt=34988, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-35.75%, turnover=26235971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T06:45:01+00:00, last15m_closed_end=2026-11-10T06:45+00:00, prior8high=192.660000, depth_time=2026-11-10T06:45:19+00:00, book20_bid_proxy_usdt=62849, book20_ask_proxy_usdt=54351, funding_indicative=-0.000166, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.60%, turnover=35514432. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T06:45:01+00:00, last15m_closed_end=2026-11-10T06:45+00:00, prior8high=86.580000, depth_time=2026-11-10T06:45:26+00:00, book20_bid_proxy_usdt=17877499, book20_ask_proxy_usdt=12807959, funding_indicative=0.000042, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=675259567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T06:45:01+00:00, last15m_closed_end=2026-11-10T06:45+00:00, prior8high=1165.460000, depth_time=2026-11-10T06:45:14+00:00, book20_bid_proxy_usdt=48068, book20_ask_proxy_usdt=499442, funding_indicative=0.000069, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.05%, turnover=2441102365. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
