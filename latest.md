# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T09:15:34Z**
- feed_generated_utc: 2026-11-11T09:15:35+00:00
- source_sha256: `2c9650fb4596fdf894c74c8379f963b619c991f3210565d98320b2688aef68f0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T09:15+00:00, close=73629, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-11T09:00+00:00, close=73699.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.201630|-19.65|49.93|-20.26|67564954|4.47|
|AKE_USDT|0.002538|-12.90|-38.93|-13.51|9008958|7.88|
|ONE_USDT|0.001577|-12.10|41.23|-12.71|11351004|0.63|
|ZEC_USDT|968.000000|-11.46|-19.58|-12.07|2173254724|0.10|
|UNI_USDT|6.372000|-6.70|-13.34|-7.31|40436324|3.14|
|PEPE_USDT|0.000005|-4.75|2.23|-5.36|78771047|0.20|
|DASH_USDT|43.140000|-4.43|-6.50|-5.04|17016544|2.32|
|VVV_USDT|18.869000|-1.92|-15.61|-2.53|5425157|6.36|
|QNT_USDT|177.600000|-1.71|-9.11|-2.32|45566059|0.56|
|ARB_USDT|0.158900|-1.53|-0.61|-2.14|29017540|0.63|
|HBAR_USDT|0.065390|-0.59|-6.62|-1.20|6383309|1.53|
|DOT_USDT|0.837800|-0.46|-11.11|-1.07|8585288|1.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002538|0.002501|0.002538|0.34|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158900|0.157280|0.158900|1.09|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.140000|43.110000|43.140000|1.33|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.837800|0.824500|0.837800|0.17|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065390|0.064970|0.065390|0.32|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.201630|0.183320|0.201690|1.24|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001577|0.001564|0.001577|0.81|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|5.23|Y|Y/Y|N/N|Y|N|
|QNT_USDT|177.600000|177.180000|177.600000|1.03|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.372000|6.364000|6.372000|0.71|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|18.869000|18.772000|18.869000|0.76|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|968.000000|965.410000|967.830000|1.16|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T09:15:00+00:00, last15m_closed_end=2026-11-11T09:15+00:00, prior8high=0.002673, depth_time=2026-11-11T09:15:09+00:00, book20_bid_proxy_usdt=69363, book20_ask_proxy_usdt=41877, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.90%, turnover=9008958. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T09:15:00+00:00, last15m_closed_end=2026-11-11T09:15+00:00, prior8high=0.160150, depth_time=2026-11-11T09:15:27+00:00, book20_bid_proxy_usdt=88716, book20_ask_proxy_usdt=73493, funding_indicative=-0.000021, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=29017540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T09:15:00+00:00, last15m_closed_end=2026-11-11T09:15+00:00, prior8high=44.240000, depth_time=2026-11-11T09:15:15+00:00, book20_bid_proxy_usdt=1042147, book20_ask_proxy_usdt=645576, funding_indicative=-0.000117, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.43%, turnover=17016544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T09:15:00+00:00, last15m_closed_end=2026-11-11T09:15+00:00, prior8high=0.841800, depth_time=2026-11-11T09:15:29+00:00, book20_bid_proxy_usdt=502634, book20_ask_proxy_usdt=419873, funding_indicative=0.000082, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.46%, turnover=8585288. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T09:15:00+00:00, last15m_closed_end=2026-11-11T09:15+00:00, prior8high=0.065780, depth_time=2026-11-11T09:15:27+00:00, book20_bid_proxy_usdt=760269, book20_ask_proxy_usdt=606329, funding_indicative=0.000000, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.59%, turnover=6383309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T09:14:59+00:00, last15m_closed_end=2026-11-11T09:15+00:00, prior8high=0.225680, depth_time=2026-11-11T09:15:07+00:00, book20_bid_proxy_usdt=7668, book20_ask_proxy_usdt=10896, funding_indicative=-0.011419, next_funding_utc=2026-11-11T10:00:00+00:00, funding_cycle_h=1, 24h_change=-19.65%, turnover=67564954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T09:14:59+00:00, last15m_closed_end=2026-11-11T09:15+00:00, prior8high=0.001680, depth_time=2026-11-11T09:15:11+00:00, book20_bid_proxy_usdt=16560, book20_ask_proxy_usdt=16555, funding_indicative=-0.001451, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.10%, turnover=11351004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T09:15:00+00:00, last15m_closed_end=2026-11-11T09:15+00:00, prior8high=0.000005, depth_time=2026-11-11T09:15:18+00:00, book20_bid_proxy_usdt=32030, book20_ask_proxy_usdt=41478, funding_indicative=-0.000101, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.75%, turnover=78771047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T09:15:00+00:00, last15m_closed_end=2026-11-11T09:15+00:00, prior8high=179.710000, depth_time=2026-11-11T09:15:25+00:00, book20_bid_proxy_usdt=101673, book20_ask_proxy_usdt=98714, funding_indicative=-0.000136, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=45566059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T09:15:00+00:00, last15m_closed_end=2026-11-11T09:15+00:00, prior8high=6.495000, depth_time=2026-11-11T09:15:14+00:00, book20_bid_proxy_usdt=3262093, book20_ask_proxy_usdt=3615329, funding_indicative=-0.000004, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.70%, turnover=40436324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T09:15:00+00:00, last15m_closed_end=2026-11-11T09:15+00:00, prior8high=19.191000, depth_time=2026-11-11T09:15:22+00:00, book20_bid_proxy_usdt=28247, book20_ask_proxy_usdt=66180, funding_indicative=0.000042, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=5425157. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T09:14:59+00:00, last15m_closed_end=2026-11-11T09:15+00:00, prior8high=1003.100000, depth_time=2026-11-11T09:15:14+00:00, book20_bid_proxy_usdt=183112, book20_ask_proxy_usdt=164062, funding_indicative=0.000017, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.46%, turnover=2173254724. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
