# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T00:15:11Z**
- feed_generated_utc: 2026-10-25T00:15:14+00:00
- source_sha256: `f9015466bde2f01fae70146371881f153873e2cf50b6406638935a8625a9eba9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T00:15+00:00, close=80742, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.089860|-7.98|85.20|-9.20|11735241|8.91|
|IRYS_USDT|0.044140|-4.14|245.92|-5.36|34027638|2.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.089860|0.083640|0.089860|5.86|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.044140|0.040280|0.044190|5.99|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T00:15:03+00:00, last15m_closed_end=2026-10-25T00:15+00:00, prior8high=0.092330, depth_time=2026-10-25T00:15:08+00:00, book20_bid_proxy_usdt=9061, book20_ask_proxy_usdt=7610, funding_indicative=-0.012268, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.98%, turnover=11735241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T00:15:02+00:00, last15m_closed_end=2026-10-25T00:15+00:00, prior8high=0.045020, depth_time=2026-10-25T00:15:10+00:00, book20_bid_proxy_usdt=47564, book20_ask_proxy_usdt=37743, funding_indicative=-0.000165, next_funding_utc=2026-10-25T01:00:00+00:00, funding_cycle_h=1, 24h_change=-4.14%, turnover=34027638. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
