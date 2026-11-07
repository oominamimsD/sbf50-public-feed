# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T16:15:08Z**
- feed_generated_utc: 2026-11-07T16:15:09+00:00
- source_sha256: `941d0a1e1388a5a83da488abd71fde4adf1ba62641c26a4449e25e114ed0b201`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T16:15+00:00, close=75746.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T16:00+00:00, close=75725.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T16:00+00:00, close=75725.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PUMPFUN_USDT|0.003600|-1.34|-13.91|-1.36|16177464|2.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|PUMPFUN_USDT|0.003600|0.003632|0.003601|17.85|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- PUMPFUN_USDT: quote_utc=2026-11-07T16:15:01+00:00, last15m_closed_end=2026-11-07T16:15+00:00, prior8high=0.003791, depth_time=2026-11-07T16:15:07+00:00, book20_bid_proxy_usdt=1914292, book20_ask_proxy_usdt=2591159, funding_indicative=-0.000003, next_funding_utc=2026-11-07T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=16177464. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
