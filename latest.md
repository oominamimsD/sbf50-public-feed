# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T17:45:43Z**
- feed_generated_utc: 2026-11-02T17:45:46+00:00
- source_sha256: `08a72b6b75f161b6c3fa1b277e185978ccb24be3c31cabb545dabd84f1b9550e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T17:45+00:00, close=76988.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T17:00+00:00, close=77464.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1181.340000|-5.80|-5.32|-5.17|1648261174|0.09|
|UAI_USDT|0.126800|-4.44|-49.03|-3.81|7145741|7.88|
|PUMPFUN_USDT|0.003951|-3.72|-8.71|-3.09|10430349|2.53|
|ENA_USDT|0.169250|-3.30|-19.54|-2.67|70355921|0.59|
|ZRO_USDT|1.720000|-2.72|0.75|-2.09|7408703|1.16|
|ESPORTS_USDT|0.014816|-2.62|87.78|-1.99|6219683|4.05|
|QNT_USDT|197.520000|-2.43|-6.06|-1.80|49685588|0.51|
|AAVE_USDT|127.470000|-2.36|-6.77|-1.73|26381513|0.78|
|NEAR_USDT|3.923000|-2.16|-14.21|-1.53|75208053|2.55|
|ARB_USDT|0.155880|-2.16|-8.30|-1.53|14295594|0.64|
|TAO_USDT|222.730000|-1.94|-12.14|-1.31|38011280|1.35|
|XPL_USDT|0.068250|-1.91|-8.13|-1.28|9647763|1.47|
|HYPE_USDT|84.111000|-1.86|7.22|-1.23|98968196|0.12|
|TIA_USDT|0.448500|-1.83|-16.27|-1.20|11330781|2.23|
|DASH_USDT|46.340000|-1.82|-11.26|-1.19|9979616|2.16|
|FET_USDT|0.154900|-1.71|-12.28|-1.08|5650288|6.46|
|WLD_USDT|0.374800|-1.67|-15.77|-1.04|51584380|2.67|
|OP_USDT|0.110560|-1.66|-1.02|-1.03|13480483|0.90|
|IDOL_USDT|0.013036|-1.65|67.90|-1.02|17920485|4.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.470000|126.990000|127.470000|1.34|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.155880|0.156380|0.155880|6.23|Y|Y/Y|Y/Y|Y|Y|
|DASH_USDT|46.340000|46.340000|46.340000|0.18|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.169250|0.169900|0.169250|3.09|Y|Y/Y|Y/Y|Y|Y|
|ESPORTS_USDT|0.014816|0.014590|0.014840|0.67|N|Y/Y|N/N|Y|N|
|HYPE_USDT|84.111000|83.672000|84.111000|0.95|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.923000|3.934000|3.923000|2.38|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.003951|0.003951|0.003951|0.46|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|197.520000|197.220000|197.520000|2.73|N|Y/N|N/N|Y|N|
|TAO_USDT|222.730000|223.780000|222.730000|2.48|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.448500|0.447200|0.448500|1.16|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.126800|0.126700|0.126800|0.48|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.068250|0.068140|0.068250|0.38|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1181.340000|1185.700000|1181.350000|1.71|Y|Y/Y|Y/N|Y|N|
|ZRO_USDT|1.720000|1.708300|1.719800|2.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=131.530000, depth_time=2026-11-02T17:45:26+00:00, book20_bid_proxy_usdt=556061, book20_ask_proxy_usdt=467926, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.36%, turnover=26381513. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=0.160550, depth_time=2026-11-02T17:45:30+00:00, book20_bid_proxy_usdt=116938, book20_ask_proxy_usdt=72865, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=14295594. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=47.750000, depth_time=2026-11-02T17:45:41+00:00, book20_bid_proxy_usdt=557288, book20_ask_proxy_usdt=511070, funding_indicative=0.000032, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=9979616. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=0.177110, depth_time=2026-11-02T17:45:16+00:00, book20_bid_proxy_usdt=251246, book20_ask_proxy_usdt=233814, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.30%, turnover=70355921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ESPORTS_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=0.016564, depth_time=2026-11-02T17:45:21+00:00, book20_bid_proxy_usdt=8915, book20_ask_proxy_usdt=11951, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.62%, turnover=6219683. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=86.426000, depth_time=2026-11-02T17:45:37+00:00, book20_bid_proxy_usdt=145394, book20_ask_proxy_usdt=125358, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=98968196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=4.070000, depth_time=2026-11-02T17:45:28+00:00, book20_bid_proxy_usdt=4348680, book20_ask_proxy_usdt=2437614, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=75208053. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=0.004193, depth_time=2026-11-02T17:45:14+00:00, book20_bid_proxy_usdt=3015271, book20_ask_proxy_usdt=544416, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.72%, turnover=10430349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=204.820000, depth_time=2026-11-02T17:45:23+00:00, book20_bid_proxy_usdt=60957, book20_ask_proxy_usdt=59225, funding_indicative=0.000081, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=49685588. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=229.640000, depth_time=2026-11-02T17:45:33+00:00, book20_bid_proxy_usdt=258502, book20_ask_proxy_usdt=362968, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.94%, turnover=38011280. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=0.460100, depth_time=2026-11-02T17:45:40+00:00, book20_bid_proxy_usdt=318663, book20_ask_proxy_usdt=273492, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.83%, turnover=11330781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=0.135800, depth_time=2026-11-02T17:45:10+00:00, book20_bid_proxy_usdt=146624, book20_ask_proxy_usdt=104828, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.44%, turnover=7145741. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=0.070990, depth_time=2026-11-02T17:45:35+00:00, book20_bid_proxy_usdt=421200, book20_ask_proxy_usdt=604596, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.91%, turnover=9647763. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=1269.050000, depth_time=2026-11-02T17:45:08+00:00, book20_bid_proxy_usdt=141349, book20_ask_proxy_usdt=548000, funding_indicative=0.000079, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.80%, turnover=1648261174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T17:45:00+00:00, last15m_closed_end=2026-11-02T17:45+00:00, prior8high=1.794700, depth_time=2026-11-02T17:45:18+00:00, book20_bid_proxy_usdt=37034, book20_ask_proxy_usdt=56739, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.72%, turnover=7408703. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
