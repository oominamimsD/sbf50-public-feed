# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T18:00:45Z**
- feed_generated_utc: 2026-11-02T18:00:47+00:00
- source_sha256: `ca754e981505c298e515f69ce1ed6ba80f9eb6bcc6db117696cf81be98bb3509`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T18:00+00:00, close=77124, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T18:00+00:00, close=77124, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.126800|-6.14|-49.03|-5.71|6687667|7.90|
|ZEC_USDT|1177.140000|-6.13|-5.65|-5.70|1641297843|1.19|
|XPL_USDT|0.068180|-3.33|-8.22|-2.90|9471948|1.47|
|ENA_USDT|0.169540|-3.14|-19.40|-2.71|70742386|1.18|
|PUMPFUN_USDT|0.003975|-3.14|-8.15|-2.71|10339120|2.52|
|AAVE_USDT|127.990000|-2.87|-6.39|-2.44|25259654|0.78|
|DASH_USDT|46.340000|-2.83|-11.26|-2.40|9888748|2.16|
|ZRO_USDT|1.732000|-2.75|1.45|-2.32|7183534|1.15|
|INJ_USDT|6.994000|-2.50|-11.84|-2.07|22072193|4.29|
|FET_USDT|0.155100|-2.32|-12.17|-1.89|5670228|6.45|
|AVAX_USDT|8.380000|-2.27|-6.85|-1.84|26525831|1.19|
|TIA_USDT|0.449300|-2.09|-16.12|-1.66|11502935|2.23|
|NEAR_USDT|3.932000|-1.94|-14.01|-1.51|73947180|2.54|
|ARB_USDT|0.156540|-1.88|-7.91|-1.45|14151054|1.92|
|PENGU_USDT|0.007011|-1.84|-7.43|-1.41|5055555|1.43|
|WLD_USDT|0.374700|-1.70|-15.79|-1.27|49855260|2.67|
|HYPE_USDT|84.327000|-1.61|7.50|-1.18|98671813|0.12|
|OP_USDT|0.110730|-1.51|-0.86|-1.08|13400951|1.81|
|SOL_USDT|92.130000|-1.47|-9.53|-1.04|700859627|1.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.990000|126.860000|127.980000|0.76|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.156540|0.155850|0.156540|1.62|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.380000|8.365000|8.380000|1.98|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.340000|46.320000|46.340000|1.13|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.169540|0.168830|0.169510|2.68|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.155100|0.154700|0.155100|2.23|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|6.994000|6.961000|6.994000|1.27|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.932000|3.910000|3.932000|0.98|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007011|0.007004|0.007011|3.91|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003975|0.003950|0.003973|1.58|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.449300|0.447200|0.449300|1.70|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.126800|0.126000|0.126800|1.28|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.068180|0.068140|0.068180|1.54|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1177.140000|1175.060000|1176.720000|1.49|N|Y/Y|Y/N|Y|N|
|ZRO_USDT|1.732000|1.707500|1.732000|1.50|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-02T18:00:03+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=131.340000, depth_time=2026-11-02T18:00:20+00:00, book20_bid_proxy_usdt=397122, book20_ask_proxy_usdt=345562, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.87%, turnover=25259654. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-02T18:00:03+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=0.160550, depth_time=2026-11-02T18:00:41+00:00, book20_bid_proxy_usdt=127320, book20_ask_proxy_usdt=87640, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.88%, turnover=14151054. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-02T18:00:03+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=8.584000, depth_time=2026-11-02T18:00:33+00:00, book20_bid_proxy_usdt=1217932, book20_ask_proxy_usdt=916975, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=26525831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-02T18:00:04+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=47.750000, depth_time=2026-11-02T18:00:23+00:00, book20_bid_proxy_usdt=718406, book20_ask_proxy_usdt=634781, funding_indicative=0.000048, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.83%, turnover=9888748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-02T18:00:03+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=0.177040, depth_time=2026-11-02T18:00:15+00:00, book20_bid_proxy_usdt=214198, book20_ask_proxy_usdt=176048, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.14%, turnover=70742386. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-02T18:00:04+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=0.159500, depth_time=2026-11-02T18:00:30+00:00, book20_bid_proxy_usdt=1591102, book20_ask_proxy_usdt=1064640, funding_indicative=0.000052, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=5670228. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-02T18:00:03+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=7.188000, depth_time=2026-11-02T18:00:28+00:00, book20_bid_proxy_usdt=246303, book20_ask_proxy_usdt=377653, funding_indicative=0.000014, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=22072193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-02T18:00:03+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=4.070000, depth_time=2026-11-02T18:00:38+00:00, book20_bid_proxy_usdt=4502140, book20_ask_proxy_usdt=3399850, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=73947180. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-02T18:00:04+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=0.007178, depth_time=2026-11-02T18:00:44+00:00, book20_bid_proxy_usdt=279169, book20_ask_proxy_usdt=210818, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=5055555. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T18:00:03+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=0.004185, depth_time=2026-11-02T18:00:18+00:00, book20_bid_proxy_usdt=772330, book20_ask_proxy_usdt=1381706, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.14%, turnover=10339120. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-02T18:00:04+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=0.460100, depth_time=2026-11-02T18:00:35+00:00, book20_bid_proxy_usdt=273837, book20_ask_proxy_usdt=323668, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=11502935. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T18:00:03+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=0.134900, depth_time=2026-11-02T18:00:08+00:00, book20_bid_proxy_usdt=121425, book20_ask_proxy_usdt=129086, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.14%, turnover=6687667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T18:00:04+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=0.070990, depth_time=2026-11-02T18:00:13+00:00, book20_bid_proxy_usdt=384330, book20_ask_proxy_usdt=525563, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.33%, turnover=9471948. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T18:00:03+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=1269.050000, depth_time=2026-11-02T18:00:11+00:00, book20_bid_proxy_usdt=132199, book20_ask_proxy_usdt=390613, funding_indicative=0.000065, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-6.13%, turnover=1641297843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T18:00:03+00:00, last15m_closed_end=2026-11-02T18:00+00:00, prior8high=1.794700, depth_time=2026-11-02T18:00:26+00:00, book20_bid_proxy_usdt=28850, book20_ask_proxy_usdt=38893, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=7183534. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
