# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T22:30:18Z**
- feed_generated_utc: 2026-10-14T22:30:19+00:00
- source_sha256: `45361710b79897472c7b6d66d15d57a9159e58e8fa6337451f4d7974ff215aa3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T22:30+00:00, close=81569.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T22:00+00:00, close=81736.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.168540|-3.37|69.96|-3.34|27175300|2.97|
|FET_USDT|0.197300|-3.23|-12.89|-3.20|10763018|5.07|
|S_USDT|0.053110|-3.06|33.30|-3.03|5465941|1.88|
|AAVE_USDT|153.460000|-1.55|-10.65|-1.52|26149300|1.30|
|LDO_USDT|0.401000|-1.18|-6.17|-1.15|5148267|2.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.460000|153.210000|153.460000|1.08|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.168540|0.167700|0.168540|0.21|N|Y/Y|Y/N|Y|N|
|FET_USDT|0.197300|0.194800|0.197300|0.33|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.401000|0.394500|0.401000|3.13|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053110|0.052410|0.053110|0.16|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T22:30:01+00:00, last15m_closed_end=2026-10-14T22:30+00:00, prior8high=155.360000, depth_time=2026-10-14T22:30:13+00:00, book20_bid_proxy_usdt=258186, book20_ask_proxy_usdt=275978, funding_indicative=0.000081, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=26149300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T22:30:00+00:00, last15m_closed_end=2026-10-14T22:30+00:00, prior8high=0.172860, depth_time=2026-10-14T22:30:08+00:00, book20_bid_proxy_usdt=27927, book20_ask_proxy_usdt=33430, funding_indicative=0.000021, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.37%, turnover=27175300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T22:30:01+00:00, last15m_closed_end=2026-10-14T22:30+00:00, prior8high=0.198600, depth_time=2026-10-14T22:30:10+00:00, book20_bid_proxy_usdt=1224736, book20_ask_proxy_usdt=954810, funding_indicative=-0.000015, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.23%, turnover=10763018. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-14T22:30:01+00:00, last15m_closed_end=2026-10-14T22:30+00:00, prior8high=0.403800, depth_time=2026-10-14T22:30:15+00:00, book20_bid_proxy_usdt=549651, book20_ask_proxy_usdt=666038, funding_indicative=-0.000063, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=5148267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T22:30:01+00:00, last15m_closed_end=2026-10-14T22:30+00:00, prior8high=0.053710, depth_time=2026-10-14T22:30:11+00:00, book20_bid_proxy_usdt=158463, book20_ask_proxy_usdt=142586, funding_indicative=-0.000068, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=5465941. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
