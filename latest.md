# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T22:00:15Z**
- feed_generated_utc: 2026-11-09T22:00:16+00:00
- source_sha256: `5578d7975ede014173e1615c4965878a0affec3313e5fcae6c386631f2ccda68`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T22:00+00:00, close=75004.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T22:00+00:00, close=75004.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1174.440000|-4.18|-6.35|-3.53|2598906535|0.17|
|DOT_USDT|0.860500|-3.41|-7.87|-2.76|12651888|1.16|
|QNT_USDT|194.950000|-2.54|-3.70|-1.89|45498523|1.54|
|SOL_USDT|86.430000|-1.66|-7.57|-1.01|848735332|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|0.860500|0.859200|0.860500|0.23|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.950000|194.710000|195.100000|0.66|N|Y/Y|Y/N|Y|N|
|SOL_USDT|86.430000|86.220000|86.430000|0.49|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1174.440000|1162.360000|1174.450000|0.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-11-09T21:59:59+00:00, last15m_closed_end=2026-11-09T22:00+00:00, prior8high=0.870800, depth_time=2026-11-09T22:00:08+00:00, book20_bid_proxy_usdt=749242, book20_ask_proxy_usdt=725093, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.41%, turnover=12651888. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-09T21:59:59+00:00, last15m_closed_end=2026-11-09T22:00+00:00, prior8high=197.230000, depth_time=2026-11-09T22:00:12+00:00, book20_bid_proxy_usdt=60350, book20_ask_proxy_usdt=66514, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=45498523. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T21:59:59+00:00, last15m_closed_end=2026-11-09T22:00+00:00, prior8high=87.040000, depth_time=2026-11-09T22:00:14+00:00, book20_bid_proxy_usdt=14012475, book20_ask_proxy_usdt=17340184, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.66%, turnover=848735332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T21:59:59+00:00, last15m_closed_end=2026-11-09T22:00+00:00, prior8high=1186.440000, depth_time=2026-11-09T22:00:07+00:00, book20_bid_proxy_usdt=199360, book20_ask_proxy_usdt=205149, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.18%, turnover=2598906535. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
