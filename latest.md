# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T12:15:13Z**
- feed_generated_utc: 2026-11-06T12:15:14+00:00
- source_sha256: `69adfc738116ea03bce27b068e1c44020c756f1a628b59c0655d7f5ce971382f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T12:15+00:00, close=76101.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T12:00+00:00, close=76114.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T12:00+00:00, close=76114.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|XRP_USDT|1.197600|-3.77|-8.54|-3.88|483085984|0.83|
|BCH_USDT|268.890000|-3.66|-6.72|-3.77|7155147|4.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|268.890000|266.560000|268.940000|1.35|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.197600|1.189600|1.197700|0.21|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T12:15:03+00:00, last15m_closed_end=2026-11-06T12:15+00:00, prior8high=269.310000, depth_time=2026-11-06T12:15:12+00:00, book20_bid_proxy_usdt=47910, book20_ask_proxy_usdt=65308, funding_indicative=-0.000044, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.66%, turnover=7155147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T12:15:03+00:00, last15m_closed_end=2026-11-06T12:15+00:00, prior8high=1.201800, depth_time=2026-11-06T12:15:07+00:00, book20_bid_proxy_usdt=4221519, book20_ask_proxy_usdt=4120034, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.77%, turnover=483085984. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
