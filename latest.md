# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T01:45:25Z**
- feed_generated_utc: 2026-11-06T01:45:26+00:00
- source_sha256: `ee47bb69c3d4f0ef282ffe6fea8827b23643c81c54bd4b3f801e27ec202514c0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T01:45+00:00, close=76089.6, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T01:00+00:00, close=76300, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T00:00+00:00, close=76050.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002350|-8.91|-88.84|-9.00|19886882|4.27|
|FLUID_USDT|2.407000|-4.93|16.61|-5.02|7132540|4.16|
|XRP_USDT|1.216700|-2.24|-7.08|-2.33|437758636|0.82|
|XPL_USDT|0.057420|-1.98|-27.25|-2.07|12673798|1.74|
|BCH_USDT|275.190000|-1.40|-4.54|-1.49|8736638|2.18|
|ZRO_USDT|1.599400|-1.40|-9.34|-1.49|7234556|0.62|
|ATOM_USDT|1.402000|-1.26|-14.04|-1.35|6433503|7.13|
|HYPE_USDT|77.837000|-1.09|-17.13|-1.18|88293729|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002350|0.002077|0.002350|1.59|N|Y/Y|Y/Y|Y|N|
|ATOM_USDT|1.402000|1.350000|1.402000|0.36|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|275.190000|269.380000|275.190000|0.16|N|N/Y|Y/Y|Y|N|
|FLUID_USDT|2.407000|2.392000|2.407000|0.79|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.837000|76.568000|77.842000|2.08|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057420|0.056740|0.057420|0.72|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.216700|1.206100|1.216700|0.53|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.599400|1.580000|1.599100|0.64|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T01:45:01+00:00, last15m_closed_end=2026-11-06T01:45+00:00, prior8high=0.002257, depth_time=2026-11-06T01:45:06+00:00, book20_bid_proxy_usdt=41468, book20_ask_proxy_usdt=17057, funding_indicative=-0.001095, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.91%, turnover=19886882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-11-06T01:45:01+00:00, last15m_closed_end=2026-11-06T01:45+00:00, prior8high=1.401000, depth_time=2026-11-06T01:45:17+00:00, book20_bid_proxy_usdt=1788862, book20_ask_proxy_usdt=2416165, funding_indicative=-0.000037, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=6433503. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-06T01:45:01+00:00, last15m_closed_end=2026-11-06T01:45+00:00, prior8high=279.250000, depth_time=2026-11-06T01:45:16+00:00, book20_bid_proxy_usdt=80092, book20_ask_proxy_usdt=41237, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=8736638. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T01:45:01+00:00, last15m_closed_end=2026-11-06T01:45+00:00, prior8high=2.470000, depth_time=2026-11-06T01:45:05+00:00, book20_bid_proxy_usdt=296917, book20_ask_proxy_usdt=180342, funding_indicative=0.000461, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=7132540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-06T01:45:01+00:00, last15m_closed_end=2026-11-06T01:45+00:00, prior8high=77.943000, depth_time=2026-11-06T01:45:23+00:00, book20_bid_proxy_usdt=240641, book20_ask_proxy_usdt=36563, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.09%, turnover=88293729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T01:45:01+00:00, last15m_closed_end=2026-11-06T01:45+00:00, prior8high=0.058300, depth_time=2026-11-06T01:45:14+00:00, book20_bid_proxy_usdt=369904, book20_ask_proxy_usdt=404327, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.98%, turnover=12673798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T01:45:01+00:00, last15m_closed_end=2026-11-06T01:45+00:00, prior8high=1.222700, depth_time=2026-11-06T01:45:12+00:00, book20_bid_proxy_usdt=3499657, book20_ask_proxy_usdt=3813045, funding_indicative=0.000100, next_funding_utc=2026-11-06T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=437758636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-06T01:45:01+00:00, last15m_closed_end=2026-11-06T01:45+00:00, prior8high=1.618800, depth_time=2026-11-06T01:45:14+00:00, book20_bid_proxy_usdt=72434, book20_ask_proxy_usdt=55692, funding_indicative=0.000050, next_funding_utc=2026-11-06T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=7234556. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
