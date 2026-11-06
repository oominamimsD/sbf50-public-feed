# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T11:45:13Z**
- feed_generated_utc: 2026-11-06T11:45:14+00:00
- source_sha256: `cc920369b69f99b05c067ab182e0e837d77c5d1d667ba840bf73e2d8405d7317`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T11:45+00:00, close=76136.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T11:00+00:00, close=76033.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|267.790000|-4.05|-7.10|-4.21|7536031|2.99|
|XRP_USDT|1.195700|-3.92|-8.69|-4.08|490829928|0.84|
|QNT_USDT|188.850000|-1.54|-4.97|-1.70|35312596|1.06|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|267.790000|266.560000|267.790000|0.29|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|188.850000|188.460000|188.850000|0.69|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.195700|1.189600|1.195700|0.88|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T11:45:00+00:00, last15m_closed_end=2026-11-06T11:45+00:00, prior8high=269.310000, depth_time=2026-11-06T11:45:07+00:00, book20_bid_proxy_usdt=50214, book20_ask_proxy_usdt=90621, funding_indicative=-0.000047, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.05%, turnover=7536031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T11:45:00+00:00, last15m_closed_end=2026-11-06T11:45+00:00, prior8high=189.600000, depth_time=2026-11-06T11:45:12+00:00, book20_bid_proxy_usdt=83466, book20_ask_proxy_usdt=69774, funding_indicative=-0.000004, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=35312596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T11:44:59+00:00, last15m_closed_end=2026-11-06T11:45+00:00, prior8high=1.201800, depth_time=2026-11-06T11:45:10+00:00, book20_bid_proxy_usdt=3184276, book20_ask_proxy_usdt=3957923, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.92%, turnover=490829928. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
