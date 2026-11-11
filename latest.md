# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T12:15:29Z**
- feed_generated_utc: 2026-11-11T12:15:30+00:00
- source_sha256: `1a031df791778bcd01663aacd991646e7ba3411a45f8cc49d2ad026c982e9cc0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T12:15+00:00, close=73926.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T12:00+00:00, close=73963.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T12:00+00:00, close=73963.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.179620|-28.42|33.56|-29.43|67339310|4.45|
|ONE_USDT|0.001545|-13.89|38.35|-14.90|8150837|0.65|
|AKE_USDT|0.002521|-13.48|-39.34|-14.49|8712329|3.97|
|BTW_USDT|1.076100|-10.22|1.62|-11.23|6025299|1.86|
|ZEC_USDT|987.540000|-9.67|-17.96|-10.68|2146015046|1.62|
|UNI_USDT|6.451000|-5.54|-12.26|-6.55|40884113|1.55|
|PEPE_USDT|0.000005|-4.97|1.99|-5.98|81383457|0.20|
|DASH_USDT|44.280000|-1.90|-4.03|-2.91|17054278|2.26|
|QNT_USDT|177.660000|-1.68|-9.08|-2.69|43663187|1.69|
|ARB_USDT|0.160470|-0.56|0.36|-1.57|27158748|1.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002521|0.002465|0.002521|1.19|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.160470|0.158170|0.160470|0.92|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.076100|1.070200|1.076100|0.88|N|Y/Y|Y/N|Y|N|
|DASH_USDT|44.280000|43.450000|44.280000|1.53|N|N/Y|Y/Y|Y|N|
|INIT_USDT|0.179620|0.177500|0.179590|0.51|N|Y/Y|Y/N|Y|N|
|ONE_USDT|0.001545|0.001528|0.001545|0.85|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.54|N|Y/Y|Y/N|Y|N|
|QNT_USDT|177.660000|176.950000|177.660000|0.93|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.451000|6.383000|6.451000|0.63|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|987.540000|978.240000|987.540000|1.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T12:15:00+00:00, last15m_closed_end=2026-11-11T12:15+00:00, prior8high=0.002623, depth_time=2026-11-11T12:15:11+00:00, book20_bid_proxy_usdt=55254, book20_ask_proxy_usdt=42249, funding_indicative=0.000050, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.48%, turnover=8712329. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T12:15:00+00:00, last15m_closed_end=2026-11-11T12:15+00:00, prior8high=0.161860, depth_time=2026-11-11T12:15:26+00:00, book20_bid_proxy_usdt=56970, book20_ask_proxy_usdt=64477, funding_indicative=-0.000122, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.56%, turnover=27158748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T12:15:00+00:00, last15m_closed_end=2026-11-11T12:15+00:00, prior8high=1.096600, depth_time=2026-11-11T12:15:13+00:00, book20_bid_proxy_usdt=22254, book20_ask_proxy_usdt=17669, funding_indicative=-0.000366, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.22%, turnover=6025299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T12:15:00+00:00, last15m_closed_end=2026-11-11T12:15+00:00, prior8high=44.430000, depth_time=2026-11-11T12:15:18+00:00, book20_bid_proxy_usdt=487228, book20_ask_proxy_usdt=532533, funding_indicative=-0.000001, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.90%, turnover=17054278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T12:14:59+00:00, last15m_closed_end=2026-11-11T12:15+00:00, prior8high=0.192240, depth_time=2026-11-11T12:15:07+00:00, book20_bid_proxy_usdt=17746, book20_ask_proxy_usdt=13865, funding_indicative=-0.003983, next_funding_utc=2026-11-11T13:00:00+00:00, funding_cycle_h=1, 24h_change=-28.42%, turnover=67339310. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T12:14:59+00:00, last15m_closed_end=2026-11-11T12:15+00:00, prior8high=0.001563, depth_time=2026-11-11T12:15:09+00:00, book20_bid_proxy_usdt=26631, book20_ask_proxy_usdt=23270, funding_indicative=-0.000483, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.89%, turnover=8150837. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T12:15:00+00:00, last15m_closed_end=2026-11-11T12:15+00:00, prior8high=0.000005, depth_time=2026-11-11T12:15:21+00:00, book20_bid_proxy_usdt=26458, book20_ask_proxy_usdt=36689, funding_indicative=-0.000201, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.97%, turnover=81383457. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T12:15:00+00:00, last15m_closed_end=2026-11-11T12:15+00:00, prior8high=179.750000, depth_time=2026-11-11T12:15:25+00:00, book20_bid_proxy_usdt=78050, book20_ask_proxy_usdt=58173, funding_indicative=-0.000140, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.68%, turnover=43663187. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T12:15:00+00:00, last15m_closed_end=2026-11-11T12:15+00:00, prior8high=6.519000, depth_time=2026-11-11T12:15:18+00:00, book20_bid_proxy_usdt=3529067, book20_ask_proxy_usdt=2695057, funding_indicative=-0.000020, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.54%, turnover=40884113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T12:14:59+00:00, last15m_closed_end=2026-11-11T12:15+00:00, prior8high=999.700000, depth_time=2026-11-11T12:15:16+00:00, book20_bid_proxy_usdt=180780, book20_ask_proxy_usdt=585404, funding_indicative=0.000033, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.67%, turnover=2146015046. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
