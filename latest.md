# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T05:15:30Z**
- feed_generated_utc: 2026-11-10T05:15:31+00:00
- source_sha256: `81049ba96ae991c8ddf4d2aae81a34512620b56a936fd53120fdb76915afdc02`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T05:15+00:00, close=74824.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T05:00+00:00, close=74754.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002507|-48.80|-54.43|-47.91|15338232|3.99|
|JCT_USDT|0.007550|-25.47|74.88|-24.58|26604211|5.30|
|ARB_USDT|0.171890|-6.60|7.88|-5.71|33529426|0.58|
|ZEC_USDT|1157.110000|-5.59|-7.73|-4.70|2407863049|0.09|
|AAVE_USDT|126.920000|-4.82|-2.78|-3.93|13484221|0.79|
|DOT_USDT|0.853800|-4.16|-8.59|-3.27|10681035|1.17|
|QNT_USDT|192.230000|-3.90|-5.04|-3.01|36539722|0.52|
|DASH_USDT|46.140000|-3.10|-2.24|-2.21|14132187|2.17|
|INJ_USDT|7.985000|-2.34|13.92|-1.45|17961650|3.76|
|SOL_USDT|86.210000|-1.91|-7.80|-1.02|641564914|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.920000|126.070000|127.020000|1.50|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002507|0.002302|0.002508|0.23|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.171890|0.170290|0.171880|4.02|N|Y/Y|N/N|Y|N|
|DASH_USDT|46.140000|45.750000|46.140000|0.89|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.853800|0.846300|0.853800|1.03|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.985000|7.956000|7.985000|0.23|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.007550|0.007526|0.007565|0.95|N|Y/Y|N/N|Y|N|
|QNT_USDT|192.230000|190.450000|192.230000|0.79|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.210000|85.470000|86.210000|1.37|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1157.110000|1142.950000|1156.920000|0.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T05:15:02+00:00, last15m_closed_end=2026-11-10T05:15+00:00, prior8high=131.160000, depth_time=2026-11-10T05:15:13+00:00, book20_bid_proxy_usdt=488708, book20_ask_proxy_usdt=404750, funding_indicative=0.000010, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.82%, turnover=13484221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T05:15:02+00:00, last15m_closed_end=2026-11-10T05:15+00:00, prior8high=0.002790, depth_time=2026-11-10T05:15:07+00:00, book20_bid_proxy_usdt=70899, book20_ask_proxy_usdt=55786, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-48.80%, turnover=15338232. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T05:15:02+00:00, last15m_closed_end=2026-11-10T05:15+00:00, prior8high=0.173080, depth_time=2026-11-10T05:15:09+00:00, book20_bid_proxy_usdt=78080, book20_ask_proxy_usdt=63522, funding_indicative=-0.000003, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.60%, turnover=33529426. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T05:15:02+00:00, last15m_closed_end=2026-11-10T05:15+00:00, prior8high=46.350000, depth_time=2026-11-10T05:15:24+00:00, book20_bid_proxy_usdt=637511, book20_ask_proxy_usdt=683210, funding_indicative=0.000006, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.10%, turnover=14132187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T05:15:02+00:00, last15m_closed_end=2026-11-10T05:15+00:00, prior8high=0.854500, depth_time=2026-11-10T05:15:18+00:00, book20_bid_proxy_usdt=449766, book20_ask_proxy_usdt=632352, funding_indicative=0.000011, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.16%, turnover=10681035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-10T05:15:02+00:00, last15m_closed_end=2026-11-10T05:15+00:00, prior8high=8.068000, depth_time=2026-11-10T05:15:23+00:00, book20_bid_proxy_usdt=154545, book20_ask_proxy_usdt=199717, funding_indicative=-0.000067, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=17961650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T05:15:02+00:00, last15m_closed_end=2026-11-10T05:15+00:00, prior8high=0.008970, depth_time=2026-11-10T05:15:09+00:00, book20_bid_proxy_usdt=24423, book20_ask_proxy_usdt=25103, funding_indicative=0.000054, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-25.47%, turnover=26604211. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T05:15:02+00:00, last15m_closed_end=2026-11-10T05:15+00:00, prior8high=194.060000, depth_time=2026-11-10T05:15:22+00:00, book20_bid_proxy_usdt=86692, book20_ask_proxy_usdt=70454, funding_indicative=-0.000088, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.90%, turnover=36539722. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T05:15:02+00:00, last15m_closed_end=2026-11-10T05:15+00:00, prior8high=86.220000, depth_time=2026-11-10T05:15:29+00:00, book20_bid_proxy_usdt=16236479, book20_ask_proxy_usdt=19095900, funding_indicative=0.000009, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=641564914. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T05:15:02+00:00, last15m_closed_end=2026-11-10T05:15+00:00, prior8high=1162.430000, depth_time=2026-11-10T05:15:14+00:00, book20_bid_proxy_usdt=284311, book20_ask_proxy_usdt=146692, funding_indicative=0.000074, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.59%, turnover=2407863049. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
