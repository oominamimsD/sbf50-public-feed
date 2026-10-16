# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T10:30:13Z**
- feed_generated_utc: 2026-10-16T10:30:14+00:00
- source_sha256: `c73b81e330b6c21c33cff861c1d91253ff5d937ec15097c6dbe81e7ea92ef03f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T10:30+00:00, close=81993.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T10:00+00:00, close=81985.9, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.077310|-19.76|28.50|-19.30|43789742|1.29|
|AKE_USDT|0.029969|-5.17|3.25|-4.71|19964877|1.00|
|NIL_USDT|0.084050|-3.25|-2.93|-2.79|6221802|1.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.029969|0.028483|0.029969|0.62|N|Y/Y|N/N|Y|N|
|NIL_USDT|0.084050|0.081680|0.084050|1.31|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.077310|0.077350|0.077310|1.25|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T10:29:59+00:00, last15m_closed_end=2026-10-16T10:30+00:00, prior8high=0.031827, depth_time=2026-10-16T10:30:09+00:00, book20_bid_proxy_usdt=13163, book20_ask_proxy_usdt=9700, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.17%, turnover=19964877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T10:30:00+00:00, last15m_closed_end=2026-10-16T10:30+00:00, prior8high=0.083960, depth_time=2026-10-16T10:30:11+00:00, book20_bid_proxy_usdt=24131, book20_ask_proxy_usdt=28236, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.25%, turnover=6221802. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T10:29:59+00:00, last15m_closed_end=2026-10-16T10:30+00:00, prior8high=0.079570, depth_time=2026-10-16T10:30:08+00:00, book20_bid_proxy_usdt=245146, book20_ask_proxy_usdt=411352, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.76%, turnover=43789742. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
