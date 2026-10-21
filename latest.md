# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T01:00:16Z**
- feed_generated_utc: 2026-10-21T01:00:18+00:00
- source_sha256: `ed362cb351572f53c8a05e88fefc15a35ee1f118df8bf71eeb34274bb837bbbd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T01:00+00:00, close=82991, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T01:00+00:00, close=82991, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.192090|-10.97|8.29|-11.46|10283936|0.52|
|XMR_USDT|584.010000|-5.83|10.62|-6.32|16899583|0.17|
|TIA_USDT|0.610400|-1.97|5.73|-2.46|48051217|1.64|
|PHA_USDT|0.057360|-0.79|4.23|-1.28|10880355|3.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.192090|0.191100|0.192090|2.53|N|Y/Y|N/N|N|N|
|PHA_USDT|0.057360|0.057540|0.057360|0.53|N|Y/Y|N/N|N|N|
|TIA_USDT|0.610400|0.613700|0.610400|6.40|Y|Y/Y|Y/Y|N|Y|
|XMR_USDT|584.010000|582.440000|584.010000|1.80|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-21T00:59:59+00:00, last15m_closed_end=2026-10-21T01:00+00:00, prior8high=0.195840, depth_time=2026-10-21T01:00:07+00:00, book20_bid_proxy_usdt=30115, book20_ask_proxy_usdt=24546, funding_indicative=0.000071, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.97%, turnover=10283936. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T00:59:59+00:00, last15m_closed_end=2026-10-21T01:00+00:00, prior8high=0.058570, depth_time=2026-10-21T01:00:14+00:00, book20_bid_proxy_usdt=72709, book20_ask_proxy_usdt=82640, funding_indicative=-0.000061, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.79%, turnover=10880355. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T00:59:59+00:00, last15m_closed_end=2026-10-21T01:00+00:00, prior8high=0.625200, depth_time=2026-10-21T01:00:11+00:00, book20_bid_proxy_usdt=173640, book20_ask_proxy_usdt=267833, funding_indicative=-0.000071, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=48051217. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T00:59:59+00:00, last15m_closed_end=2026-10-21T01:00+00:00, prior8high=624.900000, depth_time=2026-10-21T01:00:09+00:00, book20_bid_proxy_usdt=10492, book20_ask_proxy_usdt=11766, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.83%, turnover=16899583. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
