# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T08:45:34Z**
- feed_generated_utc: 2026-11-10T08:45:36+00:00
- source_sha256: `156bcca9acc2ef55f4ff75d3dba7b07134fc21c5e39b6076f32940e8986f685c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T08:45+00:00, close=74538.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002441|-50.15|-55.63|-48.88|15393514|4.10|
|JCT_USDT|0.006055|-40.23|40.25|-38.96|25026816|3.30|
|ARB_USDT|0.167940|-8.74|5.40|-7.47|37334618|0.59|
|ZEC_USDT|1144.850000|-6.59|-8.71|-5.32|2363194068|0.09|
|AAVE_USDT|126.020000|-5.49|-3.47|-4.22|12842821|0.79|
|QNT_USDT|189.250000|-5.39|-6.52|-4.12|33840206|3.17|
|DOT_USDT|0.856000|-3.91|-8.36|-2.64|8454288|1.17|
|DASH_USDT|45.860000|-3.69|-2.83|-2.42|10968598|2.18|
|PUMPFUN_USDT|0.003554|-3.47|-13.40|-2.20|7432214|2.81|
|SOL_USDT|85.700000|-2.49|-8.35|-1.22|650947941|1.17|
|XRP_USDT|1.086200|-2.48|-12.99|-1.21|272088112|0.92|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.020000|125.540000|126.020000|1.09|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002441|0.002448|0.002441|0.74|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167940|0.166250|0.167940|1.53|N|Y/Y|Y/N|Y|N|
|DASH_USDT|45.860000|45.390000|45.860000|1.46|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.856000|0.854200|0.856000|0.50|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006055|0.005560|0.006084|1.06|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003554|0.003532|0.003554|4.78|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.250000|189.350000|189.260000|1.75|Y|Y/Y|Y/Y|Y|Y|
|SOL_USDT|85.700000|85.580000|85.700000|1.19|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.086200|1.085300|1.086200|2.43|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1144.850000|1134.630000|1144.850000|0.69|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T08:45:01+00:00, last15m_closed_end=2026-11-10T08:45+00:00, prior8high=127.890000, depth_time=2026-11-10T08:45:17+00:00, book20_bid_proxy_usdt=671123, book20_ask_proxy_usdt=446835, funding_indicative=0.000073, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.49%, turnover=12842821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T08:45:00+00:00, last15m_closed_end=2026-11-10T08:45+00:00, prior8high=0.002555, depth_time=2026-11-10T08:45:08+00:00, book20_bid_proxy_usdt=49713, book20_ask_proxy_usdt=86790, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-50.15%, turnover=15393514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T08:45:00+00:00, last15m_closed_end=2026-11-10T08:45+00:00, prior8high=0.172460, depth_time=2026-11-10T08:45:12+00:00, book20_bid_proxy_usdt=84921, book20_ask_proxy_usdt=67283, funding_indicative=-0.000110, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.74%, turnover=37334618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T08:45:01+00:00, last15m_closed_end=2026-11-10T08:45+00:00, prior8high=45.950000, depth_time=2026-11-10T08:45:25+00:00, book20_bid_proxy_usdt=590153, book20_ask_proxy_usdt=686956, funding_indicative=0.000037, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=10968598. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T08:45:01+00:00, last15m_closed_end=2026-11-10T08:45+00:00, prior8high=0.862700, depth_time=2026-11-10T08:45:23+00:00, book20_bid_proxy_usdt=733952, book20_ask_proxy_usdt=494444, funding_indicative=-0.000036, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.91%, turnover=8454288. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T08:45:00+00:00, last15m_closed_end=2026-11-10T08:45+00:00, prior8high=0.006849, depth_time=2026-11-10T08:45:11+00:00, book20_bid_proxy_usdt=21963, book20_ask_proxy_usdt=13300, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-40.23%, turnover=25026816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T08:45:01+00:00, last15m_closed_end=2026-11-10T08:45+00:00, prior8high=0.003602, depth_time=2026-11-10T08:45:28+00:00, book20_bid_proxy_usdt=3163661, book20_ask_proxy_usdt=2458531, funding_indicative=0.000040, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.47%, turnover=7432214. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T08:45:01+00:00, last15m_closed_end=2026-11-10T08:45+00:00, prior8high=192.140000, depth_time=2026-11-10T08:45:20+00:00, book20_bid_proxy_usdt=126000, book20_ask_proxy_usdt=87857, funding_indicative=-0.000159, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.39%, turnover=33840206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T08:45:00+00:00, last15m_closed_end=2026-11-10T08:45+00:00, prior8high=86.490000, depth_time=2026-11-10T08:45:30+00:00, book20_bid_proxy_usdt=21251529, book20_ask_proxy_usdt=15205466, funding_indicative=0.000083, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=650947941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-10T08:45:00+00:00, last15m_closed_end=2026-11-10T08:45+00:00, prior8high=1.106100, depth_time=2026-11-10T08:45:33+00:00, book20_bid_proxy_usdt=5579327, book20_ask_proxy_usdt=2845555, funding_indicative=0.000085, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=272088112. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T08:45:00+00:00, last15m_closed_end=2026-11-10T08:45+00:00, prior8high=1159.070000, depth_time=2026-11-10T08:45:15+00:00, book20_bid_proxy_usdt=206853, book20_ask_proxy_usdt=238376, funding_indicative=0.000051, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.59%, turnover=2363194068. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
