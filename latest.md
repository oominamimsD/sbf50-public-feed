# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T03:30:25Z**
- feed_generated_utc: 2026-10-26T03:30:28+00:00
- source_sha256: `153ea2587534fb2448e04e8a946d11c252c2f4a8517f19a8870d4894eeac6d19`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T03:30+00:00, close=79621.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T03:00+00:00, close=79535.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005266|-24.46|185.72|-23.24|11588068|5.70|
|APR_USDT|0.034970|-15.34|28.37|-14.12|12110682|2.86|
|T_USDT|0.004958|-7.89|5.44|-6.67|6934393|2.02|
|DASH_USDT|50.450000|-3.73|5.36|-2.51|13757071|1.98|
|WLD_USDT|0.441700|-3.26|-7.26|-2.04|73211593|2.26|
|PUMPFUN_USDT|0.004167|-2.75|-0.66|-1.53|17241153|2.40|
|PEPE_USDT|0.000004|-2.68|10.97|-1.46|70554712|1.64|
|LIT_USDT|3.098400|-2.51|5.73|-1.29|6105206|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034970|0.032120|0.034970|1.71|N|Y/Y|N/N|Y|N|
|DASH_USDT|50.450000|50.270000|50.450000|0.08|N|Y/Y|Y/N|Y|N|
|JCT_USDT|0.005266|0.003891|0.005242|3.08|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.098400|3.103400|3.098400|1.00|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.41|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004167|0.004152|0.004167|0.61|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004958|0.004873|0.004958|0.76|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.441700|0.441300|0.441900|1.76|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T03:30:01+00:00, last15m_closed_end=2026-10-26T03:30+00:00, prior8high=0.038770, depth_time=2026-10-26T03:30:10+00:00, book20_bid_proxy_usdt=62239, book20_ask_proxy_usdt=78803, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-15.34%, turnover=12110682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T03:30:01+00:00, last15m_closed_end=2026-10-26T03:30+00:00, prior8high=51.480000, depth_time=2026-10-26T03:30:14+00:00, book20_bid_proxy_usdt=903493, book20_ask_proxy_usdt=628816, funding_indicative=0.000057, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.73%, turnover=13757071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T03:30:01+00:00, last15m_closed_end=2026-10-26T03:30+00:00, prior8high=0.005895, depth_time=2026-10-26T03:30:08+00:00, book20_bid_proxy_usdt=7762, book20_ask_proxy_usdt=14217, funding_indicative=0.000187, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-24.46%, turnover=11588068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T03:30:01+00:00, last15m_closed_end=2026-10-26T03:30+00:00, prior8high=3.184300, depth_time=2026-10-26T03:30:23+00:00, book20_bid_proxy_usdt=23437, book20_ask_proxy_usdt=23633, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.51%, turnover=6105206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T03:30:01+00:00, last15m_closed_end=2026-10-26T03:30+00:00, prior8high=0.000004, depth_time=2026-10-26T03:30:22+00:00, book20_bid_proxy_usdt=84882, book20_ask_proxy_usdt=78239, funding_indicative=-0.000001, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.68%, turnover=70554712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T03:30:01+00:00, last15m_closed_end=2026-10-26T03:30+00:00, prior8high=0.004265, depth_time=2026-10-26T03:30:20+00:00, book20_bid_proxy_usdt=1707109, book20_ask_proxy_usdt=2120742, funding_indicative=0.000043, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=17241153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T03:30:01+00:00, last15m_closed_end=2026-10-26T03:30+00:00, prior8high=0.004998, depth_time=2026-10-26T03:30:12+00:00, book20_bid_proxy_usdt=33173, book20_ask_proxy_usdt=63431, funding_indicative=-0.001827, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=1, 24h_change=-7.89%, turnover=6934393. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T03:30:01+00:00, last15m_closed_end=2026-10-26T03:30+00:00, prior8high=0.449100, depth_time=2026-10-26T03:30:17+00:00, book20_bid_proxy_usdt=2474422, book20_ask_proxy_usdt=2393170, funding_indicative=0.000097, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.26%, turnover=73211593. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
