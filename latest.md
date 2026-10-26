# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T23:45:16Z**
- feed_generated_utc: 2026-10-26T23:45:19+00:00
- source_sha256: `2c2b3351b642d93b185b57d38495af2da5ad7e4424ae57f8b133132913a42267`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T23:45+00:00, close=80109.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T23:00+00:00, close=79977.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.627100|-4.68|-14.45|-4.32|5376785|1.23|
|LIT_USDT|3.011000|-3.44|-0.68|-3.08|5109729|0.33|
|BR_USDT|0.490000|-1.90|-20.45|-1.54|10337707|6.11|
|NEAR_USDT|4.495000|-1.70|-8.34|-1.34|114930530|2.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BR_USDT|0.490000|0.473800|0.490000|1.55|N|Y/Y|Y/N|Y|N|
|LIT_USDT|3.011000|2.980000|3.011000|0.41|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.495000|4.422000|4.494000|1.09|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.627100|1.610100|1.627100|0.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BR_USDT: quote_utc=2026-10-26T23:45:03+00:00, last15m_closed_end=2026-10-26T23:45+00:00, prior8high=0.487600, depth_time=2026-10-26T23:45:11+00:00, book20_bid_proxy_usdt=39183, book20_ask_proxy_usdt=41567, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.90%, turnover=10337707. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T23:45:03+00:00, last15m_closed_end=2026-10-26T23:45+00:00, prior8high=3.013800, depth_time=2026-10-26T23:45:09+00:00, book20_bid_proxy_usdt=27173, book20_ask_proxy_usdt=24029, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.44%, turnover=5109729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T23:45:02+00:00, last15m_closed_end=2026-10-26T23:45+00:00, prior8high=4.492000, depth_time=2026-10-26T23:45:15+00:00, book20_bid_proxy_usdt=3782160, book20_ask_proxy_usdt=3311807, funding_indicative=0.000048, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=114930530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-26T23:45:03+00:00, last15m_closed_end=2026-10-26T23:45+00:00, prior8high=1.643300, depth_time=2026-10-26T23:45:06+00:00, book20_bid_proxy_usdt=18379, book20_ask_proxy_usdt=55745, funding_indicative=0.000016, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.68%, turnover=5376785. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
