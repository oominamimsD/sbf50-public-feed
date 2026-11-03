# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T21:45:12Z**
- feed_generated_utc: 2026-11-03T21:45:13+00:00
- source_sha256: `84f539f8416470b1a5d21d8a5f2413f1ad856f820517e4c8f404cf6244935f12`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T21:45+00:00, close=78015.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T21:00+00:00, close=77833.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|193.250000|-1.11|-2.34|-1.58|58144408|0.52|
|AKE_USDT|0.004131|-0.60|-80.44|-1.07|13916744|2.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004131|0.003851|0.004131|1.64|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.250000|190.330000|193.210000|0.54|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T21:45:03+00:00, last15m_closed_end=2026-11-03T21:45+00:00, prior8high=0.004125, depth_time=2026-11-03T21:45:11+00:00, book20_bid_proxy_usdt=83855, book20_ask_proxy_usdt=35553, funding_indicative=-0.000468, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.60%, turnover=13916744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T21:45:03+00:00, last15m_closed_end=2026-11-03T21:45+00:00, prior8high=193.640000, depth_time=2026-11-03T21:45:08+00:00, book20_bid_proxy_usdt=74561, book20_ask_proxy_usdt=83879, funding_indicative=0.000085, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=58144408. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
