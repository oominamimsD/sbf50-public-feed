# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T07:30:34Z**
- feed_generated_utc: 2026-10-20T07:30:36+00:00
- source_sha256: `8862ad0d0e0fb924aec0994f38dddeb89aeff4e8bda3799010abb1c1859c44f0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T07:30+00:00, close=81599.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T07:00+00:00, close=81779.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.077387|-11.09|364.45|-10.71|11220748|2.06|
|Q_USDT|0.119347|-5.26|287.60|-4.88|7763259|4.78|
|CT_USDT|0.312800|-5.24|-8.57|-4.86|5486461|3.84|
|BTW_USDT|1.667300|-4.83|-5.04|-4.45|30445784|3.00|
|SAND_USDT|0.056890|-3.80|-8.37|-3.42|7618950|3.51|
|ZRO_USDT|1.846500|-2.91|-18.33|-2.53|7591629|0.54|
|NEAR_USDT|4.779000|-2.54|-13.87|-2.16|168870326|2.09|
|ATOM_USDT|1.742000|-1.91|-4.70|-1.53|5397507|5.74|
|QNT_USDT|192.270000|-1.75|-15.81|-1.37|81767754|0.52|
|UNI_USDT|7.177000|-1.52|-3.24|-1.14|10198492|1.39|
|TAO_USDT|264.230000|-1.51|-7.70|-1.13|55014250|1.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.077387|0.076392|0.077326|1.46|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.742000|1.742000|1.741000|6.59|Y|N/N|N/N|Y|N|
|BTW_USDT|1.667300|1.660000|1.667300|0.99|N|Y/Y|Y/Y|Y|N|
|CT_USDT|0.312800|0.301550|0.312800|1.12|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.779000|4.749000|4.780000|0.57|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|192.270000|191.100000|192.300000|0.82|N|Y/Y|N/Y|Y|N|
|Q_USDT|0.119347|0.110142|0.119364|0.81|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.056890|0.056650|0.056890|0.63|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|264.230000|263.780000|264.230000|3.34|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.177000|7.119000|7.177000|3.48|N|Y/Y|N/N|Y|N|
|ZRO_USDT|1.846500|1.826700|1.846500|0.79|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T07:30:02+00:00, last15m_closed_end=2026-10-20T07:30+00:00, prior8high=0.090417, depth_time=2026-10-20T07:30:07+00:00, book20_bid_proxy_usdt=2946, book20_ask_proxy_usdt=7583, funding_indicative=0.000281, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.09%, turnover=11220748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T07:30:03+00:00, last15m_closed_end=2026-10-20T07:30+00:00, prior8high=1.766000, depth_time=2026-10-20T07:30:26+00:00, book20_bid_proxy_usdt=1562646, book20_ask_proxy_usdt=1075330, funding_indicative=0.000094, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=5397507. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T07:30:02+00:00, last15m_closed_end=2026-10-20T07:30+00:00, prior8high=1.799100, depth_time=2026-10-20T07:30:17+00:00, book20_bid_proxy_usdt=10147, book20_ask_proxy_usdt=5831, funding_indicative=-0.004286, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.83%, turnover=30445784. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-20T07:30:02+00:00, last15m_closed_end=2026-10-20T07:30+00:00, prior8high=0.310430, depth_time=2026-10-20T07:30:14+00:00, book20_bid_proxy_usdt=11574, book20_ask_proxy_usdt=11311, funding_indicative=-0.002379, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.24%, turnover=5486461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T07:30:02+00:00, last15m_closed_end=2026-10-20T07:30+00:00, prior8high=4.817000, depth_time=2026-10-20T07:30:23+00:00, book20_bid_proxy_usdt=2640892, book20_ask_proxy_usdt=2853873, funding_indicative=-0.000013, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=168870326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T07:30:02+00:00, last15m_closed_end=2026-10-20T07:30+00:00, prior8high=194.880000, depth_time=2026-10-20T07:30:27+00:00, book20_bid_proxy_usdt=67335, book20_ask_proxy_usdt=218208, funding_indicative=0.000016, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=81767754. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T07:30:02+00:00, last15m_closed_end=2026-10-20T07:30+00:00, prior8high=0.133710, depth_time=2026-10-20T07:30:10+00:00, book20_bid_proxy_usdt=13670, book20_ask_proxy_usdt=15797, funding_indicative=-0.000024, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.26%, turnover=7763259. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T07:30:03+00:00, last15m_closed_end=2026-10-20T07:30+00:00, prior8high=0.057320, depth_time=2026-10-20T07:30:19+00:00, book20_bid_proxy_usdt=789476, book20_ask_proxy_usdt=992972, funding_indicative=-0.001471, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.80%, turnover=7618950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T07:30:02+00:00, last15m_closed_end=2026-10-20T07:30+00:00, prior8high=266.700000, depth_time=2026-10-20T07:30:33+00:00, book20_bid_proxy_usdt=143180, book20_ask_proxy_usdt=67315, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=55014250. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T07:30:03+00:00, last15m_closed_end=2026-10-20T07:30+00:00, prior8high=7.271000, depth_time=2026-10-20T07:30:31+00:00, book20_bid_proxy_usdt=2661810, book20_ask_proxy_usdt=2250903, funding_indicative=0.000026, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=10198492. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T07:30:03+00:00, last15m_closed_end=2026-10-20T07:30+00:00, prior8high=1.882200, depth_time=2026-10-20T07:30:22+00:00, book20_bid_proxy_usdt=225043, book20_ask_proxy_usdt=40634, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.91%, turnover=7591629. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
