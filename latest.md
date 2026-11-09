# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T13:15:36Z**
- feed_generated_utc: 2026-11-09T13:15:37+00:00
- source_sha256: `cf7442b69fd814cacdaa6c6203784194d6f81d5f1a742c275f04bc465f53a6e8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T13:15+00:00, close=74736.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T13:00+00:00, close=74895.8, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001494|-23.68|28.31|-21.97|6149702|0.67|
|AKE_USDT|0.004805|-10.30|-47.54|-8.59|9113011|4.17|
|ASTER_USDT|0.639400|-5.94|-8.57|-4.23|5701290|1.56|
|ETH_USDT|2120.140000|-5.39|-6.42|-3.68|1596350951|0.05|
|HYPE_USDT|73.547000|-5.01|-16.12|-3.30|49607013|0.14|
|XRP_USDT|1.098200|-4.98|-12.13|-3.27|288152132|0.91|
|TRUMPOFFICIAL_USDT|1.135000|-4.54|-33.85|-2.83|6295805|8.80|
|AIOT_USDT|0.144440|-4.43|64.62|-2.72|7289074|4.85|
|ZEC_USDT|1216.570000|-4.25|-1.72|-2.54|2308940711|0.08|
|NEAR_USDT|3.547000|-4.16|-18.10|-2.45|46813409|2.82|
|HOT_USDT|0.000414|-3.65|15.10|-1.94|6838146|4.83|
|SOL_USDT|86.520000|-3.52|-8.69|-1.81|749403794|1.16|
|LIT_USDT|3.092100|-3.17|-4.27|-1.46|13076140|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIOT_USDT|0.144440|0.143010|0.144470|0.58|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.004805|0.004635|0.004805|0.21|N|Y/N|N/Y|Y|N|
|ASTER_USDT|0.639400|0.626700|0.639400|1.37|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2120.140000|2104.370000|2120.140000|0.81|N|Y/Y|Y/Y|Y|N|
|HOT_USDT|0.000414|0.000411|0.000414|0.25|N|Y/N|N/N|Y|N|
|HYPE_USDT|73.547000|72.747000|73.547000|0.64|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.092100|3.086500|3.092100|0.68|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.547000|3.480000|3.547000|1.20|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001494|0.001487|0.001494|0.99|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.520000|85.770000|86.520000|1.60|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.135000|1.125000|1.135000|1.74|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.098200|1.076200|1.098200|1.16|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1216.570000|1192.930000|1216.570000|1.12|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AIOT_USDT: quote_utc=2026-11-09T13:14:59+00:00, last15m_closed_end=2026-11-09T13:15+00:00, prior8high=0.164250, depth_time=2026-11-09T13:15:21+00:00, book20_bid_proxy_usdt=3729, book20_ask_proxy_usdt=5101, funding_indicative=0.000180, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.43%, turnover=7289074. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-09T13:14:59+00:00, last15m_closed_end=2026-11-09T13:15+00:00, prior8high=0.005718, depth_time=2026-11-09T13:15:09+00:00, book20_bid_proxy_usdt=28594, book20_ask_proxy_usdt=27914, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.30%, turnover=9113011. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T13:15:00+00:00, last15m_closed_end=2026-11-09T13:15+00:00, prior8high=0.643800, depth_time=2026-11-09T13:15:10+00:00, book20_bid_proxy_usdt=728829, book20_ask_proxy_usdt=880114, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.94%, turnover=5701290. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T13:14:59+00:00, last15m_closed_end=2026-11-09T13:15+00:00, prior8high=2132.860000, depth_time=2026-11-09T13:15:13+00:00, book20_bid_proxy_usdt=2678211, book20_ask_proxy_usdt=2131788, funding_indicative=-0.000010, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.39%, turnover=1596350951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-09T13:14:59+00:00, last15m_closed_end=2026-11-09T13:15+00:00, prior8high=0.000427, depth_time=2026-11-09T13:15:30+00:00, book20_bid_proxy_usdt=72557, book20_ask_proxy_usdt=146649, funding_indicative=-0.000898, next_funding_utc=2026-11-09T14:00:00+00:00, funding_cycle_h=1, 24h_change=-3.65%, turnover=6838146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T13:14:59+00:00, last15m_closed_end=2026-11-09T13:15+00:00, prior8high=74.040000, depth_time=2026-11-09T13:15:16+00:00, book20_bid_proxy_usdt=141937, book20_ask_proxy_usdt=72831, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.01%, turnover=49607013. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-09T13:15:00+00:00, last15m_closed_end=2026-11-09T13:15+00:00, prior8high=3.152000, depth_time=2026-11-09T13:15:34+00:00, book20_bid_proxy_usdt=28755, book20_ask_proxy_usdt=26610, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.17%, turnover=13076140. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T13:14:59+00:00, last15m_closed_end=2026-11-09T13:15+00:00, prior8high=3.587000, depth_time=2026-11-09T13:15:26+00:00, book20_bid_proxy_usdt=2324199, book20_ask_proxy_usdt=2189948, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.16%, turnover=46813409. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T13:14:59+00:00, last15m_closed_end=2026-11-09T13:15+00:00, prior8high=0.001556, depth_time=2026-11-09T13:15:06+00:00, book20_bid_proxy_usdt=18354, book20_ask_proxy_usdt=21215, funding_indicative=0.000003, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.68%, turnover=6149702. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T13:14:59+00:00, last15m_closed_end=2026-11-09T13:15+00:00, prior8high=87.140000, depth_time=2026-11-09T13:15:33+00:00, book20_bid_proxy_usdt=13878638, book20_ask_proxy_usdt=16910818, funding_indicative=0.000016, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.52%, turnover=749403794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T13:15:00+00:00, last15m_closed_end=2026-11-09T13:15+00:00, prior8high=1.148000, depth_time=2026-11-09T13:15:21+00:00, book20_bid_proxy_usdt=2783462, book20_ask_proxy_usdt=2188809, funding_indicative=0.000017, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.54%, turnover=6295805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T13:14:59+00:00, last15m_closed_end=2026-11-09T13:15+00:00, prior8high=1.110100, depth_time=2026-11-09T13:15:18+00:00, book20_bid_proxy_usdt=3118288, book20_ask_proxy_usdt=2891051, funding_indicative=0.000082, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.98%, turnover=288152132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T13:14:59+00:00, last15m_closed_end=2026-11-09T13:15+00:00, prior8high=1228.080000, depth_time=2026-11-09T13:15:25+00:00, book20_bid_proxy_usdt=192161, book20_ask_proxy_usdt=464800, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.25%, turnover=2308940711. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
