# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T14:30:26Z**
- feed_generated_utc: 2026-10-26T14:30:29+00:00
- source_sha256: `769eda9b8487cf79c444ccc96105cc98a564943c5c47dda1f1da82ac06b21e8d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1186; contracts: 1178; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T14:30+00:00, close=79839.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T14:00+00:00, close=79668.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.028090|-26.92|130.24|-25.96|11780830|3.56|
|APR_USDT|0.032580|-21.13|19.60|-20.17|5958365|3.07|
|BTW_USDT|1.324000|-20.18|-42.56|-19.22|11788464|3.03|
|BRL_USDT|0.182600|-8.79|-7.21|-7.83|5242504|5.48|
|WLD_USDT|0.439500|-3.74|-7.72|-2.78|61793979|2.27|
|LIT_USDT|3.076800|-3.19|4.99|-2.23|5191247|0.33|
|STRK_USDT|0.044780|-2.09|-27.25|-1.13|9527004|2.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.032580|0.031070|0.032580|1.01|N|Y/Y|N/N|Y|N|
|BRL_USDT|0.182600|0.179700|0.182600|1.80|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.324000|1.335600|1.324400|4.63|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.028090|0.027330|0.028090|0.85|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.076800|3.039700|3.076800|5.10|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044780|0.044200|0.044780|0.88|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.439500|0.435800|0.439700|1.55|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T14:30:00+00:00, last15m_closed_end=2026-10-26T14:30+00:00, prior8high=0.037130, depth_time=2026-10-26T14:30:12+00:00, book20_bid_proxy_usdt=27816, book20_ask_proxy_usdt=51218, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.13%, turnover=5958365. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BRL_USDT: quote_utc=2026-10-26T14:30:01+00:00, last15m_closed_end=2026-10-26T14:30+00:00, prior8high=0.183300, depth_time=2026-10-26T14:30:17+00:00, book20_bid_proxy_usdt=377437, book20_ask_proxy_usdt=380701, funding_indicative=-0.000116, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.79%, turnover=5242504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T14:30:00+00:00, last15m_closed_end=2026-10-26T14:30+00:00, prior8high=1.462300, depth_time=2026-10-26T14:30:15+00:00, book20_bid_proxy_usdt=8256, book20_ask_proxy_usdt=15378, funding_indicative=-0.016901, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.18%, turnover=11788464. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T14:30:00+00:00, last15m_closed_end=2026-10-26T14:30+00:00, prior8high=0.029430, depth_time=2026-10-26T14:30:10+00:00, book20_bid_proxy_usdt=68619, book20_ask_proxy_usdt=85678, funding_indicative=-0.000953, next_funding_utc=2026-10-26T15:00:00+00:00, funding_cycle_h=1, 24h_change=-26.92%, turnover=11780830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T14:30:00+00:00, last15m_closed_end=2026-10-26T14:30+00:00, prior8high=3.115900, depth_time=2026-10-26T14:30:23+00:00, book20_bid_proxy_usdt=30946, book20_ask_proxy_usdt=16371, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.19%, turnover=5191247. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T14:30:01+00:00, last15m_closed_end=2026-10-26T14:30+00:00, prior8high=0.044930, depth_time=2026-10-26T14:30:26+00:00, book20_bid_proxy_usdt=835318, book20_ask_proxy_usdt=629440, funding_indicative=0.000022, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=9527004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T14:30:00+00:00, last15m_closed_end=2026-10-26T14:30+00:00, prior8high=0.444700, depth_time=2026-10-26T14:30:20+00:00, book20_bid_proxy_usdt=2315374, book20_ask_proxy_usdt=2385076, funding_indicative=-0.000154, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=61793979. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
