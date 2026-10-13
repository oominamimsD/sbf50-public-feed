# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T09:15:40Z**
- feed_generated_utc: 2026-10-13T09:15:44+00:00
- source_sha256: `ecebf2301b62c841540454b49d4317b02240da34fe1c672fc0fa3026f4dbedab`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T09:15+00:00, close=83532.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T09:00+00:00, close=83555.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T08:00+00:00, close=83829.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.225200|-22.21|5.72|-23.24|9421802|4.44|
|ZRO_USDT|2.085100|-7.77|1.93|-8.80|22448408|1.44|
|NEAR_USDT|5.140000|-7.37|2.34|-8.40|267408056|1.95|
|LIT_USDT|3.377700|-6.82|-11.16|-7.85|10118209|0.30|
|PUMPFUN_USDT|0.005039|-5.08|-20.45|-6.11|32087816|1.98|
|ONDO_USDT|0.472800|-5.07|-3.27|-6.10|65325495|2.12|
|RLC_USDT|0.940300|-4.88|71.58|-5.91|6765037|2.13|
|SEI_USDT|0.063600|-4.17|-11.55|-5.20|9127077|1.57|
|ENA_USDT|0.213380|-3.73|-13.10|-4.76|63971658|0.47|
|JUP_USDT|0.330400|-3.64|-2.21|-4.67|8613350|9.08|
|ICP_USDT|3.181000|-3.45|-8.22|-4.48|17253061|3.15|
|HBAR_USDT|0.087390|-3.43|-13.21|-4.46|22645028|1.14|
|STRK_USDT|0.087840|-3.12|68.56|-4.15|60828405|1.14|
|USELESS_USDT|0.176060|-3.05|-22.35|-4.08|6198225|0.57|
|PONS_USDT|0.285900|-2.98|-25.44|-4.01|6256760|3.50|
|SAND_USDT|0.060350|-2.80|-10.59|-3.83|7834929|3.31|
|FET_USDT|0.215600|-2.66|-13.51|-3.69|21228784|4.64|
|QNT_USDT|222.330000|-2.64|-13.41|-3.67|75711355|3.15|
|S_USDT|0.056990|-0.69|32.68|-1.72|6630861|3.51|
|GRASS_USDT|0.744200|-0.37|5.53|-1.40|6327497|1.34|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.225200|0.221400|0.225700|0.64|N|Y/Y|Y/Y|N|N|
|ENA_USDT|0.213380|0.215280|0.213380|4.79|Y|Y/Y|Y/Y|N|Y|
|HBAR_USDT|0.087390|0.087450|0.087430|2.42|Y|Y/Y|Y/Y|N|Y|
|ICP_USDT|3.181000|3.187000|3.181000|1.16|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.330400|0.331700|0.330400|1.88|Y|Y/Y|Y/Y|N|Y|
|LIT_USDT|3.377700|3.373000|3.377700|2.38|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.140000|5.151000|5.140000|2.49|Y|Y/Y|Y/Y|N|Y|
|ONDO_USDT|0.472800|0.474900|0.472900|2.98|Y|Y/Y|Y/Y|N|Y|
|PONS_USDT|0.285900|0.284600|0.286000|2.13|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005039|0.005044|0.005039|1.73|Y|Y/Y|Y/Y|N|Y|
|RLC_USDT|0.940300|0.917000|0.939900|1.07|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.063600|0.063930|0.063600|13.91|Y|Y/Y|Y/Y|N|Y|
|STRK_USDT|0.087840|0.083010|0.087820|1.07|N|Y/Y|Y/Y|N|N|
|USELESS_USDT|0.176060|0.176670|0.176060|2.26|Y|Y/Y|Y/Y|N|Y|
|ZRO_USDT|2.085100|2.075100|2.084900|0.92|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=0.234500, depth_time=2026-10-13T09:15:08+00:00, book20_bid_proxy_usdt=103173, book20_ask_proxy_usdt=103831, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-22.21%, turnover=9421802. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=0.218850, depth_time=2026-10-13T09:15:26+00:00, book20_bid_proxy_usdt=195739, book20_ask_proxy_usdt=114175, funding_indicative=0.000031, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.73%, turnover=63971658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=0.088760, depth_time=2026-10-13T09:15:33+00:00, book20_bid_proxy_usdt=374940, book20_ask_proxy_usdt=831186, funding_indicative=-0.000025, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.43%, turnover=22645028. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=3.249000, depth_time=2026-10-13T09:15:31+00:00, book20_bid_proxy_usdt=897207, book20_ask_proxy_usdt=867978, funding_indicative=-0.000037, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=17253061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=0.338800, depth_time=2026-10-13T09:15:28+00:00, book20_bid_proxy_usdt=570875, book20_ask_proxy_usdt=543384, funding_indicative=-0.000049, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.64%, turnover=8613350. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=3.456200, depth_time=2026-10-13T09:15:15+00:00, book20_bid_proxy_usdt=29654, book20_ask_proxy_usdt=46326, funding_indicative=0.000025, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.82%, turnover=10118209. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T09:15:02+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=5.293000, depth_time=2026-10-13T09:15:11+00:00, book20_bid_proxy_usdt=1810004, book20_ask_proxy_usdt=4015379, funding_indicative=0.000051, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.37%, turnover=267408056. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=0.482500, depth_time=2026-10-13T09:15:19+00:00, book20_bid_proxy_usdt=2045179, book20_ask_proxy_usdt=2054200, funding_indicative=-0.000001, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.07%, turnover=65325495. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=0.295200, depth_time=2026-10-13T09:15:39+00:00, book20_bid_proxy_usdt=225216, book20_ask_proxy_usdt=233132, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.98%, turnover=6256760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=0.005142, depth_time=2026-10-13T09:15:17+00:00, book20_bid_proxy_usdt=1618992, book20_ask_proxy_usdt=1333253, funding_indicative=-0.000005, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.08%, turnover=32087816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=0.957000, depth_time=2026-10-13T09:15:20+00:00, book20_bid_proxy_usdt=46342, book20_ask_proxy_usdt=46818, funding_indicative=-0.000864, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.88%, turnover=6765037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=0.064840, depth_time=2026-10-13T09:15:24+00:00, book20_bid_proxy_usdt=228642, book20_ask_proxy_usdt=191770, funding_indicative=0.000051, next_funding_utc=2026-10-13T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.17%, turnover=9127077. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=0.087750, depth_time=2026-10-13T09:15:35+00:00, book20_bid_proxy_usdt=125879, book20_ask_proxy_usdt=98713, funding_indicative=0.000020, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.12%, turnover=60828405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=0.180980, depth_time=2026-10-13T09:15:36+00:00, book20_bid_proxy_usdt=57787, book20_ask_proxy_usdt=69554, funding_indicative=0.000050, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=6198225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T09:15:03+00:00, last15m_closed_end=2026-10-13T09:15+00:00, prior8high=2.157300, depth_time=2026-10-13T09:15:10+00:00, book20_bid_proxy_usdt=185898, book20_ask_proxy_usdt=88972, funding_indicative=-0.000037, next_funding_utc=2026-10-13T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.77%, turnover=22448408. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
