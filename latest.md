# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T12:45:20Z**
- feed_generated_utc: 2026-11-03T12:45:21+00:00
- source_sha256: `c54485c8c0972881af3bd0c5584cd85a8d58bb104e586f1b0f62d3e670bc6a38`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T12:45+00:00, close=77374.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004474|-18.68|-85.46|-18.55|12211966|6.71|
|XPL_USDT|0.065390|-6.02|-11.98|-5.89|11707056|1.53|
|SILVER_USDT|49.440000|-3.17|-8.83|-3.04|442530493|2.02|
|NEAR_USDT|3.902000|-2.69|-14.67|-2.56|80157285|2.56|
|DASH_USDT|46.530000|-1.41|-10.89|-1.28|9690912|2.15|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004474|0.004436|0.004475|1.02|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.530000|45.680000|46.550000|1.99|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.902000|3.824000|3.902000|1.78|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|49.440000|48.980000|49.430000|4.01|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.065390|0.063400|0.065390|1.67|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T12:45:03+00:00, last15m_closed_end=2026-11-03T12:45+00:00, prior8high=0.004630, depth_time=2026-11-03T12:45:08+00:00, book20_bid_proxy_usdt=51078, book20_ask_proxy_usdt=50479, funding_indicative=-0.001939, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-18.68%, turnover=12211966. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T12:45:03+00:00, last15m_closed_end=2026-11-03T12:45+00:00, prior8high=46.470000, depth_time=2026-11-03T12:45:19+00:00, book20_bid_proxy_usdt=728864, book20_ask_proxy_usdt=739780, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=9690912. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T12:45:03+00:00, last15m_closed_end=2026-11-03T12:45+00:00, prior8high=3.926000, depth_time=2026-11-03T12:45:15+00:00, book20_bid_proxy_usdt=3746877, book20_ask_proxy_usdt=3741127, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.69%, turnover=80157285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-03T12:45:03+00:00, last15m_closed_end=2026-11-03T12:45+00:00, prior8high=49.350000, depth_time=2026-11-03T12:45:12+00:00, book20_bid_proxy_usdt=57745879, book20_ask_proxy_usdt=47869428, funding_indicative=0.000111, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.17%, turnover=442530493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T12:45:03+00:00, last15m_closed_end=2026-11-03T12:45+00:00, prior8high=0.065520, depth_time=2026-11-03T12:45:10+00:00, book20_bid_proxy_usdt=476622, book20_ask_proxy_usdt=364148, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.02%, turnover=11707056. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
