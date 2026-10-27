# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T21:45:09Z**
- feed_generated_utc: 2026-10-27T21:45:11+00:00
- source_sha256: `863203888a0706ebbd7faa9d9996da8a609721db93b2ee71641708e31e93adfe`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T21:45+00:00, close=80932, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T21:00+00:00, close=80753.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T20:00+00:00, close=80778.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.054920|-13.62|-55.26|-14.11|51448314|4.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|Q_USDT|0.054920|0.051125|0.054926|1.42|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- Q_USDT: quote_utc=2026-10-27T21:45:02+00:00, last15m_closed_end=2026-10-27T21:45+00:00, prior8high=0.055500, depth_time=2026-10-27T21:45:08+00:00, book20_bid_proxy_usdt=2679, book20_ask_proxy_usdt=16293, funding_indicative=0.000016, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-13.62%, turnover=51448314. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
