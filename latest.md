# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T07:45:28Z**
- feed_generated_utc: 2026-11-10T07:45:30+00:00
- source_sha256: `2e7d4faf80ff9e259a4cad3390223bd5291c2c48f47cadf6fbd35a0d3c810391`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T07:45+00:00, close=74881.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T07:00+00:00, close=74627.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002501|-48.92|-54.54|-48.10|15468793|8.00|
|JCT_USDT|0.005840|-42.35|35.27|-41.53|25953442|1.71|
|ARB_USDT|0.168200|-8.60|5.56|-7.78|36239859|0.59|
|ZEC_USDT|1156.800000|-5.62|-7.75|-4.80|2402457668|0.09|
|AAVE_USDT|127.030000|-4.73|-2.70|-3.91|13268263|0.79|
|DASH_USDT|45.660000|-4.11|-3.26|-3.29|12381223|2.19|
|QNT_USDT|191.820000|-4.10|-5.25|-3.28|34741529|0.52|
|DOT_USDT|0.859100|-3.56|-8.02|-2.74|8819951|1.16|
|SOL_USDT|86.260000|-1.85|-7.75|-1.03|659011105|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.030000|125.050000|127.030000|1.77|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002501|0.002443|0.002501|0.99|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.168200|0.167760|0.168200|1.41|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.660000|45.630000|45.660000|0.90|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.859100|0.852600|0.859100|0.68|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005840|0.006153|0.005814|2.14|Y|Y/Y|N/N|Y|N|
|QNT_USDT|191.820000|189.670000|191.820000|0.96|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.260000|85.770000|86.260000|0.98|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1156.800000|1144.770000|1156.340000|0.98|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T07:45:02+00:00, last15m_closed_end=2026-11-10T07:45+00:00, prior8high=127.620000, depth_time=2026-11-10T07:45:12+00:00, book20_bid_proxy_usdt=383740, book20_ask_proxy_usdt=421186, funding_indicative=0.000063, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.73%, turnover=13268263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T07:45:02+00:00, last15m_closed_end=2026-11-10T07:45+00:00, prior8high=0.002556, depth_time=2026-11-10T07:45:07+00:00, book20_bid_proxy_usdt=54831, book20_ask_proxy_usdt=69670, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-48.92%, turnover=15468793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T07:45:02+00:00, last15m_closed_end=2026-11-10T07:45+00:00, prior8high=0.173110, depth_time=2026-11-10T07:45:11+00:00, book20_bid_proxy_usdt=73561, book20_ask_proxy_usdt=76806, funding_indicative=-0.000061, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-8.60%, turnover=36239859. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T07:45:02+00:00, last15m_closed_end=2026-11-10T07:45+00:00, prior8high=46.200000, depth_time=2026-11-10T07:45:17+00:00, book20_bid_proxy_usdt=860935, book20_ask_proxy_usdt=567844, funding_indicative=0.000042, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.11%, turnover=12381223. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T07:45:02+00:00, last15m_closed_end=2026-11-10T07:45+00:00, prior8high=0.860700, depth_time=2026-11-10T07:45:24+00:00, book20_bid_proxy_usdt=609564, book20_ask_proxy_usdt=563034, funding_indicative=0.000012, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.56%, turnover=8819951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T07:45:02+00:00, last15m_closed_end=2026-11-10T07:45+00:00, prior8high=0.007663, depth_time=2026-11-10T07:45:10+00:00, book20_bid_proxy_usdt=49889, book20_ask_proxy_usdt=33860, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-42.35%, turnover=25953442. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T07:45:02+00:00, last15m_closed_end=2026-11-10T07:45+00:00, prior8high=192.180000, depth_time=2026-11-10T07:45:22+00:00, book20_bid_proxy_usdt=98074, book20_ask_proxy_usdt=103193, funding_indicative=-0.000117, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.10%, turnover=34741529. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T07:45:01+00:00, last15m_closed_end=2026-11-10T07:45+00:00, prior8high=86.580000, depth_time=2026-11-10T07:45:27+00:00, book20_bid_proxy_usdt=17227416, book20_ask_proxy_usdt=14454208, funding_indicative=0.000084, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=659011105. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T07:45:02+00:00, last15m_closed_end=2026-11-10T07:45+00:00, prior8high=1165.460000, depth_time=2026-11-10T07:45:15+00:00, book20_bid_proxy_usdt=352675, book20_ask_proxy_usdt=119940, funding_indicative=0.000052, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.62%, turnover=2402457668. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
