# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T05:00:41Z**
- feed_generated_utc: 2026-10-17T05:00:44+00:00
- source_sha256: `dee651c4281be8e7fb88b47f881aa3f9154010d09d34b4b5a34ff5c87c752859`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 22; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T05:00+00:00, close=81500.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T05:00+00:00, close=81500.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|RIVER_USDT|1.078000|-9.02|-8.79|-9.23|5001193|9.27|
|ZRO_USDT|1.971500|-8.89|-3.20|-9.10|14411180|0.51|
|BAT_USDT|0.197000|-4.70|61.92|-4.91|14195470|0.51|
|ZEC_USDT|1156.460000|-4.34|-5.08|-4.55|1359380809|0.09|
|TAO_USDT|275.900000|-3.48|0.44|-3.69|74748275|0.72|
|ARB_USDT|0.190670|-3.32|5.45|-3.53|32459655|1.05|
|ENA_USDT|0.198290|-3.02|-8.02|-3.23|38504647|0.51|
|NEAR_USDT|5.067000|-2.94|6.65|-3.15|141365558|1.97|
|AVAX_USDT|9.984000|-2.94|-2.04|-3.15|117829584|1.00|
|STRK_USDT|0.071890|-2.78|-4.54|-2.99|21291140|1.39|
|AAVE_USDT|155.890000|-2.66|-8.21|-2.87|28186673|0.64|
|SEI_USDT|0.064370|-2.64|-1.69|-2.85|19038724|1.55|
|FET_USDT|0.194700|-2.45|-10.27|-2.66|11310878|5.14|
|FARTCOIN_USDT|0.153590|-2.24|-5.98|-2.45|6966392|0.65|
|APT_USDT|0.848000|-2.13|5.93|-2.34|12315515|1.18|
|HBAR_USDT|0.083940|-1.87|-7.61|-2.08|19251216|1.19|
|LINK_USDT|12.296000|-1.75|-4.00|-1.96|63347768|0.81|
|XRP_USDT|1.308100|-1.46|-5.36|-1.67|339268218|0.76|
|ONDO_USDT|0.456200|-1.44|-4.97|-1.65|27972694|2.19|
|SILVER_USDT|57.140000|-1.24|-6.29|-1.45|184129111|1.75|
|LTC_USDT|59.770000|-1.22|-6.02|-1.43|8873208|3.35|
|ADA_USDT|0.224800|-1.18|-5.30|-1.39|37684829|4.45|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.890000|154.690000|155.890000|1.12|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.848000|0.835000|0.848000|1.87|N|N/Y|N/N|Y|N|
|ARB_USDT|0.190670|0.187870|0.190670|0.96|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|9.984000|9.934000|9.984000|0.57|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.197000|0.195330|0.197000|0.94|N|Y/N|N/N|Y|N|
|ENA_USDT|0.198290|0.196880|0.198290|0.84|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.153590|0.152200|0.153590|0.15|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.194700|0.194100|0.194600|0.46|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|5.067000|5.029000|5.067000|0.51|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.078000|1.071000|1.078000|0.33|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.064370|0.063570|0.064370|0.37|N|N/Y|N/N|Y|N|
|STRK_USDT|0.071890|0.069640|0.071880|0.43|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.900000|273.300000|275.900000|1.84|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1156.460000|1141.480000|1156.460000|0.53|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.971500|1.943800|1.971500|1.66|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=156.680000, depth_time=2026-10-17T05:00:31+00:00, book20_bid_proxy_usdt=213990, book20_ask_proxy_usdt=255453, funding_indicative=0.000045, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=28186673. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=0.854500, depth_time=2026-10-17T05:00:41+00:00, book20_bid_proxy_usdt=101577, book20_ask_proxy_usdt=101801, funding_indicative=0.000061, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=12315515. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=0.191350, depth_time=2026-10-17T05:00:19+00:00, book20_bid_proxy_usdt=55214, book20_ask_proxy_usdt=73026, funding_indicative=-0.000017, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.32%, turnover=32459655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=10.037000, depth_time=2026-10-17T05:00:26+00:00, book20_bid_proxy_usdt=582595, book20_ask_proxy_usdt=1420134, funding_indicative=0.000074, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=117829584. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=0.203660, depth_time=2026-10-17T05:00:12+00:00, book20_bid_proxy_usdt=25289, book20_ask_proxy_usdt=27057, funding_indicative=-0.000027, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.70%, turnover=14195470. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=0.200900, depth_time=2026-10-17T05:00:21+00:00, book20_bid_proxy_usdt=150845, book20_ask_proxy_usdt=241496, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=38504647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=0.154120, depth_time=2026-10-17T05:00:38+00:00, book20_bid_proxy_usdt=50658, book20_ask_proxy_usdt=70327, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=6966392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=0.196500, depth_time=2026-10-17T05:00:35+00:00, book20_bid_proxy_usdt=2041800, book20_ask_proxy_usdt=1425399, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=11310878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=5.139000, depth_time=2026-10-17T05:00:22+00:00, book20_bid_proxy_usdt=3225906, book20_ask_proxy_usdt=2575007, funding_indicative=0.000016, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=141365558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=1.090000, depth_time=2026-10-17T05:00:07+00:00, book20_bid_proxy_usdt=395283, book20_ask_proxy_usdt=333980, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.02%, turnover=5001193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=0.064740, depth_time=2026-10-17T05:00:33+00:00, book20_bid_proxy_usdt=258746, book20_ask_proxy_usdt=213199, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=19038724. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=0.072020, depth_time=2026-10-17T05:00:29+00:00, book20_bid_proxy_usdt=253519, book20_ask_proxy_usdt=257194, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.78%, turnover=21291140. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=277.190000, depth_time=2026-10-17T05:00:15+00:00, book20_bid_proxy_usdt=106247, book20_ask_proxy_usdt=69430, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.48%, turnover=74748275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=1160.740000, depth_time=2026-10-17T05:00:14+00:00, book20_bid_proxy_usdt=772058, book20_ask_proxy_usdt=1288986, funding_indicative=0.000029, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.34%, turnover=1359380809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T05:00:02+00:00, last15m_closed_end=2026-10-17T05:00+00:00, prior8high=1.992900, depth_time=2026-10-17T05:00:09+00:00, book20_bid_proxy_usdt=40081, book20_ask_proxy_usdt=52040, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.89%, turnover=14411180. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
