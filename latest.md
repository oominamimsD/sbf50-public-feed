# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T17:15:12Z**
- feed_generated_utc: 2026-10-27T17:15:15+00:00
- source_sha256: `2cd9862e10954cbfc628aefd6fd9490e06b1c7745c16882023a8f1c313825d5c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T17:15+00:00, close=80596.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T17:00+00:00, close=80620.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T16:00+00:00, close=80529.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.055200|-13.18|-55.03|-13.27|60674450|5.61|
|IRYS_USDT|0.024420|-1.96|87.55|-2.05|5970770|8.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.024420|0.024340|0.024420|0.81|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.055200|0.053221|0.055108|1.73|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-27T17:15:03+00:00, last15m_closed_end=2026-10-27T17:15+00:00, prior8high=0.025550, depth_time=2026-10-27T17:15:11+00:00, book20_bid_proxy_usdt=126096, book20_ask_proxy_usdt=127019, funding_indicative=-0.000513, next_funding_utc=2026-10-27T18:00:00+00:00, funding_cycle_h=1, 24h_change=-1.96%, turnover=5970770. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-27T17:15:03+00:00, last15m_closed_end=2026-10-27T17:15+00:00, prior8high=0.069329, depth_time=2026-10-27T17:15:09+00:00, book20_bid_proxy_usdt=2280, book20_ask_proxy_usdt=1933, funding_indicative=0.000050, next_funding_utc=2026-10-27T20:00:00+00:00, funding_cycle_h=4, 24h_change=-13.18%, turnover=60674450. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
