# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T08:30:34Z**
- feed_generated_utc: 2026-11-11T08:30:36+00:00
- source_sha256: `14ddb75b4152f74f4d8bcdb5532f2c35d67a7ee0984e85864b1523f85ead94bb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T08:30+00:00, close=73759.7, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.201900|-19.54|50.13|-20.33|67530683|5.48|
|ONE_USDT|0.001568|-12.60|40.42|-13.39|12270516|0.64|
|AKE_USDT|0.002550|-12.49|-38.64|-13.28|9180315|7.86|
|ZEC_USDT|977.650000|-10.58|-18.78|-11.37|2183436935|0.10|
|UNI_USDT|6.399000|-6.31|-12.97|-7.10|40168218|1.56|
|DASH_USDT|43.440000|-3.76|-5.85|-4.55|16913675|2.30|
|VVV_USDT|18.914000|-1.68|-15.41|-2.47|5454460|2.64|
|PEPE_USDT|0.000005|-1.64|5.56|-2.43|76892831|0.19|
|ARB_USDT|0.158850|-1.56|-0.64|-2.35|29907017|0.63|
|QNT_USDT|177.950000|-1.52|-8.93|-2.31|46233607|0.56|
|HBAR_USDT|0.065320|-0.69|-6.72|-1.48|6504657|1.53|
|DOT_USDT|0.838400|-0.39|-11.05|-1.18|8651888|1.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002550|0.002543|0.002551|1.56|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158850|0.157280|0.158780|4.42|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.440000|43.260000|43.440000|3.74|N|Y/N|Y/Y|Y|N|
|DOT_USDT|0.838400|0.824500|0.838400|0.33|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065320|0.064970|0.065320|2.40|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.201900|0.183320|0.201900|0.55|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001568|0.001593|0.001566|1.05|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|2.07|Y|Y/Y|N/N|Y|N|
|QNT_USDT|177.950000|177.180000|177.880000|0.56|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.399000|6.373000|6.399000|1.24|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|18.914000|18.851000|18.914000|0.89|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|977.650000|965.410000|977.730000|1.04|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T08:30:01+00:00, last15m_closed_end=2026-11-11T08:30+00:00, prior8high=0.002776, depth_time=2026-11-11T08:30:12+00:00, book20_bid_proxy_usdt=62614, book20_ask_proxy_usdt=51560, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.49%, turnover=9180315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T08:30:02+00:00, last15m_closed_end=2026-11-11T08:30+00:00, prior8high=0.160400, depth_time=2026-11-11T08:30:26+00:00, book20_bid_proxy_usdt=37036, book20_ask_proxy_usdt=127694, funding_indicative=0.000000, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=29907017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T08:30:02+00:00, last15m_closed_end=2026-11-11T08:30+00:00, prior8high=44.460000, depth_time=2026-11-11T08:30:18+00:00, book20_bid_proxy_usdt=551703, book20_ask_proxy_usdt=559020, funding_indicative=-0.000101, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.76%, turnover=16913675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-11T08:30:02+00:00, last15m_closed_end=2026-11-11T08:30+00:00, prior8high=0.840900, depth_time=2026-11-11T08:30:32+00:00, book20_bid_proxy_usdt=653174, book20_ask_proxy_usdt=553763, funding_indicative=0.000076, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.39%, turnover=8651888. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T08:30:02+00:00, last15m_closed_end=2026-11-11T08:30+00:00, prior8high=0.065780, depth_time=2026-11-11T08:30:26+00:00, book20_bid_proxy_usdt=744329, book20_ask_proxy_usdt=729200, funding_indicative=-0.000020, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.69%, turnover=6504657. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T08:30:01+00:00, last15m_closed_end=2026-11-11T08:30+00:00, prior8high=0.242680, depth_time=2026-11-11T08:30:07+00:00, book20_bid_proxy_usdt=17642, book20_ask_proxy_usdt=7033, funding_indicative=-0.006590, next_funding_utc=2026-11-11T09:00:00+00:00, funding_cycle_h=1, 24h_change=-19.54%, turnover=67530683. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T08:30:01+00:00, last15m_closed_end=2026-11-11T08:30+00:00, prior8high=0.001733, depth_time=2026-11-11T08:30:10+00:00, book20_bid_proxy_usdt=27810, book20_ask_proxy_usdt=39896, funding_indicative=-0.002295, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.60%, turnover=12270516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T08:30:01+00:00, last15m_closed_end=2026-11-11T08:30+00:00, prior8high=0.000005, depth_time=2026-11-11T08:30:24+00:00, book20_bid_proxy_usdt=31015, book20_ask_proxy_usdt=27461, funding_indicative=-0.000074, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=76892831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T08:30:02+00:00, last15m_closed_end=2026-11-11T08:30+00:00, prior8high=179.930000, depth_time=2026-11-11T08:30:27+00:00, book20_bid_proxy_usdt=108570, book20_ask_proxy_usdt=103887, funding_indicative=-0.000103, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=46233607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T08:30:02+00:00, last15m_closed_end=2026-11-11T08:30+00:00, prior8high=6.628000, depth_time=2026-11-11T08:30:17+00:00, book20_bid_proxy_usdt=2066005, book20_ask_proxy_usdt=2707766, funding_indicative=-0.000004, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.31%, turnover=40168218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T08:30:02+00:00, last15m_closed_end=2026-11-11T08:30+00:00, prior8high=19.191000, depth_time=2026-11-11T08:30:21+00:00, book20_bid_proxy_usdt=27014, book20_ask_proxy_usdt=38446, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=5454460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T08:30:01+00:00, last15m_closed_end=2026-11-11T08:30+00:00, prior8high=1011.900000, depth_time=2026-11-11T08:30:14+00:00, book20_bid_proxy_usdt=119830, book20_ask_proxy_usdt=126871, funding_indicative=0.000028, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.58%, turnover=2183436935. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
