# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T13:30:33Z**
- feed_generated_utc: 2026-10-20T13:30:36+00:00
- source_sha256: `10e554699bb8e6f99732ce9d5f4e2bcbab1fd6cab1080f9e4386055bfe159a4d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1201; contracts: 1194; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T13:30+00:00, close=81383.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T13:00+00:00, close=81577.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.067166|-22.83|303.10|-22.17|8663699|0.60|
|ZRO_USDT|1.791700|-5.79|-20.75|-5.13|8160691|1.12|
|NEAR_USDT|4.686000|-4.44|-15.55|-3.78|165212794|2.14|
|ARB_USDT|0.187810|-3.99|-0.35|-3.33|96245853|0.53|
|SAND_USDT|0.057210|-3.26|-7.85|-2.60|5354113|3.50|
|BTW_USDT|1.702200|-2.84|-3.05|-2.18|36096941|1.76|
|AKE_USDT|0.030035|-2.37|27.59|-1.71|6611985|0.33|
|UNI_USDT|7.143000|-1.98|-3.70|-1.32|9669622|1.40|
|TAO_USDT|263.200000|-1.90|-8.06|-1.24|59861229|1.14|
|QNT_USDT|192.240000|-1.76|-15.82|-1.10|71620396|0.52|
|LTC_USDT|58.720000|-1.69|-6.73|-1.03|13054300|5.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.067166|0.066903|0.067116|0.92|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.030035|0.029934|0.030034|0.29|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.187810|0.187500|0.187810|0.59|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.702200|1.675000|1.702200|0.34|N|Y/Y|Y/Y|Y|N|
|LTC_USDT|58.720000|58.250000|58.720000|0.21|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.686000|4.630000|4.686000|1.18|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|192.240000|191.840000|192.240000|0.71|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.057210|0.056510|0.057210|0.46|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.200000|262.540000|263.300000|0.41|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.143000|7.094000|7.148000|0.62|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.791700|1.756300|1.791700|3.71|N|Y/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T13:30:00+00:00, last15m_closed_end=2026-10-20T13:30+00:00, prior8high=0.069163, depth_time=2026-10-20T13:30:06+00:00, book20_bid_proxy_usdt=8959, book20_ask_proxy_usdt=9640, funding_indicative=0.000066, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.83%, turnover=8663699. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-20T13:30:00+00:00, last15m_closed_end=2026-10-20T13:30+00:00, prior8high=0.031085, depth_time=2026-10-20T13:30:23+00:00, book20_bid_proxy_usdt=10136, book20_ask_proxy_usdt=12492, funding_indicative=0.000050, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.37%, turnover=6611985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T13:30:00+00:00, last15m_closed_end=2026-10-20T13:30+00:00, prior8high=0.190110, depth_time=2026-10-20T13:30:16+00:00, book20_bid_proxy_usdt=38046, book20_ask_proxy_usdt=43000, funding_indicative=0.000061, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.99%, turnover=96245853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T13:30:00+00:00, last15m_closed_end=2026-10-20T13:30+00:00, prior8high=1.857100, depth_time=2026-10-20T13:30:20+00:00, book20_bid_proxy_usdt=13431, book20_ask_proxy_usdt=12599, funding_indicative=-0.003071, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=36096941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-20T13:30:01+00:00, last15m_closed_end=2026-10-20T13:30+00:00, prior8high=59.000000, depth_time=2026-10-20T13:30:32+00:00, book20_bid_proxy_usdt=1432387, book20_ask_proxy_usdt=1393887, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=13054300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T13:30:00+00:00, last15m_closed_end=2026-10-20T13:30+00:00, prior8high=4.728000, depth_time=2026-10-20T13:30:13+00:00, book20_bid_proxy_usdt=2969197, book20_ask_proxy_usdt=4385821, funding_indicative=-0.000016, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.44%, turnover=165212794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T13:30:00+00:00, last15m_closed_end=2026-10-20T13:30+00:00, prior8high=195.540000, depth_time=2026-10-20T13:30:30+00:00, book20_bid_proxy_usdt=41862, book20_ask_proxy_usdt=70389, funding_indicative=0.000087, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=71620396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T13:30:01+00:00, last15m_closed_end=2026-10-20T13:30+00:00, prior8high=0.057280, depth_time=2026-10-20T13:30:16+00:00, book20_bid_proxy_usdt=688961, book20_ask_proxy_usdt=733709, funding_indicative=-0.001794, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.26%, turnover=5354113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T13:30:00+00:00, last15m_closed_end=2026-10-20T13:30+00:00, prior8high=265.610000, depth_time=2026-10-20T13:30:28+00:00, book20_bid_proxy_usdt=46358, book20_ask_proxy_usdt=44862, funding_indicative=0.000038, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=59861229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T13:30:01+00:00, last15m_closed_end=2026-10-20T13:30+00:00, prior8high=7.197000, depth_time=2026-10-20T13:30:26+00:00, book20_bid_proxy_usdt=1084534, book20_ask_proxy_usdt=2311841, funding_indicative=-0.000003, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=9669622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T13:30:01+00:00, last15m_closed_end=2026-10-20T13:30+00:00, prior8high=1.913900, depth_time=2026-10-20T13:30:11+00:00, book20_bid_proxy_usdt=30949, book20_ask_proxy_usdt=39555, funding_indicative=0.000012, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.79%, turnover=8160691. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
