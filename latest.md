# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T21:00:15Z**
- feed_generated_utc: 2026-10-25T21:00:18+00:00
- source_sha256: `207b2e32dcbef7dd7853854762fdd18c59a3ade3bd23d85d8ce8bc92cda39653`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T21:00+00:00, close=80457, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T21:00+00:00, close=80457, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T20:00+00:00, close=80530.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DASH_USDT|51.850000|-2.18|8.29|-2.00|13829952|3.86|
|T_USDT|0.005293|-1.67|12.56|-1.49|8525794|1.89|
|USELESS_USDT|0.169770|-1.44|20.02|-1.26|5052696|0.59|
|PEPE_USDT|0.000004|-1.33|13.31|-1.15|71547074|1.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|51.850000|51.730000|51.850000|1.64|N|Y/N|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|2.05|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.005293|0.005255|0.005302|0.45|N|Y/Y|N/N|Y|N|
|USELESS_USDT|0.169770|0.167500|0.169770|1.16|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-10-25T21:00:01+00:00, last15m_closed_end=2026-10-25T21:00+00:00, prior8high=52.450000, depth_time=2026-10-25T21:00:05+00:00, book20_bid_proxy_usdt=490673, book20_ask_proxy_usdt=684560, funding_indicative=0.000100, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=13829952. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-25T21:00:01+00:00, last15m_closed_end=2026-10-25T21:00+00:00, prior8high=0.000004, depth_time=2026-10-25T21:00:15+00:00, book20_bid_proxy_usdt=55013, book20_ask_proxy_usdt=87979, funding_indicative=0.000039, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=71547074. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-25T21:00:01+00:00, last15m_closed_end=2026-10-25T21:00+00:00, prior8high=0.005459, depth_time=2026-10-25T21:00:09+00:00, book20_bid_proxy_usdt=99466, book20_ask_proxy_usdt=73848, funding_indicative=-0.003177, next_funding_utc=2026-10-25T22:00:00+00:00, funding_cycle_h=1, 24h_change=-1.67%, turnover=8525794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T21:00:01+00:00, last15m_closed_end=2026-10-25T21:00+00:00, prior8high=0.170640, depth_time=2026-10-25T21:00:12+00:00, book20_bid_proxy_usdt=24485, book20_ask_proxy_usdt=31848, funding_indicative=0.000160, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.44%, turnover=5052696. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
