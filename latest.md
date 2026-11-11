# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T11:15:34Z**
- feed_generated_utc: 2026-11-11T11:15:36+00:00
- source_sha256: `9ce62b141123ca96177f05fdc67d005526f2d1aa8f60d410460eb77bc4199c53`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T11:15+00:00, close=74011.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T11:00+00:00, close=74018, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.183320|-26.94|36.31|-28.07|68224582|7.09|
|AKE_USDT|0.002517|-13.62|-39.43|-14.75|8941328|3.97|
|ONE_USDT|0.001550|-13.58|38.85|-14.71|9026365|1.29|
|ZEC_USDT|989.400000|-9.50|-17.81|-10.63|2145468331|0.10|
|BTW_USDT|1.090000|-9.06|2.93|-10.19|6021683|1.83|
|PEPE_USDT|0.000005|-5.88|1.01|-7.01|79506174|0.61|
|UNI_USDT|6.462000|-5.38|-12.11|-6.51|41231666|1.55|
|DASH_USDT|43.780000|-3.01|-5.11|-4.14|16918623|2.28|
|ARB_USDT|0.158330|-1.88|-0.96|-3.01|27995824|0.63|
|QNT_USDT|178.240000|-1.36|-8.79|-2.49|44026412|0.56|
|VVV_USDT|19.176000|-0.32|-14.24|-1.45|5450246|0.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002517|0.002493|0.002517|1.49|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158330|0.158090|0.158330|1.85|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.090000|1.072100|1.090000|1.25|N|Y/Y|Y/N|Y|N|
|DASH_USDT|43.780000|42.990000|43.780000|0.01|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.183320|0.174240|0.183320|0.76|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001550|0.001533|0.001551|0.75|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.35|Y|Y/Y|N/N|Y|N|
|QNT_USDT|178.240000|176.850000|178.240000|1.46|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.462000|6.336000|6.462000|0.52|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.176000|18.795000|19.176000|0.76|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|989.400000|960.750000|989.400000|0.70|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T11:14:59+00:00, last15m_closed_end=2026-11-11T11:15+00:00, prior8high=0.002623, depth_time=2026-11-11T11:15:10+00:00, book20_bid_proxy_usdt=44056, book20_ask_proxy_usdt=57632, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.62%, turnover=8941328. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T11:14:59+00:00, last15m_closed_end=2026-11-11T11:15+00:00, prior8high=0.160070, depth_time=2026-11-11T11:15:28+00:00, book20_bid_proxy_usdt=341248, book20_ask_proxy_usdt=45375, funding_indicative=-0.000062, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=27995824. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T11:14:59+00:00, last15m_closed_end=2026-11-11T11:15+00:00, prior8high=1.133700, depth_time=2026-11-11T11:15:19+00:00, book20_bid_proxy_usdt=13579, book20_ask_proxy_usdt=15025, funding_indicative=-0.000483, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.06%, turnover=6021683. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T11:15:00+00:00, last15m_closed_end=2026-11-11T11:15+00:00, prior8high=44.240000, depth_time=2026-11-11T11:15:26+00:00, book20_bid_proxy_usdt=795663, book20_ask_proxy_usdt=729195, funding_indicative=-0.000023, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.01%, turnover=16918623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T11:14:59+00:00, last15m_closed_end=2026-11-11T11:15+00:00, prior8high=0.218530, depth_time=2026-11-11T11:15:08+00:00, book20_bid_proxy_usdt=9458, book20_ask_proxy_usdt=31124, funding_indicative=-0.006268, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=1, 24h_change=-26.94%, turnover=68224582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T11:14:59+00:00, last15m_closed_end=2026-11-11T11:15+00:00, prior8high=0.001606, depth_time=2026-11-11T11:15:13+00:00, book20_bid_proxy_usdt=25808, book20_ask_proxy_usdt=16019, funding_indicative=-0.000406, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.58%, turnover=9026365. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T11:14:59+00:00, last15m_closed_end=2026-11-11T11:15+00:00, prior8high=0.000005, depth_time=2026-11-11T11:15:21+00:00, book20_bid_proxy_usdt=18476, book20_ask_proxy_usdt=35932, funding_indicative=-0.000179, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.88%, turnover=79506174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T11:14:59+00:00, last15m_closed_end=2026-11-11T11:15+00:00, prior8high=179.750000, depth_time=2026-11-11T11:15:31+00:00, book20_bid_proxy_usdt=90517, book20_ask_proxy_usdt=48812, funding_indicative=-0.000175, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.36%, turnover=44026412. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T11:14:59+00:00, last15m_closed_end=2026-11-11T11:15+00:00, prior8high=6.519000, depth_time=2026-11-11T11:15:21+00:00, book20_bid_proxy_usdt=3011326, book20_ask_proxy_usdt=3112814, funding_indicative=-0.000002, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.38%, turnover=41231666. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T11:15:00+00:00, last15m_closed_end=2026-11-11T11:15+00:00, prior8high=19.170000, depth_time=2026-11-11T11:15:32+00:00, book20_bid_proxy_usdt=41289, book20_ask_proxy_usdt=41120, funding_indicative=-0.000009, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.32%, turnover=5450246. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T11:14:59+00:00, last15m_closed_end=2026-11-11T11:15+00:00, prior8high=999.700000, depth_time=2026-11-11T11:15:17+00:00, book20_bid_proxy_usdt=639899, book20_ask_proxy_usdt=55301, funding_indicative=0.000036, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.50%, turnover=2145468331. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
