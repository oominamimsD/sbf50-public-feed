# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T20:00:10Z**
- feed_generated_utc: 2026-11-09T20:00:11+00:00
- source_sha256: `5f90dba4dfedcb321d0a5107b2a51a7f01aa7bbb5dc06623fe4fb7290060540d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1173.030000|-3.93|-6.46|-3.92|2461952494|0.09|
|ONE_USDT|0.001479|-1.96|32.55|-1.95|5020059|0.68|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ONE_USDT|0.001479|0.001442|0.001479|0.92|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1173.030000|1158.500000|1173.030000|0.96|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ONE_USDT: quote_utc=2026-11-09T20:00:00+00:00, last15m_closed_end=2026-11-09T20:00+00:00, prior8high=0.001494, depth_time=2026-11-09T20:00:09+00:00, book20_bid_proxy_usdt=14511, book20_ask_proxy_usdt=15994, funding_indicative=-0.000422, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=5020059. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T20:00:00+00:00, last15m_closed_end=2026-11-09T20:00+00:00, prior8high=1189.910000, depth_time=2026-11-09T20:00:07+00:00, book20_bid_proxy_usdt=690131, book20_ask_proxy_usdt=143732, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.93%, turnover=2461952494. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
