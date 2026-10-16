# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T15:00:16Z**
- feed_generated_utc: 2026-10-16T15:00:18+00:00
- source_sha256: `31bcddbcfd3acea2b10b2c4e32149cbda4d75e35ffe1d47f77d03e81ec18d069`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T15:00+00:00, close=81943.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T15:00+00:00, close=81943.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.076320|-10.29|26.86|-9.74|37897409|2.62|
|AKE_USDT|0.028619|-2.67|-1.39|-2.12|13977291|6.29|
|PEPE_USDT|0.000004|-2.63|8.17|-2.08|100041315|0.25|
|UNI_USDT|7.360000|-2.45|0.58|-1.90|14869863|1.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028619|0.028589|0.028619|0.77|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.78|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.076320|0.075410|0.076320|0.80|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.360000|7.361000|7.363000|2.43|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T15:00:01+00:00, last15m_closed_end=2026-10-16T15:00+00:00, prior8high=0.029768, depth_time=2026-10-16T15:00:10+00:00, book20_bid_proxy_usdt=15189, book20_ask_proxy_usdt=23318, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=13977291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-16T15:00:01+00:00, last15m_closed_end=2026-10-16T15:00+00:00, prior8high=0.000004, depth_time=2026-10-16T15:00:13+00:00, book20_bid_proxy_usdt=62798, book20_ask_proxy_usdt=61496, funding_indicative=0.000067, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.63%, turnover=100041315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T15:00:01+00:00, last15m_closed_end=2026-10-16T15:00+00:00, prior8high=0.077680, depth_time=2026-10-16T15:00:08+00:00, book20_bid_proxy_usdt=208302, book20_ask_proxy_usdt=295819, funding_indicative=-0.000026, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.29%, turnover=37897409. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-16T15:00:01+00:00, last15m_closed_end=2026-10-16T15:00+00:00, prior8high=7.457000, depth_time=2026-10-16T15:00:15+00:00, book20_bid_proxy_usdt=1477405, book20_ask_proxy_usdt=1643595, funding_indicative=-0.000011, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=14869863. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
