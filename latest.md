# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T04:30:18Z**
- feed_generated_utc: 2026-10-20T04:30:20+00:00
- source_sha256: `09c6b2cc051517f05c0bd61ff32fbe0e0967211471b8c8697b4af2e5c7b94585`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T04:30+00:00, close=82050, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.119766|-4.93|288.96|-5.10|13501434|0.83|
|SAND_USDT|0.057480|-2.80|-7.42|-2.97|8927104|1.74|
|CT_USDT|0.321270|-2.67|-6.09|-2.84|5364960|1.25|
|NEAR_USDT|4.809000|-1.93|-13.33|-2.10|167006258|2.08|
|ZRO_USDT|1.873900|-1.47|-17.12|-1.64|7685001|4.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.321270|0.322230|0.321270|4.91|Y|Y/N|Y/Y|N|N|
|NEAR_USDT|4.809000|4.788000|4.809000|0.73|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.119766|0.119369|0.119766|1.01|N|Y/Y|N/N|N|N|
|SAND_USDT|0.057480|0.057600|0.057480|0.89|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.873900|1.847300|1.873900|0.55|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-20T04:29:59+00:00, last15m_closed_end=2026-10-20T04:30+00:00, prior8high=0.340920, depth_time=2026-10-20T04:30:12+00:00, book20_bid_proxy_usdt=11207, book20_ask_proxy_usdt=14174, funding_indicative=-0.002807, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=5364960. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T04:30:03+00:00, last15m_closed_end=2026-10-20T04:30+00:00, prior8high=4.884000, depth_time=2026-10-20T04:30:14+00:00, book20_bid_proxy_usdt=3764080, book20_ask_proxy_usdt=1998470, funding_indicative=0.000032, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=167006258. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T04:30:03+00:00, last15m_closed_end=2026-10-20T04:30+00:00, prior8high=0.128625, depth_time=2026-10-20T04:30:07+00:00, book20_bid_proxy_usdt=23115, book20_ask_proxy_usdt=21595, funding_indicative=-0.000179, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=13501434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T04:29:59+00:00, last15m_closed_end=2026-10-20T04:30+00:00, prior8high=0.058600, depth_time=2026-10-20T04:30:04+00:00, book20_bid_proxy_usdt=567157, book20_ask_proxy_usdt=909631, funding_indicative=-0.001999, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=8927104. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T04:29:59+00:00, last15m_closed_end=2026-10-20T04:30+00:00, prior8high=1.883500, depth_time=2026-10-20T04:30:17+00:00, book20_bid_proxy_usdt=35655, book20_ask_proxy_usdt=26428, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.47%, turnover=7685001. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
