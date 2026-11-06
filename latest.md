# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T14:45:11Z**
- feed_generated_utc: 2026-11-06T14:45:12+00:00
- source_sha256: `2675276cd54c07979051f7c510172df81891cedf4a0ac48ba0758ddc493a7fe7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T14:45+00:00, close=75713.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T14:00+00:00, close=75866.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T12:00+00:00, close=76114.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|XRP_USDT|1.186200|-4.69|-9.41|-4.29|492725420|0.84|
|BCH_USDT|267.760000|-4.06|-7.11|-3.66|6897136|3.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|267.760000|264.300000|267.650000|1.52|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.186200|1.177800|1.186200|2.88|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T14:45:02+00:00, last15m_closed_end=2026-11-06T14:45+00:00, prior8high=271.890000, depth_time=2026-11-06T14:45:10+00:00, book20_bid_proxy_usdt=53789, book20_ask_proxy_usdt=78210, funding_indicative=-0.000038, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.06%, turnover=6897136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T14:45:02+00:00, last15m_closed_end=2026-11-06T14:45+00:00, prior8high=1.200200, depth_time=2026-11-06T14:45:08+00:00, book20_bid_proxy_usdt=2910589, book20_ask_proxy_usdt=2943605, funding_indicative=0.000080, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.69%, turnover=492725420. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
