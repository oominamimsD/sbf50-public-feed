# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T07:00:18Z**
- feed_generated_utc: 2026-11-06T07:00:19+00:00
- source_sha256: `13cb1dd9fefa7da4adf43ce04495c7d67d47cf91e461595a8cbc3077eb4a8073`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T07:00+00:00, close=75670, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T07:00+00:00, close=75670, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ELSA_USDT|0.077440|-4.57|3.66|-4.13|5810152|2.58|
|XRP_USDT|1.190600|-4.33|-9.07|-3.89|447541722|0.84|
|FLUID_USDT|2.425000|-4.22|17.49|-3.78|6248300|8.24|
|BCH_USDT|268.910000|-3.65|-6.71|-3.21|7413518|3.72|
|XPL_USDT|0.057450|-1.92|-27.21|-1.48|12477016|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|268.910000|266.830000|268.910000|0.57|N|Y/Y|Y/Y|Y|N|
|ELSA_USDT|0.077440|0.076350|0.077440|0.48|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.425000|2.409000|2.425000|1.42|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.057450|0.056460|0.057450|0.50|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.190600|1.188800|1.190600|0.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T06:59:59+00:00, last15m_closed_end=2026-11-06T07:00+00:00, prior8high=277.780000, depth_time=2026-11-06T07:00:15+00:00, book20_bid_proxy_usdt=67853, book20_ask_proxy_usdt=39979, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.65%, turnover=7413518. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ELSA_USDT: quote_utc=2026-11-06T06:59:59+00:00, last15m_closed_end=2026-11-06T07:00+00:00, prior8high=0.078430, depth_time=2026-11-06T07:00:07+00:00, book20_bid_proxy_usdt=24214, book20_ask_proxy_usdt=26013, funding_indicative=0.000078, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.57%, turnover=5810152. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T06:59:59+00:00, last15m_closed_end=2026-11-06T07:00+00:00, prior8high=2.458000, depth_time=2026-11-06T07:00:07+00:00, book20_bid_proxy_usdt=242604, book20_ask_proxy_usdt=155998, funding_indicative=0.000362, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.22%, turnover=6248300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T06:59:59+00:00, last15m_closed_end=2026-11-06T07:00+00:00, prior8high=0.057590, depth_time=2026-11-06T07:00:17+00:00, book20_bid_proxy_usdt=470486, book20_ask_proxy_usdt=424518, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=12477016. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T06:59:59+00:00, last15m_closed_end=2026-11-06T07:00+00:00, prior8high=1.207300, depth_time=2026-11-06T07:00:09+00:00, book20_bid_proxy_usdt=3324168, book20_ask_proxy_usdt=3233576, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.33%, turnover=447541722. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
