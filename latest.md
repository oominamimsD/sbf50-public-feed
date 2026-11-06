# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T06:30:15Z**
- feed_generated_utc: 2026-11-06T06:30:16+00:00
- source_sha256: `e11ea8b6f6226e66b242a0f9f6b0929e710a707ddb1d784822332e18d6968ee8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T06:30+00:00, close=75632, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T06:00+00:00, close=75669.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FLUID_USDT|2.413000|-4.69|16.90|-4.21|6229545|4.15|
|ELSA_USDT|0.077510|-4.48|3.76|-4.00|5798466|1.29|
|XRP_USDT|1.197700|-3.76|-8.53|-3.28|443886928|0.83|
|XPL_USDT|0.057190|-2.37|-27.54|-1.89|12433695|1.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ELSA_USDT|0.077510|0.076350|0.077510|1.02|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.413000|2.409000|2.413000|0.72|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.057190|0.056460|0.057190|0.61|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.197700|1.188800|1.197700|0.91|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ELSA_USDT: quote_utc=2026-11-06T06:30:00+00:00, last15m_closed_end=2026-11-06T06:30+00:00, prior8high=0.078430, depth_time=2026-11-06T06:30:09+00:00, book20_bid_proxy_usdt=18806, book20_ask_proxy_usdt=26796, funding_indicative=0.000072, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.48%, turnover=5798466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T06:30:01+00:00, last15m_closed_end=2026-11-06T06:30+00:00, prior8high=2.456000, depth_time=2026-11-06T06:30:01+00:00, book20_bid_proxy_usdt=258623, book20_ask_proxy_usdt=159936, funding_indicative=0.000339, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.69%, turnover=6229545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T06:30:01+00:00, last15m_closed_end=2026-11-06T06:30+00:00, prior8high=0.057540, depth_time=2026-11-06T06:30:13+00:00, book20_bid_proxy_usdt=360102, book20_ask_proxy_usdt=405940, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.37%, turnover=12433695. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T06:30:00+00:00, last15m_closed_end=2026-11-06T06:30+00:00, prior8high=1.207300, depth_time=2026-11-06T06:30:11+00:00, book20_bid_proxy_usdt=4262302, book20_ask_proxy_usdt=3161785, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.76%, turnover=443886928. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
