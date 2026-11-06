# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T02:45:28Z**
- feed_generated_utc: 2026-11-06T02:45:29+00:00
- source_sha256: `ef911ea2f06b9d1bd4f7a8cb5624fa14a7c41affa4655d6db857b162d9646332`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T02:45+00:00, close=76085.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T02:00+00:00, close=76099, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002330|-9.68|-88.93|-9.77|19289981|4.29|
|FLUID_USDT|2.432000|-3.94|17.82|-4.03|7022465|4.11|
|XRP_USDT|1.216600|-2.24|-7.09|-2.33|432399167|0.82|
|XPL_USDT|0.057530|-1.79|-27.11|-1.88|12519520|1.74|
|ELSA_USDT|0.079780|-1.68|6.80|-1.77|7098078|7.52|
|BCH_USDT|275.400000|-1.33|-4.46|-1.42|7236008|2.54|
|ATOM_USDT|1.405000|-1.05|-13.85|-1.14|7531686|7.12|
|QNT_USDT|190.030000|-0.93|-4.38|-1.02|40747961|0.53|
|ZRO_USDT|1.607200|-0.92|-8.90|-1.01|7254294|2.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002330|0.002077|0.002330|0.57|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.405000|1.383000|1.405000|0.47|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|275.400000|273.910000|275.400000|0.82|N|Y/Y|Y/Y|Y|N|
|ELSA_USDT|0.079780|0.079890|0.079780|2.23|Y|Y/Y|N/N|Y|N|
|FLUID_USDT|2.432000|2.394000|2.432000|0.71|N|Y/Y|N/N|Y|N|
|QNT_USDT|190.030000|189.240000|190.030000|0.16|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057530|0.056870|0.057530|0.33|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.216600|1.212100|1.216600|0.74|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.607200|1.590700|1.607300|0.17|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T02:45:00+00:00, last15m_closed_end=2026-11-06T02:45+00:00, prior8high=0.002399, depth_time=2026-11-06T02:45:07+00:00, book20_bid_proxy_usdt=33397, book20_ask_proxy_usdt=53836, funding_indicative=-0.000951, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.68%, turnover=19289981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-06T02:45:00+00:00, last15m_closed_end=2026-11-06T02:45+00:00, prior8high=1.413000, depth_time=2026-11-06T02:45:20+00:00, book20_bid_proxy_usdt=1474839, book20_ask_proxy_usdt=2528825, funding_indicative=0.000008, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=7531686. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-06T02:45:00+00:00, last15m_closed_end=2026-11-06T02:45+00:00, prior8high=279.250000, depth_time=2026-11-06T02:45:19+00:00, book20_bid_proxy_usdt=87428, book20_ask_proxy_usdt=52239, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.33%, turnover=7236008. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ELSA_USDT: quote_utc=2026-11-06T02:45:00+00:00, last15m_closed_end=2026-11-06T02:45+00:00, prior8high=0.084260, depth_time=2026-11-06T02:45:16+00:00, book20_bid_proxy_usdt=24404, book20_ask_proxy_usdt=22437, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=7098078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T02:45:00+00:00, last15m_closed_end=2026-11-06T02:45+00:00, prior8high=2.470000, depth_time=2026-11-06T02:45:09+00:00, book20_bid_proxy_usdt=162788, book20_ask_proxy_usdt=122401, funding_indicative=0.000256, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.94%, turnover=7022465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T02:45:00+00:00, last15m_closed_end=2026-11-06T02:45+00:00, prior8high=193.410000, depth_time=2026-11-06T02:45:23+00:00, book20_bid_proxy_usdt=38350, book20_ask_proxy_usdt=88838, funding_indicative=0.000009, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=40747961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T02:45:00+00:00, last15m_closed_end=2026-11-06T02:45+00:00, prior8high=0.058300, depth_time=2026-11-06T02:45:14+00:00, book20_bid_proxy_usdt=395394, book20_ask_proxy_usdt=370221, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=12519520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T02:45:00+00:00, last15m_closed_end=2026-11-06T02:45+00:00, prior8high=1.222700, depth_time=2026-11-06T02:45:11+00:00, book20_bid_proxy_usdt=4669653, book20_ask_proxy_usdt=3696355, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=432399167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T02:45:00+00:00, last15m_closed_end=2026-11-06T02:45+00:00, prior8high=1.618800, depth_time=2026-11-06T02:45:26+00:00, book20_bid_proxy_usdt=41652, book20_ask_proxy_usdt=44748, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.92%, turnover=7254294. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
