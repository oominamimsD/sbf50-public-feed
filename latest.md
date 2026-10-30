# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T16:30:12Z**
- feed_generated_utc: 2026-10-30T16:30:13+00:00
- source_sha256: `de9e816b18cb5a6ce827bcb58f772a261815f2dd8d3287493c40facc0a3e691c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 15/15 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 2; crypto_deep: 2
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T16:30+00:00, close=77577.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.009533|-3.22|16.81|-3.22|19516594|5.24|
|BTW_USDT|1.166000|-2.79|-31.50|-2.79|10011712|3.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009533|0.009320|0.009551|1.51|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.166000|1.166100|1.166000|1.16|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T16:30:02+00:00, last15m_closed_end=2026-10-30T16:30+00:00, prior8high=0.013650, depth_time=2026-10-30T16:30:08+00:00, book20_bid_proxy_usdt=13613, book20_ask_proxy_usdt=15246, funding_indicative=0.000211, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.22%, turnover=19516594. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T16:30:02+00:00, last15m_closed_end=2026-10-30T16:30+00:00, prior8high=1.257600, depth_time=2026-10-30T16:30:10+00:00, book20_bid_proxy_usdt=16686, book20_ask_proxy_usdt=13443, funding_indicative=-0.000080, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=10011712. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
