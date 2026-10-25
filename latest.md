# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T19:00:11Z**
- feed_generated_utc: 2026-10-25T19:00:14+00:00
- source_sha256: `81ba5b07a35ef3b83a05ad0e74708a68d845d0d99d39f443f4f5dda961a45e71`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T19:00+00:00, close=80623.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T19:00+00:00, close=80623.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|USELESS_USDT|0.168650|-2.09|19.23|-2.11|5234836|0.59|
|ASTER_USDT|0.699900|-1.00|0.37|-1.02|7353654|1.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.699900|0.698700|0.699900|1.05|N|Y/Y|N/N|Y|N|
|USELESS_USDT|0.168650|0.166550|0.168650|0.70|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-10-25T19:00:01+00:00, last15m_closed_end=2026-10-25T19:00+00:00, prior8high=0.704500, depth_time=2026-10-25T19:00:10+00:00, book20_bid_proxy_usdt=950624, book20_ask_proxy_usdt=771770, funding_indicative=0.000032, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.00%, turnover=7353654. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-25T19:00:01+00:00, last15m_closed_end=2026-10-25T19:00+00:00, prior8high=0.172060, depth_time=2026-10-25T19:00:06+00:00, book20_bid_proxy_usdt=31418, book20_ask_proxy_usdt=36127, funding_indicative=0.000130, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=5234836. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
