# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T11:45:46Z**
- feed_generated_utc: 2026-11-10T11:45:49+00:00
- source_sha256: `53bd4542958364af42e13d08eca9853b7a58441be533a93422e7e25e021b2bb3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1205; contracts: 1197; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T11:45+00:00, close=74338.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T11:00+00:00, close=74200.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T08:00+00:00, close=74805.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002517|-48.60|-54.25|-47.07|13807734|3.96|
|JCT_USDT|0.006036|-40.42|39.81|-38.89|24917343|1.66|
|ON_USDT|0.118500|-20.78|-30.08|-19.25|5453456|8.44|
|ARB_USDT|0.162120|-11.91|1.75|-10.38|38773165|0.62|
|XMR_USDT|550.040000|-8.91|-9.12|-7.38|6034726|1.09|
|AVAX_USDT|8.298000|-7.69|-2.38|-6.16|51701625|1.21|
|QNT_USDT|186.580000|-6.72|-7.83|-5.19|34257304|1.61|
|ZEC_USDT|1144.400000|-6.63|-8.74|-5.10|2296946663|0.09|
|AAVE_USDT|124.500000|-6.63|-4.64|-5.10|11503996|0.80|
|PUMPFUN_USDT|0.003503|-4.86|-14.64|-3.33|7856605|2.85|
|DOT_USDT|0.852100|-4.35|-8.77|-2.82|8339082|1.17|
|SUI_USDT|0.831300|-4.15|-6.04|-2.62|36143220|1.20|
|DASH_USDT|45.720000|-3.98|-3.13|-2.45|10153679|2.19|
|SOL_USDT|84.600000|-3.74|-9.52|-2.21|673634185|1.18|
|HYPE_USDT|73.798000|-3.29|-13.90|-1.76|47079197|0.14|
|WLD_USDT|0.315700|-3.12|-17.18|-1.59|27747973|3.17|
|LINK_USDT|10.449000|-3.11|-6.98|-1.58|108531406|0.96|
|XRP_USDT|1.080300|-3.01|-13.46|-1.48|283768163|0.93|
|HBAR_USDT|0.066410|-3.00|-5.76|-1.47|9669204|1.51|
|TAO_USDT|218.830000|-2.66|-3.66|-1.13|45129189|1.37|
|ETH_USDT|2092.100000|-2.54|-7.93|-1.01|1273063961|0.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|124.500000|124.140000|124.500000|0.65|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.002517|0.002406|0.002517|1.36|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.162120|0.162920|0.162120|1.72|Y|Y/Y|Y/N|Y|N|
|AVAX_USDT|8.298000|8.264000|8.298000|1.35|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.720000|45.400000|45.720000|0.31|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.852100|0.845000|0.852100|3.98|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.798000|73.342000|73.798000|0.35|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006036|0.005322|0.006036|0.49|N|Y/Y|Y/N|Y|N|
|ON_USDT|0.118500|0.116700|0.118500|1.32|N|Y/Y|N/Y|Y|N|
|PUMPFUN_USDT|0.003503|0.003494|0.003503|2.54|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|186.580000|186.250000|186.580000|1.42|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|84.600000|84.250000|84.600000|0.96|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.831300|0.830300|0.831300|1.95|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|550.040000|539.060000|550.040000|0.38|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1144.400000|1131.050000|1144.400000|0.62|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=125.840000, depth_time=2026-11-10T11:45:29+00:00, book20_bid_proxy_usdt=356185, book20_ask_proxy_usdt=309094, funding_indicative=0.000068, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.63%, turnover=11503996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=0.002533, depth_time=2026-11-10T11:45:07+00:00, book20_bid_proxy_usdt=74099, book20_ask_proxy_usdt=70126, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-48.60%, turnover=13807734. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=0.169260, depth_time=2026-11-10T11:45:16+00:00, book20_bid_proxy_usdt=69339, book20_ask_proxy_usdt=99346, funding_indicative=-0.000223, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.91%, turnover=38773165. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=8.450000, depth_time=2026-11-10T11:45:21+00:00, book20_bid_proxy_usdt=707861, book20_ask_proxy_usdt=955111, funding_indicative=0.000006, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-7.69%, turnover=51701625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=46.340000, depth_time=2026-11-10T11:45:40+00:00, book20_bid_proxy_usdt=750775, book20_ask_proxy_usdt=667886, funding_indicative=-0.000004, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.98%, turnover=10153679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=0.855200, depth_time=2026-11-10T11:45:33+00:00, book20_bid_proxy_usdt=554044, book20_ask_proxy_usdt=599673, funding_indicative=0.000001, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.35%, turnover=8339082. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=74.581000, depth_time=2026-11-10T11:45:42+00:00, book20_bid_proxy_usdt=50814, book20_ask_proxy_usdt=62418, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.29%, turnover=47079197. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=0.006488, depth_time=2026-11-10T11:45:10+00:00, book20_bid_proxy_usdt=42300, book20_ask_proxy_usdt=33987, funding_indicative=0.000316, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-40.42%, turnover=24917343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ON_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=0.158900, depth_time=2026-11-10T11:45:14+00:00, book20_bid_proxy_usdt=62938, book20_ask_proxy_usdt=61332, funding_indicative=0.000050, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-20.78%, turnover=5453456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=0.003552, depth_time=2026-11-10T11:45:31+00:00, book20_bid_proxy_usdt=3075308, book20_ask_proxy_usdt=3071619, funding_indicative=-0.000025, next_funding_utc=2026-11-10T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.86%, turnover=7856605. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=189.740000, depth_time=2026-11-10T11:45:23+00:00, book20_bid_proxy_usdt=89044, book20_ask_proxy_usdt=79713, funding_indicative=-0.000079, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.72%, turnover=34257304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=85.660000, depth_time=2026-11-10T11:45:41+00:00, book20_bid_proxy_usdt=12237724, book20_ask_proxy_usdt=17139577, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=673634185. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=0.843500, depth_time=2026-11-10T11:45:33+00:00, book20_bid_proxy_usdt=2099349, book20_ask_proxy_usdt=1516781, funding_indicative=0.000084, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.15%, turnover=36143220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=556.760000, depth_time=2026-11-10T11:45:19+00:00, book20_bid_proxy_usdt=9233, book20_ask_proxy_usdt=9742, funding_indicative=0.000100, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.91%, turnover=6034726. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T11:45:00+00:00, last15m_closed_end=2026-11-10T11:45+00:00, prior8high=1154.630000, depth_time=2026-11-10T11:45:27+00:00, book20_bid_proxy_usdt=415215, book20_ask_proxy_usdt=154687, funding_indicative=0.000080, next_funding_utc=2026-11-10T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.63%, turnover=2296946663. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
