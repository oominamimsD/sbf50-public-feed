# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T12:00:22Z**
- feed_generated_utc: 2026-10-28T12:00:25+00:00
- source_sha256: `20c1044f1caf952195e0f7725c666cd19e2f8691ef827f2ffcbeab733d12f2df`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T12:00+00:00, close=81305.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.055210|-13.16|-55.02|-14.12|20817081|3.62|
|BEAT_USDT|0.080750|-11.35|8.08|-12.31|16218061|1.24|
|AKE_USDT|0.020149|-4.62|-35.19|-5.58|6513057|0.50|
|ENA_USDT|0.203710|-4.25|7.28|-5.21|74817155|0.49|
|INJ_USDT|7.936000|-3.12|-7.72|-4.08|24720671|1.26|
|DASH_USDT|53.540000|-0.98|7.20|-1.94|15866317|1.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020149|0.019671|0.020149|1.02|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.080750|0.074400|0.080750|0.45|N|Y/Y|Y/N|N|N|
|DASH_USDT|53.540000|53.440000|53.540000|0.26|N|Y/Y|N/N|N|N|
|ENA_USDT|0.203710|0.202410|0.203720|0.77|N|Y/Y|Y/N|N|N|
|INJ_USDT|7.936000|7.902000|7.935000|0.74|N|Y/Y|N/N|N|N|
|Q_USDT|0.055210|0.054330|0.055200|0.79|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T11:59:59+00:00, last15m_closed_end=2026-10-28T12:00+00:00, prior8high=0.021104, depth_time=2026-10-28T12:00:13+00:00, book20_bid_proxy_usdt=12376, book20_ask_proxy_usdt=6441, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.62%, turnover=6513057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T11:59:59+00:00, last15m_closed_end=2026-10-28T12:00+00:00, prior8high=0.088980, depth_time=2026-10-28T12:00:11+00:00, book20_bid_proxy_usdt=6724, book20_ask_proxy_usdt=4783, funding_indicative=0.000050, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.35%, turnover=16218061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T12:00:00+00:00, last15m_closed_end=2026-10-28T12:00+00:00, prior8high=54.220000, depth_time=2026-10-28T12:00:20+00:00, book20_bid_proxy_usdt=824237, book20_ask_proxy_usdt=598913, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=15866317. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T11:59:59+00:00, last15m_closed_end=2026-10-28T12:00+00:00, prior8high=0.208060, depth_time=2026-10-28T12:00:16+00:00, book20_bid_proxy_usdt=156618, book20_ask_proxy_usdt=164930, funding_indicative=0.000014, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=74817155. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T11:59:59+00:00, last15m_closed_end=2026-10-28T12:00+00:00, prior8high=7.998000, depth_time=2026-10-28T12:00:18+00:00, book20_bid_proxy_usdt=262284, book20_ask_proxy_usdt=369882, funding_indicative=0.000230, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=24720671. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T11:59:59+00:00, last15m_closed_end=2026-10-28T12:00+00:00, prior8high=0.059890, depth_time=2026-10-28T12:00:09+00:00, book20_bid_proxy_usdt=38324, book20_ask_proxy_usdt=39315, funding_indicative=-0.000412, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.16%, turnover=20817081. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
