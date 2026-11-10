# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T07:00:28Z**
- feed_generated_utc: 2026-11-10T07:00:30+00:00
- source_sha256: `81cf9bdb7a391627de5f779e58d93b32777aa88105126fc98d6d630d7f1d969d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T07:00+00:00, close=74627.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T07:00+00:00, close=74627.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T04:00+00:00, close=74537.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002510|-48.74|-54.38|-47.58|15265833|3.98|
|JCT_USDT|0.006509|-40.68|50.77|-39.52|25211297|1.54|
|ZEC_USDT|1150.280000|-6.15|-8.27|-4.99|2345272321|0.17|
|ARB_USDT|0.171170|-5.06|7.43|-3.90|34167509|0.58|
|QNT_USDT|190.810000|-4.56|-5.74|-3.40|34137971|0.52|
|AAVE_USDT|126.700000|-4.39|-2.95|-3.23|12910469|0.79|
|ON_USDT|0.191600|-3.71|13.03|-2.55|5562227|5.20|
|DASH_USDT|45.750000|-3.29|-3.07|-2.13|12256504|2.19|
|DOT_USDT|0.859100|-3.01|-8.02|-1.85|8764935|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.700000|125.050000|126.700000|0.70|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.002510|0.002443|0.002509|0.45|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.171170|0.170290|0.171170|0.87|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.750000|45.630000|45.750000|0.90|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.859100|0.848100|0.859100|0.56|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006509|0.006444|0.006509|1.14|N|Y/Y|N/N|Y|N|
|ON_USDT|0.191600|0.165700|0.191500|5.58|N|N/Y|Y/Y|Y|N|
|QNT_USDT|190.810000|189.670000|190.810000|0.38|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1150.280000|1144.770000|1150.740000|0.69|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T07:00:02+00:00, last15m_closed_end=2026-11-10T07:00+00:00, prior8high=127.600000, depth_time=2026-11-10T07:00:19+00:00, book20_bid_proxy_usdt=363606, book20_ask_proxy_usdt=302277, funding_indicative=0.000046, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.39%, turnover=12910469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T07:00:02+00:00, last15m_closed_end=2026-11-10T07:00+00:00, prior8high=0.002566, depth_time=2026-11-10T07:00:06+00:00, book20_bid_proxy_usdt=84923, book20_ask_proxy_usdt=47587, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-48.74%, turnover=15265833. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T07:00:02+00:00, last15m_closed_end=2026-11-10T07:00+00:00, prior8high=0.173110, depth_time=2026-11-10T07:00:14+00:00, book20_bid_proxy_usdt=137915, book20_ask_proxy_usdt=67426, funding_indicative=-0.000022, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.06%, turnover=34167509. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T07:00:02+00:00, last15m_closed_end=2026-11-10T07:00+00:00, prior8high=46.250000, depth_time=2026-11-10T07:00:21+00:00, book20_bid_proxy_usdt=833087, book20_ask_proxy_usdt=704231, funding_indicative=0.000041, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.29%, turnover=12256504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T07:00:02+00:00, last15m_closed_end=2026-11-10T07:00+00:00, prior8high=0.859900, depth_time=2026-11-10T07:00:27+00:00, book20_bid_proxy_usdt=628813, book20_ask_proxy_usdt=672614, funding_indicative=0.000047, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.01%, turnover=8764935. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T07:00:01+00:00, last15m_closed_end=2026-11-10T07:00+00:00, prior8high=0.007976, depth_time=2026-11-10T07:00:10+00:00, book20_bid_proxy_usdt=24497, book20_ask_proxy_usdt=32631, funding_indicative=0.000050, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-40.68%, turnover=25211297. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ON_USDT: quote_utc=2026-11-10T07:00:02+00:00, last15m_closed_end=2026-11-10T07:00+00:00, prior8high=0.190100, depth_time=2026-11-10T07:00:22+00:00, book20_bid_proxy_usdt=32478, book20_ask_proxy_usdt=36713, funding_indicative=0.000086, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.71%, turnover=5562227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T07:00:02+00:00, last15m_closed_end=2026-11-10T07:00+00:00, prior8high=192.660000, depth_time=2026-11-10T07:00:17+00:00, book20_bid_proxy_usdt=52158, book20_ask_proxy_usdt=142474, funding_indicative=-0.000151, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.56%, turnover=34137971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T07:00:01+00:00, last15m_closed_end=2026-11-10T07:00+00:00, prior8high=1165.460000, depth_time=2026-11-10T07:00:13+00:00, book20_bid_proxy_usdt=408712, book20_ask_proxy_usdt=173840, funding_indicative=0.000063, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.15%, turnover=2345272321. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
