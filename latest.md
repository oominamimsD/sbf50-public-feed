# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T01:30:17Z**
- feed_generated_utc: 2026-10-21T01:30:19+00:00
- source_sha256: `2d2d77a68ea32b2477425d9a9d6a70d7f11f2f307ba41a7da703bd2f8a72d346`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T01:30+00:00, close=82920.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T01:00+00:00, close=82991, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T00:00+00:00, close=82984.8, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.190400|-11.75|7.34|-12.14|10279419|0.53|
|XMR_USDT|584.420000|-5.76|10.70|-6.15|18204675|0.17|
|TIA_USDT|0.614000|-1.39|6.35|-1.78|48211532|1.63|
|PHA_USDT|0.057190|-1.08|3.92|-1.47|9836712|3.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.190400|0.189610|0.190580|1.90|N|Y/Y|N/N|N|N|
|PHA_USDT|0.057190|0.056840|0.057190|1.77|N|Y/Y|N/N|N|N|
|TIA_USDT|0.614000|0.605800|0.613700|1.67|N|Y/Y|Y/Y|N|N|
|XMR_USDT|584.420000|580.650000|584.500000|7.74|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-21T01:30:01+00:00, last15m_closed_end=2026-10-21T01:30+00:00, prior8high=0.195840, depth_time=2026-10-21T01:30:07+00:00, book20_bid_proxy_usdt=29581, book20_ask_proxy_usdt=22190, funding_indicative=0.000078, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.75%, turnover=10279419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T01:30:01+00:00, last15m_closed_end=2026-10-21T01:30+00:00, prior8high=0.058570, depth_time=2026-10-21T01:30:15+00:00, book20_bid_proxy_usdt=68682, book20_ask_proxy_usdt=69914, funding_indicative=-0.000064, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=9836712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T01:30:01+00:00, last15m_closed_end=2026-10-21T01:30+00:00, prior8high=0.625200, depth_time=2026-10-21T01:30:13+00:00, book20_bid_proxy_usdt=197048, book20_ask_proxy_usdt=224294, funding_indicative=-0.000045, next_funding_utc=2026-10-21T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.39%, turnover=48211532. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T01:30:01+00:00, last15m_closed_end=2026-10-21T01:30+00:00, prior8high=605.900000, depth_time=2026-10-21T01:30:10+00:00, book20_bid_proxy_usdt=7463, book20_ask_proxy_usdt=6578, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.76%, turnover=18204675. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
