# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T00:30:15Z**
- feed_generated_utc: 2026-10-15T00:30:17+00:00
- source_sha256: `23defd21b4eb7b996b07b24cbbb073c77aa8b1e9210b77d79401e5890100a1b2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T00:30+00:00, close=81742.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FET_USDT|0.199300|-2.25|-12.00|-2.42|10797430|5.02|
|BAT_USDT|0.172310|-1.20|73.76|-1.37|24447409|2.32|
|AAVE_USDT|154.080000|-1.16|-10.29|-1.33|26107082|0.65|
|FARTCOIN_USDT|0.154980|-1.05|-3.24|-1.22|7950889|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.080000|152.860000|154.100000|0.48|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.172310|0.168080|0.172320|2.01|N|Y/Y|N/N|Y|N|
|FARTCOIN_USDT|0.154980|0.155320|0.154980|2.67|Y|Y/Y|Y/Y|Y|Y|
|FET_USDT|0.199300|0.196400|0.199300|1.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-15T00:29:59+00:00, last15m_closed_end=2026-10-15T00:30+00:00, prior8high=154.460000, depth_time=2026-10-15T00:30:12+00:00, book20_bid_proxy_usdt=202398, book20_ask_proxy_usdt=261178, funding_indicative=0.000068, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=26107082. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-15T00:29:59+00:00, last15m_closed_end=2026-10-15T00:30+00:00, prior8high=0.178290, depth_time=2026-10-15T00:30:09+00:00, book20_bid_proxy_usdt=20414, book20_ask_proxy_usdt=30015, funding_indicative=0.000046, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=24447409. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-15T00:29:59+00:00, last15m_closed_end=2026-10-15T00:30+00:00, prior8high=0.157820, depth_time=2026-10-15T00:30:13+00:00, book20_bid_proxy_usdt=35786, book20_ask_proxy_usdt=69608, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.05%, turnover=7950889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-15T00:29:59+00:00, last15m_closed_end=2026-10-15T00:30+00:00, prior8high=0.199000, depth_time=2026-10-15T00:30:06+00:00, book20_bid_proxy_usdt=1068552, book20_ask_proxy_usdt=828754, funding_indicative=0.000046, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=10797430. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
