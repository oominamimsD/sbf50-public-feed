# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T05:15:08Z**
- feed_generated_utc: 2026-10-16T05:15:10+00:00
- source_sha256: `e173d1565330f4f87e3b67fab3de22d1f6ed222f4d28e08ee107faca6836f042`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 10/10 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 1; crypto_deep: 1
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T05:15+00:00, close=82262.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T05:00+00:00, close=82130.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEREBRO_USDT|0.039939|-22.13|45.46|-22.00|6946567|2.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ZEREBRO_USDT|0.039939|0.038700|0.039878|0.75|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ZEREBRO_USDT: quote_utc=2026-10-16T05:15:02+00:00, last15m_closed_end=2026-10-16T05:15+00:00, prior8high=0.051467, depth_time=2026-10-16T05:15:06+00:00, book20_bid_proxy_usdt=43879, book20_ask_proxy_usdt=23835, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-22.13%, turnover=6946567. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
