# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T23:00:13Z**
- feed_generated_utc: 2026-10-15T23:00:15+00:00
- source_sha256: `7626aaf9a143082dd2666132a2abb8e8a3eb68b96eb205f81efdb179eefbfa3d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T23:00+00:00, close=82414, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T23:00+00:00, close=82414, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T20:00+00:00, close=82350.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.050610|-7.05|52.02|-7.09|7436005|1.98|
|NIL_USDT|0.083870|-3.46|-3.14|-3.50|12840386|1.19|
|BTW_USDT|1.896100|-1.73|36.57|-1.77|22738197|1.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.896100|1.861800|1.896100|0.89|N|Y/Y|Y/Y|Y|N|
|NIL_USDT|0.083870|0.082010|0.083890|0.52|N|Y/Y|N/N|Y|N|
|WAL_USDT|0.050610|0.050670|0.050610|1.10|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-15T23:00:02+00:00, last15m_closed_end=2026-10-15T23:00+00:00, prior8high=1.944100, depth_time=2026-10-15T23:00:12+00:00, book20_bid_proxy_usdt=8527, book20_ask_proxy_usdt=7591, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.73%, turnover=22738197. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-15T23:00:02+00:00, last15m_closed_end=2026-10-15T23:00+00:00, prior8high=0.085340, depth_time=2026-10-15T23:00:10+00:00, book20_bid_proxy_usdt=35305, book20_ask_proxy_usdt=30239, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=12840386. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T23:00:02+00:00, last15m_closed_end=2026-10-15T23:00+00:00, prior8high=0.052350, depth_time=2026-10-15T23:00:07+00:00, book20_bid_proxy_usdt=109685, book20_ask_proxy_usdt=137583, funding_indicative=-0.000271, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.05%, turnover=7436005. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
