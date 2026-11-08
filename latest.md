# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T18:30:16Z**
- feed_generated_utc: 2026-11-08T18:30:17+00:00
- source_sha256: `4bf18b340cc6bb0f1ed1fdb5c55928f3864f93ed436968030a6fb08727c7edb8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T18:30+00:00, close=75877.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T18:00+00:00, close=75716, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001838|-6.12|57.83|-5.92|17571475|0.54|
|AKE_USDT|0.005215|-2.65|-43.06|-2.45|19292790|1.92|
|IDOL_USDT|0.030315|-1.76|54.08|-1.56|7560071|2.64|
|NEAR_USDT|3.641000|-1.62|-15.93|-1.42|31714543|2.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005215|0.005192|0.005215|1.54|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.030315|0.029412|0.030315|0.17|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.641000|3.586000|3.641000|2.89|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001838|0.001693|0.001839|0.55|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T18:30:03+00:00, last15m_closed_end=2026-11-08T18:30+00:00, prior8high=0.005344, depth_time=2026-11-08T18:30:10+00:00, book20_bid_proxy_usdt=42991, book20_ask_proxy_usdt=64278, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.65%, turnover=19292790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T18:30:03+00:00, last15m_closed_end=2026-11-08T18:30+00:00, prior8high=0.031558, depth_time=2026-11-08T18:30:12+00:00, book20_bid_proxy_usdt=7353, book20_ask_proxy_usdt=4177, funding_indicative=0.000878, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.76%, turnover=7560071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T18:30:03+00:00, last15m_closed_end=2026-11-08T18:30+00:00, prior8high=3.699000, depth_time=2026-11-08T18:30:15+00:00, book20_bid_proxy_usdt=2720720, book20_ask_proxy_usdt=3994415, funding_indicative=0.000085, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=31714543. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T18:30:03+00:00, last15m_closed_end=2026-11-08T18:30+00:00, prior8high=0.001957, depth_time=2026-11-08T18:30:07+00:00, book20_bid_proxy_usdt=14996, book20_ask_proxy_usdt=7693, funding_indicative=-0.001064, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.12%, turnover=17571475. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
