# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T03:00:29Z**
- feed_generated_utc: 2026-11-10T03:00:30+00:00
- source_sha256: `315f1c57f2107c4e02e99f4a8072912ba84123a706b2c87ad2aeadf035e74a05`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T03:00+00:00, close=74843.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T03:00+00:00, close=74843.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002457|-49.82|-55.34|-48.97|14459201|4.07|
|JCT_USDT|0.008926|-18.66|106.76|-17.81|27374426|1.12|
|ON_USDT|0.165000|-17.08|-2.65|-16.23|5413739|6.07|
|ZEC_USDT|1159.580000|-5.39|-7.53|-4.54|2354315207|0.09|
|ARB_USDT|0.172920|-4.09|8.52|-3.24|31097147|1.16|
|DOT_USDT|0.851800|-3.83|-8.81|-2.98|10613284|1.17|
|QNT_USDT|193.700000|-3.11|-4.32|-2.26|36818411|0.52|
|PUMPFUN_USDT|0.003575|-2.77|-12.88|-1.92|7953218|2.80|
|DASH_USDT|46.220000|-2.30|-2.07|-1.45|15183064|2.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002457|0.002304|0.002448|0.29|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.172920|0.172130|0.172920|1.07|N|Y/Y|N/N|Y|N|
|DASH_USDT|46.220000|45.970000|46.220000|1.48|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.851800|0.850800|0.851800|1.14|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008926|0.008752|0.008926|1.38|N|Y/Y|N/N|Y|N|
|ON_USDT|0.165000|0.162700|0.165000|0.28|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003575|0.003550|0.003575|2.10|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.700000|192.510000|193.700000|0.44|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1159.580000|1141.980000|1159.100000|1.35|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T03:00:00+00:00, last15m_closed_end=2026-11-10T03:00+00:00, prior8high=0.002982, depth_time=2026-11-10T03:00:09+00:00, book20_bid_proxy_usdt=38860, book20_ask_proxy_usdt=49548, funding_indicative=0.000050, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-49.82%, turnover=14459201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T03:00:00+00:00, last15m_closed_end=2026-11-10T03:00+00:00, prior8high=0.175390, depth_time=2026-11-10T03:00:18+00:00, book20_bid_proxy_usdt=38956, book20_ask_proxy_usdt=83182, funding_indicative=-0.000009, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.09%, turnover=31097147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T03:00:01+00:00, last15m_closed_end=2026-11-10T03:00+00:00, prior8high=47.310000, depth_time=2026-11-10T03:00:25+00:00, book20_bid_proxy_usdt=581322, book20_ask_proxy_usdt=578678, funding_indicative=0.000012, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.30%, turnover=15183064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T03:00:01+00:00, last15m_closed_end=2026-11-10T03:00+00:00, prior8high=0.858400, depth_time=2026-11-10T03:00:21+00:00, book20_bid_proxy_usdt=595515, book20_ask_proxy_usdt=818843, funding_indicative=0.000003, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.83%, turnover=10613284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T03:00:00+00:00, last15m_closed_end=2026-11-10T03:00+00:00, prior8high=0.011124, depth_time=2026-11-10T03:00:11+00:00, book20_bid_proxy_usdt=24121, book20_ask_proxy_usdt=17484, funding_indicative=0.000928, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-18.66%, turnover=27374426. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ON_USDT: quote_utc=2026-11-10T03:00:00+00:00, last15m_closed_end=2026-11-10T03:00+00:00, prior8high=0.175100, depth_time=2026-11-10T03:00:13+00:00, book20_bid_proxy_usdt=69458, book20_ask_proxy_usdt=43620, funding_indicative=0.000050, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-17.08%, turnover=5413739. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T03:00:01+00:00, last15m_closed_end=2026-11-10T03:00+00:00, prior8high=0.003615, depth_time=2026-11-10T03:00:25+00:00, book20_bid_proxy_usdt=2350511, book20_ask_proxy_usdt=2798437, funding_indicative=0.000027, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=7953218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T03:00:00+00:00, last15m_closed_end=2026-11-10T03:00+00:00, prior8high=195.180000, depth_time=2026-11-10T03:00:23+00:00, book20_bid_proxy_usdt=37289, book20_ask_proxy_usdt=70427, funding_indicative=0.000059, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=36818411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T03:00:00+00:00, last15m_closed_end=2026-11-10T03:00+00:00, prior8high=1178.530000, depth_time=2026-11-10T03:00:16+00:00, book20_bid_proxy_usdt=323730, book20_ask_proxy_usdt=78422, funding_indicative=0.000068, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.39%, turnover=2354315207. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
