# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T12:45:19Z**
- feed_generated_utc: 2026-10-14T12:45:21+00:00
- source_sha256: `b8c33b3e51815e9d2227942ecf89346929a22b62eeec63b43c272b037f59b061`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T12:45+00:00, close=82805.6, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-14T12:00+00:00, close=83424.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T12:00+00:00, close=83424.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.079880|-8.10|53.05|-7.40|28165580|1.25|
|W_USDT|0.015805|-5.93|8.90|-5.23|6441233|2.53|
|TIA_USDT|0.550500|-4.64|15.57|-3.94|35056625|1.81|
|UNI_USDT|7.265000|-4.05|-16.15|-3.35|20490980|1.38|
|SILVER_USDT|57.840000|-2.60|-5.75|-1.90|307705470|1.73|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|SILVER_USDT|57.840000|58.480000|57.860000|15.02|Y|Y/Y|Y/Y|N|Y|
|STRK_USDT|0.079880|0.077420|0.079890|2.96|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.550500|0.540500|0.550500|3.64|N|Y/Y|Y/Y|N|N|
|UNI_USDT|7.265000|7.313000|7.267000|43.17|Y|Y/Y|Y/Y|N|Y|
|W_USDT|0.015805|0.015562|0.015798|2.19|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- SILVER_USDT: quote_utc=2026-10-14T12:45:01+00:00, last15m_closed_end=2026-10-14T12:45+00:00, prior8high=58.910000, depth_time=2026-10-14T12:45:18+00:00, book20_bid_proxy_usdt=35075274, book20_ask_proxy_usdt=31239705, funding_indicative=0.000109, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=307705470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T12:45:01+00:00, last15m_closed_end=2026-10-14T12:45+00:00, prior8high=0.080580, depth_time=2026-10-14T12:45:08+00:00, book20_bid_proxy_usdt=247918, book20_ask_proxy_usdt=182064, funding_indicative=0.000050, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.10%, turnover=28165580. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T12:45:01+00:00, last15m_closed_end=2026-10-14T12:45+00:00, prior8high=0.560900, depth_time=2026-10-14T12:45:13+00:00, book20_bid_proxy_usdt=123385, book20_ask_proxy_usdt=181170, funding_indicative=-0.000035, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.64%, turnover=35056625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T12:45:01+00:00, last15m_closed_end=2026-10-14T12:45+00:00, prior8high=7.404000, depth_time=2026-10-14T12:45:15+00:00, book20_bid_proxy_usdt=953718, book20_ask_proxy_usdt=1377304, funding_indicative=0.000083, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.05%, turnover=20490980. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T12:45:01+00:00, last15m_closed_end=2026-10-14T12:45+00:00, prior8high=0.016220, depth_time=2026-10-14T12:45:10+00:00, book20_bid_proxy_usdt=20631, book20_ask_proxy_usdt=40208, funding_indicative=-0.000221, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.93%, turnover=6441233. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
