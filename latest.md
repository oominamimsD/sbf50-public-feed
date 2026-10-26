# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T18:00:14Z**
- feed_generated_utc: 2026-10-26T18:00:17+00:00
- source_sha256: `8db176ceae337c0a2edc2ec8c3ce6fdd169eaa4f7b61ba438df01623a49e8816`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T18:00+00:00, close=80301.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T18:00+00:00, close=80301.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.027140|-2.65|121.00|-2.53|9744373|3.69|
|DOT_USDT|1.015000|-1.57|-11.49|-1.45|9537951|0.98|
|NEAR_USDT|4.508000|-1.42|-8.07|-1.30|120810131|2.22|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.015000|1.003500|1.015000|0.75|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.027140|0.026240|0.027140|0.21|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.508000|4.474000|4.510000|1.09|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-26T18:00:04+00:00, last15m_closed_end=2026-10-26T18:00+00:00, prior8high=1.028100, depth_time=2026-10-26T18:00:11+00:00, book20_bid_proxy_usdt=194414, book20_ask_proxy_usdt=267512, funding_indicative=-0.000017, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=9537951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T18:00:03+00:00, last15m_closed_end=2026-10-26T18:00+00:00, prior8high=0.027820, depth_time=2026-10-26T18:00:09+00:00, book20_bid_proxy_usdt=99762, book20_ask_proxy_usdt=75092, funding_indicative=-0.000989, next_funding_utc=2026-10-26T19:00:00+00:00, funding_cycle_h=1, 24h_change=-2.65%, turnover=9744373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T18:00:03+00:00, last15m_closed_end=2026-10-26T18:00+00:00, prior8high=4.624000, depth_time=2026-10-26T18:00:13+00:00, book20_bid_proxy_usdt=3190388, book20_ask_proxy_usdt=4994090, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=120810131. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
