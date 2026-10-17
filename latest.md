# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T19:30:07Z**
- feed_generated_utc: 2026-10-17T19:30:09+00:00
- source_sha256: `70ec79ee6a6ac2ae2d4864d24fec18d049e529b953ba3f508068bec2b381332a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T19:30+00:00, close=81462.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T19:00+00:00, close=81466.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T16:00+00:00, close=81315.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DNA_USDT|0.255500|-6.10|UNKNOWN|-6.28|7152665|3.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DNA_USDT|0.255500|0.249000|0.255500|0.38|N|Y/Y|?|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DNA_USDT: quote_utc=2026-10-17T19:29:59+00:00, last15m_closed_end=2026-10-17T19:30+00:00, prior8high=0.272400, depth_time=2026-10-17T19:30:06+00:00, book20_bid_proxy_usdt=72819, book20_ask_proxy_usdt=65683, funding_indicative=-0.001307, next_funding_utc=2026-10-17T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.10%, turnover=7152665. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
