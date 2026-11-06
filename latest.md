# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T10:15:15Z**
- feed_generated_utc: 2026-11-06T10:15:16+00:00
- source_sha256: `b2e805f7fa271c3dc3024a7904b6b261e34a31bc2625227fc1cf2b32dc1e12e9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1197; contracts: 1189; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T10:15+00:00, close=76145.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T10:00+00:00, close=76151.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|XRP_USDT|1.197800|-3.76|-8.52|-3.93|474731207|0.83|
|BCH_USDT|268.710000|-3.72|-6.78|-3.89|7386551|3.35|
|XPL_USDT|0.057680|-1.53|-26.92|-1.70|12125700|1.73|
|QNT_USDT|189.360000|-1.28|-4.71|-1.45|36051823|3.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|268.710000|263.610000|268.710000|1.96|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.360000|188.370000|189.360000|1.25|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057680|0.057290|0.057680|2.59|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.197800|1.183400|1.197800|1.21|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T10:14:59+00:00, last15m_closed_end=2026-11-06T10:15+00:00, prior8high=269.270000, depth_time=2026-11-06T10:15:09+00:00, book20_bid_proxy_usdt=50342, book20_ask_proxy_usdt=91429, funding_indicative=-0.000037, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=7386551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T10:14:59+00:00, last15m_closed_end=2026-11-06T10:15+00:00, prior8high=190.420000, depth_time=2026-11-06T10:15:13+00:00, book20_bid_proxy_usdt=85772, book20_ask_proxy_usdt=99124, funding_indicative=0.000031, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=36051823. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T10:14:59+00:00, last15m_closed_end=2026-11-06T10:15+00:00, prior8high=0.057950, depth_time=2026-11-06T10:15:11+00:00, book20_bid_proxy_usdt=479863, book20_ask_proxy_usdt=444912, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=12125700. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T10:14:59+00:00, last15m_closed_end=2026-11-06T10:15+00:00, prior8high=1.201000, depth_time=2026-11-06T10:15:07+00:00, book20_bid_proxy_usdt=3385267, book20_ask_proxy_usdt=3207118, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.76%, turnover=474731207. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
