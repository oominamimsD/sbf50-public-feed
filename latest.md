# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T00:30:14Z**
- feed_generated_utc: 2026-10-25T00:30:17+00:00
- source_sha256: `41805b6809ff655fa72bd44b9dc6de0bda849159181996d3ecd3ced76352d4a8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T00:30+00:00, close=80834.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.074380|-23.83|53.29|-25.16|11807349|2.67|
|IRYS_USDT|0.036840|-20.00|188.71|-21.33|34695767|2.71|
|ORDER_USDT|0.057940|-14.03|87.20|-15.36|13205965|8.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.074380|0.083300|0.074380|5.48|Y|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.036840|0.040260|0.036910|5.43|Y|Y/Y|Y/Y|Y|Y|
|ORDER_USDT|0.057940|0.053680|0.057950|0.91|N|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T00:30:03+00:00, last15m_closed_end=2026-10-25T00:30+00:00, prior8high=0.100590, depth_time=2026-10-25T00:30:08+00:00, book20_bid_proxy_usdt=5516, book20_ask_proxy_usdt=12137, funding_indicative=-0.016230, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-23.83%, turnover=11807349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T00:30:03+00:00, last15m_closed_end=2026-10-25T00:30+00:00, prior8high=0.047160, depth_time=2026-10-25T00:30:11+00:00, book20_bid_proxy_usdt=32260, book20_ask_proxy_usdt=26742, funding_indicative=-0.000356, next_funding_utc=2026-10-25T01:00:00+00:00, funding_cycle_h=1, 24h_change=-20.00%, turnover=34695767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T00:30:03+00:00, last15m_closed_end=2026-10-25T00:30+00:00, prior8high=0.073400, depth_time=2026-10-25T00:30:13+00:00, book20_bid_proxy_usdt=24327, book20_ask_proxy_usdt=50747, funding_indicative=-0.002936, next_funding_utc=2026-10-25T01:00:00+00:00, funding_cycle_h=1, 24h_change=-14.03%, turnover=13205965. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
