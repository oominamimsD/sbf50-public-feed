# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T16:15:10Z**
- feed_generated_utc: 2026-10-31T16:15:12+00:00
- source_sha256: `b62aa7b50545d7458982be40c33a1d54e77f946d4105beba75cc75a2f0df6d9e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T16:15+00:00, close=77584.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.031230|-2.64|-60.43|-2.67|10931044|3.20|
|IDOL_USDT|0.017265|-1.46|118.54|-1.49|15534654|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IDOL_USDT|0.017265|0.017035|0.017265|3.58|N|Y/Y|N/N|Y|N|
|Q_USDT|0.031230|0.031680|0.031230|3.58|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- IDOL_USDT: quote_utc=2026-10-31T16:15:02+00:00, last15m_closed_end=2026-10-31T16:15+00:00, prior8high=0.020565, depth_time=2026-10-31T16:15:09+00:00, book20_bid_proxy_usdt=10323, book20_ask_proxy_usdt=9594, funding_indicative=0.000142, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=15534654. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T16:15:02+00:00, last15m_closed_end=2026-10-31T16:15+00:00, prior8high=0.033470, depth_time=2026-10-31T16:15:07+00:00, book20_bid_proxy_usdt=57518, book20_ask_proxy_usdt=59919, funding_indicative=-0.000661, next_funding_utc=2026-10-31T17:00:00+00:00, funding_cycle_h=1, 24h_change=-2.64%, turnover=10931044. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
