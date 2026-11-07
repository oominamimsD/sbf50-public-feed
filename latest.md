# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T17:45:09Z**
- feed_generated_utc: 2026-11-07T17:45:09+00:00
- source_sha256: `b4926fa1aae05bc1be97053c0d93218a28b283ae71289dc44de633742033c921`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.01 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T17:45+00:00, close=75824, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T17:00+00:00, close=75712.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T16:00+00:00, close=75725.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|195.970000|-1.44|-2.52|-1.56|42318214|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|QNT_USDT|195.970000|194.580000|195.970000|0.86|N|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- QNT_USDT: quote_utc=2026-11-07T17:45:00+00:00, last15m_closed_end=2026-11-07T17:45+00:00, prior8high=199.710000, depth_time=2026-11-07T17:45:06+00:00, book20_bid_proxy_usdt=68787, book20_ask_proxy_usdt=43573, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=42318214. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
