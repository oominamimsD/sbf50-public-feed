# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T23:00:16Z**
- feed_generated_utc: 2026-10-28T23:00:20+00:00
- source_sha256: `481227483e415bfecc172f6d0a72f02bbf705cabafcca231726f7ed4bf8b55a0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T23:00+00:00, close=81236, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T23:00+00:00, close=81236, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.010769|-1.22|33.80|-2.09|23795597|9.30|
|BTW_USDT|1.721700|-1.15|17.13|-2.02|11328670|0.58|
|BCH_USDT|290.610000|-1.10|0.32|-1.97|5869745|4.13|
|HBAR_USDT|0.075150|-0.43|-12.55|-1.30|11951631|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|290.610000|288.270000|290.610000|0.32|N|Y/Y|N/N|N|N|
|BLESS_USDT|0.010769|0.010757|0.010769|0.42|N|Y/N|N/N|N|N|
|BTW_USDT|1.721700|1.721600|1.721700|0.68|N|N/N|N/N|N|N|
|HBAR_USDT|0.075150|0.075040|0.075150|0.46|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-28T23:00:01+00:00, last15m_closed_end=2026-10-28T23:00+00:00, prior8high=291.470000, depth_time=2026-10-28T23:00:12+00:00, book20_bid_proxy_usdt=54810, book20_ask_proxy_usdt=67796, funding_indicative=0.000002, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=5869745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-28T23:00:00+00:00, last15m_closed_end=2026-10-28T23:00+00:00, prior8high=0.011275, depth_time=2026-10-28T23:00:08+00:00, book20_bid_proxy_usdt=11475, book20_ask_proxy_usdt=38363, funding_indicative=0.000151, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.22%, turnover=23795597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-28T23:00:00+00:00, last15m_closed_end=2026-10-28T23:00+00:00, prior8high=1.751000, depth_time=2026-10-28T23:00:10+00:00, book20_bid_proxy_usdt=21321, book20_ask_proxy_usdt=23240, funding_indicative=0.000050, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.15%, turnover=11328670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T23:00:01+00:00, last15m_closed_end=2026-10-28T23:00+00:00, prior8high=0.076200, depth_time=2026-10-28T23:00:15+00:00, book20_bid_proxy_usdt=1932056, book20_ask_proxy_usdt=757985, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.43%, turnover=11951631. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
