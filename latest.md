# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T13:45:34Z**
- feed_generated_utc: 2026-10-20T13:45:37+00:00
- source_sha256: `27edc18f3f12631b77c4956ff31a859caafc2cfdf8e5464a2b485105a0e1a058`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T13:45+00:00, close=81614.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T13:00+00:00, close=81577.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.066214|-23.92|297.39|-23.55|8757094|8.43|
|NEAR_USDT|4.695000|-4.26|-15.39|-3.89|167751884|2.13|
|BTW_USDT|1.684700|-3.84|-4.04|-3.47|36268434|0.59|
|ARB_USDT|0.188220|-3.78|-0.13|-3.41|97218197|0.53|
|ZRO_USDT|1.833200|-3.61|-18.92|-3.24|8415920|0.55|
|SAND_USDT|0.057020|-3.58|-8.16|-3.21|5369205|1.75|
|AKE_USDT|0.029946|-2.66|27.21|-2.29|6661243|1.67|
|QNT_USDT|192.340000|-1.71|-15.78|-1.34|72729043|0.52|
|UNI_USDT|7.166000|-1.67|-3.39|-1.30|9852642|1.40|
|LTC_USDT|58.790000|-1.57|-6.62|-1.20|13269950|1.70|
|TAO_USDT|264.400000|-1.45|-7.64|-1.08|60665255|1.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066214|0.066903|0.065914|1.35|Y|Y/Y|Y/N|Y|N|
|AKE_USDT|0.029946|0.029930|0.029946|0.31|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.188220|0.187500|0.188330|2.23|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.684700|1.675000|1.684700|0.36|N|Y/Y|Y/Y|Y|N|
|LTC_USDT|58.790000|58.250000|58.790000|3.31|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.695000|4.641000|4.697000|1.83|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|192.340000|191.840000|192.340000|2.30|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.057020|0.056510|0.057050|0.60|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|264.400000|262.540000|264.460000|1.39|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.166000|7.094000|7.167000|3.37|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.833200|1.756300|1.835200|5.03|N|Y/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T13:45:02+00:00, last15m_closed_end=2026-10-20T13:45+00:00, prior8high=0.069163, depth_time=2026-10-20T13:45:08+00:00, book20_bid_proxy_usdt=16433, book20_ask_proxy_usdt=7228, funding_indicative=0.000047, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.92%, turnover=8757094. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-20T13:45:02+00:00, last15m_closed_end=2026-10-20T13:45+00:00, prior8high=0.031045, depth_time=2026-10-20T13:45:23+00:00, book20_bid_proxy_usdt=10427, book20_ask_proxy_usdt=13255, funding_indicative=0.000050, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=6661243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T13:45:02+00:00, last15m_closed_end=2026-10-20T13:45+00:00, prior8high=0.190110, depth_time=2026-10-20T13:45:16+00:00, book20_bid_proxy_usdt=45621, book20_ask_proxy_usdt=81282, funding_indicative=0.000048, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.78%, turnover=97218197. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T13:45:02+00:00, last15m_closed_end=2026-10-20T13:45+00:00, prior8high=1.839100, depth_time=2026-10-20T13:45:14+00:00, book20_bid_proxy_usdt=13188, book20_ask_proxy_usdt=8127, funding_indicative=-0.003001, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.84%, turnover=36268434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-20T13:45:02+00:00, last15m_closed_end=2026-10-20T13:45+00:00, prior8high=59.000000, depth_time=2026-10-20T13:45:30+00:00, book20_bid_proxy_usdt=826448, book20_ask_proxy_usdt=880440, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=13269950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T13:45:02+00:00, last15m_closed_end=2026-10-20T13:45+00:00, prior8high=4.728000, depth_time=2026-10-20T13:45:11+00:00, book20_bid_proxy_usdt=738225, book20_ask_proxy_usdt=365230, funding_indicative=-0.000024, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.26%, turnover=167751884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T13:45:02+00:00, last15m_closed_end=2026-10-20T13:45+00:00, prior8high=195.540000, depth_time=2026-10-20T13:45:26+00:00, book20_bid_proxy_usdt=69201, book20_ask_proxy_usdt=88075, funding_indicative=0.000093, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=72729043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T13:45:03+00:00, last15m_closed_end=2026-10-20T13:45+00:00, prior8high=0.057330, depth_time=2026-10-20T13:45:19+00:00, book20_bid_proxy_usdt=1172422, book20_ask_proxy_usdt=843341, funding_indicative=-0.001802, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=5369205. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T13:45:02+00:00, last15m_closed_end=2026-10-20T13:45+00:00, prior8high=265.610000, depth_time=2026-10-20T13:45:33+00:00, book20_bid_proxy_usdt=62695, book20_ask_proxy_usdt=116945, funding_indicative=0.000043, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.45%, turnover=60665255. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T13:45:02+00:00, last15m_closed_end=2026-10-20T13:45+00:00, prior8high=7.197000, depth_time=2026-10-20T13:45:28+00:00, book20_bid_proxy_usdt=1367420, book20_ask_proxy_usdt=1361095, funding_indicative=-0.000009, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=9852642. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T13:45:02+00:00, last15m_closed_end=2026-10-20T13:45+00:00, prior8high=1.911700, depth_time=2026-10-20T13:45:18+00:00, book20_bid_proxy_usdt=39686, book20_ask_proxy_usdt=36498, funding_indicative=0.000008, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.61%, turnover=8415920. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
