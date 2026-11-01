# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T09:00:23Z**
- feed_generated_utc: 2026-11-01T09:00:24+00:00
- source_sha256: `17cf02e2d67ebd54fc5a38b850ba0005e6825522b79108419a071373cf02ee25`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T09:00+00:00, close=78217.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T09:00+00:00, close=78217.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T08:00+00:00, close=77928.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.227750|-23.09|35.63|-23.93|31139786|2.20|
|AKE_USDT|0.009055|-17.35|-69.02|-18.19|9120640|2.21|
|BLESS_USDT|0.009517|-10.73|17.30|-11.57|5976682|1.05|
|XPL_USDT|0.074710|-7.01|3.46|-7.85|6817170|2.68|
|ZEC_USDT|1253.290000|-2.43|9.43|-3.27|939728948|0.08|
|NEAR_USDT|4.400000|-1.69|-0.04|-2.53|53557271|2.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009055|0.008738|0.009055|2.58|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009517|0.009395|0.009517|0.85|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.227750|0.219110|0.227750|1.05|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.400000|4.356000|4.400000|1.08|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.074710|0.072930|0.074720|1.92|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1253.290000|1239.270000|1253.290000|1.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T09:00:00+00:00, last15m_closed_end=2026-11-01T09:00+00:00, prior8high=0.009684, depth_time=2026-11-01T09:00:11+00:00, book20_bid_proxy_usdt=9158, book20_ask_proxy_usdt=9565, funding_indicative=-0.002838, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.35%, turnover=9120640. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T09:00:00+00:00, last15m_closed_end=2026-11-01T09:00+00:00, prior8high=0.009599, depth_time=2026-11-01T09:00:13+00:00, book20_bid_proxy_usdt=15566, book20_ask_proxy_usdt=11820, funding_indicative=0.000071, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.73%, turnover=5976682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T08:59:59+00:00, last15m_closed_end=2026-11-01T09:00+00:00, prior8high=0.238280, depth_time=2026-11-01T09:00:09+00:00, book20_bid_proxy_usdt=9672, book20_ask_proxy_usdt=5432, funding_indicative=-0.002427, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-23.09%, turnover=31139786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T08:59:59+00:00, last15m_closed_end=2026-11-01T09:00+00:00, prior8high=4.396000, depth_time=2026-11-01T09:00:22+00:00, book20_bid_proxy_usdt=3834959, book20_ask_proxy_usdt=2585247, funding_indicative=0.000100, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=53557271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T09:00:00+00:00, last15m_closed_end=2026-11-01T09:00+00:00, prior8high=0.074940, depth_time=2026-11-01T09:00:16+00:00, book20_bid_proxy_usdt=365433, book20_ask_proxy_usdt=348695, funding_indicative=0.000050, next_funding_utc=2026-11-01T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.01%, turnover=6817170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T08:59:59+00:00, last15m_closed_end=2026-11-01T09:00+00:00, prior8high=1253.260000, depth_time=2026-11-01T09:00:18+00:00, book20_bid_proxy_usdt=490094, book20_ask_proxy_usdt=391960, funding_indicative=-0.000061, next_funding_utc=2026-11-01T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=939728948. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
