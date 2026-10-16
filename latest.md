# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T12:00:12Z**
- feed_generated_utc: 2026-10-16T12:00:13+00:00
- source_sha256: `27b14bdbe678b90a0996b6c15443d49403b3281854a80b224bf96dc2d2017d3d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.667400|-13.58|20.10|-13.85|21437184|3.59|
|NIL_USDT|0.082290|-7.62|-4.96|-7.89|5368162|6.08|
|STRK_USDT|0.078870|-7.29|31.10|-7.56|39496834|1.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.667400|1.611400|1.667600|1.32|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.082290|0.081680|0.082300|0.34|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.078870|0.075950|0.078870|1.09|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-16T12:00:00+00:00, last15m_closed_end=2026-10-16T12:00+00:00, prior8high=2.027100, depth_time=2026-10-16T12:00:06+00:00, book20_bid_proxy_usdt=7176, book20_ask_proxy_usdt=6684, funding_indicative=-0.000734, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.58%, turnover=21437184. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T12:00:01+00:00, last15m_closed_end=2026-10-16T12:00+00:00, prior8high=0.084570, depth_time=2026-10-16T12:00:06+00:00, book20_bid_proxy_usdt=36572, book20_ask_proxy_usdt=20969, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.62%, turnover=5368162. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T12:00:00+00:00, last15m_closed_end=2026-10-16T12:00+00:00, prior8high=0.080420, depth_time=2026-10-16T12:00:11+00:00, book20_bid_proxy_usdt=172821, book20_ask_proxy_usdt=415342, funding_indicative=-0.000009, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.29%, turnover=39496834. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
