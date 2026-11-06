# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T02:30:23Z**
- feed_generated_utc: 2026-11-06T02:30:24+00:00
- source_sha256: `9f64ffded63743fa3b998129413bbb369a9cbc766e2fb3177e2554593016a5c1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T02:30+00:00, close=76160.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T02:00+00:00, close=76099, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002289|-11.27|-89.13|-11.43|19248777|4.37|
|FLUID_USDT|2.445000|-3.43|18.45|-3.59|7012308|4.09|
|XRP_USDT|1.220300|-1.95|-6.81|-2.11|430634994|0.82|
|XPL_USDT|0.057810|-1.31|-26.75|-1.47|12503119|1.73|
|BCH_USDT|276.140000|-1.06|-4.21|-1.22|7221594|3.62|
|ATOM_USDT|1.407000|-0.91|-13.73|-1.07|7510244|7.12|
|HYPE_USDT|77.984000|-0.90|-16.98|-1.06|87023760|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002289|0.002077|0.002289|0.65|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.407000|1.360000|1.407000|24.57|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|276.140000|273.910000|276.140000|0.05|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.445000|2.394000|2.442000|0.58|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.984000|77.111000|77.984000|0.35|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057810|0.056870|0.057810|0.54|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.220300|1.210400|1.220300|0.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T02:30:01+00:00, last15m_closed_end=2026-11-06T02:30+00:00, prior8high=0.002399, depth_time=2026-11-06T02:30:07+00:00, book20_bid_proxy_usdt=40087, book20_ask_proxy_usdt=29442, funding_indicative=-0.000979, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.27%, turnover=19248777. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-06T02:30:01+00:00, last15m_closed_end=2026-11-06T02:30+00:00, prior8high=1.409000, depth_time=2026-11-06T02:30:18+00:00, book20_bid_proxy_usdt=2055529, book20_ask_proxy_usdt=2260972, funding_indicative=-0.000008, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.91%, turnover=7510244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-06T02:30:01+00:00, last15m_closed_end=2026-11-06T02:30+00:00, prior8high=279.250000, depth_time=2026-11-06T02:30:17+00:00, book20_bid_proxy_usdt=67320, book20_ask_proxy_usdt=49194, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=7221594. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T02:30:01+00:00, last15m_closed_end=2026-11-06T02:30+00:00, prior8high=2.470000, depth_time=2026-11-06T02:30:07+00:00, book20_bid_proxy_usdt=207515, book20_ask_proxy_usdt=118405, funding_indicative=0.000229, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.43%, turnover=7012308. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T02:30:01+00:00, last15m_closed_end=2026-11-06T02:30+00:00, prior8high=78.057000, depth_time=2026-11-06T02:30:22+00:00, book20_bid_proxy_usdt=123654, book20_ask_proxy_usdt=76650, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.90%, turnover=87023760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T02:30:01+00:00, last15m_closed_end=2026-11-06T02:30+00:00, prior8high=0.058300, depth_time=2026-11-06T02:30:14+00:00, book20_bid_proxy_usdt=378740, book20_ask_proxy_usdt=364014, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=12503119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T02:30:01+00:00, last15m_closed_end=2026-11-06T02:30+00:00, prior8high=1.222700, depth_time=2026-11-06T02:30:12+00:00, book20_bid_proxy_usdt=4169938, book20_ask_proxy_usdt=3013860, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=430634994. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
