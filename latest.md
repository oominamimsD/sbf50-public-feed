# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T17:45:11Z**
- feed_generated_utc: 2026-10-20T17:45:13+00:00
- source_sha256: `6d2c99a2368f927de2db32a07b3f2d43c2d17fd5a90f8dda3142a4964a4e6c7c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T17:45+00:00, close=82779.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T17:00+00:00, close=82743.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T16:00+00:00, close=82581.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.723400|-6.82|-11.73|-7.05|34517895|2.90|
|AGT_USDT|0.062730|-2.93|287.77|-3.16|7724896|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.062730|0.062222|0.062751|0.35|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.723400|1.743300|1.722700|0.95|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T17:45:01+00:00, last15m_closed_end=2026-10-20T17:45+00:00, prior8high=0.066618, depth_time=2026-10-20T17:45:08+00:00, book20_bid_proxy_usdt=12765, book20_ask_proxy_usdt=5950, funding_indicative=0.000047, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=7724896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T17:45:01+00:00, last15m_closed_end=2026-10-20T17:45+00:00, prior8high=1.889700, depth_time=2026-10-20T17:45:08+00:00, book20_bid_proxy_usdt=22551, book20_ask_proxy_usdt=5860, funding_indicative=-0.002963, next_funding_utc=2026-10-20T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.82%, turnover=34517895. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
