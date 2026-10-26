# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T19:45:18Z**
- feed_generated_utc: 2026-10-26T19:45:21+00:00
- source_sha256: `207fb31edeb94889d088692e1b1ec750f13cd03cfc894ef48631f5ee751a6054`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T19:45+00:00, close=80029.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T19:00+00:00, close=79961.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.114400|-6.79|-36.39|-6.34|20494730|5.38|
|IRYS_USDT|0.026230|-4.89|113.59|-4.44|9666020|7.62|
|LIT_USDT|3.043100|-2.41|0.36|-1.96|5130051|0.33|
|NEAR_USDT|4.493000|-1.74|-8.38|-1.29|120839320|2.23|
|DOT_USDT|1.007400|-1.48|-12.15|-1.03|10397688|0.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.114400|1.112800|1.114300|0.18|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.007400|0.999500|1.007400|0.81|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026230|0.026060|0.026230|0.63|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.043100|3.047500|3.043100|1.46|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.493000|4.442000|4.493000|0.84|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T19:45:00+00:00, last15m_closed_end=2026-10-26T19:45+00:00, prior8high=1.304000, depth_time=2026-10-26T19:45:08+00:00, book20_bid_proxy_usdt=24433, book20_ask_proxy_usdt=13239, funding_indicative=0.000050, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.79%, turnover=20494730. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T19:45:00+00:00, last15m_closed_end=2026-10-26T19:45+00:00, prior8high=1.017900, depth_time=2026-10-26T19:45:17+00:00, book20_bid_proxy_usdt=490696, book20_ask_proxy_usdt=538413, funding_indicative=0.000051, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=10397688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T19:45:00+00:00, last15m_closed_end=2026-10-26T19:45+00:00, prior8high=0.027470, depth_time=2026-10-26T19:45:11+00:00, book20_bid_proxy_usdt=77209, book20_ask_proxy_usdt=127598, funding_indicative=-0.000728, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=1, 24h_change=-4.89%, turnover=9666020. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T19:45:01+00:00, last15m_closed_end=2026-10-26T19:45+00:00, prior8high=3.150400, depth_time=2026-10-26T19:45:12+00:00, book20_bid_proxy_usdt=18335, book20_ask_proxy_usdt=20951, funding_indicative=0.000050, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.41%, turnover=5130051. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T19:45:00+00:00, last15m_closed_end=2026-10-26T19:45+00:00, prior8high=4.533000, depth_time=2026-10-26T19:45:15+00:00, book20_bid_proxy_usdt=5176733, book20_ask_proxy_usdt=4964439, funding_indicative=0.000095, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=120839320. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
