# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T19:45:17Z**
- feed_generated_utc: 2026-11-03T19:45:19+00:00
- source_sha256: `7bd6e0e6a1931790543c0a756353b1f333e66a01474145e897daff8454b0f6ba`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T19:45+00:00, close=77575.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T19:00+00:00, close=77569.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003901|-6.13|-81.53|-6.03|13412699|2.56|
|QNT_USDT|190.990000|-2.26|-3.48|-2.16|58041967|1.57|
|TRUMPOFFICIAL_USDT|1.578000|-1.86|-6.51|-1.76|6215726|6.34|
|XPL_USDT|0.062970|-1.68|-14.69|-1.58|9769415|3.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003901|0.003757|0.003898|0.47|N|Y/Y|Y/Y|N|N|
|QNT_USDT|190.990000|190.580000|190.990000|0.75|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.578000|1.574000|1.578000|0.63|N|Y/Y|Y/Y|N|N|
|XPL_USDT|0.062970|0.063120|0.062970|0.74|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T19:45:03+00:00, last15m_closed_end=2026-11-03T19:45+00:00, prior8high=0.004084, depth_time=2026-11-03T19:45:08+00:00, book20_bid_proxy_usdt=64702, book20_ask_proxy_usdt=48585, funding_indicative=-0.000495, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.13%, turnover=13412699. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T19:45:03+00:00, last15m_closed_end=2026-11-03T19:45+00:00, prior8high=195.440000, depth_time=2026-11-03T19:45:11+00:00, book20_bid_proxy_usdt=122628, book20_ask_proxy_usdt=102409, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=58041967. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T19:45:03+00:00, last15m_closed_end=2026-11-03T19:45+00:00, prior8high=1.592000, depth_time=2026-11-03T19:45:12+00:00, book20_bid_proxy_usdt=1885450, book20_ask_proxy_usdt=1940309, funding_indicative=0.000042, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=6215726. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T19:45:03+00:00, last15m_closed_end=2026-11-03T19:45+00:00, prior8high=0.064140, depth_time=2026-11-03T19:45:16+00:00, book20_bid_proxy_usdt=349680, book20_ask_proxy_usdt=579117, funding_indicative=0.000050, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=9769415. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
