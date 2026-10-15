# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T22:30:13Z**
- feed_generated_utc: 2026-10-15T22:30:14+00:00
- source_sha256: `f4de399ffe7a59e35546ef35b4ccc6f874714716c604eb2c8172e15e99569c18`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T22:30+00:00, close=82463, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-15T22:00+00:00, close=82385.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-15T20:00+00:00, close=82350.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|WAL_USDT|0.050940|-4.42|53.01|-4.52|8142812|1.96|
|NIL_USDT|0.084170|-3.11|-2.79|-3.21|13417622|3.57|
|BTW_USDT|1.883100|-1.27|35.64|-1.37|23383357|1.59|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.883100|1.896600|1.883100|1.62|Y|Y/Y|Y/Y|Y|Y|
|NIL_USDT|0.084170|0.082010|0.084170|0.23|N|Y/Y|N/N|Y|N|
|WAL_USDT|0.050940|0.050780|0.050940|0.35|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-15T22:30:00+00:00, last15m_closed_end=2026-10-15T22:30+00:00, prior8high=1.944100, depth_time=2026-10-15T22:30:12+00:00, book20_bid_proxy_usdt=10524, book20_ask_proxy_usdt=10163, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=23383357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-15T22:30:00+00:00, last15m_closed_end=2026-10-15T22:30+00:00, prior8high=0.085340, depth_time=2026-10-15T22:30:10+00:00, book20_bid_proxy_usdt=23299, book20_ask_proxy_usdt=30671, funding_indicative=0.000050, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.11%, turnover=13417622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WAL_USDT: quote_utc=2026-10-15T22:30:00+00:00, last15m_closed_end=2026-10-15T22:30+00:00, prior8high=0.052350, depth_time=2026-10-15T22:30:07+00:00, book20_bid_proxy_usdt=138800, book20_ask_proxy_usdt=160040, funding_indicative=-0.000215, next_funding_utc=2026-10-16T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.42%, turnover=8142812. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
