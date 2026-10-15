# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T01:15:22Z**
- feed_generated_utc: 2026-10-15T01:15:24+00:00
- source_sha256: `1621be688e77375c1678d9e60855bd8b8ff1564a69a44219c239723a5dee4a99`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T01:15+00:00, close=81687.6, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-15T01:00+00:00, close=81624.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PONS_USDT|0.309500|-10.02|-24.60|-10.12|6985697|9.70|
|BAT_USDT|0.168780|-3.23|70.20|-3.33|23470817|0.59|
|FET_USDT|0.198600|-2.59|-12.31|-2.69|10876453|5.03|
|FARTCOIN_USDT|0.153430|-2.04|-4.21|-2.14|7930598|0.65|
|S_USDT|0.053940|-1.55|35.39|-1.65|5007722|1.85|
|AAVE_USDT|153.920000|-1.26|-10.38|-1.36|25735526|0.65|
|QNT_USDT|202.580000|-1.19|-16.55|-1.29|94071052|3.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.920000|153.330000|153.920000|1.43|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.168780|0.169000|0.168780|1.37|Y|Y/Y|N/N|Y|N|
|FARTCOIN_USDT|0.153430|0.153760|0.153430|1.79|Y|Y/Y|Y/Y|Y|Y|
|FET_USDT|0.198600|0.196700|0.198600|0.67|N|Y/Y|Y/Y|Y|N|
|PONS_USDT|0.309500|0.312400|0.309600|2.08|Y|Y/Y|N/N|Y|N|
|QNT_USDT|202.580000|202.310000|202.580000|1.43|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053940|0.053150|0.053940|1.04|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-15T01:15:00+00:00, last15m_closed_end=2026-10-15T01:15+00:00, prior8high=154.460000, depth_time=2026-10-15T01:15:19+00:00, book20_bid_proxy_usdt=283868, book20_ask_proxy_usdt=458306, funding_indicative=0.000058, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=25735526. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-15T01:15:00+00:00, last15m_closed_end=2026-10-15T01:15+00:00, prior8high=0.178290, depth_time=2026-10-15T01:15:09+00:00, book20_bid_proxy_usdt=29415, book20_ask_proxy_usdt=20868, funding_indicative=0.000009, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=23470817. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-15T01:15:00+00:00, last15m_closed_end=2026-10-15T01:15+00:00, prior8high=0.156920, depth_time=2026-10-15T01:15:14+00:00, book20_bid_proxy_usdt=41940, book20_ask_proxy_usdt=71448, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.04%, turnover=7930598. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-15T01:15:00+00:00, last15m_closed_end=2026-10-15T01:15+00:00, prior8high=0.200000, depth_time=2026-10-15T01:15:09+00:00, book20_bid_proxy_usdt=1182022, book20_ask_proxy_usdt=1018579, funding_indicative=-0.000014, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.59%, turnover=10876453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-15T01:15:00+00:00, last15m_closed_end=2026-10-15T01:15+00:00, prior8high=0.336400, depth_time=2026-10-15T01:15:07+00:00, book20_bid_proxy_usdt=211478, book20_ask_proxy_usdt=204672, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.02%, turnover=6985697. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-15T01:15:00+00:00, last15m_closed_end=2026-10-15T01:15+00:00, prior8high=206.710000, depth_time=2026-10-15T01:15:21+00:00, book20_bid_proxy_usdt=70954, book20_ask_proxy_usdt=73232, funding_indicative=0.000024, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=94071052. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-15T01:15:00+00:00, last15m_closed_end=2026-10-15T01:15+00:00, prior8high=0.054780, depth_time=2026-10-15T01:15:17+00:00, book20_bid_proxy_usdt=135076, book20_ask_proxy_usdt=171790, funding_indicative=-0.000110, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.55%, turnover=5007722. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
