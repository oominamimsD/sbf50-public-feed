# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T00:15:08Z**
- feed_generated_utc: 2026-10-20T00:15:11+00:00
- source_sha256: `ca7012822c6c42a724a525bc00cc5e2a430287605b0858224bc4890260b5f737`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T00:15+00:00, close=81752.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.320340|-2.95|-6.36|-2.76|5170060|0.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.320340|0.322780|0.320340|4.72|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-20T00:15:01+00:00, last15m_closed_end=2026-10-20T00:15+00:00, prior8high=0.328280, depth_time=2026-10-20T00:15:07+00:00, book20_bid_proxy_usdt=13265, book20_ask_proxy_usdt=9430, funding_indicative=-0.001066, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.95%, turnover=5170060. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
