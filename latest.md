# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T04:15:31Z**
- feed_generated_utc: 2026-11-10T04:15:33+00:00
- source_sha256: `da1a128921a900a5561bb5bfa16eb0ab30563e36ea73ae641f6bc4be00d412a3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T04:15+00:00, close=74583.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002688|-45.10|-51.14|-43.89|15224028|3.73|
|JCT_USDT|0.008092|-20.12|87.44|-18.91|27067305|4.93|
|ARB_USDT|0.171710|-6.69|7.77|-5.48|32100781|4.08|
|ZEC_USDT|1150.660000|-6.12|-8.24|-4.91|2390393550|0.09|
|DOT_USDT|0.850000|-4.59|-9.00|-3.38|10882762|1.18|
|QNT_USDT|191.100000|-4.46|-5.60|-3.25|36398313|0.52|
|AAVE_USDT|127.870000|-4.10|-2.06|-2.89|13537877|0.78|
|DASH_USDT|45.990000|-3.42|-2.56|-2.21|14209617|2.17|
|HYPE_USDT|73.932000|-3.12|-13.74|-1.91|47442884|0.14|
|WLD_USDT|0.316400|-2.91|-16.99|-1.70|26093241|3.16|
|SOL_USDT|85.910000|-2.25|-8.12|-1.04|629504767|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.870000|128.190000|127.930000|3.38|Y|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002688|0.002302|0.002688|0.44|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.171710|0.170950|0.171690|3.93|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.990000|45.810000|45.990000|1.24|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.850000|0.846300|0.850000|2.62|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.932000|73.284000|73.932000|2.57|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008092|0.007903|0.008087|2.13|N|Y/Y|N/N|Y|N|
|QNT_USDT|191.100000|191.900000|191.100000|1.34|Y|Y/Y|Y/Y|Y|Y|
|SOL_USDT|85.910000|85.470000|85.900000|3.16|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.316400|0.314400|0.316200|1.87|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1150.660000|1141.980000|1150.650000|0.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T04:15:00+00:00, last15m_closed_end=2026-11-10T04:15+00:00, prior8high=131.890000, depth_time=2026-11-10T04:15:21+00:00, book20_bid_proxy_usdt=318638, book20_ask_proxy_usdt=323174, funding_indicative=0.000005, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.10%, turnover=13537877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T04:15:00+00:00, last15m_closed_end=2026-11-10T04:15+00:00, prior8high=0.002858, depth_time=2026-11-10T04:15:07+00:00, book20_bid_proxy_usdt=21629, book20_ask_proxy_usdt=37469, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-45.10%, turnover=15224028. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T04:15:00+00:00, last15m_closed_end=2026-11-10T04:15+00:00, prior8high=0.174030, depth_time=2026-11-10T04:15:12+00:00, book20_bid_proxy_usdt=58952, book20_ask_proxy_usdt=66858, funding_indicative=0.000000, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.69%, turnover=32100781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T04:15:01+00:00, last15m_closed_end=2026-11-10T04:15+00:00, prior8high=46.610000, depth_time=2026-11-10T04:15:23+00:00, book20_bid_proxy_usdt=478119, book20_ask_proxy_usdt=529574, funding_indicative=-0.000023, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.42%, turnover=14209617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T04:15:00+00:00, last15m_closed_end=2026-11-10T04:15+00:00, prior8high=0.856600, depth_time=2026-11-10T04:15:15+00:00, book20_bid_proxy_usdt=674363, book20_ask_proxy_usdt=461448, funding_indicative=0.000044, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.59%, turnover=10882762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T04:15:00+00:00, last15m_closed_end=2026-11-10T04:15+00:00, prior8high=74.662000, depth_time=2026-11-10T04:15:24+00:00, book20_bid_proxy_usdt=117362, book20_ask_proxy_usdt=77205, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.12%, turnover=47442884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T04:15:00+00:00, last15m_closed_end=2026-11-10T04:15+00:00, prior8high=0.009990, depth_time=2026-11-10T04:15:10+00:00, book20_bid_proxy_usdt=21074, book20_ask_proxy_usdt=16504, funding_indicative=0.000402, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-20.12%, turnover=27067305. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T04:15:00+00:00, last15m_closed_end=2026-11-10T04:15+00:00, prior8high=194.730000, depth_time=2026-11-10T04:15:18+00:00, book20_bid_proxy_usdt=33894, book20_ask_proxy_usdt=70427, funding_indicative=-0.000034, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.46%, turnover=36398313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T04:15:00+00:00, last15m_closed_end=2026-11-10T04:15+00:00, prior8high=86.270000, depth_time=2026-11-10T04:15:30+00:00, book20_bid_proxy_usdt=17351953, book20_ask_proxy_usdt=14618463, funding_indicative=-0.000008, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=629504767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T04:15:00+00:00, last15m_closed_end=2026-11-10T04:15+00:00, prior8high=0.317600, depth_time=2026-11-10T04:15:25+00:00, book20_bid_proxy_usdt=4683792, book20_ask_proxy_usdt=5417816, funding_indicative=0.000051, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=26093241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T04:15:00+00:00, last15m_closed_end=2026-11-10T04:15+00:00, prior8high=1166.920000, depth_time=2026-11-10T04:15:14+00:00, book20_bid_proxy_usdt=551832, book20_ask_proxy_usdt=276372, funding_indicative=0.000062, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.12%, turnover=2390393550. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
