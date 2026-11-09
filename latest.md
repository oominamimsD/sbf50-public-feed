# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T21:00:12Z**
- feed_generated_utc: 2026-11-09T21:00:13+00:00
- source_sha256: `77429fe74b6d497e5c6222391e525dee3c0cc37cefccc50c913482a693ee2002`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T21:00+00:00, close=74845.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T21:00+00:00, close=74845.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T20:00+00:00, close=74856.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ON_USDT|0.166000|-16.58|-2.06|-15.71|5164556|6.02|
|ZEC_USDT|1167.020000|-4.42|-6.94|-3.55|2504648393|0.09|
|QNT_USDT|195.930000|-2.05|-3.22|-1.18|43699339|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ON_USDT|0.166000|0.161100|0.166000|0.47|N|Y/Y|Y/N|Y|N|
|QNT_USDT|195.930000|194.710000|196.090000|0.74|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1167.020000|1161.730000|1167.100000|0.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ON_USDT: quote_utc=2026-11-09T21:00:00+00:00, last15m_closed_end=2026-11-09T21:00+00:00, prior8high=0.171800, depth_time=2026-11-09T21:00:07+00:00, book20_bid_proxy_usdt=50347, book20_ask_proxy_usdt=66309, funding_indicative=0.000050, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=4, 24h_change=-16.58%, turnover=5164556. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-09T21:00:00+00:00, last15m_closed_end=2026-11-09T21:00+00:00, prior8high=197.510000, depth_time=2026-11-09T21:00:10+00:00, book20_bid_proxy_usdt=71806, book20_ask_proxy_usdt=30570, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=43699339. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T21:00:00+00:00, last15m_closed_end=2026-11-09T21:00+00:00, prior8high=1189.910000, depth_time=2026-11-09T21:00:08+00:00, book20_bid_proxy_usdt=322454, book20_ask_proxy_usdt=75194, funding_indicative=0.000100, next_funding_utc=2026-11-10T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.42%, turnover=2504648393. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
