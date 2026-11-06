# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T22:00:14Z**
- feed_generated_utc: 2026-11-06T22:00:16+00:00
- source_sha256: `2f7aecb240f91622192c71b43a92d807a06dcacc36c7502451231676526b49e7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T22:00+00:00, close=75895.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T22:00+00:00, close=75895.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.135900|-28.47|-48.83|-28.55|32769661|7.34|
|ANTHROPIC_USDT|1353.470000|-5.43|-19.26|-5.51|6478819|3.10|
|PUMPFUN_USDT|0.003954|-2.24|-3.72|-2.32|11589375|2.53|
|LIT_USDT|3.344000|-1.42|18.40|-1.50|9885253|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1353.470000|1309.270000|1353.340000|0.73|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.344000|3.273100|3.345400|0.50|N|Y/Y|Y/N|Y|N|
|PUMPFUN_USDT|0.003954|0.003935|0.003956|0.38|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.135900|0.119800|0.136000|0.83|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T22:00:03+00:00, last15m_closed_end=2026-11-06T22:00+00:00, prior8high=1364.300000, depth_time=2026-11-06T22:00:05+00:00, book20_bid_proxy_usdt=34588, book20_ask_proxy_usdt=27648, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.43%, turnover=6478819. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T22:00:03+00:00, last15m_closed_end=2026-11-06T22:00+00:00, prior8high=3.346900, depth_time=2026-11-06T22:00:13+00:00, book20_bid_proxy_usdt=41252, book20_ask_proxy_usdt=30162, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.42%, turnover=9885253. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-06T22:00:03+00:00, last15m_closed_end=2026-11-06T22:00+00:00, prior8high=0.004011, depth_time=2026-11-06T22:00:11+00:00, book20_bid_proxy_usdt=2314722, book20_ask_proxy_usdt=2056897, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=11589375. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T22:00:03+00:00, last15m_closed_end=2026-11-06T22:00+00:00, prior8high=0.149300, depth_time=2026-11-06T22:00:07+00:00, book20_bid_proxy_usdt=147944, book20_ask_proxy_usdt=116816, funding_indicative=-0.000006, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-28.47%, turnover=32769661. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
