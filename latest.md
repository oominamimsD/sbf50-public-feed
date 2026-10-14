# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T00:00:13Z**
- feed_generated_utc: 2026-10-14T00:00:15+00:00
- source_sha256: `4905c2352dfcfd3d5abf792991239d1323b62c138fb490233774a94e0b6fc1ef`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|RLC_USDT|0.891100|-3.47|8.69|-3.15|5119254|1.12|
|CT_USDT|0.360470|-3.03|-2.99|-2.71|5451885|2.77|
|STRK_USDT|0.085150|-2.04|63.15|-1.72|38169173|1.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.360470|0.356040|0.360470|0.17|N|Y/Y|N/N|N|N|
|RLC_USDT|0.891100|0.887000|0.891100|0.19|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.085150|0.082530|0.085150|0.60|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T23:59:59+00:00, last15m_closed_end=2026-10-14T00:00+00:00, prior8high=0.366370, depth_time=2026-10-14T00:00:10+00:00, book20_bid_proxy_usdt=10183, book20_ask_proxy_usdt=9065, funding_indicative=0.000050, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.03%, turnover=5451885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T23:59:59+00:00, last15m_closed_end=2026-10-14T00:00+00:00, prior8high=0.903000, depth_time=2026-10-14T00:00:07+00:00, book20_bid_proxy_usdt=87907, book20_ask_proxy_usdt=66413, funding_indicative=-0.000455, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.47%, turnover=5119254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T23:59:59+00:00, last15m_closed_end=2026-10-14T00:00+00:00, prior8high=0.085960, depth_time=2026-10-14T00:00:12+00:00, book20_bid_proxy_usdt=405161, book20_ask_proxy_usdt=139336, funding_indicative=-0.000006, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.04%, turnover=38169173. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
