# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T07:30:18Z**
- feed_generated_utc: 2026-11-06T07:30:19+00:00
- source_sha256: `9d13efb1e0d242291a7c14f58973bf80f9cb84a52ced7eb968e903ffb29542f0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T07:30+00:00, close=75320, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T07:00+00:00, close=75670, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FLUID_USDT|2.394000|-5.45|15.98|-4.54|5678793|4.18|
|ELSA_USDT|0.076850|-5.29|2.87|-4.38|5485623|7.79|
|XRP_USDT|1.181400|-5.07|-9.78|-4.16|458278217|0.85|
|BCH_USDT|265.190000|-4.99|-8.00|-4.08|7553128|3.77|
|XPL_USDT|0.056920|-2.83|-27.88|-1.92|12221520|3.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|265.190000|266.660000|265.190000|15.48|Y|Y/Y|Y/Y|Y|Y|
|ELSA_USDT|0.076850|0.076350|0.076850|1.22|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.394000|2.388000|2.394000|5.05|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.056920|0.056460|0.056910|1.31|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.181400|1.183900|1.181400|2.54|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T07:30:00+00:00, last15m_closed_end=2026-11-06T07:30+00:00, prior8high=277.780000, depth_time=2026-11-06T07:30:15+00:00, book20_bid_proxy_usdt=70056, book20_ask_proxy_usdt=32241, funding_indicative=0.000064, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.99%, turnover=7553128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ELSA_USDT: quote_utc=2026-11-06T07:29:59+00:00, last15m_closed_end=2026-11-06T07:30+00:00, prior8high=0.078390, depth_time=2026-11-06T07:30:10+00:00, book20_bid_proxy_usdt=24286, book20_ask_proxy_usdt=22119, funding_indicative=0.000072, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.29%, turnover=5485623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T07:30:00+00:00, last15m_closed_end=2026-11-06T07:30+00:00, prior8high=2.459000, depth_time=2026-11-06T07:30:08+00:00, book20_bid_proxy_usdt=238438, book20_ask_proxy_usdt=142424, funding_indicative=0.000253, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.45%, turnover=5678793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T07:30:00+00:00, last15m_closed_end=2026-11-06T07:30+00:00, prior8high=0.057590, depth_time=2026-11-06T07:30:17+00:00, book20_bid_proxy_usdt=390351, book20_ask_proxy_usdt=449516, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.83%, turnover=12221520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T07:29:59+00:00, last15m_closed_end=2026-11-06T07:30+00:00, prior8high=1.201600, depth_time=2026-11-06T07:30:12+00:00, book20_bid_proxy_usdt=3645887, book20_ask_proxy_usdt=4378661, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.07%, turnover=458278217. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
