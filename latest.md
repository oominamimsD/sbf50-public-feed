# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T16:45:19Z**
- feed_generated_utc: 2026-11-02T16:45:21+00:00
- source_sha256: `3f3209a23a490230e6e76ffc09f79ec948359a871e4c1e277a2851de60c6460a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T16:45+00:00, close=77497.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.128900|-2.86|-48.19|-2.91|8068700|7.74|
|Q_USDT|0.025410|-2.41|-56.97|-2.46|6912455|3.93|
|ENA_USDT|0.172520|-1.43|-17.99|-1.48|66415243|0.58|
|ZEC_USDT|1236.170000|-1.42|-0.92|-1.47|1583743497|0.08|
|PUMPFUN_USDT|0.004059|-1.09|-6.21|-1.14|9362475|2.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.172520|0.171150|0.172430|1.12|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004059|0.004055|0.004059|2.36|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.025410|0.025280|0.025410|1.84|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.128900|0.129300|0.128700|0.86|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1236.170000|1229.950000|1234.960000|1.16|N|N/N|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-02T16:45:03+00:00, last15m_closed_end=2026-11-02T16:45+00:00, prior8high=0.178850, depth_time=2026-11-02T16:45:13+00:00, book20_bid_proxy_usdt=183156, book20_ask_proxy_usdt=346349, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=66415243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T16:45:03+00:00, last15m_closed_end=2026-11-02T16:45+00:00, prior8high=0.004222, depth_time=2026-11-02T16:45:18+00:00, book20_bid_proxy_usdt=1550548, book20_ask_proxy_usdt=2385247, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.09%, turnover=9362475. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-02T16:45:03+00:00, last15m_closed_end=2026-11-02T16:45+00:00, prior8high=0.026920, depth_time=2026-11-02T16:45:11+00:00, book20_bid_proxy_usdt=69562, book20_ask_proxy_usdt=61497, funding_indicative=-0.000554, next_funding_utc=2026-11-02T17:00:00+00:00, funding_cycle_h=1, 24h_change=-2.41%, turnover=6912455. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T16:45:03+00:00, last15m_closed_end=2026-11-02T16:45+00:00, prior8high=0.138900, depth_time=2026-11-02T16:45:06+00:00, book20_bid_proxy_usdt=162660, book20_ask_proxy_usdt=162997, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=8068700. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T16:45:03+00:00, last15m_closed_end=2026-11-02T16:45+00:00, prior8high=1273.850000, depth_time=2026-11-02T16:45:16+00:00, book20_bid_proxy_usdt=296051, book20_ask_proxy_usdt=775780, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=1583743497. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
