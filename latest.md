# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T23:30:12Z**
- feed_generated_utc: 2026-10-18T23:30:13+00:00
- source_sha256: `8c963b9e46945c2603b2b29cebefbe8a4e6415fe134922612e88458ae9cdbf1a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T23:30+00:00, close=82132.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T23:00+00:00, close=81727.3, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T20:00+00:00, close=80844.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.060300|-2.04|-49.44|-3.29|15900580|1.66|
|SAND_USDT|0.058840|0.13|-11.43|-1.12|34052648|1.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|SAND_USDT|0.058840|0.056220|0.058840|1.39|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.060300|0.058650|0.060300|0.98|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- SAND_USDT: quote_utc=2026-10-18T23:30:01+00:00, last15m_closed_end=2026-10-18T23:30+00:00, prior8high=0.058440, depth_time=2026-10-18T23:30:11+00:00, book20_bid_proxy_usdt=988233, book20_ask_proxy_usdt=736120, funding_indicative=-0.002570, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=0.13%, turnover=34052648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T23:30:01+00:00, last15m_closed_end=2026-10-18T23:30+00:00, prior8high=0.061020, depth_time=2026-10-18T23:30:07+00:00, book20_bid_proxy_usdt=490290, book20_ask_proxy_usdt=461660, funding_indicative=0.000050, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.04%, turnover=15900580. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
