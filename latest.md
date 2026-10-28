# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T20:00:11Z**
- feed_generated_utc: 2026-10-28T20:00:14+00:00
- source_sha256: `7e2ce12e3d5c5b1df7bb65de7fff199776021a1c9b074da7a9ee7930f8e36176`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AIN_USDT|0.139220|-4.44|247.61|-5.72|7362752|0.72|
|BCH_USDT|288.810000|-1.72|-0.30|-3.00|5366260|3.46|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.139220|0.140360|0.139220|1.03|N|Y/Y|N/N|N|N|
|BCH_USDT|288.810000|282.710000|288.810000|0.59|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-10-28T20:00:03+00:00, last15m_closed_end=2026-10-28T20:00+00:00, prior8high=0.147550, depth_time=2026-10-28T20:00:08+00:00, book20_bid_proxy_usdt=7195, book20_ask_proxy_usdt=21706, funding_indicative=0.000839, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.44%, turnover=7362752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-28T20:00:03+00:00, last15m_closed_end=2026-10-28T20:00+00:00, prior8high=288.550000, depth_time=2026-10-28T20:00:10+00:00, book20_bid_proxy_usdt=48214, book20_ask_proxy_usdt=73015, funding_indicative=0.000026, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=5366260. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
