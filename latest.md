# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T21:15:12Z**
- feed_generated_utc: 2026-10-28T21:15:15+00:00
- source_sha256: `fa2a6f7778c0e920b19a283f7febd0d04fe77d7f0c3c3f41e259d05ede45fd3f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T21:15+00:00, close=81332.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T21:00+00:00, close=81291.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|289.610000|-1.13|-0.02|-2.12|5828620|3.11|
|XMR_USDT|600.380000|-0.61|0.69|-1.60|5365993|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|289.610000|284.790000|289.470000|0.26|N|Y/Y|N/N|N|N|
|XMR_USDT|600.380000|595.790000|600.380000|1.32|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-28T21:15:03+00:00, last15m_closed_end=2026-10-28T21:15+00:00, prior8high=292.510000, depth_time=2026-10-28T21:15:08+00:00, book20_bid_proxy_usdt=45786, book20_ask_proxy_usdt=86300, funding_indicative=0.000022, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=5828620. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T21:15:03+00:00, last15m_closed_end=2026-10-28T21:15+00:00, prior8high=604.680000, depth_time=2026-10-28T21:15:11+00:00, book20_bid_proxy_usdt=34962, book20_ask_proxy_usdt=18171, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.61%, turnover=5365993. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
