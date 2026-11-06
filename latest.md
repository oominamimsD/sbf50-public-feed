# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T04:30:23Z**
- feed_generated_utc: 2026-11-06T04:30:24+00:00
- source_sha256: `f98c9bc09e297bd18c889871135ee7780a1956653c8fd7adec21cc7a069d89c4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T04:30+00:00, close=75633.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T04:00+00:00, close=75880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ELSA_USDT|0.077370|-4.65|3.57|-4.15|6719643|3.88|
|XRP_USDT|1.201500|-3.46|-8.24|-2.96|429084201|0.83|
|FLUID_USDT|2.447000|-3.35|18.55|-2.85|6750617|4.09|
|XPL_USDT|0.056880|-2.90|-27.93|-2.40|12568535|1.76|
|ZRO_USDT|1.579000|-2.66|-10.50|-2.16|7383645|1.90|
|HYPE_USDT|77.351000|-1.71|-17.65|-1.21|84723419|0.13|
|BCH_USDT|274.360000|-1.70|-4.82|-1.20|6979693|3.28|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|274.360000|273.600000|274.360000|1.00|N|Y/Y|Y/Y|Y|N|
|ELSA_USDT|0.077370|0.077150|0.077370|0.24|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.447000|2.411000|2.447000|0.42|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.351000|77.142000|77.373000|0.47|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.056880|0.056370|0.056880|1.37|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.201500|1.201200|1.201500|1.67|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.579000|1.572400|1.580000|1.50|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T04:30:03+00:00, last15m_closed_end=2026-11-06T04:30+00:00, prior8high=277.560000, depth_time=2026-11-06T04:30:21+00:00, book20_bid_proxy_usdt=63216, book20_ask_proxy_usdt=49506, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=6979693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ELSA_USDT: quote_utc=2026-11-06T04:30:03+00:00, last15m_closed_end=2026-11-06T04:30+00:00, prior8high=0.082230, depth_time=2026-11-06T04:30:05+00:00, book20_bid_proxy_usdt=29974, book20_ask_proxy_usdt=15625, funding_indicative=0.000079, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.65%, turnover=6719643. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T04:30:03+00:00, last15m_closed_end=2026-11-06T04:30+00:00, prior8high=2.468000, depth_time=2026-11-06T04:30:10+00:00, book20_bid_proxy_usdt=185650, book20_ask_proxy_usdt=136760, funding_indicative=0.000154, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.35%, turnover=6750617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T04:30:03+00:00, last15m_closed_end=2026-11-06T04:30+00:00, prior8high=78.260000, depth_time=2026-11-06T04:30:20+00:00, book20_bid_proxy_usdt=348426, book20_ask_proxy_usdt=99514, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=84723419. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T04:30:03+00:00, last15m_closed_end=2026-11-06T04:30+00:00, prior8high=0.058050, depth_time=2026-11-06T04:30:14+00:00, book20_bid_proxy_usdt=421700, book20_ask_proxy_usdt=451337, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.90%, turnover=12568535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T04:30:03+00:00, last15m_closed_end=2026-11-06T04:30+00:00, prior8high=1.222500, depth_time=2026-11-06T04:30:10+00:00, book20_bid_proxy_usdt=3205123, book20_ask_proxy_usdt=3237188, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.46%, turnover=429084201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T04:30:03+00:00, last15m_closed_end=2026-11-06T04:30+00:00, prior8high=1.616700, depth_time=2026-11-06T04:30:17+00:00, book20_bid_proxy_usdt=45619, book20_ask_proxy_usdt=113761, funding_indicative=0.000050, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=7383645. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
