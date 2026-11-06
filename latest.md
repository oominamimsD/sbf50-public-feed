# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T14:30:13Z**
- feed_generated_utc: 2026-11-06T14:30:14+00:00
- source_sha256: `b8e9d55ecec000d9b20b808647818f0a12b1630b473d3864fa1f19e305644959`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T14:30+00:00, close=75591.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T14:00+00:00, close=75866.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T12:00+00:00, close=76114.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|XRP_USDT|1.180400|-5.15|-9.85|-4.63|482353244|0.85|
|BCH_USDT|265.420000|-4.90|-7.92|-4.38|6834523|1.88|
|QNT_USDT|188.830000|-1.55|-4.98|-1.03|38678858|1.06|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|265.420000|264.300000|265.420000|0.37|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.830000|187.280000|188.800000|3.82|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.180400|1.177800|1.179600|0.78|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T14:29:59+00:00, last15m_closed_end=2026-11-06T14:30+00:00, prior8high=271.890000, depth_time=2026-11-06T14:30:10+00:00, book20_bid_proxy_usdt=42329, book20_ask_proxy_usdt=81893, funding_indicative=-0.000047, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.90%, turnover=6834523. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T14:30:03+00:00, last15m_closed_end=2026-11-06T14:30+00:00, prior8high=192.700000, depth_time=2026-11-06T14:30:11+00:00, book20_bid_proxy_usdt=85625, book20_ask_proxy_usdt=60423, funding_indicative=-0.000014, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=38678858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T14:30:03+00:00, last15m_closed_end=2026-11-06T14:30+00:00, prior8high=1.202300, depth_time=2026-11-06T14:30:07+00:00, book20_bid_proxy_usdt=2355262, book20_ask_proxy_usdt=2908261, funding_indicative=0.000085, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.15%, turnover=482353244. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
