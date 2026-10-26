# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T02:45:26Z**
- feed_generated_utc: 2026-10-26T02:45:30+00:00
- source_sha256: `c053ca83b3a4cfb63b31d86ff44613918cfd1580cd74d79d31ac3d50936893c9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T02:45+00:00, close=79549.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T02:00+00:00, close=79714.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004322|-38.00|134.50|-36.70|10955740|2.31|
|APR_USDT|0.032980|-20.16|21.07|-18.86|12135272|3.03|
|T_USDT|0.004932|-8.37|4.89|-7.07|7354821|2.03|
|DASH_USDT|50.440000|-3.75|5.34|-2.45|13832809|1.98|
|WLD_USDT|0.442400|-3.10|-7.11|-1.80|73639892|2.26|
|PUMPFUN_USDT|0.004161|-2.89|-0.81|-1.59|17252698|2.40|
|PEPE_USDT|0.000004|-2.87|10.75|-1.57|73724164|0.23|
|XMR_USDT|589.990000|-2.84|1.28|-1.54|6824077|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.032980|0.032120|0.033100|1.02|N|Y/Y|N/N|Y|N|
|DASH_USDT|50.440000|50.550000|50.440000|1.49|Y|Y/Y|Y/N|Y|N|
|JCT_USDT|0.004322|0.004206|0.004332|3.74|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.31|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004161|0.004162|0.004161|0.47|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004932|0.004873|0.004932|0.98|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.442400|0.442200|0.442400|0.68|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|589.990000|588.410000|589.980000|1.68|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T02:45:02+00:00, last15m_closed_end=2026-10-26T02:45+00:00, prior8high=0.040160, depth_time=2026-10-26T02:45:09+00:00, book20_bid_proxy_usdt=69351, book20_ask_proxy_usdt=75972, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-20.16%, turnover=12135272. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T02:45:03+00:00, last15m_closed_end=2026-10-26T02:45+00:00, prior8high=51.910000, depth_time=2026-10-26T02:45:13+00:00, book20_bid_proxy_usdt=981533, book20_ask_proxy_usdt=647350, funding_indicative=0.000067, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.75%, turnover=13832809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T02:45:02+00:00, last15m_closed_end=2026-10-26T02:45+00:00, prior8high=0.006232, depth_time=2026-10-26T02:45:07+00:00, book20_bid_proxy_usdt=18489, book20_ask_proxy_usdt=13944, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-38.00%, turnover=10955740. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T02:45:03+00:00, last15m_closed_end=2026-10-26T02:45+00:00, prior8high=0.000004, depth_time=2026-10-26T02:45:21+00:00, book20_bid_proxy_usdt=65814, book20_ask_proxy_usdt=49700, funding_indicative=0.000035, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.87%, turnover=73724164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T02:45:03+00:00, last15m_closed_end=2026-10-26T02:45+00:00, prior8high=0.004272, depth_time=2026-10-26T02:45:19+00:00, book20_bid_proxy_usdt=2530972, book20_ask_proxy_usdt=2279646, funding_indicative=0.000042, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=17252698. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T02:45:02+00:00, last15m_closed_end=2026-10-26T02:45+00:00, prior8high=0.005030, depth_time=2026-10-26T02:45:10+00:00, book20_bid_proxy_usdt=61665, book20_ask_proxy_usdt=70646, funding_indicative=-0.001858, next_funding_utc=2026-10-26T03:00:00+00:00, funding_cycle_h=1, 24h_change=-8.37%, turnover=7354821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T02:45:03+00:00, last15m_closed_end=2026-10-26T02:45+00:00, prior8high=0.449900, depth_time=2026-10-26T02:45:16+00:00, book20_bid_proxy_usdt=2239125, book20_ask_proxy_usdt=2233712, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.10%, turnover=73639892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T02:45:02+00:00, last15m_closed_end=2026-10-26T02:45+00:00, prior8high=597.180000, depth_time=2026-10-26T02:45:25+00:00, book20_bid_proxy_usdt=17422, book20_ask_proxy_usdt=8628, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.84%, turnover=6824077. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
