# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T21:30:13Z**
- feed_generated_utc: 2026-10-20T21:30:16+00:00
- source_sha256: `03e648d2c4588320a172dc653c36a9e4e78815f0dceec9c977a6e7e059d9258c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T21:30+00:00, close=82886.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T21:00+00:00, close=82810, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T20:00+00:00, close=82561, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.058752|-9.09|263.18|-9.45|7148417|0.85|
|BAT_USDT|0.198370|-8.06|11.83|-8.42|10568725|0.50|
|BTW_USDT|1.730900|-6.41|-11.34|-6.77|27699313|2.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.058752|0.057751|0.058752|0.91|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.198370|0.198230|0.198370|0.20|N|Y/N|N/N|N|N|
|BTW_USDT|1.730900|1.657000|1.730900|1.10|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T21:29:59+00:00, last15m_closed_end=2026-10-20T21:30+00:00, prior8high=0.062837, depth_time=2026-10-20T21:30:07+00:00, book20_bid_proxy_usdt=3684, book20_ask_proxy_usdt=3442, funding_indicative=0.000047, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.09%, turnover=7148417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-20T21:29:59+00:00, last15m_closed_end=2026-10-20T21:30+00:00, prior8high=0.204480, depth_time=2026-10-20T21:30:10+00:00, book20_bid_proxy_usdt=18625, book20_ask_proxy_usdt=22616, funding_indicative=0.000025, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=8, 24h_change=-8.06%, turnover=10568725. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T21:29:59+00:00, last15m_closed_end=2026-10-20T21:30+00:00, prior8high=1.734600, depth_time=2026-10-20T21:30:12+00:00, book20_bid_proxy_usdt=16268, book20_ask_proxy_usdt=7452, funding_indicative=-0.003564, next_funding_utc=2026-10-21T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.41%, turnover=27699313. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
