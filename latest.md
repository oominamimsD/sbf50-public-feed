# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T04:00:43Z**
- feed_generated_utc: 2026-10-27T04:00:48+00:00
- source_sha256: `5d213ec2918b692eea02ed82fd83db9c63e13757e0389833f571259be0371d5d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|201.760000|-5.39|3.09|-4.65|122692677|0.50|
|NEAR_USDT|4.426000|-4.91|-9.74|-4.17|100799424|2.26|
|PUMPFUN_USDT|0.004161|-4.49|-6.62|-3.75|21003627|2.40|
|DOT_USDT|0.990800|-3.91|-13.60|-3.17|10717354|1.01|
|AAVE_USDT|132.800000|-3.68|-9.79|-2.94|24777779|1.51|
|ONDO_USDT|0.407100|-3.64|-5.89|-2.90|22477221|2.46|
|FET_USDT|0.171600|-3.43|-9.20|-2.69|6448071|5.83|
|ARB_USDT|0.166420|-3.18|-14.93|-2.44|20412479|0.60|
|FILECOIN_USDT|0.898000|-3.07|-11.26|-2.33|6436779|1.11|
|WLD_USDT|0.437100|-2.47|-13.66|-1.73|70115217|2.29|
|TIA_USDT|0.528500|-2.41|-13.14|-1.67|17888008|1.89|
|AVAX_USDT|8.787000|-2.37|-8.10|-1.63|57557071|1.14|
|TAO_USDT|248.900000|-2.33|-7.23|-1.59|45934031|1.21|
|PENGU_USDT|0.007439|-2.27|-0.69|-1.53|5493622|1.34|
|LINK_USDT|11.329000|-2.04|-5.14|-1.30|108482226|0.88|
|SOL_USDT|100.120000|-1.92|-3.81|-1.18|683228510|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.800000|132.420000|132.800000|0.55|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166420|0.165910|0.166420|3.08|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.787000|8.762000|8.787000|0.70|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.990800|0.988500|0.990800|0.44|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.171600|0.170600|0.171600|2.18|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.898000|0.892600|0.898000|2.54|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.329000|11.264000|11.329000|0.79|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.426000|4.389000|4.426000|0.36|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.407100|0.404300|0.407200|0.60|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007439|0.007387|0.007439|2.29|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004161|0.004118|0.004161|1.52|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|201.760000|200.410000|201.760000|0.41|N|Y/Y|N/N|Y|N|
|TAO_USDT|248.900000|247.350000|248.900000|0.16|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.528500|0.523500|0.528500|0.48|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.437100|0.433900|0.437100|0.76|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=135.430000, depth_time=2026-10-27T04:00:17+00:00, book20_bid_proxy_usdt=390668, book20_ask_proxy_usdt=353020, funding_indicative=0.000081, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.68%, turnover=24777779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=0.168940, depth_time=2026-10-27T04:00:24+00:00, book20_bid_proxy_usdt=113005, book20_ask_proxy_usdt=76731, funding_indicative=-0.000014, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.18%, turnover=20412479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=8.933000, depth_time=2026-10-27T04:00:34+00:00, book20_bid_proxy_usdt=1444200, book20_ask_proxy_usdt=2048231, funding_indicative=-0.000022, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.37%, turnover=57557071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=1.002800, depth_time=2026-10-27T04:00:15+00:00, book20_bid_proxy_usdt=248907, book20_ask_proxy_usdt=424259, funding_indicative=-0.000127, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.91%, turnover=10717354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=0.175100, depth_time=2026-10-27T04:00:16+00:00, book20_bid_proxy_usdt=1738655, book20_ask_proxy_usdt=935157, funding_indicative=0.000088, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.43%, turnover=6448071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=0.909800, depth_time=2026-10-27T04:00:23+00:00, book20_bid_proxy_usdt=1031851, book20_ask_proxy_usdt=1337982, funding_indicative=-0.000023, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.07%, turnover=6436779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=11.380000, depth_time=2026-10-27T04:00:42+00:00, book20_bid_proxy_usdt=456693, book20_ask_proxy_usdt=488383, funding_indicative=-0.000012, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=108482226. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=4.515000, depth_time=2026-10-27T04:00:10+00:00, book20_bid_proxy_usdt=4138002, book20_ask_proxy_usdt=3872589, funding_indicative=0.000043, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.91%, turnover=100799424. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=0.412900, depth_time=2026-10-27T04:00:19+00:00, book20_bid_proxy_usdt=2408847, book20_ask_proxy_usdt=2972255, funding_indicative=0.000031, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.64%, turnover=22477221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=0.007519, depth_time=2026-10-27T04:00:40+00:00, book20_bid_proxy_usdt=214209, book20_ask_proxy_usdt=307378, funding_indicative=-0.000008, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=5493622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=0.004268, depth_time=2026-10-27T04:00:12+00:00, book20_bid_proxy_usdt=1564066, book20_ask_proxy_usdt=2063364, funding_indicative=0.000029, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.49%, turnover=21003627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=205.330000, depth_time=2026-10-27T04:00:08+00:00, book20_bid_proxy_usdt=74226, book20_ask_proxy_usdt=60591, funding_indicative=-0.000111, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.39%, turnover=122692677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=251.000000, depth_time=2026-10-27T04:00:37+00:00, book20_bid_proxy_usdt=96201, book20_ask_proxy_usdt=145840, funding_indicative=0.000027, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=45934031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=0.540700, depth_time=2026-10-27T04:00:31+00:00, book20_bid_proxy_usdt=345216, book20_ask_proxy_usdt=508532, funding_indicative=0.000039, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.41%, turnover=17888008. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T04:00:00+00:00, last15m_closed_end=2026-10-27T04:00+00:00, prior8high=0.443200, depth_time=2026-10-27T04:00:29+00:00, book20_bid_proxy_usdt=4111089, book20_ask_proxy_usdt=3771864, funding_indicative=-0.000194, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=70115217. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
