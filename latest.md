# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T03:00:29Z**
- feed_generated_utc: 2026-11-11T03:00:30+00:00
- source_sha256: `05b6ef4d7ec76ca075e61ddf73b1840bcb400cf05aa7b176fc92965fe63a1fe6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T03:00+00:00, close=73615.2, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T03:00+00:00, close=73615.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DASH_USDT|43.410000|-6.74|-5.91|-7.33|13685823|2.30|
|ZEC_USDT|1021.430000|-6.57|-15.15|-7.16|2149181911|0.10|
|UNI_USDT|6.675000|-5.52|-9.22|-6.11|34530179|3.00|
|VVV_USDT|19.161000|-3.31|-14.31|-3.90|5310787|2.09|
|WLD_USDT|0.309600|-2.61|-16.79|-3.20|29322407|3.23|
|HYPE_USDT|71.823000|-2.43|-17.77|-3.02|40547412|0.14|
|JCT_USDT|0.005899|-2.15|41.19|-2.74|17202429|1.69|
|DOT_USDT|0.844100|-2.13|-10.44|-2.72|8237510|1.19|
|SOL_USDT|83.220000|-1.29|-11.20|-1.88|639457148|1.20|
|XRP_USDT|1.056300|-0.83|-17.52|-1.42|309849113|0.95|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|43.410000|42.750000|43.410000|1.07|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.844100|0.835600|0.844100|0.40|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|71.823000|71.323000|71.823000|1.12|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005899|0.005017|0.005898|1.98|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|83.220000|82.830000|83.220000|1.09|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.675000|6.626000|6.675000|1.15|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.161000|19.007000|19.161000|1.16|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.309600|0.306800|0.309600|0.48|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.056300|1.046700|1.056300|1.88|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1021.430000|1007.730000|1020.790000|1.42|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-11T03:00:01+00:00, last15m_closed_end=2026-11-11T03:00+00:00, prior8high=44.600000, depth_time=2026-11-11T03:00:06+00:00, book20_bid_proxy_usdt=753936, book20_ask_proxy_usdt=667333, funding_indicative=-0.000140, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.74%, turnover=13685823. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T03:00:01+00:00, last15m_closed_end=2026-11-11T03:00+00:00, prior8high=0.851900, depth_time=2026-11-11T03:00:21+00:00, book20_bid_proxy_usdt=698950, book20_ask_proxy_usdt=363282, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=8237510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-11T03:00:01+00:00, last15m_closed_end=2026-11-11T03:00+00:00, prior8high=72.632000, depth_time=2026-11-11T03:00:18+00:00, book20_bid_proxy_usdt=161253, book20_ask_proxy_usdt=120640, funding_indicative=0.000050, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.43%, turnover=40547412. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-11T03:00:01+00:00, last15m_closed_end=2026-11-11T03:00+00:00, prior8high=0.005725, depth_time=2026-11-11T03:00:21+00:00, book20_bid_proxy_usdt=28897, book20_ask_proxy_usdt=54736, funding_indicative=0.000133, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.15%, turnover=17202429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-11T03:00:01+00:00, last15m_closed_end=2026-11-11T03:00+00:00, prior8high=84.030000, depth_time=2026-11-11T03:00:25+00:00, book20_bid_proxy_usdt=17425754, book20_ask_proxy_usdt=17050392, funding_indicative=0.000065, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=639457148. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T03:00:01+00:00, last15m_closed_end=2026-11-11T03:00+00:00, prior8high=6.820000, depth_time=2026-11-11T03:00:08+00:00, book20_bid_proxy_usdt=2809825, book20_ask_proxy_usdt=2956728, funding_indicative=0.000013, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.52%, turnover=34530179. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T03:00:01+00:00, last15m_closed_end=2026-11-11T03:00+00:00, prior8high=19.688000, depth_time=2026-11-11T03:00:13+00:00, book20_bid_proxy_usdt=25533, book20_ask_proxy_usdt=26343, funding_indicative=0.000050, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.31%, turnover=5310787. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-11T03:00:01+00:00, last15m_closed_end=2026-11-11T03:00+00:00, prior8high=0.314200, depth_time=2026-11-11T03:00:15+00:00, book20_bid_proxy_usdt=6267271, book20_ask_proxy_usdt=6193909, funding_indicative=0.000003, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=29322407. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-11T03:00:01+00:00, last15m_closed_end=2026-11-11T03:00+00:00, prior8high=1.063100, depth_time=2026-11-11T03:00:26+00:00, book20_bid_proxy_usdt=3603497, book20_ask_proxy_usdt=3800318, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.83%, turnover=309849113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T03:00:01+00:00, last15m_closed_end=2026-11-11T03:00+00:00, prior8high=1042.760000, depth_time=2026-11-11T03:00:09+00:00, book20_bid_proxy_usdt=288182, book20_ask_proxy_usdt=227406, funding_indicative=0.000100, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.57%, turnover=2149181911. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
