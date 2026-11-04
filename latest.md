# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T06:00:17Z**
- feed_generated_utc: 2026-11-04T06:00:19+00:00
- source_sha256: `38995d7dc120b839413322e95dcb2d4fb4445941ed4c20cc67a2ea43a42a977a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T06:00+00:00, close=77721.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T06:00+00:00, close=77721.7, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.038020|-29.34|-19.99|-29.42|11021365|5.26|
|AKE_USDT|0.003152|-24.15|-85.07|-24.23|12408930|3.17|
|TRUMPOFFICIAL_USDT|1.522000|-5.34|-9.83|-5.42|8339794|6.58|
|Q_USDT|0.027730|-1.56|-56.38|-1.64|7361617|3.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.038020|0.036380|0.037950|1.51|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.003152|0.002979|0.003150|1.81|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.027730|0.027450|0.027760|0.58|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.522000|1.492000|1.521000|1.06|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T06:00:04+00:00, last15m_closed_end=2026-11-04T06:00+00:00, prior8high=0.038630, depth_time=2026-11-04T06:00:09+00:00, book20_bid_proxy_usdt=41733, book20_ask_proxy_usdt=23563, funding_indicative=0.000134, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-29.34%, turnover=11021365. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T06:00:04+00:00, last15m_closed_end=2026-11-04T06:00+00:00, prior8high=0.003654, depth_time=2026-11-04T06:00:11+00:00, book20_bid_proxy_usdt=61474, book20_ask_proxy_usdt=35919, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-24.15%, turnover=12408930. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T06:00:04+00:00, last15m_closed_end=2026-11-04T06:00+00:00, prior8high=0.028340, depth_time=2026-11-04T06:00:17+00:00, book20_bid_proxy_usdt=54572, book20_ask_proxy_usdt=55221, funding_indicative=-0.000462, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.56%, turnover=7361617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T06:00:04+00:00, last15m_closed_end=2026-11-04T06:00+00:00, prior8high=1.521000, depth_time=2026-11-04T06:00:12+00:00, book20_bid_proxy_usdt=2431684, book20_ask_proxy_usdt=2290737, funding_indicative=-0.000154, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.34%, turnover=8339794. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
