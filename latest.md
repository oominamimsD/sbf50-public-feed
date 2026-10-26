# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T13:30:30Z**
- feed_generated_utc: 2026-10-26T13:30:33+00:00
- source_sha256: `0444b2fdfbdde29856c2b5e49bb43ef57e0e62002c8e959b855f124b3e5db9ae`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T13:30+00:00, close=79920.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T13:00+00:00, close=80301.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.027840|-27.57|128.19|-26.73|12292705|3.59|
|APR_USDT|0.033090|-19.89|21.47|-19.05|6439964|3.04|
|CAP_USDT|0.088580|-17.58|33.20|-16.74|7213085|5.65|
|BTW_USDT|1.415000|-14.70|-38.62|-13.86|11032405|3.53|
|WLD_USDT|0.437900|-4.09|-8.06|-3.25|60229156|2.28|
|LIT_USDT|3.056500|-3.83|4.30|-2.99|5117423|0.33|
|STRK_USDT|0.044380|-2.97|-27.90|-2.13|9401094|4.51|
|XMR_USDT|592.510000|-2.42|1.71|-1.58|5555529|0.17|
|DOT_USDT|1.016900|-2.14|-4.90|-1.30|8755092|0.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.033090|0.033190|0.033080|5.42|Y|Y/Y|N/N|Y|N|
|BTW_USDT|1.415000|1.395000|1.415200|1.49|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.088580|0.070960|0.088580|1.05|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.016900|1.013300|1.016900|0.31|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.027840|0.027970|0.027860|3.17|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|3.056500|3.057300|3.056500|1.49|Y|Y/Y|Y/Y|Y|Y|
|STRK_USDT|0.044380|0.044360|0.044380|0.97|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.437900|0.436400|0.437900|1.04|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|592.510000|588.800000|592.510000|0.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T13:29:59+00:00, last15m_closed_end=2026-10-26T13:30+00:00, prior8high=0.037130, depth_time=2026-10-26T13:30:12+00:00, book20_bid_proxy_usdt=8947, book20_ask_proxy_usdt=29100, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-19.89%, turnover=6439964. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T13:29:59+00:00, last15m_closed_end=2026-10-26T13:30+00:00, prior8high=1.516100, depth_time=2026-10-26T13:30:17+00:00, book20_bid_proxy_usdt=17397, book20_ask_proxy_usdt=19971, funding_indicative=-0.015764, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.70%, turnover=11032405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T13:29:59+00:00, last15m_closed_end=2026-10-26T13:30+00:00, prior8high=0.090830, depth_time=2026-10-26T13:30:14+00:00, book20_bid_proxy_usdt=48017, book20_ask_proxy_usdt=52689, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-17.58%, turnover=7213085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T13:29:59+00:00, last15m_closed_end=2026-10-26T13:30+00:00, prior8high=1.028300, depth_time=2026-10-26T13:30:29+00:00, book20_bid_proxy_usdt=219663, book20_ask_proxy_usdt=191787, funding_indicative=-0.000054, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=8755092. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T13:29:59+00:00, last15m_closed_end=2026-10-26T13:30+00:00, prior8high=0.029430, depth_time=2026-10-26T13:30:08+00:00, book20_bid_proxy_usdt=145213, book20_ask_proxy_usdt=97598, funding_indicative=-0.000672, next_funding_utc=2026-10-26T14:00:00+00:00, funding_cycle_h=1, 24h_change=-27.57%, turnover=12292705. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T13:29:59+00:00, last15m_closed_end=2026-10-26T13:30+00:00, prior8high=3.115900, depth_time=2026-10-26T13:30:22+00:00, book20_bid_proxy_usdt=19348, book20_ask_proxy_usdt=16837, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.83%, turnover=5117423. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T13:30:00+00:00, last15m_closed_end=2026-10-26T13:30+00:00, prior8high=0.044890, depth_time=2026-10-26T13:30:24+00:00, book20_bid_proxy_usdt=661033, book20_ask_proxy_usdt=570275, funding_indicative=0.000000, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.97%, turnover=9401094. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T13:29:59+00:00, last15m_closed_end=2026-10-26T13:30+00:00, prior8high=0.444700, depth_time=2026-10-26T13:30:19+00:00, book20_bid_proxy_usdt=2185590, book20_ask_proxy_usdt=2222223, funding_indicative=-0.000165, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.09%, turnover=60229156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T13:29:59+00:00, last15m_closed_end=2026-10-26T13:30+00:00, prior8high=594.610000, depth_time=2026-10-26T13:30:25+00:00, book20_bid_proxy_usdt=8466, book20_ask_proxy_usdt=19433, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=5555529. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
