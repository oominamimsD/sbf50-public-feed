# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T11:15:33Z**
- feed_generated_utc: 2026-10-23T11:15:35+00:00
- source_sha256: `bf258ab466770584425db5b448e54c4a46ec3e6440095261fc94ac63685b5822`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T11:15+00:00, close=81569.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T11:00+00:00, close=81656.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LIT_USDT|3.378700|-6.51|9.29|-6.42|8986079|0.30|
|STRK_USDT|0.051350|-5.53|-46.71|-5.44|12074162|1.95|
|QNT_USDT|181.900000|-4.61|-12.51|-4.52|52118327|0.55|
|TIA_USDT|0.548000|-3.58|-9.04|-3.49|25071764|1.82|
|PUMPFUN_USDT|0.004556|-2.62|0.66|-2.53|36605555|2.19|
|ARB_USDT|0.179880|-2.04|-5.29|-1.95|24812101|0.56|
|ZEC_USDT|1209.130000|-2.03|2.49|-1.94|1884702542|0.08|
|SILVER_USDT|54.180000|-1.95|-5.18|-1.86|331179138|1.85|
|OP_USDT|0.117580|-1.89|-15.33|-1.80|5975863|0.85|
|HBAR_USDT|0.079020|-1.36|-5.42|-1.27|20213617|1.26|
|NEAR_USDT|4.882000|-1.25|-4.62|-1.16|120144584|2.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.179880|0.179350|0.179880|1.34|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.079020|0.078930|0.079020|1.20|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.378700|3.369300|3.378700|1.03|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.882000|4.880000|4.881000|1.52|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.117580|0.117670|0.117580|2.87|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.004556|0.004535|0.004557|3.54|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|181.900000|181.170000|181.930000|1.69|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.180000|53.870000|54.170000|2.27|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.051350|0.051250|0.051350|2.85|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.548000|0.547000|0.548000|0.83|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1209.130000|1206.310000|1209.290000|1.61|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T11:15:02+00:00, last15m_closed_end=2026-10-23T11:15+00:00, prior8high=0.182070, depth_time=2026-10-23T11:15:20+00:00, book20_bid_proxy_usdt=138516, book20_ask_proxy_usdt=80375, funding_indicative=-0.000011, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=24812101. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-23T11:15:02+00:00, last15m_closed_end=2026-10-23T11:15+00:00, prior8high=0.080150, depth_time=2026-10-23T11:15:29+00:00, book20_bid_proxy_usdt=488596, book20_ask_proxy_usdt=1056682, funding_indicative=0.000042, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=20213617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T11:15:02+00:00, last15m_closed_end=2026-10-23T11:15+00:00, prior8high=3.420200, depth_time=2026-10-23T11:15:07+00:00, book20_bid_proxy_usdt=26119, book20_ask_proxy_usdt=39154, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.51%, turnover=8986079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-23T11:15:01+00:00, last15m_closed_end=2026-10-23T11:15+00:00, prior8high=4.970000, depth_time=2026-10-23T11:15:33+00:00, book20_bid_proxy_usdt=2677042, book20_ask_proxy_usdt=4326853, funding_indicative=-0.000004, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=120144584. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T11:15:02+00:00, last15m_closed_end=2026-10-23T11:15+00:00, prior8high=0.119340, depth_time=2026-10-23T11:15:27+00:00, book20_bid_proxy_usdt=86707, book20_ask_proxy_usdt=118436, funding_indicative=0.000031, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=5975863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T11:15:02+00:00, last15m_closed_end=2026-10-23T11:15+00:00, prior8high=0.004638, depth_time=2026-10-23T11:15:17+00:00, book20_bid_proxy_usdt=1336932, book20_ask_proxy_usdt=2735956, funding_indicative=0.000010, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.62%, turnover=36605555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T11:15:02+00:00, last15m_closed_end=2026-10-23T11:15+00:00, prior8high=187.530000, depth_time=2026-10-23T11:15:12+00:00, book20_bid_proxy_usdt=70601, book20_ask_proxy_usdt=90012, funding_indicative=-0.000160, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.61%, turnover=52118327. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T11:15:01+00:00, last15m_closed_end=2026-10-23T11:15+00:00, prior8high=54.210000, depth_time=2026-10-23T11:15:22+00:00, book20_bid_proxy_usdt=36276769, book20_ask_proxy_usdt=33027478, funding_indicative=0.000015, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=331179138. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T11:15:02+00:00, last15m_closed_end=2026-10-23T11:15+00:00, prior8high=0.052350, depth_time=2026-10-23T11:15:10+00:00, book20_bid_proxy_usdt=658478, book20_ask_proxy_usdt=625712, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.53%, turnover=12074162. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T11:15:02+00:00, last15m_closed_end=2026-10-23T11:15+00:00, prior8high=0.554600, depth_time=2026-10-23T11:15:15+00:00, book20_bid_proxy_usdt=375589, book20_ask_proxy_usdt=388543, funding_indicative=0.000017, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.58%, turnover=25071764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-23T11:15:01+00:00, last15m_closed_end=2026-10-23T11:15+00:00, prior8high=1234.380000, depth_time=2026-10-23T11:15:23+00:00, book20_bid_proxy_usdt=736849, book20_ask_proxy_usdt=294284, funding_indicative=0.000032, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=1884702542. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
