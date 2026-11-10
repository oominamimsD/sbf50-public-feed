# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T16:45:28Z**
- feed_generated_utc: 2026-11-10T16:45:30+00:00
- source_sha256: `785e63487fe6540b4d74a748669a39d6f3cc8ed053308653104cffa13f15874f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T16:45+00:00, close=73119.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.873100|-7.55|59.35|-7.47|10735805|2.67|
|ZEC_USDT|1030.610000|-5.73|-14.38|-5.65|2408380085|0.10|
|DASH_USDT|44.020000|-2.48|-4.59|-2.40|13831139|2.27|
|ARB_USDT|0.158610|-1.71|-0.79|-1.63|41364472|0.63|
|ANTHROPIC_USDT|1296.420000|-1.60|-22.55|-1.52|7815338|2.01|
|NEAR_USDT|3.506000|-1.54|-9.14|-1.46|39275527|2.85|
|UNI_USDT|6.736000|-1.37|-8.39|-1.29|25521266|1.48|
|ONDO_USDT|0.361000|-1.31|-7.24|-1.23|16826433|2.77|
|QNT_USDT|178.660000|-1.12|-8.57|-1.04|40816695|2.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1296.420000|1280.200000|1296.420000|0.27|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158610|0.158340|0.158660|2.03|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|44.020000|44.090000|44.020000|1.12|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.506000|3.501000|3.506000|2.03|N|Y/N|Y/Y|Y|N|
|ONDO_USDT|0.361000|0.360600|0.361000|2.99|N|Y/N|Y/N|Y|N|
|PIEVERSE_USDT|1.873100|1.890000|1.873100|2.49|Y|N/N|N/N|Y|N|
|QNT_USDT|178.660000|177.570000|178.680000|1.67|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.736000|6.727000|6.736000|3.99|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1030.610000|1047.610000|1030.610000|2.70|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-10T16:45:01+00:00, last15m_closed_end=2026-11-10T16:45+00:00, prior8high=1326.010000, depth_time=2026-11-10T16:45:16+00:00, book20_bid_proxy_usdt=10078, book20_ask_proxy_usdt=15231, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=7815338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T16:45:01+00:00, last15m_closed_end=2026-11-10T16:45+00:00, prior8high=0.166600, depth_time=2026-11-10T16:45:13+00:00, book20_bid_proxy_usdt=693948, book20_ask_proxy_usdt=42084, funding_indicative=-0.000098, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=41364472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T16:45:02+00:00, last15m_closed_end=2026-11-10T16:45+00:00, prior8high=47.390000, depth_time=2026-11-10T16:45:11+00:00, book20_bid_proxy_usdt=392322, book20_ask_proxy_usdt=460120, funding_indicative=-0.000003, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=13831139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-10T16:45:01+00:00, last15m_closed_end=2026-11-10T16:45+00:00, prior8high=3.760000, depth_time=2026-11-10T16:45:19+00:00, book20_bid_proxy_usdt=138778, book20_ask_proxy_usdt=1982494, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=39275527. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T16:45:01+00:00, last15m_closed_end=2026-11-10T16:45+00:00, prior8high=0.383600, depth_time=2026-11-10T16:45:25+00:00, book20_bid_proxy_usdt=1190726, book20_ask_proxy_usdt=3347895, funding_indicative=0.000002, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=16826433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T16:45:01+00:00, last15m_closed_end=2026-11-10T16:45+00:00, prior8high=2.084800, depth_time=2026-11-10T16:45:07+00:00, book20_bid_proxy_usdt=11933, book20_ask_proxy_usdt=18638, funding_indicative=0.000286, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.55%, turnover=10735805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T16:45:01+00:00, last15m_closed_end=2026-11-10T16:45+00:00, prior8high=186.060000, depth_time=2026-11-10T16:45:27+00:00, book20_bid_proxy_usdt=78302, book20_ask_proxy_usdt=55298, funding_indicative=-0.000088, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=40816695. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T16:45:01+00:00, last15m_closed_end=2026-11-10T16:45+00:00, prior8high=7.157000, depth_time=2026-11-10T16:45:21+00:00, book20_bid_proxy_usdt=1664996, book20_ask_proxy_usdt=1591651, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=25521266. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T16:45:01+00:00, last15m_closed_end=2026-11-10T16:45+00:00, prior8high=1198.440000, depth_time=2026-11-10T16:45:09+00:00, book20_bid_proxy_usdt=103087, book20_ask_proxy_usdt=110308, funding_indicative=-0.000001, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.73%, turnover=2408380085. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
