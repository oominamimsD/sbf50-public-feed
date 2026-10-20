# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T01:45:11Z**
- feed_generated_utc: 2026-10-20T01:45:13+00:00
- source_sha256: `9c37235afe9034849679a3b30cefa6ce97889952cd959826d17c19fe686ad3ab`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T01:45+00:00, close=81658.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T01:00+00:00, close=81700.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T00:00+00:00, close=81903.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.869400|-1.71|-17.31|-1.40|7845413|0.54|
|SAND_USDT|0.058300|-1.42|-6.10|-1.11|8995954|1.72|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|SAND_USDT|0.058300|0.057130|0.058300|6.27|N|Y/Y|N/Y|Y|N|
|ZRO_USDT|1.869400|1.833600|1.869200|1.18|N|Y/N|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- SAND_USDT: quote_utc=2026-10-20T01:45:01+00:00, last15m_closed_end=2026-10-20T01:45+00:00, prior8high=0.059350, depth_time=2026-10-20T01:45:10+00:00, book20_bid_proxy_usdt=649595, book20_ask_proxy_usdt=766647, funding_indicative=-0.002383, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=8995954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T01:45:02+00:00, last15m_closed_end=2026-10-20T01:45+00:00, prior8high=1.924500, depth_time=2026-10-20T01:45:08+00:00, book20_bid_proxy_usdt=38695, book20_ask_proxy_usdt=43843, funding_indicative=0.000050, next_funding_utc=2026-10-20T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=7845413. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
