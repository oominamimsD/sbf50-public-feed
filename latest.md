# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T02:15:25Z**
- feed_generated_utc: 2026-11-06T02:15:26+00:00
- source_sha256: `02a502b168116171f4075a558907743aea1d2eed20a82d3aecf6a8f4f0130ba2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T02:15+00:00, close=76100.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T02:00+00:00, close=76099, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002221|-13.91|-89.45|-14.02|19199577|4.50|
|FLUID_USDT|2.431000|-3.98|17.78|-4.09|7003575|8.22|
|XRP_USDT|1.220000|-1.97|-6.83|-2.08|428266349|0.82|
|XPL_USDT|0.057880|-1.19|-26.66|-1.30|12475534|1.73|
|ZRO_USDT|1.603300|-1.16|-9.12|-1.27|7115052|1.25|
|BCH_USDT|275.970000|-1.12|-4.27|-1.23|7220606|2.54|
|HYPE_USDT|77.822000|-1.11|-17.15|-1.22|86892895|0.13|
|ATOM_USDT|1.406000|-0.98|-13.79|-1.09|6427485|7.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002221|0.002077|0.002221|1.02|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.406000|1.350000|1.406000|0.75|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|275.970000|272.510000|275.970000|0.73|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.431000|2.394000|2.431000|0.63|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.822000|76.568000|77.822000|0.51|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057880|0.056870|0.057890|0.77|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.220000|1.206700|1.219800|0.60|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.603300|1.587000|1.601600|2.08|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T02:14:59+00:00, last15m_closed_end=2026-11-06T02:15+00:00, prior8high=0.002399, depth_time=2026-11-06T02:15:07+00:00, book20_bid_proxy_usdt=28914, book20_ask_proxy_usdt=39853, funding_indicative=-0.000970, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-13.91%, turnover=19199577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-06T02:14:59+00:00, last15m_closed_end=2026-11-06T02:15+00:00, prior8high=1.409000, depth_time=2026-11-06T02:15:23+00:00, book20_bid_proxy_usdt=2158475, book20_ask_proxy_usdt=1764818, funding_indicative=-0.000017, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=6427485. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-06T02:14:59+00:00, last15m_closed_end=2026-11-06T02:15+00:00, prior8high=279.250000, depth_time=2026-11-06T02:15:19+00:00, book20_bid_proxy_usdt=81449, book20_ask_proxy_usdt=52208, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=7220606. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T02:14:59+00:00, last15m_closed_end=2026-11-06T02:15+00:00, prior8high=2.470000, depth_time=2026-11-06T02:15:08+00:00, book20_bid_proxy_usdt=253082, book20_ask_proxy_usdt=141112, funding_indicative=0.000273, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.98%, turnover=7003575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T02:14:59+00:00, last15m_closed_end=2026-11-06T02:15+00:00, prior8high=78.057000, depth_time=2026-11-06T02:15:21+00:00, book20_bid_proxy_usdt=101278, book20_ask_proxy_usdt=137420, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.11%, turnover=86892895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T02:14:59+00:00, last15m_closed_end=2026-11-06T02:15+00:00, prior8high=0.058300, depth_time=2026-11-06T02:15:14+00:00, book20_bid_proxy_usdt=361424, book20_ask_proxy_usdt=414321, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.19%, turnover=12475534. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T02:14:59+00:00, last15m_closed_end=2026-11-06T02:15+00:00, prior8high=1.222700, depth_time=2026-11-06T02:15:11+00:00, book20_bid_proxy_usdt=3540936, book20_ask_proxy_usdt=3982447, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=428266349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T02:14:59+00:00, last15m_closed_end=2026-11-06T02:15+00:00, prior8high=1.618800, depth_time=2026-11-06T02:15:12+00:00, book20_bid_proxy_usdt=17494, book20_ask_proxy_usdt=62880, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=7115052. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
