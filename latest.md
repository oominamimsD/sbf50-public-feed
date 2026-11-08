# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T19:30:13Z**
- feed_generated_utc: 2026-11-08T19:30:13+00:00
- source_sha256: `ccca5eafa634dfa8a986e4c17bd6dc9144fe6a4cc2aa2dd4a20fc22fa089e295`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.01 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T19:30+00:00, close=75851.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T19:00+00:00, close=75913.5, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001790|-8.55|53.75|-8.31|16329332|0.56|
|AKE_USDT|0.005158|-3.71|-43.68|-3.47|18360623|3.88|
|ARB_USDT|0.166800|-1.82|0.37|-1.58|19077599|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005158|0.005112|0.005158|1.23|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.166800|0.166590|0.166780|0.58|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001790|0.001754|0.001791|0.44|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T19:29:59+00:00, last15m_closed_end=2026-11-08T19:30+00:00, prior8high=0.005317, depth_time=2026-11-08T19:30:09+00:00, book20_bid_proxy_usdt=44139, book20_ask_proxy_usdt=50904, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.71%, turnover=18360623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-08T19:29:59+00:00, last15m_closed_end=2026-11-08T19:30+00:00, prior8high=0.169110, depth_time=2026-11-08T19:30:11+00:00, book20_bid_proxy_usdt=86508, book20_ask_proxy_usdt=160870, funding_indicative=-0.000033, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=19077599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T19:29:59+00:00, last15m_closed_end=2026-11-08T19:30+00:00, prior8high=0.001846, depth_time=2026-11-08T19:30:06+00:00, book20_bid_proxy_usdt=10291, book20_ask_proxy_usdt=8422, funding_indicative=-0.000677, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.55%, turnover=16329332. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
