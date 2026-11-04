# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T00:00:27Z**
- feed_generated_utc: 2026-11-04T00:00:29+00:00
- source_sha256: `e989250ec4ba6445d3e016bbdc91199d01d3a3b7f0b996d6dff826b713d5a1a6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T00:00+00:00, close=77441.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T00:00+00:00, close=77441.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T00:00+00:00, close=77441.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003976|-3.23|-81.17|-2.95|13256235|5.03|
|XPL_USDT|0.062970|-2.06|-14.69|-1.78|6871441|1.59|
|OP_USDT|0.109260|-1.72|-1.85|-1.44|8568257|0.92|
|QNT_USDT|192.200000|-1.64|-2.87|-1.36|57845433|0.52|
|TIA_USDT|0.433200|-1.52|-19.19|-1.24|12052447|2.31|
|XLM_USDT|0.162330|-1.49|-4.06|-1.21|31623756|0.62|
|LINK_USDT|11.026000|-1.29|-3.71|-1.01|151840002|0.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003976|0.003903|0.003963|1.16|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.026000|11.067000|11.026000|1.15|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.109260|0.109480|0.109230|2.82|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|192.200000|192.110000|192.170000|0.56|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.433200|0.432100|0.433200|1.79|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.162330|0.162410|0.162340|0.87|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.062970|0.063520|0.062970|4.09|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T00:00:03+00:00, last15m_closed_end=2026-11-04T00:00+00:00, prior8high=0.004140, depth_time=2026-11-04T00:00:08+00:00, book20_bid_proxy_usdt=28973, book20_ask_proxy_usdt=33343, funding_indicative=-0.000882, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=13256235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-04T00:00:03+00:00, last15m_closed_end=2026-11-04T00:00+00:00, prior8high=11.183000, depth_time=2026-11-04T00:00:26+00:00, book20_bid_proxy_usdt=412500, book20_ask_proxy_usdt=1296470, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=151840002. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-04T00:00:03+00:00, last15m_closed_end=2026-11-04T00:00+00:00, prior8high=0.110510, depth_time=2026-11-04T00:00:14+00:00, book20_bid_proxy_usdt=95176, book20_ask_proxy_usdt=124136, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=8568257. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-04T00:00:03+00:00, last15m_closed_end=2026-11-04T00:00+00:00, prior8high=194.210000, depth_time=2026-11-04T00:00:16+00:00, book20_bid_proxy_usdt=80858, book20_ask_proxy_usdt=80434, funding_indicative=0.000028, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=57845433. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-04T00:00:03+00:00, last15m_closed_end=2026-11-04T00:00+00:00, prior8high=0.439200, depth_time=2026-11-04T00:00:19+00:00, book20_bid_proxy_usdt=199808, book20_ask_proxy_usdt=298256, funding_indicative=0.000012, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=12052447. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-04T00:00:03+00:00, last15m_closed_end=2026-11-04T00:00+00:00, prior8high=0.164620, depth_time=2026-11-04T00:00:22+00:00, book20_bid_proxy_usdt=105429, book20_ask_proxy_usdt=233356, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=31623756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-04T00:00:03+00:00, last15m_closed_end=2026-11-04T00:00+00:00, prior8high=0.064750, depth_time=2026-11-04T00:00:11+00:00, book20_bid_proxy_usdt=341472, book20_ask_proxy_usdt=570284, funding_indicative=0.000050, next_funding_utc=2026-11-04T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=6871441. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
