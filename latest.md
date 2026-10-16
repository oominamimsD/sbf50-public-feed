# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T19:00:42Z**
- feed_generated_utc: 2026-10-16T19:00:44+00:00
- source_sha256: `b301035e8d4efb3dd8ca54ebd0d0d9637310f38a5fb60c66d605ebc6ebf40307`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T19:00+00:00, close=81114.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-16T19:00+00:00, close=81114.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T16:00+00:00, close=81322.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|RIVER_USDT|1.071000|-4.88|-9.39|-4.62|6187691|9.34|
|INJ_USDT|8.616000|-4.03|24.34|-3.77|116443558|1.16|
|BAT_USDT|0.196820|-4.00|61.77|-3.74|22544709|3.56|
|ZEC_USDT|1142.850000|-3.80|-6.19|-3.54|1559755469|0.09|
|ZRO_USDT|2.029400|-3.42|-0.36|-3.16|15973085|0.49|
|OP_USDT|0.135440|-3.25|9.91|-2.99|15374128|0.74|
|PYTH_USDT|0.083620|-3.08|-2.07|-2.82|5753183|2.39|
|TAO_USDT|273.380000|-2.58|-0.46|-2.32|84193943|0.37|
|STRK_USDT|0.072080|-2.52|-4.28|-2.26|27776319|2.77|
|APT_USDT|0.835600|-2.39|4.38|-2.13|13185483|1.20|
|WLD_USDT|0.497700|-2.16|1.05|-1.90|94648821|2.01|
|DOT_USDT|1.146800|-2.04|-3.46|-1.78|22844451|0.87|
|HBAR_USDT|0.082400|-2.03|-9.31|-1.77|22929694|1.21|
|ARB_USDT|0.191380|-1.82|5.85|-1.56|37179638|0.52|
|BCH_USDT|273.400000|-1.67|-0.70|-1.41|5974542|4.75|
|FARTCOIN_USDT|0.152180|-1.64|-6.84|-1.38|7786274|0.66|
|RENDER_USDT|1.891000|-1.56|0.96|-1.30|5030713|5.29|
|AAVE_USDT|154.940000|-1.48|-8.77|-1.22|33138993|0.65|
|AVAX_USDT|9.943000|-1.38|-2.44|-1.12|124962148|1.00|
|DASH_USDT|48.310000|-1.30|-5.90|-1.04|11331565|4.14|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.835600|0.825100|0.835500|2.29|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.191380|0.189190|0.191380|0.80|N|Y/Y|N/N|Y|N|
|BAT_USDT|0.196820|0.191460|0.196820|0.49|N|Y/Y|N/N|Y|N|
|BCH_USDT|273.400000|272.380000|273.400000|1.76|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.146800|1.134400|1.147300|0.38|N|Y/N|N/N|Y|N|
|HBAR_USDT|0.082400|0.082050|0.082400|0.68|N|Y/Y|Y/N|Y|N|
|INJ_USDT|8.616000|8.521000|8.616000|1.94|N|Y/Y|N/N|Y|N|
|OP_USDT|0.135440|0.133270|0.135440|1.20|N|Y/Y|N/N|Y|N|
|PYTH_USDT|0.083620|0.083200|0.083620|0.44|N|Y/Y|Y/N|Y|N|
|RIVER_USDT|1.071000|1.073000|1.071000|0.48|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.072080|0.071800|0.072080|1.31|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|273.380000|272.270000|273.460000|1.17|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.497700|0.492700|0.497700|1.02|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1142.850000|1133.160000|1142.850000|0.67|N|Y/Y|Y/N|Y|N|
|ZRO_USDT|2.029400|1.975000|2.031900|0.37|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=0.853600, depth_time=2026-10-16T19:00:28+00:00, book20_bid_proxy_usdt=90609, book20_ask_proxy_usdt=131602, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=13185483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=0.195640, depth_time=2026-10-16T19:00:39+00:00, book20_bid_proxy_usdt=44875, book20_ask_proxy_usdt=52601, funding_indicative=0.000040, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=37179638. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=0.204230, depth_time=2026-10-16T19:00:12+00:00, book20_bid_proxy_usdt=19997, book20_ask_proxy_usdt=24602, funding_indicative=-0.000217, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.00%, turnover=22544709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=277.180000, depth_time=2026-10-16T19:00:41+00:00, book20_bid_proxy_usdt=117104, book20_ask_proxy_usdt=70689, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.67%, turnover=5974542. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=1.181200, depth_time=2026-10-16T19:00:33+00:00, book20_bid_proxy_usdt=183098, book20_ask_proxy_usdt=295245, funding_indicative=0.000051, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=22844451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=0.083760, depth_time=2026-10-16T19:00:36+00:00, book20_bid_proxy_usdt=1274836, book20_ask_proxy_usdt=1291113, funding_indicative=0.000031, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=22929694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=8.853000, depth_time=2026-10-16T19:00:10+00:00, book20_bid_proxy_usdt=293639, book20_ask_proxy_usdt=203394, funding_indicative=0.000232, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.03%, turnover=116443558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=0.138300, depth_time=2026-10-16T19:00:18+00:00, book20_bid_proxy_usdt=37212, book20_ask_proxy_usdt=41593, funding_indicative=0.000047, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=15374128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=0.086370, depth_time=2026-10-16T19:00:20+00:00, book20_bid_proxy_usdt=100699, book20_ask_proxy_usdt=107753, funding_indicative=-0.000030, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=5753183. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=1.129000, depth_time=2026-10-16T19:00:07+00:00, book20_bid_proxy_usdt=384710, book20_ask_proxy_usdt=305654, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.88%, turnover=6187691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=0.074160, depth_time=2026-10-16T19:00:26+00:00, book20_bid_proxy_usdt=535929, book20_ask_proxy_usdt=342561, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=27776319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=280.300000, depth_time=2026-10-16T19:00:24+00:00, book20_bid_proxy_usdt=52194, book20_ask_proxy_usdt=66891, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.58%, turnover=84193943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=0.510100, depth_time=2026-10-16T19:00:31+00:00, book20_bid_proxy_usdt=1421070, book20_ask_proxy_usdt=1692406, funding_indicative=0.000077, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=94648821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=1173.240000, depth_time=2026-10-16T19:00:14+00:00, book20_bid_proxy_usdt=359913, book20_ask_proxy_usdt=509912, funding_indicative=0.000054, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.80%, turnover=1559755469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T18:59:58+00:00, last15m_closed_end=2026-10-16T19:00+00:00, prior8high=2.077200, depth_time=2026-10-16T19:00:16+00:00, book20_bid_proxy_usdt=27582, book20_ask_proxy_usdt=50708, funding_indicative=0.000050, next_funding_utc=2026-10-16T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.42%, turnover=15973085. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
