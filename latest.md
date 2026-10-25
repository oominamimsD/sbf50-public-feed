# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T00:45:14Z**
- feed_generated_utc: 2026-10-25T00:45:17+00:00
- source_sha256: `52e0fba8c21983ba678a68c1e560dbb917bf6fb95d354cd0e029feca34ed4615`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T00:45+00:00, close=80845.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.071000|-27.29|46.33|-28.64|11836127|4.22|
|IRYS_USDT|0.034020|-26.12|166.61|-27.47|35211421|2.93|
|ORDER_USDT|0.057460|-14.74|85.65|-16.09|13228726|3.48|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.071000|0.073860|0.070840|2.20|Y|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.034020|0.035800|0.034020|4.69|Y|Y/Y|Y/Y|Y|Y|
|ORDER_USDT|0.057460|0.055850|0.057110|0.59|N|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T00:45:03+00:00, last15m_closed_end=2026-10-25T00:45+00:00, prior8high=0.100590, depth_time=2026-10-25T00:45:09+00:00, book20_bid_proxy_usdt=12518, book20_ask_proxy_usdt=10722, funding_indicative=-0.017639, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-27.29%, turnover=11836127. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T00:45:03+00:00, last15m_closed_end=2026-10-25T00:45+00:00, prior8high=0.047160, depth_time=2026-10-25T00:45:11+00:00, book20_bid_proxy_usdt=70084, book20_ask_proxy_usdt=67801, funding_indicative=-0.000401, next_funding_utc=2026-10-25T01:00:00+00:00, funding_cycle_h=1, 24h_change=-26.12%, turnover=35211421. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T00:45:03+00:00, last15m_closed_end=2026-10-25T00:45+00:00, prior8high=0.073400, depth_time=2026-10-25T00:45:14+00:00, book20_bid_proxy_usdt=34696, book20_ask_proxy_usdt=43917, funding_indicative=-0.003018, next_funding_utc=2026-10-25T01:00:00+00:00, funding_cycle_h=1, 24h_change=-14.74%, turnover=13228726. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
