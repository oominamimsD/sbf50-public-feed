# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T20:15:19Z**
- feed_generated_utc: 2026-10-26T20:15:22+00:00
- source_sha256: `ae7cb0d587bc85dab63881850ecd3f712d69a65036d481b37f6e6fd2e5d2f689`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T20:15+00:00, close=79926.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.026000|-5.72|111.72|-5.14|9482762|3.85|
|BTW_USDT|1.136500|-4.95|-35.13|-4.37|20368694|2.65|
|LIT_USDT|3.027600|-2.90|-0.14|-2.32|5076295|0.33|
|PUMPFUN_USDT|0.004230|-2.26|-5.07|-1.68|22127671|2.36|
|NEAR_USDT|4.475000|-2.14|-8.74|-1.56|117678149|2.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.136500|1.103200|1.130600|0.34|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026000|0.026060|0.026000|1.51|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|3.027600|3.040000|3.027600|0.42|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.475000|4.442000|4.475000|0.94|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004230|0.004209|0.004229|0.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T20:15:03+00:00, last15m_closed_end=2026-10-26T20:15+00:00, prior8high=1.298000, depth_time=2026-10-26T20:15:11+00:00, book20_bid_proxy_usdt=16258, book20_ask_proxy_usdt=11089, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.95%, turnover=20368694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T20:15:03+00:00, last15m_closed_end=2026-10-26T20:15+00:00, prior8high=0.027140, depth_time=2026-10-26T20:15:09+00:00, book20_bid_proxy_usdt=87538, book20_ask_proxy_usdt=107052, funding_indicative=-0.000753, next_funding_utc=2026-10-26T21:00:00+00:00, funding_cycle_h=1, 24h_change=-5.72%, turnover=9482762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T20:15:03+00:00, last15m_closed_end=2026-10-26T20:15+00:00, prior8high=3.132600, depth_time=2026-10-26T20:15:13+00:00, book20_bid_proxy_usdt=16662, book20_ask_proxy_usdt=19586, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.90%, turnover=5076295. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T20:15:03+00:00, last15m_closed_end=2026-10-26T20:15+00:00, prior8high=4.530000, depth_time=2026-10-26T20:15:19+00:00, book20_bid_proxy_usdt=6147364, book20_ask_proxy_usdt=2983619, funding_indicative=0.000079, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=117678149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T20:15:03+00:00, last15m_closed_end=2026-10-26T20:15+00:00, prior8high=0.004291, depth_time=2026-10-26T20:15:16+00:00, book20_bid_proxy_usdt=1940102, book20_ask_proxy_usdt=1740413, funding_indicative=0.000049, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=22127671. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
