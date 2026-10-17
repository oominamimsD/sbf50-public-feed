# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T00:15:43Z**
- feed_generated_utc: 2026-10-17T00:15:45+00:00
- source_sha256: `e211deed6d80caa048194f11e327fd7e9c32d3b44156ade2feb287f52eec43a7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T00:15+00:00, close=81607.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|2.010300|-4.33|-1.30|-4.68|16317196|4.98|
|RIVER_USDT|1.084000|-3.73|-8.29|-4.08|5468177|9.22|
|BAT_USDT|0.197940|-3.45|62.69|-3.80|16478882|1.52|
|INJ_USDT|8.684000|-3.27|25.32|-3.62|115936526|1.15|
|ZEC_USDT|1150.460000|-3.16|-5.57|-3.51|1366268951|0.09|
|ARB_USDT|0.190960|-2.04|5.61|-2.39|30870531|0.52|
|TAO_USDT|275.470000|-1.83|0.29|-2.18|82957921|1.09|
|AAVE_USDT|154.790000|-1.58|-8.86|-1.93|31104069|1.29|
|AVAX_USDT|9.928000|-1.53|-2.59|-1.88|125310157|1.01|
|APT_USDT|0.845800|-1.20|5.65|-1.55|12331356|1.18|
|FET_USDT|0.197600|-1.00|-8.94|-1.35|11102283|5.06|
|ONDO_USDT|0.453000|-0.89|-5.64|-1.24|28504805|2.21|
|QNT_USDT|200.010000|-0.76|-19.81|-1.11|67149290|0.50|
|ENA_USDT|0.198430|-0.75|-7.95|-1.10|40186429|0.50|
|HBAR_USDT|0.083490|-0.73|-8.11|-1.08|21023344|1.20|
|STRK_USDT|0.073430|-0.70|-2.49|-1.05|20943368|1.36|
|SUI_USDT|1.013800|-0.65|-4.14|-1.00|95589817|0.99|
|ICP_USDT|3.018000|-0.65|-0.03|-1.00|8581226|3.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.790000|153.830000|154.790000|0.72|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.845800|0.833500|0.845800|0.97|N|N/Y|N/N|Y|N|
|ARB_USDT|0.190960|0.190500|0.190960|0.60|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.928000|9.931000|9.929000|0.83|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.197940|0.194970|0.197940|0.70|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.198430|0.197000|0.198430|0.25|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.197600|0.198200|0.197700|0.78|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.083490|0.083050|0.083490|0.89|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.684000|8.561000|8.679000|1.26|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.453000|0.451400|0.453000|3.01|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|200.010000|198.640000|200.010000|0.61|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.084000|1.085000|1.084000|1.51|Y|Y/Y|N/N|Y|N|
|TAO_USDT|275.470000|271.710000|275.470000|1.44|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1150.460000|1138.360000|1150.680000|0.71|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|2.010300|2.027800|2.010000|3.10|Y|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=155.320000, depth_time=2026-10-17T00:15:26+00:00, book20_bid_proxy_usdt=545180, book20_ask_proxy_usdt=275143, funding_indicative=0.000054, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=31104069. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=0.848400, depth_time=2026-10-17T00:15:30+00:00, book20_bid_proxy_usdt=126307, book20_ask_proxy_usdt=116917, funding_indicative=0.000041, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=12331356. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=0.191930, depth_time=2026-10-17T00:15:20+00:00, book20_bid_proxy_usdt=83806, book20_ask_proxy_usdt=54104, funding_indicative=-0.000108, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=30870531. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=9.997000, depth_time=2026-10-17T00:15:28+00:00, book20_bid_proxy_usdt=732868, book20_ask_proxy_usdt=667489, funding_indicative=0.000023, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=125310157. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=0.201600, depth_time=2026-10-17T00:15:13+00:00, book20_bid_proxy_usdt=26431, book20_ask_proxy_usdt=32345, funding_indicative=-0.000099, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=16478882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=0.199290, depth_time=2026-10-17T00:15:40+00:00, book20_bid_proxy_usdt=128926, book20_ask_proxy_usdt=176524, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.75%, turnover=40186429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=0.200000, depth_time=2026-10-17T00:15:32+00:00, book20_bid_proxy_usdt=1658890, book20_ask_proxy_usdt=1036491, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=11102283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=0.083810, depth_time=2026-10-17T00:15:42+00:00, book20_bid_proxy_usdt=800374, book20_ask_proxy_usdt=1161991, funding_indicative=0.000004, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.73%, turnover=21023344. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=8.739000, depth_time=2026-10-17T00:15:16+00:00, book20_bid_proxy_usdt=249323, book20_ask_proxy_usdt=224094, funding_indicative=-0.000132, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.27%, turnover=115936526. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=0.456600, depth_time=2026-10-17T00:15:35+00:00, book20_bid_proxy_usdt=1750763, book20_ask_proxy_usdt=1409916, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.89%, turnover=28504805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=203.290000, depth_time=2026-10-17T00:15:38+00:00, book20_bid_proxy_usdt=82808, book20_ask_proxy_usdt=75794, funding_indicative=-0.000001, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.76%, turnover=67149290. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=1.108000, depth_time=2026-10-17T00:15:08+00:00, book20_bid_proxy_usdt=554363, book20_ask_proxy_usdt=413872, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.73%, turnover=5468177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=276.100000, depth_time=2026-10-17T00:15:24+00:00, book20_bid_proxy_usdt=130114, book20_ask_proxy_usdt=97992, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.83%, turnover=82957921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=1153.000000, depth_time=2026-10-17T00:15:19+00:00, book20_bid_proxy_usdt=1131638, book20_ask_proxy_usdt=222624, funding_indicative=0.000098, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=1366268951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T00:15:01+00:00, last15m_closed_end=2026-10-17T00:15+00:00, prior8high=2.066300, depth_time=2026-10-17T00:15:08+00:00, book20_bid_proxy_usdt=48591, book20_ask_proxy_usdt=50984, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.33%, turnover=16317196. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
