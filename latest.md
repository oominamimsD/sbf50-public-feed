# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T16:45:14Z**
- feed_generated_utc: 2026-10-25T16:45:16+00:00
- source_sha256: `c98f6b273bedf840b6c57b55bb70d01cd7aeec8926aa0d522d42ba5186c0ee9d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T16:45+00:00, close=80570.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.597600|-3.69|-30.70|-3.65|13020944|1.88|
|IRYS_USDT|0.037620|-2.13|208.36|-2.09|23747574|2.66|
|STRK_USDT|0.045260|-1.04|-26.47|-1.00|10456983|2.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.597600|1.557100|1.597600|0.93|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.037620|0.034410|0.037640|0.79|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045260|0.044670|0.045260|1.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-25T16:45:01+00:00, last15m_closed_end=2026-10-25T16:45+00:00, prior8high=1.699100, depth_time=2026-10-25T16:45:08+00:00, book20_bid_proxy_usdt=9402, book20_ask_proxy_usdt=10055, funding_indicative=-0.007487, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.69%, turnover=13020944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T16:45:00+00:00, last15m_closed_end=2026-10-25T16:45+00:00, prior8high=0.039980, depth_time=2026-10-25T16:45:10+00:00, book20_bid_proxy_usdt=35349, book20_ask_proxy_usdt=37287, funding_indicative=-0.000168, next_funding_utc=2026-10-25T17:00:00+00:00, funding_cycle_h=1, 24h_change=-2.13%, turnover=23747574. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T16:45:01+00:00, last15m_closed_end=2026-10-25T16:45+00:00, prior8high=0.046020, depth_time=2026-10-25T16:45:13+00:00, book20_bid_proxy_usdt=1010748, book20_ask_proxy_usdt=819820, funding_indicative=0.000034, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=10456983. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
