# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T19:15:17Z**
- feed_generated_utc: 2026-10-26T19:15:20+00:00
- source_sha256: `cef62a0c711011e31f29b79819ccee3c3423b7eb0433bac08a91795352d958de`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T19:15+00:00, close=80068.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T19:00+00:00, close=79961.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.138900|-4.75|-34.99|-4.34|20278110|0.88|
|IRYS_USDT|0.026530|-3.80|116.04|-3.39|9595497|3.77|
|NEAR_USDT|4.470000|-2.25|-8.84|-1.84|118469881|2.24|
|LIT_USDT|3.071700|-1.49|1.31|-1.08|5010429|0.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.138900|0.894600|1.145400|0.37|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026530|0.026060|0.026530|0.28|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.071700|3.049400|3.071700|0.66|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.470000|4.453000|4.470000|0.99|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T19:15:03+00:00, last15m_closed_end=2026-10-26T19:15+00:00, prior8high=1.304000, depth_time=2026-10-26T19:15:08+00:00, book20_bid_proxy_usdt=9561, book20_ask_proxy_usdt=12885, funding_indicative=0.000050, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.75%, turnover=20278110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T19:15:03+00:00, last15m_closed_end=2026-10-26T19:15+00:00, prior8high=0.027470, depth_time=2026-10-26T19:15:10+00:00, book20_bid_proxy_usdt=78331, book20_ask_proxy_usdt=121337, funding_indicative=-0.000620, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=1, 24h_change=-3.80%, turnover=9595497. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T19:15:03+00:00, last15m_closed_end=2026-10-26T19:15+00:00, prior8high=3.150400, depth_time=2026-10-26T19:15:16+00:00, book20_bid_proxy_usdt=23260, book20_ask_proxy_usdt=19906, funding_indicative=0.000050, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.49%, turnover=5010429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T19:15:03+00:00, last15m_closed_end=2026-10-26T19:15+00:00, prior8high=4.569000, depth_time=2026-10-26T19:15:14+00:00, book20_bid_proxy_usdt=3171542, book20_ask_proxy_usdt=4519832, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=118469881. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
