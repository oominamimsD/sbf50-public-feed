# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T05:45:17Z**
- feed_generated_utc: 2026-11-11T05:45:18+00:00
- source_sha256: `46fe1b59558c460ec124c39d7fc2909ccd31a6f4882d8439229df452b9928475`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T05:45+00:00, close=73828.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T05:00+00:00, close=73703.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T04:00+00:00, close=73740.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1016.630000|-7.01|-15.54|-7.89|2190656454|1.48|
|UNI_USDT|6.645000|-2.70|-9.62|-3.58|36676267|1.50|
|VVV_USDT|19.148000|-0.47|-14.36|-1.35|5414320|2.61|
|QNT_USDT|180.350000|-0.19|-7.71|-1.07|45778653|1.66|
|HBAR_USDT|0.065650|-0.19|-6.25|-1.07|7502525|1.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|HBAR_USDT|0.065650|0.065430|0.065660|0.12|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|180.350000|179.480000|180.350000|1.01|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.645000|6.629000|6.645000|0.69|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.148000|19.006000|19.148000|0.99|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1016.630000|1002.510000|1016.920000|0.88|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- HBAR_USDT: quote_utc=2026-11-11T05:45:01+00:00, last15m_closed_end=2026-11-11T05:45+00:00, prior8high=0.066160, depth_time=2026-11-11T05:45:13+00:00, book20_bid_proxy_usdt=678997, book20_ask_proxy_usdt=783796, funding_indicative=-0.000013, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.19%, turnover=7502525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T05:45:01+00:00, last15m_closed_end=2026-11-11T05:45+00:00, prior8high=181.640000, depth_time=2026-11-11T05:45:13+00:00, book20_bid_proxy_usdt=77490, book20_ask_proxy_usdt=87119, funding_indicative=-0.000095, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.19%, turnover=45778653. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T05:45:01+00:00, last15m_closed_end=2026-11-11T05:45+00:00, prior8high=6.736000, depth_time=2026-11-11T05:45:08+00:00, book20_bid_proxy_usdt=3123057, book20_ask_proxy_usdt=1866043, funding_indicative=0.000030, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=36676267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T05:45:01+00:00, last15m_closed_end=2026-11-11T05:45+00:00, prior8high=19.473000, depth_time=2026-11-11T05:45:12+00:00, book20_bid_proxy_usdt=49006, book20_ask_proxy_usdt=13167, funding_indicative=0.000050, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.47%, turnover=5414320. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T05:45:01+00:00, last15m_closed_end=2026-11-11T05:45+00:00, prior8high=1035.400000, depth_time=2026-11-11T05:45:07+00:00, book20_bid_proxy_usdt=242238, book20_ask_proxy_usdt=1710309, funding_indicative=0.000093, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.01%, turnover=2190656454. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
