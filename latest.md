# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T02:00:17Z**
- feed_generated_utc: 2026-10-25T02:00:19+00:00
- source_sha256: `3b7551dbce9b43481a738e5581386cb735a7e7a958ebd2c008d46b8a2d5baaf8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T02:00+00:00, close=80872.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T02:00+00:00, close=80872.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.032400|-43.07|153.91|-44.46|32177401|3.09|
|ORDER_USDT|0.051240|-23.97|65.55|-25.36|13355724|1.95|
|STRK_USDT|0.046620|-1.45|-29.52|-2.84|8167827|2.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.032400|0.031610|0.032400|1.18|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.051240|0.051110|0.051210|0.54|N|Y/N|N/N|Y|N|
|STRK_USDT|0.046620|0.046420|0.046620|0.36|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-25T02:00:00+00:00, last15m_closed_end=2026-10-25T02:00+00:00, prior8high=0.047160, depth_time=2026-10-25T02:00:11+00:00, book20_bid_proxy_usdt=52783, book20_ask_proxy_usdt=54813, funding_indicative=-0.000042, next_funding_utc=2026-10-25T03:00:00+00:00, funding_cycle_h=1, 24h_change=-43.07%, turnover=32177401. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T02:00:00+00:00, last15m_closed_end=2026-10-25T02:00+00:00, prior8high=0.073400, depth_time=2026-10-25T02:00:12+00:00, book20_bid_proxy_usdt=73276, book20_ask_proxy_usdt=48742, funding_indicative=-0.001507, next_funding_utc=2026-10-25T03:00:00+00:00, funding_cycle_h=1, 24h_change=-23.97%, turnover=13355724. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T02:00:01+00:00, last15m_closed_end=2026-10-25T02:00+00:00, prior8high=0.047560, depth_time=2026-10-25T02:00:16+00:00, book20_bid_proxy_usdt=931192, book20_ask_proxy_usdt=625220, funding_indicative=0.000050, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.45%, turnover=8167827. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
