# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T06:30:14Z**
- feed_generated_utc: 2026-10-16T06:30:15+00:00
- source_sha256: `d891716130fe59350f84d76c28bdfde78d2a35f76acc59edcc0273402044be98`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T06:30+00:00, close=82020.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T06:00+00:00, close=82131.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T04:00+00:00, close=82094.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEREBRO_USDT|0.043015|-16.14|56.66|-15.71|6843866|0.47|
|STRK_USDT|0.082260|-14.63|36.73|-14.20|47209560|1.22|
|AKE_USDT|0.030798|-2.55|6.11|-2.12|20840775|2.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.030798|0.030578|0.030798|1.59|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.082260|0.082850|0.082250|1.08|N|Y/Y|N/N|Y|N|
|ZEREBRO_USDT|0.043015|0.038700|0.043000|0.69|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T06:30:00+00:00, last15m_closed_end=2026-10-16T06:30+00:00, prior8high=0.033159, depth_time=2026-10-16T06:30:13+00:00, book20_bid_proxy_usdt=10704, book20_ask_proxy_usdt=14182, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.55%, turnover=20840775. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T06:30:00+00:00, last15m_closed_end=2026-10-16T06:30+00:00, prior8high=0.085080, depth_time=2026-10-16T06:30:11+00:00, book20_bid_proxy_usdt=189582, book20_ask_proxy_usdt=305413, funding_indicative=-0.000057, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.63%, turnover=47209560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T06:30:00+00:00, last15m_closed_end=2026-10-16T06:30+00:00, prior8high=0.041300, depth_time=2026-10-16T06:30:08+00:00, book20_bid_proxy_usdt=11814, book20_ask_proxy_usdt=29011, funding_indicative=0.000050, next_funding_utc=2026-10-16T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.14%, turnover=6843866. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
