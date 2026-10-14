# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T02:00:12Z**
- feed_generated_utc: 2026-10-14T02:00:14+00:00
- source_sha256: `e10a096d5d129d71aea018a288e40cd131b67ac32e36ce67adc04568c5f4ec90`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T02:00+00:00, close=83281.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T02:00+00:00, close=83281.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T00:00+00:00, close=83125.7, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.058340|-17.36|33.50|-17.21|23959234|1.71|
|OGN_USDT|0.034320|-4.53|53.14|-4.38|5025715|2.91|
|MAGIC_USDT|0.116270|-2.00|70.68|-1.85|7307434|2.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.116270|0.115510|0.116380|0.87|N|Y/Y|N/N|N|N|
|OGN_USDT|0.034320|0.034090|0.034320|0.27|N|Y/Y|Y/N|N|N|
|S_USDT|0.058340|0.056970|0.058340|0.84|N|N/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T02:00:02+00:00, last15m_closed_end=2026-10-14T02:00+00:00, prior8high=0.123950, depth_time=2026-10-14T02:00:12+00:00, book20_bid_proxy_usdt=173191, book20_ask_proxy_usdt=176770, funding_indicative=-0.000061, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.00%, turnover=7307434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OGN_USDT: quote_utc=2026-10-14T02:00:02+00:00, last15m_closed_end=2026-10-14T02:00+00:00, prior8high=0.035070, depth_time=2026-10-14T02:00:07+00:00, book20_bid_proxy_usdt=164916, book20_ask_proxy_usdt=165908, funding_indicative=-0.000148, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.53%, turnover=5025715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T02:00:02+00:00, last15m_closed_end=2026-10-14T02:00+00:00, prior8high=0.058510, depth_time=2026-10-14T02:00:06+00:00, book20_bid_proxy_usdt=78953, book20_ask_proxy_usdt=49385, funding_indicative=-0.000082, next_funding_utc=2026-10-14T04:00:00+00:00, funding_cycle_h=4, 24h_change=-17.36%, turnover=23959234. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
