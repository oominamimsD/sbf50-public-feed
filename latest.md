# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T21:15:14Z**
- feed_generated_utc: 2026-10-20T21:15:16+00:00
- source_sha256: `e2997f6a659daf5bcf891dffab02a89df6bbbeae67eace819f525f69ac5e871c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T21:15+00:00, close=82895.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T21:00+00:00, close=82810, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.058261|-9.85|260.14|-10.23|7108414|3.95|
|BTW_USDT|1.710400|-7.52|-12.39|-7.90|27506683|1.17|
|BAT_USDT|0.200000|-7.30|12.75|-7.68|10551097|0.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.058261|0.057751|0.058261|0.46|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.200000|0.198230|0.200000|0.17|N|Y/N|N/N|N|N|
|BTW_USDT|1.710400|1.657000|1.710200|0.66|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T21:15:01+00:00, last15m_closed_end=2026-10-20T21:15+00:00, prior8high=0.063088, depth_time=2026-10-20T21:15:06+00:00, book20_bid_proxy_usdt=4469, book20_ask_proxy_usdt=6157, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.85%, turnover=7108414. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T21:15:01+00:00, last15m_closed_end=2026-10-20T21:15+00:00, prior8high=0.204480, depth_time=2026-10-20T21:15:12+00:00, book20_bid_proxy_usdt=17196, book20_ask_proxy_usdt=16822, funding_indicative=0.000025, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.30%, turnover=10551097. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T21:15:01+00:00, last15m_closed_end=2026-10-20T21:15+00:00, prior8high=1.754000, depth_time=2026-10-20T21:15:11+00:00, book20_bid_proxy_usdt=11985, book20_ask_proxy_usdt=11318, funding_indicative=-0.003389, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.52%, turnover=27506683. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
