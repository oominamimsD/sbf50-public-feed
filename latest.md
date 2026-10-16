# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T07:00:12Z**
- feed_generated_utc: 2026-10-16T07:00:14+00:00
- source_sha256: `f16d26e64b0f1ecb80f67dc744212a20d34ab0332635a42f7471e8bfad2a6d08`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T07:00+00:00, close=82146.4, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T07:00+00:00, close=82146.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEREBRO_USDT|0.042852|-8.89|56.06|-8.60|6730144|6.51|
|NIL_USDT|0.085590|-3.91|-1.15|-3.62|9058903|1.17|
|AKE_USDT|0.030545|-3.35|5.24|-3.06|20908093|1.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030545|0.030300|0.030545|0.71|N|Y/Y|N/N|Y|N|
|NIL_USDT|0.085590|0.085330|0.085560|0.86|N|Y/N|N/N|Y|N|
|ZEREBRO_USDT|0.042852|0.038850|0.042852|1.00|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T07:00:02+00:00, last15m_closed_end=2026-10-16T07:00+00:00, prior8high=0.033159, depth_time=2026-10-16T07:00:12+00:00, book20_bid_proxy_usdt=10676, book20_ask_proxy_usdt=11694, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.35%, turnover=20908093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T07:00:02+00:00, last15m_closed_end=2026-10-16T07:00+00:00, prior8high=0.088380, depth_time=2026-10-16T07:00:09+00:00, book20_bid_proxy_usdt=22771, book20_ask_proxy_usdt=16335, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.91%, turnover=9058903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T07:00:02+00:00, last15m_closed_end=2026-10-16T07:00+00:00, prior8high=0.044310, depth_time=2026-10-16T07:00:07+00:00, book20_bid_proxy_usdt=24434, book20_ask_proxy_usdt=5798, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.89%, turnover=6730144. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
