# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T09:30:32Z**
- feed_generated_utc: 2026-11-11T09:30:34+00:00
- source_sha256: `c4bcf0dd674ae148e32e127635bbe21fd64b99a57b74ac41bc80f08b3db8b862`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T09:30+00:00, close=73730.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T09:00+00:00, close=73699.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.185030|-26.26|37.58|-27.01|68028772|4.86|
|AKE_USDT|0.002522|-13.45|-39.31|-14.20|9040361|3.96|
|ONE_USDT|0.001554|-13.40|39.13|-14.15|11461399|0.64|
|ZEC_USDT|973.150000|-10.99|-19.16|-11.74|2177745951|0.10|
|BTW_USDT|1.097600|-8.42|3.65|-9.17|5966996|7.30|
|UNI_USDT|6.384000|-6.53|-13.17|-7.28|40786047|1.57|
|DASH_USDT|43.270000|-4.14|-6.22|-4.89|17135932|2.31|
|PEPE_USDT|0.000005|-3.94|3.09|-4.69|79905342|0.20|
|QNT_USDT|177.930000|-1.53|-8.94|-2.28|45817500|1.12|
|ARB_USDT|0.158900|-1.53|-0.61|-2.28|29271693|0.63|
|VVV_USDT|18.954000|-1.48|-15.23|-2.23|5463243|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002522|0.002501|0.002525|0.91|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158900|0.157380|0.158900|1.71|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.097600|1.100000|1.094600|1.64|Y|Y/Y|Y/N|Y|N|
|DASH_USDT|43.270000|43.100000|43.260000|0.94|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.185030|0.183320|0.185030|0.98|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001554|0.001564|0.001553|1.62|Y|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|2.06|N|Y/Y|N/N|Y|N|
|QNT_USDT|177.930000|176.850000|177.930000|1.06|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.384000|6.364000|6.384000|1.08|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|18.954000|18.772000|18.954000|0.96|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|973.150000|960.750000|973.150000|0.21|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T09:29:59+00:00, last15m_closed_end=2026-11-11T09:30+00:00, prior8high=0.002671, depth_time=2026-11-11T09:30:09+00:00, book20_bid_proxy_usdt=49494, book20_ask_proxy_usdt=54962, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.45%, turnover=9040361. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T09:29:59+00:00, last15m_closed_end=2026-11-11T09:30+00:00, prior8high=0.160150, depth_time=2026-11-11T09:30:28+00:00, book20_bid_proxy_usdt=61788, book20_ask_proxy_usdt=73148, funding_indicative=-0.000030, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=29271693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T09:29:59+00:00, last15m_closed_end=2026-11-11T09:30+00:00, prior8high=1.154700, depth_time=2026-11-11T09:30:16+00:00, book20_bid_proxy_usdt=10416, book20_ask_proxy_usdt=20432, funding_indicative=-0.000448, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.42%, turnover=5966996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T09:29:59+00:00, last15m_closed_end=2026-11-11T09:30+00:00, prior8high=44.240000, depth_time=2026-11-11T09:30:18+00:00, book20_bid_proxy_usdt=751370, book20_ask_proxy_usdt=660334, funding_indicative=-0.000119, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.14%, turnover=17135932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T09:29:58+00:00, last15m_closed_end=2026-11-11T09:30+00:00, prior8high=0.225680, depth_time=2026-11-11T09:30:07+00:00, book20_bid_proxy_usdt=3871, book20_ask_proxy_usdt=7521, funding_indicative=-0.011156, next_funding_utc=2026-11-11T10:00:00+00:00, funding_cycle_h=1, 24h_change=-26.26%, turnover=68028772. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T09:29:58+00:00, last15m_closed_end=2026-11-11T09:30+00:00, prior8high=0.001673, depth_time=2026-11-11T09:30:11+00:00, book20_bid_proxy_usdt=32870, book20_ask_proxy_usdt=19363, funding_indicative=-0.001205, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.40%, turnover=11461399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T09:29:59+00:00, last15m_closed_end=2026-11-11T09:30+00:00, prior8high=0.000005, depth_time=2026-11-11T09:30:23+00:00, book20_bid_proxy_usdt=41841, book20_ask_proxy_usdt=20249, funding_indicative=-0.000116, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.94%, turnover=79905342. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T09:29:59+00:00, last15m_closed_end=2026-11-11T09:30+00:00, prior8high=179.710000, depth_time=2026-11-11T09:30:22+00:00, book20_bid_proxy_usdt=119251, book20_ask_proxy_usdt=112485, funding_indicative=-0.000136, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=45817500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T09:29:59+00:00, last15m_closed_end=2026-11-11T09:30+00:00, prior8high=6.495000, depth_time=2026-11-11T09:30:18+00:00, book20_bid_proxy_usdt=2444910, book20_ask_proxy_usdt=3792017, funding_indicative=-0.000008, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.53%, turnover=40786047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T09:29:59+00:00, last15m_closed_end=2026-11-11T09:30+00:00, prior8high=19.191000, depth_time=2026-11-11T09:30:30+00:00, book20_bid_proxy_usdt=16176, book20_ask_proxy_usdt=41033, funding_indicative=0.000000, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.48%, turnover=5463243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T09:29:58+00:00, last15m_closed_end=2026-11-11T09:30+00:00, prior8high=1003.100000, depth_time=2026-11-11T09:30:14+00:00, book20_bid_proxy_usdt=151794, book20_ask_proxy_usdt=203375, funding_indicative=0.000018, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.99%, turnover=2177745951. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
