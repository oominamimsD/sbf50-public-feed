# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T11:45:30Z**
- feed_generated_utc: 2026-11-11T11:45:31+00:00
- source_sha256: `24d08acea32e41809a13910e6166e41c0c126272ec7ae032315a89bad0558104`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T11:45+00:00, close=73994.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T11:00+00:00, close=74018, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.180420|-28.10|34.16|-29.21|68511710|1.11|
|AKE_USDT|0.002494|-14.41|-39.99|-15.52|9010903|4.02|
|ONE_USDT|0.001547|-13.80|38.50|-14.91|9093757|0.65|
|BTW_USDT|1.079700|-9.91|1.96|-11.02|6084868|2.78|
|ZEC_USDT|990.600000|-9.39|-17.71|-10.50|2169810747|0.10|
|UNI_USDT|6.456000|-5.47|-12.19|-6.58|41569510|1.55|
|PEPE_USDT|0.000005|-5.11|1.84|-6.22|81190990|0.20|
|DASH_USDT|44.070000|-2.37|-4.48|-3.48|17010845|2.27|
|QNT_USDT|178.430000|-1.25|-8.69|-2.36|44492249|0.56|
|VVV_USDT|19.177000|-0.32|-14.23|-1.43|5542490|0.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002494|0.002465|0.002494|0.43|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.079700|1.072100|1.079700|0.84|N|Y/Y|Y/N|Y|N|
|DASH_USDT|44.070000|42.990000|44.070000|0.04|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.180420|0.177500|0.180420|0.35|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001547|0.001528|0.001547|0.50|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.47|N|Y/Y|N/N|Y|N|
|QNT_USDT|178.430000|176.950000|178.430000|0.46|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.456000|6.336000|6.456000|0.49|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.177000|18.795000|19.177000|1.43|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|990.600000|962.630000|990.600000|0.72|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T11:44:59+00:00, last15m_closed_end=2026-11-11T11:45+00:00, prior8high=0.002623, depth_time=2026-11-11T11:45:09+00:00, book20_bid_proxy_usdt=114286, book20_ask_proxy_usdt=83500, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.41%, turnover=9010903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T11:44:59+00:00, last15m_closed_end=2026-11-11T11:45+00:00, prior8high=1.099600, depth_time=2026-11-11T11:45:14+00:00, book20_bid_proxy_usdt=25012, book20_ask_proxy_usdt=17067, funding_indicative=-0.000401, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.91%, turnover=6084868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T11:45:00+00:00, last15m_closed_end=2026-11-11T11:45+00:00, prior8high=44.240000, depth_time=2026-11-11T11:45:22+00:00, book20_bid_proxy_usdt=725561, book20_ask_proxy_usdt=667256, funding_indicative=-0.000029, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.37%, turnover=17010845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T11:44:59+00:00, last15m_closed_end=2026-11-11T11:45+00:00, prior8high=0.192310, depth_time=2026-11-11T11:45:07+00:00, book20_bid_proxy_usdt=13711, book20_ask_proxy_usdt=17799, funding_indicative=-0.005306, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=1, 24h_change=-28.10%, turnover=68511710. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T11:44:59+00:00, last15m_closed_end=2026-11-11T11:45+00:00, prior8high=0.001563, depth_time=2026-11-11T11:45:11+00:00, book20_bid_proxy_usdt=19760, book20_ask_proxy_usdt=25153, funding_indicative=-0.000460, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.80%, turnover=9093757. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T11:44:59+00:00, last15m_closed_end=2026-11-11T11:45+00:00, prior8high=0.000005, depth_time=2026-11-11T11:45:20+00:00, book20_bid_proxy_usdt=19228, book20_ask_proxy_usdt=34986, funding_indicative=-0.000191, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.11%, turnover=81190990. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T11:44:59+00:00, last15m_closed_end=2026-11-11T11:45+00:00, prior8high=179.750000, depth_time=2026-11-11T11:45:26+00:00, book20_bid_proxy_usdt=81396, book20_ask_proxy_usdt=78027, funding_indicative=-0.000152, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=44492249. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T11:44:59+00:00, last15m_closed_end=2026-11-11T11:45+00:00, prior8high=6.519000, depth_time=2026-11-11T11:45:19+00:00, book20_bid_proxy_usdt=2514177, book20_ask_proxy_usdt=3489588, funding_indicative=-0.000008, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.47%, turnover=41569510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T11:45:00+00:00, last15m_closed_end=2026-11-11T11:45+00:00, prior8high=19.342000, depth_time=2026-11-11T11:45:28+00:00, book20_bid_proxy_usdt=25492, book20_ask_proxy_usdt=40191, funding_indicative=-0.000026, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.32%, turnover=5542490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T11:44:59+00:00, last15m_closed_end=2026-11-11T11:45+00:00, prior8high=999.700000, depth_time=2026-11-11T11:45:16+00:00, book20_bid_proxy_usdt=233117, book20_ask_proxy_usdt=304797, funding_indicative=0.000039, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.39%, turnover=2169810747. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
