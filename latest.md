# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T23:45:13Z**
- feed_generated_utc: 2026-10-15T23:45:15+00:00
- source_sha256: `61ad3d940c5c7b938e3e9a83b115d4c2a42e5be3bd8b8cf6bb62326bd2421747`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T23:45+00:00, close=82137.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-15T23:00+00:00, close=82414, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T20:00+00:00, close=82350.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.050480|-5.29|51.63|-5.01|7447324|1.98|
|BTW_USDT|1.813800|-4.90|30.64|-4.62|23183650|1.66|
|NIL_USDT|0.084650|-2.56|-2.24|-2.28|12869441|2.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.813800|1.818300|1.814500|1.32|Y|Y/Y|Y/Y|Y|Y|
|NIL_USDT|0.084650|0.082470|0.084650|0.16|N|Y/Y|N/N|Y|N|
|WAL_USDT|0.050480|0.050140|0.050480|0.47|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-15T23:45:02+00:00, last15m_closed_end=2026-10-15T23:45+00:00, prior8high=1.944100, depth_time=2026-10-15T23:45:10+00:00, book20_bid_proxy_usdt=13592, book20_ask_proxy_usdt=11251, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.90%, turnover=23183650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-15T23:45:02+00:00, last15m_closed_end=2026-10-15T23:45+00:00, prior8high=0.084910, depth_time=2026-10-15T23:45:13+00:00, book20_bid_proxy_usdt=20786, book20_ask_proxy_usdt=20990, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=12869441. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T23:45:02+00:00, last15m_closed_end=2026-10-15T23:45+00:00, prior8high=0.051730, depth_time=2026-10-15T23:45:08+00:00, book20_bid_proxy_usdt=167877, book20_ask_proxy_usdt=136172, funding_indicative=-0.000364, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.29%, turnover=7447324. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
