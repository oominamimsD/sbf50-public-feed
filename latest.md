# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T12:45:31Z**
- feed_generated_utc: 2026-11-09T12:45:33+00:00
- source_sha256: `01a012e887066103ceec55b98abf1c4f2dd0aa709e260f9253ead017c1155238`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T12:45+00:00, close=74765.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001509|-22.92|29.60|-21.25|6311385|0.66|
|AKE_USDT|0.004807|-10.26|-47.52|-8.59|9681790|2.08|
|JCT_USDT|0.008950|-8.98|79.75|-7.31|66000409|1.12|
|ASTER_USDT|0.641000|-5.70|-8.35|-4.03|5667233|1.56|
|ETH_USDT|2123.040000|-5.26|-6.30|-3.59|1582044269|0.05|
|HYPE_USDT|73.576000|-4.97|-16.09|-3.30|49712321|0.14|
|XRP_USDT|1.102500|-4.61|-11.79|-2.94|286240585|0.91|
|ZEC_USDT|1215.870000|-4.31|-1.78|-2.64|2331995086|0.66|
|HOT_USDT|0.000414|-3.67|15.07|-2.00|7728807|2.42|
|SOL_USDT|86.600000|-3.43|-8.61|-1.76|742338581|1.16|
|AIOT_USDT|0.146310|-3.20|66.75|-1.53|7361921|5.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIOT_USDT|0.146310|0.146770|0.146350|1.51|Y|Y/N|N/N|Y|N|
|AKE_USDT|0.004807|0.004635|0.004789|0.94|N|N/N|N/Y|Y|N|
|ASTER_USDT|0.641000|0.623900|0.641000|1.38|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2123.040000|2101.670000|2122.960000|0.98|N|Y/Y|Y/Y|Y|N|
|HOT_USDT|0.000414|0.000411|0.000414|0.31|N|Y/N|N/N|Y|N|
|HYPE_USDT|73.576000|72.747000|73.576000|1.87|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008950|0.008306|0.008919|0.81|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001509|0.001487|0.001509|1.53|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.600000|85.770000|86.600000|1.59|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.102500|1.076200|1.102500|2.23|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1215.870000|1192.400000|1216.070000|1.23|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AIOT_USDT: quote_utc=2026-11-09T12:45:01+00:00, last15m_closed_end=2026-11-09T12:45+00:00, prior8high=0.164360, depth_time=2026-11-09T12:45:31+00:00, book20_bid_proxy_usdt=6129, book20_ask_proxy_usdt=5166, funding_indicative=0.000381, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.20%, turnover=7361921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-09T12:45:01+00:00, last15m_closed_end=2026-11-09T12:45+00:00, prior8high=0.005718, depth_time=2026-11-09T12:45:09+00:00, book20_bid_proxy_usdt=25284, book20_ask_proxy_usdt=41681, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.26%, turnover=9681790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T12:45:02+00:00, last15m_closed_end=2026-11-09T12:45+00:00, prior8high=0.639500, depth_time=2026-11-09T12:45:12+00:00, book20_bid_proxy_usdt=681943, book20_ask_proxy_usdt=735214, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.70%, turnover=5667233. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T12:45:01+00:00, last15m_closed_end=2026-11-09T12:45+00:00, prior8high=2132.860000, depth_time=2026-11-09T12:45:16+00:00, book20_bid_proxy_usdt=2800050, book20_ask_proxy_usdt=3626816, funding_indicative=-0.000011, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.26%, turnover=1582044269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-09T12:45:01+00:00, last15m_closed_end=2026-11-09T12:45+00:00, prior8high=0.000428, depth_time=2026-11-09T12:45:25+00:00, book20_bid_proxy_usdt=100673, book20_ask_proxy_usdt=132691, funding_indicative=-0.001219, next_funding_utc=2026-11-09T13:00:00+00:00, funding_cycle_h=1, 24h_change=-3.67%, turnover=7728807. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T12:45:01+00:00, last15m_closed_end=2026-11-09T12:45+00:00, prior8high=74.029000, depth_time=2026-11-09T12:45:18+00:00, book20_bid_proxy_usdt=84134, book20_ask_proxy_usdt=62562, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.97%, turnover=49712321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T12:45:01+00:00, last15m_closed_end=2026-11-09T12:45+00:00, prior8high=0.009430, depth_time=2026-11-09T12:45:11+00:00, book20_bid_proxy_usdt=49130, book20_ask_proxy_usdt=60006, funding_indicative=0.001262, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.98%, turnover=66000409. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T12:45:01+00:00, last15m_closed_end=2026-11-09T12:45+00:00, prior8high=0.001563, depth_time=2026-11-09T12:45:06+00:00, book20_bid_proxy_usdt=29267, book20_ask_proxy_usdt=19607, funding_indicative=0.000034, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-22.92%, turnover=6311385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T12:45:01+00:00, last15m_closed_end=2026-11-09T12:45+00:00, prior8high=87.140000, depth_time=2026-11-09T12:45:28+00:00, book20_bid_proxy_usdt=17399902, book20_ask_proxy_usdt=18052701, funding_indicative=0.000022, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.43%, turnover=742338581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T12:45:01+00:00, last15m_closed_end=2026-11-09T12:45+00:00, prior8high=1.094900, depth_time=2026-11-09T12:45:20+00:00, book20_bid_proxy_usdt=2515829, book20_ask_proxy_usdt=4963512, funding_indicative=0.000094, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.61%, turnover=286240585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T12:45:01+00:00, last15m_closed_end=2026-11-09T12:45+00:00, prior8high=1225.880000, depth_time=2026-11-09T12:45:23+00:00, book20_bid_proxy_usdt=230949, book20_ask_proxy_usdt=576305, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.31%, turnover=2331995086. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
