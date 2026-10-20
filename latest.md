# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T18:30:11Z**
- feed_generated_utc: 2026-10-20T18:30:13+00:00
- source_sha256: `fa169b6adb89b2c74953e880761aad3c882f1c073ad40307ed0e4f35c62e95a6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T18:30+00:00, close=82511.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T18:00+00:00, close=82781.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T16:00+00:00, close=82581.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.693200|-8.45|-13.28|-8.37|33625909|4.13|
|AGT_USDT|0.061709|-4.51|281.46|-4.43|7392347|2.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061709|0.061656|0.061709|0.97|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.693200|1.700200|1.693200|0.94|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T18:29:59+00:00, last15m_closed_end=2026-10-20T18:30+00:00, prior8high=0.065831, depth_time=2026-10-20T18:30:10+00:00, book20_bid_proxy_usdt=5634, book20_ask_proxy_usdt=10169, funding_indicative=0.000047, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.51%, turnover=7392347. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T18:29:59+00:00, last15m_closed_end=2026-10-20T18:30+00:00, prior8high=1.846000, depth_time=2026-10-20T18:30:08+00:00, book20_bid_proxy_usdt=10646, book20_ask_proxy_usdt=9645, funding_indicative=-0.002673, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.45%, turnover=33625909. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
