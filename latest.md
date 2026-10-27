# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T16:15:10Z**
- feed_generated_utc: 2026-10-27T16:15:13+00:00
- source_sha256: `6ef0c2873da542562277816b908dffb6f2a69048251e61448f310f5738bcef3d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T16:15+00:00, close=80430, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T16:00+00:00, close=80529.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T16:00+00:00, close=80529.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|NIL_USDT|0.091220|-1.58|2.65|-1.46|5511367|7.67|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|NIL_USDT|0.091220|0.089810|0.091130|0.48|N|N/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- NIL_USDT: quote_utc=2026-10-27T16:15:02+00:00, last15m_closed_end=2026-10-27T16:15+00:00, prior8high=0.092950, depth_time=2026-10-27T16:15:08+00:00, book20_bid_proxy_usdt=16292, book20_ask_proxy_usdt=10214, funding_indicative=-0.000436, next_funding_utc=2026-10-27T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.58%, turnover=5511367. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
