# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T23:00:14Z**
- feed_generated_utc: 2026-11-03T23:00:16+00:00
- source_sha256: `862a880956d631ec4f5d80598154ac0125421f967e498a4fe3dcc052150994ee`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T23:00+00:00, close=77859.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T23:00+00:00, close=77859.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003978|-3.18|-81.16|-3.45|13530858|5.03|
|QNT_USDT|192.780000|-1.35|-2.58|-1.62|57596272|0.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003978|0.003903|0.003978|0.31|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|192.780000|191.720000|192.770000|0.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T23:00:03+00:00, last15m_closed_end=2026-11-03T23:00+00:00, prior8high=0.004140, depth_time=2026-11-03T23:00:09+00:00, book20_bid_proxy_usdt=36104, book20_ask_proxy_usdt=29831, funding_indicative=-0.000836, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.18%, turnover=13530858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T23:00:03+00:00, last15m_closed_end=2026-11-03T23:00+00:00, prior8high=194.210000, depth_time=2026-11-03T23:00:12+00:00, book20_bid_proxy_usdt=56518, book20_ask_proxy_usdt=59349, funding_indicative=0.000060, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=57596272. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
