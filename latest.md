# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T08:45:33Z**
- feed_generated_utc: 2026-11-11T08:45:35+00:00
- source_sha256: `9d4bf66a33be7565f6e56d6901bd027c5c6b4aa0d56d081f618214e801c6e97b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T08:45+00:00, close=73770.1, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.214050|-14.70|59.16|-15.50|67728861|4.21|
|AKE_USDT|0.002555|-12.31|-38.52|-13.11|9195665|3.92|
|ONE_USDT|0.001580|-11.92|41.51|-12.72|12317428|0.63|
|ZEC_USDT|980.780000|-10.29|-18.52|-11.09|2202460473|0.10|
|UNI_USDT|6.419000|-6.01|-12.70|-6.81|40470478|3.12|
|DASH_USDT|43.500000|-3.63|-5.72|-4.43|16952717|2.30|
|PEPE_USDT|0.000005|-1.85|5.33|-2.65|77516600|0.19|
|VVV_USDT|18.966000|-1.41|-15.18|-2.21|5510963|0.53|
|QNT_USDT|178.290000|-1.33|-8.76|-2.13|46351696|1.12|
|ARB_USDT|0.159230|-1.33|-0.40|-2.13|30054431|0.63|
|HBAR_USDT|0.065520|-0.39|-6.44|-1.19|6517458|1.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002555|0.002501|0.002556|0.34|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159230|0.157280|0.159230|0.98|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.500000|43.260000|43.500000|0.30|N|Y/N|Y/Y|Y|N|
|HBAR_USDT|0.065520|0.064970|0.065550|0.20|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.214050|0.183320|0.214170|0.38|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001580|0.001564|0.001580|0.66|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.40|N|Y/Y|N/N|Y|N|
|QNT_USDT|178.290000|177.180000|178.290000|0.50|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.419000|6.373000|6.419000|0.93|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|18.966000|18.851000|18.972000|1.44|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|980.780000|965.410000|981.300000|0.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T08:45:02+00:00, last15m_closed_end=2026-11-11T08:45+00:00, prior8high=0.002707, depth_time=2026-11-11T08:45:10+00:00, book20_bid_proxy_usdt=51844, book20_ask_proxy_usdt=50194, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.31%, turnover=9195665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T08:45:02+00:00, last15m_closed_end=2026-11-11T08:45+00:00, prior8high=0.160190, depth_time=2026-11-11T08:45:30+00:00, book20_bid_proxy_usdt=51642, book20_ask_proxy_usdt=72870, funding_indicative=-0.000002, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=30054431. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T08:45:02+00:00, last15m_closed_end=2026-11-11T08:45+00:00, prior8high=44.280000, depth_time=2026-11-11T08:45:19+00:00, book20_bid_proxy_usdt=597797, book20_ask_proxy_usdt=592794, funding_indicative=-0.000100, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.63%, turnover=16952717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T08:45:02+00:00, last15m_closed_end=2026-11-11T08:45+00:00, prior8high=0.065780, depth_time=2026-11-11T08:45:26+00:00, book20_bid_proxy_usdt=782053, book20_ask_proxy_usdt=723615, funding_indicative=-0.000012, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.39%, turnover=6517458. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T08:45:02+00:00, last15m_closed_end=2026-11-11T08:45+00:00, prior8high=0.227500, depth_time=2026-11-11T08:45:08+00:00, book20_bid_proxy_usdt=6676, book20_ask_proxy_usdt=68699, funding_indicative=-0.008444, next_funding_utc=2026-11-11T09:00:00+00:00, funding_cycle_h=1, 24h_change=-14.70%, turnover=67728861. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T08:45:02+00:00, last15m_closed_end=2026-11-11T08:45+00:00, prior8high=0.001730, depth_time=2026-11-11T08:45:12+00:00, book20_bid_proxy_usdt=22061, book20_ask_proxy_usdt=24808, funding_indicative=-0.001953, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.92%, turnover=12317428. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T08:45:02+00:00, last15m_closed_end=2026-11-11T08:45+00:00, prior8high=0.000005, depth_time=2026-11-11T08:45:22+00:00, book20_bid_proxy_usdt=85575, book20_ask_proxy_usdt=47750, funding_indicative=-0.000080, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=77516600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T08:45:02+00:00, last15m_closed_end=2026-11-11T08:45+00:00, prior8high=179.790000, depth_time=2026-11-11T08:45:25+00:00, book20_bid_proxy_usdt=81208, book20_ask_proxy_usdt=59299, funding_indicative=-0.000112, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=46351696. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T08:45:02+00:00, last15m_closed_end=2026-11-11T08:45+00:00, prior8high=6.540000, depth_time=2026-11-11T08:45:18+00:00, book20_bid_proxy_usdt=2734130, book20_ask_proxy_usdt=3246738, funding_indicative=-0.000003, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.01%, turnover=40470478. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T08:45:02+00:00, last15m_closed_end=2026-11-11T08:45+00:00, prior8high=19.191000, depth_time=2026-11-11T08:45:22+00:00, book20_bid_proxy_usdt=18130, book20_ask_proxy_usdt=25134, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.41%, turnover=5510963. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T08:45:02+00:00, last15m_closed_end=2026-11-11T08:45+00:00, prior8high=1004.990000, depth_time=2026-11-11T08:45:15+00:00, book20_bid_proxy_usdt=166257, book20_ask_proxy_usdt=118675, funding_indicative=0.000025, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.29%, turnover=2202460473. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
