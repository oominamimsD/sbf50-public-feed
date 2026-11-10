# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T07:15:29Z**
- feed_generated_utc: 2026-11-10T07:15:31+00:00
- source_sha256: `3cbfa5e806d955a80e8b2b36e3e78459f75b63ccd7949d4ff1d248d04f5bf07b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T07:15+00:00, close=74645.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T07:00+00:00, close=74627.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002512|-48.70|-54.34|-47.57|15308557|3.97|
|JCT_USDT|0.006478|-36.05|50.05|-34.92|25414896|3.09|
|ARB_USDT|0.168000|-8.71|5.44|-7.58|35514247|0.60|
|ZEC_USDT|1145.870000|-6.51|-8.63|-5.38|2363859429|0.09|
|AAVE_USDT|127.010000|-4.75|-2.71|-3.62|13099902|1.57|
|QNT_USDT|191.030000|-4.50|-5.64|-3.37|34355745|2.62|
|DASH_USDT|45.670000|-4.09|-3.24|-2.96|12268089|6.57|
|DOT_USDT|0.857200|-3.78|-8.23|-2.65|8785096|1.17|
|PUMPFUN_USDT|0.003576|-2.87|-12.86|-1.74|7249913|2.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.010000|125.050000|127.090000|2.99|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002512|0.002443|0.002512|0.31|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.168000|0.170580|0.167910|6.97|Y|Y/Y|N/N|Y|N|
|DASH_USDT|45.670000|45.630000|45.670000|0.21|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.857200|0.849700|0.857700|0.43|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006478|0.006357|0.006478|1.21|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003576|0.003555|0.003576|1.35|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.030000|189.670000|191.030000|1.06|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1145.870000|1144.770000|1145.930000|0.80|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T07:15:03+00:00, last15m_closed_end=2026-11-10T07:15+00:00, prior8high=127.600000, depth_time=2026-11-10T07:15:17+00:00, book20_bid_proxy_usdt=518178, book20_ask_proxy_usdt=389855, funding_indicative=0.000054, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.75%, turnover=13099902. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T07:15:02+00:00, last15m_closed_end=2026-11-10T07:15+00:00, prior8high=0.002556, depth_time=2026-11-10T07:15:08+00:00, book20_bid_proxy_usdt=62706, book20_ask_proxy_usdt=69590, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-48.70%, turnover=15308557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T07:15:02+00:00, last15m_closed_end=2026-11-10T07:15+00:00, prior8high=0.173110, depth_time=2026-11-10T07:15:12+00:00, book20_bid_proxy_usdt=61214, book20_ask_proxy_usdt=73660, funding_indicative=-0.000033, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-8.71%, turnover=35514247. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T07:15:03+00:00, last15m_closed_end=2026-11-10T07:15+00:00, prior8high=46.250000, depth_time=2026-11-10T07:15:17+00:00, book20_bid_proxy_usdt=901310, book20_ask_proxy_usdt=591255, funding_indicative=0.000041, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.09%, turnover=12268089. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T07:15:03+00:00, last15m_closed_end=2026-11-10T07:15+00:00, prior8high=0.860200, depth_time=2026-11-10T07:15:25+00:00, book20_bid_proxy_usdt=643872, book20_ask_proxy_usdt=572762, funding_indicative=0.000034, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.78%, turnover=8785096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T07:15:02+00:00, last15m_closed_end=2026-11-10T07:15+00:00, prior8high=0.007976, depth_time=2026-11-10T07:15:10+00:00, book20_bid_proxy_usdt=27262, book20_ask_proxy_usdt=31346, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-36.05%, turnover=25414896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T07:15:03+00:00, last15m_closed_end=2026-11-10T07:15+00:00, prior8high=0.003603, depth_time=2026-11-10T07:15:28+00:00, book20_bid_proxy_usdt=3187113, book20_ask_proxy_usdt=2786958, funding_indicative=0.000033, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.87%, turnover=7249913. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T07:15:03+00:00, last15m_closed_end=2026-11-10T07:15+00:00, prior8high=192.660000, depth_time=2026-11-10T07:15:20+00:00, book20_bid_proxy_usdt=104146, book20_ask_proxy_usdt=71752, funding_indicative=-0.000131, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.50%, turnover=34355745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T07:15:02+00:00, last15m_closed_end=2026-11-10T07:15+00:00, prior8high=1165.460000, depth_time=2026-11-10T07:15:15+00:00, book20_bid_proxy_usdt=415704, book20_ask_proxy_usdt=156919, funding_indicative=0.000060, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.51%, turnover=2363859429. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
