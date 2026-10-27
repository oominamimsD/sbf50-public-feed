# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T01:30:22Z**
- feed_generated_utc: 2026-10-27T01:30:25+00:00
- source_sha256: `d32d7e51703622760f97c03570f7f2525f4c9ecdef3064d4ffddac383cfb6bec`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T01:30+00:00, close=80147.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T01:00+00:00, close=80194.2, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.623300|-4.90|-14.65|-4.59|5396132|0.62|
|QNT_USDT|202.080000|-3.89|3.26|-3.58|121322933|4.95|
|BTW_USDT|1.165100|-2.55|-33.49|-2.24|21046572|1.72|
|DOT_USDT|1.000000|-2.21|-12.80|-1.90|10794593|2.00|
|NEAR_USDT|4.474000|-2.16|-8.76|-1.85|111052675|2.23|
|LINK_USDT|11.362000|-1.43|-4.86|-1.12|103759939|0.88|
|FILECOIN_USDT|0.907500|-1.43|-10.32|-1.12|6578834|3.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.165100|1.168300|1.165100|0.87|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.000000|1.003700|1.000000|3.46|Y|Y/Y|Y/Y|Y|Y|
|FILECOIN_USDT|0.907500|0.900800|0.907500|0.23|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.362000|11.298000|11.362000|1.34|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.474000|4.459000|4.475000|1.59|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|202.080000|200.610000|202.080000|2.15|N|Y/N|N/N|Y|N|
|ZRO_USDT|1.623300|1.615600|1.623300|1.43|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-27T01:29:59+00:00, last15m_closed_end=2026-10-27T01:30+00:00, prior8high=1.229000, depth_time=2026-10-27T01:30:12+00:00, book20_bid_proxy_usdt=13941, book20_ask_proxy_usdt=17570, funding_indicative=-0.000258, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.55%, turnover=21046572. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T01:29:59+00:00, last15m_closed_end=2026-10-27T01:30+00:00, prior8high=1.013800, depth_time=2026-10-27T01:30:14+00:00, book20_bid_proxy_usdt=347742, book20_ask_proxy_usdt=343873, funding_indicative=-0.000118, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=10794593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T01:30:00+00:00, last15m_closed_end=2026-10-27T01:30+00:00, prior8high=0.916600, depth_time=2026-10-27T01:30:21+00:00, book20_bid_proxy_usdt=1018884, book20_ask_proxy_usdt=1361825, funding_indicative=0.000019, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=6578834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T01:29:59+00:00, last15m_closed_end=2026-10-27T01:30+00:00, prior8high=11.421000, depth_time=2026-10-27T01:30:19+00:00, book20_bid_proxy_usdt=430568, book20_ask_proxy_usdt=551890, funding_indicative=0.000074, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=103759939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T01:29:59+00:00, last15m_closed_end=2026-10-27T01:30+00:00, prior8high=4.536000, depth_time=2026-10-27T01:30:16+00:00, book20_bid_proxy_usdt=351800, book20_ask_proxy_usdt=2757966, funding_indicative=-0.000094, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=111052675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T01:29:59+00:00, last15m_closed_end=2026-10-27T01:30+00:00, prior8high=204.430000, depth_time=2026-10-27T01:30:09+00:00, book20_bid_proxy_usdt=44147, book20_ask_proxy_usdt=89587, funding_indicative=0.000100, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.89%, turnover=121322933. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T01:30:00+00:00, last15m_closed_end=2026-10-27T01:30+00:00, prior8high=1.647700, depth_time=2026-10-27T01:30:08+00:00, book20_bid_proxy_usdt=20099, book20_ask_proxy_usdt=43432, funding_indicative=-0.000190, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.90%, turnover=5396132. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
