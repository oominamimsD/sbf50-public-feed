# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T22:30:11Z**
- feed_generated_utc: 2026-10-20T22:30:13+00:00
- source_sha256: `6da1045697c3768794c9782ea8413a721781e5a8f138c25cdf1f59e24ddf0836`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T22:30+00:00, close=82993, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T22:00+00:00, close=82932.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.056574|-12.46|249.71|-12.95|7116496|0.35|
|BAT_USDT|0.195460|-9.41|10.19|-9.90|9972273|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.056574|0.057106|0.056562|0.70|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.195460|0.194560|0.195450|0.88|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T22:30:00+00:00, last15m_closed_end=2026-10-20T22:30+00:00, prior8high=0.060433, depth_time=2026-10-20T22:30:07+00:00, book20_bid_proxy_usdt=51490, book20_ask_proxy_usdt=8444, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.46%, turnover=7116496. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T22:30:00+00:00, last15m_closed_end=2026-10-20T22:30+00:00, prior8high=0.200820, depth_time=2026-10-20T22:30:10+00:00, book20_bid_proxy_usdt=18103, book20_ask_proxy_usdt=17616, funding_indicative=0.000009, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-9.41%, turnover=9972273. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
