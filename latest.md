# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T21:45:10Z**
- feed_generated_utc: 2026-11-06T21:45:11+00:00
- source_sha256: `caf3015e85d942c91d541ef8e36075321822171cbe077e0f0517cf79ecbc26c9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T21:45+00:00, close=75794, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T21:00+00:00, close=75860, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ANTHROPIC_USDT|1343.750000|-6.11|-19.84|-6.06|6438082|1.94|
|LIT_USDT|3.316200|-2.24|17.42|-2.19|10585866|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ANTHROPIC_USDT|1343.750000|1309.270000|1343.750000|1.67|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.316200|3.268700|3.316200|0.22|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ANTHROPIC_USDT: quote_utc=2026-11-06T21:44:59+00:00, last15m_closed_end=2026-11-06T21:45+00:00, prior8high=1364.300000, depth_time=2026-11-06T21:45:06+00:00, book20_bid_proxy_usdt=20838, book20_ask_proxy_usdt=27157, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-6.11%, turnover=6438082. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T21:44:59+00:00, last15m_closed_end=2026-11-06T21:45+00:00, prior8high=3.346900, depth_time=2026-11-06T21:45:06+00:00, book20_bid_proxy_usdt=29896, book20_ask_proxy_usdt=27018, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=10585866. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
