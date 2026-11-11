# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T12:00:30Z**
- feed_generated_utc: 2026-11-11T12:00:32+00:00
- source_sha256: `f084e1049fad90a77b33333656948ad2cfb387ded18d36d1a75979f661291310`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T12:00+00:00, close=73963.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T12:00+00:00, close=73963.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T12:00+00:00, close=73963.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001538|-12.32|37.78|-13.39|8102990|0.65|
|PEPE_USDT|0.000005|-10.21|1.97|-11.28|80983403|0.20|
|ZEC_USDT|988.700000|-9.57|-17.86|-10.64|2129721188|0.10|
|UNI_USDT|6.466000|-8.47|-12.06|-9.54|40679593|1.55|
|AKE_USDT|0.002549|-6.01|-38.66|-7.08|8669559|3.93|
|DASH_USDT|44.190000|-5.06|-4.22|-6.13|16914562|2.26|
|BTW_USDT|1.083700|-4.69|2.34|-5.76|5996401|4.61|
|INJ_USDT|7.908000|-3.36|7.87|-4.43|19285613|1.26|
|QNT_USDT|178.160000|-2.69|-8.83|-3.76|43476564|0.56|
|JCT_USDT|0.005903|-2.08|41.28|-3.15|19019798|5.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002549|0.002465|0.002549|0.69|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.083700|1.070200|1.083700|0.60|N|Y/Y|Y/N|Y|N|
|DASH_USDT|44.190000|43.240000|44.190000|0.14|N|N/Y|Y/Y|Y|N|
|INJ_USDT|7.908000|7.887000|7.908000|3.31|N|Y/Y|Y/N|Y|N|
|JCT_USDT|0.005903|0.005456|0.005903|0.28|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001538|0.001528|0.001538|0.78|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.45|N|Y/Y|Y/N|Y|N|
|QNT_USDT|178.160000|176.950000|178.160000|0.35|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.466000|6.346000|6.466000|0.43|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|988.700000|975.280000|988.800000|0.62|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T12:00:00+00:00, last15m_closed_end=2026-11-11T12:00+00:00, prior8high=0.002623, depth_time=2026-11-11T12:00:16+00:00, book20_bid_proxy_usdt=66129, book20_ask_proxy_usdt=55130, funding_indicative=0.000050, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.01%, turnover=8669559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T12:00:00+00:00, last15m_closed_end=2026-11-11T12:00+00:00, prior8high=1.098100, depth_time=2026-11-11T12:00:21+00:00, book20_bid_proxy_usdt=19841, book20_ask_proxy_usdt=59759, funding_indicative=-0.000379, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.69%, turnover=5996401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T12:00:01+00:00, last15m_closed_end=2026-11-11T12:00+00:00, prior8high=44.240000, depth_time=2026-11-11T12:00:19+00:00, book20_bid_proxy_usdt=810853, book20_ask_proxy_usdt=479153, funding_indicative=-0.000015, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.06%, turnover=16914562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-11T12:00:00+00:00, last15m_closed_end=2026-11-11T12:00+00:00, prior8high=8.067000, depth_time=2026-11-11T12:00:24+00:00, book20_bid_proxy_usdt=157797, book20_ask_proxy_usdt=312195, funding_indicative=-0.000193, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.36%, turnover=19285613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-11T12:00:00+00:00, last15m_closed_end=2026-11-11T12:00+00:00, prior8high=0.006116, depth_time=2026-11-11T12:00:29+00:00, book20_bid_proxy_usdt=18970, book20_ask_proxy_usdt=25244, funding_indicative=0.000050, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.08%, turnover=19019798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T12:00:00+00:00, last15m_closed_end=2026-11-11T12:00+00:00, prior8high=0.001563, depth_time=2026-11-11T12:00:07+00:00, book20_bid_proxy_usdt=14351, book20_ask_proxy_usdt=12365, funding_indicative=-0.000468, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.32%, turnover=8102990. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T12:00:00+00:00, last15m_closed_end=2026-11-11T12:00+00:00, prior8high=0.000005, depth_time=2026-11-11T12:00:09+00:00, book20_bid_proxy_usdt=33410, book20_ask_proxy_usdt=19205, funding_indicative=-0.000199, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.21%, turnover=80983403. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T12:00:00+00:00, last15m_closed_end=2026-11-11T12:00+00:00, prior8high=179.750000, depth_time=2026-11-11T12:00:26+00:00, book20_bid_proxy_usdt=83193, book20_ask_proxy_usdt=44928, funding_indicative=-0.000153, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.69%, turnover=43476564. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T12:00:00+00:00, last15m_closed_end=2026-11-11T12:00+00:00, prior8high=6.519000, depth_time=2026-11-11T12:00:13+00:00, book20_bid_proxy_usdt=2367339, book20_ask_proxy_usdt=2972390, funding_indicative=-0.000018, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.47%, turnover=40679593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T12:00:00+00:00, last15m_closed_end=2026-11-11T12:00+00:00, prior8high=999.700000, depth_time=2026-11-11T12:00:12+00:00, book20_bid_proxy_usdt=189178, book20_ask_proxy_usdt=129287, funding_indicative=0.000036, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.57%, turnover=2129721188. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
