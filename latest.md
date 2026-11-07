# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T18:00:16Z**
- feed_generated_utc: 2026-11-07T18:00:17+00:00
- source_sha256: `77d0f14fcfeba4e93fb96e434ea0924ec5847a36b338f369cccb8bc3cf7fb107`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T18:00+00:00, close=75809.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T18:00+00:00, close=75809.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T16:00+00:00, close=75725.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PUMPFUN_USDT|0.003691|-1.36|-11.74|-1.22|17734844|2.71|
|QNT_USDT|196.470000|-1.33|-2.27|-1.19|39648213|0.51|
|NEAR_USDT|3.655000|-1.29|-18.34|-1.15|24200655|2.74|
|ENA_USDT|0.158330|-1.19|-18.39|-1.05|26560423|1.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.158330|0.157160|0.158330|0.30|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.655000|3.631000|3.655000|0.89|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003691|0.003563|0.003691|3.06|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|196.470000|194.580000|196.420000|1.60|N|Y/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-07T18:00:00+00:00, last15m_closed_end=2026-11-07T18:00+00:00, prior8high=0.158610, depth_time=2026-11-07T18:00:14+00:00, book20_bid_proxy_usdt=185067, book20_ask_proxy_usdt=237395, funding_indicative=0.000050, next_funding_utc=2026-11-07T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.19%, turnover=26560423. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-07T18:00:00+00:00, last15m_closed_end=2026-11-07T18:00+00:00, prior8high=3.688000, depth_time=2026-11-07T18:00:12+00:00, book20_bid_proxy_usdt=3839556, book20_ask_proxy_usdt=4119320, funding_indicative=0.000049, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=24200655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T18:00:00+00:00, last15m_closed_end=2026-11-07T18:00+00:00, prior8high=0.003660, depth_time=2026-11-07T18:00:07+00:00, book20_bid_proxy_usdt=2183392, book20_ask_proxy_usdt=2263580, funding_indicative=-0.000055, next_funding_utc=2026-11-07T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.36%, turnover=17734844. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-07T18:00:00+00:00, last15m_closed_end=2026-11-07T18:00+00:00, prior8high=199.510000, depth_time=2026-11-07T18:00:10+00:00, book20_bid_proxy_usdt=90074, book20_ask_proxy_usdt=68742, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=39648213. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
