# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T15:00:13Z**
- feed_generated_utc: 2026-11-04T15:00:15+00:00
- source_sha256: `b2088918b0538a85921577d0842acc81e017027eeac026dc5e4e73d15b76c9c0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T15:00+00:00, close=79318.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T15:00+00:00, close=79318.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003190|-23.24|-84.89|-25.34|14544923|3.14|
|TRUMPOFFICIAL_USDT|1.426000|-11.20|-15.52|-13.30|13708367|7.01|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003190|0.002758|0.003189|1.62|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.426000|1.404000|1.426000|2.05|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T15:00:04+00:00, last15m_closed_end=2026-11-04T15:00+00:00, prior8high=0.003236, depth_time=2026-11-04T15:00:10+00:00, book20_bid_proxy_usdt=82714, book20_ask_proxy_usdt=38467, funding_indicative=-0.000057, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.24%, turnover=14544923. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T15:00:04+00:00, last15m_closed_end=2026-11-04T15:00+00:00, prior8high=1.439000, depth_time=2026-11-04T15:00:12+00:00, book20_bid_proxy_usdt=1630787, book20_ask_proxy_usdt=1751500, funding_indicative=-0.000374, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.20%, turnover=13708367. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
