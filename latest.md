# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T17:00:17Z**
- feed_generated_utc: 2026-10-23T17:00:23+00:00
- source_sha256: `b8f0738ed8dd413b03fb627d62546bd9af4a45cb9eb310f7780f4134cdbb0910`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.11 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T17:00+00:00, close=81682.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T17:00+00:00, close=81682.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T16:00+00:00, close=81651.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INJ_USDT|7.789000|-1.11|-13.24|-1.13|24215001|1.28|
|ZRO_USDT|1.797400|-1.10|-14.46|-1.12|6577749|2.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|INJ_USDT|7.789000|7.775000|7.789000|1.41|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.797400|1.789300|1.797400|0.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- INJ_USDT: quote_utc=2026-10-23T17:00:03+00:00, last15m_closed_end=2026-10-23T17:00+00:00, prior8high=7.937000, depth_time=2026-10-23T17:00:12+00:00, book20_bid_proxy_usdt=284762, book20_ask_proxy_usdt=274902, funding_indicative=0.000120, next_funding_utc=2026-10-24T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.11%, turnover=24215001. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-23T17:00:03+00:00, last15m_closed_end=2026-10-23T17:00+00:00, prior8high=1.835500, depth_time=2026-10-23T17:00:16+00:00, book20_bid_proxy_usdt=41601, book20_ask_proxy_usdt=41973, funding_indicative=0.000035, next_funding_utc=2026-10-23T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=6577749. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
