# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T01:30:42Z**
- feed_generated_utc: 2026-10-17T01:30:44+00:00
- source_sha256: `3ebdc7d26dd056904aa152337cb559f1101b7c8f00c364c5ae3e6eefee166d86`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T01:30+00:00, close=81503.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T01:00+00:00, close=81532.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.956500|-6.89|-3.94|-7.11|16346488|0.51|
|ZEC_USDT|1146.150000|-3.52|-5.92|-3.74|1370632703|0.26|
|RIVER_USDT|1.089000|-3.28|-7.86|-3.50|5487600|9.19|
|INJ_USDT|8.710000|-2.98|25.70|-3.20|115071685|1.15|
|BAT_USDT|0.198900|-2.98|63.48|-3.20|15829905|2.01|
|ARB_USDT|0.189310|-2.88|4.70|-3.10|31542630|0.53|
|TAO_USDT|273.650000|-2.48|-0.37|-2.70|81554036|0.36|
|FILECOIN_USDT|1.138000|-2.46|6.35|-2.68|23171712|0.88|
|APT_USDT|0.835700|-2.38|4.39|-2.60|12516450|1.20|
|FET_USDT|0.195600|-2.00|-9.86|-2.22|11276322|5.11|
|AVAX_USDT|9.909000|-1.72|-2.77|-1.94|125435064|1.01|
|AAVE_USDT|154.570000|-1.72|-8.99|-1.94|31123879|0.65|
|ONDO_USDT|0.449600|-1.64|-6.35|-1.86|28849163|2.22|
|SUI_USDT|1.004500|-1.56|-5.02|-1.78|98672241|0.99|
|ENA_USDT|0.197070|-1.43|-8.58|-1.65|40701355|0.51|
|ICP_USDT|3.000000|-1.25|-0.62|-1.47|8823009|3.33|
|STRK_USDT|0.073070|-1.18|-2.97|-1.40|21202348|1.37|
|QNT_USDT|199.440000|-1.04|-20.04|-1.26|67112489|1.00|
|FARTCOIN_USDT|0.153210|-0.97|-6.21|-1.19|7177880|1.30|
|SEI_USDT|0.063790|-0.79|-2.58|-1.01|18470887|1.57|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.570000|153.940000|154.570000|0.58|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.835700|0.838900|0.835700|0.94|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189310|0.188800|0.189310|1.12|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.909000|9.893000|9.908000|0.81|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.198900|0.195580|0.198900|0.43|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.197070|0.196530|0.197050|0.38|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.195600|0.195500|0.195600|0.20|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.138000|1.133500|1.138000|0.53|N|Y/N|N/N|Y|N|
|INJ_USDT|8.710000|8.619000|8.710000|0.30|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.449600|0.449000|0.449600|0.67|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.089000|1.078000|1.089000|0.77|N|Y/Y|N/N|Y|N|
|SUI_USDT|1.004500|1.003100|1.004500|0.74|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|273.650000|273.390000|273.650000|0.59|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1146.150000|1141.130000|1145.880000|1.12|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.956500|1.938500|1.956500|0.16|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=155.250000, depth_time=2026-10-17T01:30:33+00:00, book20_bid_proxy_usdt=842898, book20_ask_proxy_usdt=290011, funding_indicative=0.000053, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=31123879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=0.848400, depth_time=2026-10-17T01:30:26+00:00, book20_bid_proxy_usdt=146058, book20_ask_proxy_usdt=177546, funding_indicative=0.000028, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=12516450. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=0.191670, depth_time=2026-10-17T01:30:19+00:00, book20_bid_proxy_usdt=74254, book20_ask_proxy_usdt=73029, funding_indicative=-0.000122, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.88%, turnover=31542630. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=9.974000, depth_time=2026-10-17T01:30:30+00:00, book20_bid_proxy_usdt=728431, book20_ask_proxy_usdt=655479, funding_indicative=0.000060, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=125435064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=0.200450, depth_time=2026-10-17T01:30:17+00:00, book20_bid_proxy_usdt=28529, book20_ask_proxy_usdt=24037, funding_indicative=-0.000048, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.98%, turnover=15829905. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=0.199240, depth_time=2026-10-17T01:30:39+00:00, book20_bid_proxy_usdt=225351, book20_ask_proxy_usdt=166836, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=40701355. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=0.199100, depth_time=2026-10-17T01:30:28+00:00, book20_bid_proxy_usdt=1523160, book20_ask_proxy_usdt=1507996, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.00%, turnover=11276322. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=1.159600, depth_time=2026-10-17T01:30:23+00:00, book20_bid_proxy_usdt=491125, book20_ask_proxy_usdt=372685, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=23171712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=8.742000, depth_time=2026-10-17T01:30:14+00:00, book20_bid_proxy_usdt=238666, book20_ask_proxy_usdt=231080, funding_indicative=-0.000126, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.98%, turnover=115071685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=0.455800, depth_time=2026-10-17T01:30:35+00:00, book20_bid_proxy_usdt=2590802, book20_ask_proxy_usdt=1781352, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.64%, turnover=28849163. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=1.094000, depth_time=2026-10-17T01:30:11+00:00, book20_bid_proxy_usdt=494357, book20_ask_proxy_usdt=435420, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=5487600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=1.022600, depth_time=2026-10-17T01:30:39+00:00, book20_bid_proxy_usdt=920509, book20_ask_proxy_usdt=1178364, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=98672241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=276.100000, depth_time=2026-10-17T01:30:20+00:00, book20_bid_proxy_usdt=99732, book20_ask_proxy_usdt=259633, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.48%, turnover=81554036. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=1153.700000, depth_time=2026-10-17T01:30:09+00:00, book20_bid_proxy_usdt=851651, book20_ask_proxy_usdt=97420, funding_indicative=0.000085, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.52%, turnover=1370632703. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T01:30:00+00:00, last15m_closed_end=2026-10-17T01:30+00:00, prior8high=2.053600, depth_time=2026-10-17T01:30:07+00:00, book20_bid_proxy_usdt=36036, book20_ask_proxy_usdt=45084, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.89%, turnover=16346488. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
