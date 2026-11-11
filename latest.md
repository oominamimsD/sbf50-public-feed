# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T06:45:30Z**
- feed_generated_utc: 2026-11-11T06:45:31+00:00
- source_sha256: `abd91e6023bcec54b6244dc78e200bf016c80083dc6cc7bc8c54cec4e0fb9f28`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T06:45+00:00, close=73624.2, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T06:00+00:00, close=73895.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.216750|-13.62|61.17|-14.23|66687556|4.15|
|ZEC_USDT|983.560000|-10.04|-18.29|-10.65|2204318064|0.10|
|AKE_USDT|0.002686|-7.82|-35.37|-8.43|9422979|3.72|
|UNI_USDT|6.450000|-5.56|-12.28|-6.17|38613107|1.55|
|DASH_USDT|43.760000|-3.05|-5.15|-3.66|15376564|2.29|
|VVV_USDT|18.920000|-1.65|-15.38|-2.26|5411376|1.58|
|ARB_USDT|0.158970|-1.49|-0.56|-2.10|31873132|1.26|
|QNT_USDT|178.660000|-1.12|-8.57|-1.73|46006904|0.56|
|DOT_USDT|0.832700|-1.06|-11.65|-1.67|8260583|1.20|
|HBAR_USDT|0.065280|-0.76|-6.78|-1.37|5899489|1.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002686|0.002607|0.002686|0.41|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158970|0.159410|0.158970|1.75|Y|Y/Y|Y/Y|Y|Y|
|DASH_USDT|43.760000|43.720000|43.760000|1.34|N|N/N|Y/Y|Y|N|
|DOT_USDT|0.832700|0.834200|0.832700|2.37|Y|Y/Y|Y/Y|Y|Y|
|HBAR_USDT|0.065280|0.065430|0.065270|5.89|Y|Y/Y|Y/Y|Y|Y|
|INIT_USDT|0.216750|0.220280|0.216750|1.00|N|N/N|N/N|Y|N|
|QNT_USDT|178.660000|179.290000|178.660000|1.08|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.450000|6.497000|6.450000|1.18|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|18.920000|19.006000|18.920000|0.93|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|983.560000|998.480000|982.920000|1.20|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T06:44:59+00:00, last15m_closed_end=2026-11-11T06:45+00:00, prior8high=0.002864, depth_time=2026-11-11T06:45:12+00:00, book20_bid_proxy_usdt=47314, book20_ask_proxy_usdt=43082, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.82%, turnover=9422979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T06:44:59+00:00, last15m_closed_end=2026-11-11T06:45+00:00, prior8high=0.164540, depth_time=2026-11-11T06:45:21+00:00, book20_bid_proxy_usdt=53782, book20_ask_proxy_usdt=115602, funding_indicative=-0.000024, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=31873132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T06:44:59+00:00, last15m_closed_end=2026-11-11T06:45+00:00, prior8high=45.400000, depth_time=2026-11-11T06:45:16+00:00, book20_bid_proxy_usdt=787872, book20_ask_proxy_usdt=349408, funding_indicative=-0.000191, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.05%, turnover=15376564. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T06:44:59+00:00, last15m_closed_end=2026-11-11T06:45+00:00, prior8high=0.849100, depth_time=2026-11-11T06:45:22+00:00, book20_bid_proxy_usdt=407597, book20_ask_proxy_usdt=612003, funding_indicative=0.000034, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=8260583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T06:44:59+00:00, last15m_closed_end=2026-11-11T06:45+00:00, prior8high=0.065930, depth_time=2026-11-11T06:45:27+00:00, book20_bid_proxy_usdt=622993, book20_ask_proxy_usdt=509029, funding_indicative=-0.000009, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.76%, turnover=5899489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T06:44:59+00:00, last15m_closed_end=2026-11-11T06:45+00:00, prior8high=0.299550, depth_time=2026-11-11T06:45:07+00:00, book20_bid_proxy_usdt=11428, book20_ask_proxy_usdt=11502, funding_indicative=-0.015453, next_funding_utc=2026-11-11T07:00:00+00:00, funding_cycle_h=1, 24h_change=-13.62%, turnover=66687556. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T06:44:59+00:00, last15m_closed_end=2026-11-11T06:45+00:00, prior8high=181.050000, depth_time=2026-11-11T06:45:23+00:00, book20_bid_proxy_usdt=59340, book20_ask_proxy_usdt=91543, funding_indicative=-0.000110, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=46006904. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T06:44:59+00:00, last15m_closed_end=2026-11-11T06:45+00:00, prior8high=6.717000, depth_time=2026-11-11T06:45:13+00:00, book20_bid_proxy_usdt=2478628, book20_ask_proxy_usdt=1488822, funding_indicative=0.000000, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.56%, turnover=38613107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T06:44:59+00:00, last15m_closed_end=2026-11-11T06:45+00:00, prior8high=19.311000, depth_time=2026-11-11T06:45:19+00:00, book20_bid_proxy_usdt=54536, book20_ask_proxy_usdt=30082, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.65%, turnover=5411376. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T06:44:59+00:00, last15m_closed_end=2026-11-11T06:45+00:00, prior8high=1027.770000, depth_time=2026-11-11T06:45:10+00:00, book20_bid_proxy_usdt=112252, book20_ask_proxy_usdt=95870, funding_indicative=0.000076, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.04%, turnover=2204318064. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
