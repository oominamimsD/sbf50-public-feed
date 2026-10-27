# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T08:00:39Z**
- feed_generated_utc: 2026-10-27T08:00:42+00:00
- source_sha256: `76a677eb1b9f4119f0b3bfb2fcde99c3e00f2218affa7580284beed339776639`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.026390|-5.34|114.90|-4.57|7656850|3.80|
|AAVE_USDT|131.650000|-4.51|-10.57|-3.74|23641029|0.76|
|NEAR_USDT|4.461000|-4.16|-9.03|-3.39|94013391|2.24|
|PUMPFUN_USDT|0.004186|-3.92|-6.05|-3.15|21414298|2.39|
|DOT_USDT|0.997600|-3.25|-13.01|-2.48|10658099|1.00|
|FILECOIN_USDT|0.899000|-2.96|-11.16|-2.19|6108552|1.11|
|SILVER_USDT|52.920000|-2.46|-7.75|-1.69|254868856|1.89|
|WLD_USDT|0.437200|-2.45|-13.64|-1.68|67475844|2.29|
|ARB_USDT|0.167720|-2.43|-14.26|-1.66|19716659|1.19|
|AVAX_USDT|8.791000|-2.33|-8.06|-1.56|37867285|1.14|
|TAO_USDT|249.220000|-2.20|-7.11|-1.43|45585280|1.20|
|SOL_USDT|100.030000|-2.01|-3.90|-1.24|705748276|1.00|
|ENA_USDT|0.206320|-1.95|9.79|-1.18|85655939|0.48|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.650000|131.060000|131.650000|1.14|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167720|0.166750|0.167720|3.91|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.791000|8.733000|8.791000|1.78|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.997600|0.986000|0.997600|2.80|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.206320|0.206590|0.206320|1.86|Y|Y/N|N/N|Y|N|
|FILECOIN_USDT|0.899000|0.892900|0.899000|9.81|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026390|0.026410|0.026390|0.89|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.461000|4.405000|4.461000|2.02|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004186|0.004131|0.004186|8.39|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.920000|52.800000|52.920000|0.45|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|100.030000|99.380000|100.030000|1.98|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|249.220000|247.500000|249.230000|3.21|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.437200|0.432500|0.437200|2.60|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T08:00:03+00:00, last15m_closed_end=2026-10-27T08:00+00:00, prior8high=132.600000, depth_time=2026-10-27T08:00:10+00:00, book20_bid_proxy_usdt=756330, book20_ask_proxy_usdt=396951, funding_indicative=0.000064, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.51%, turnover=23641029. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T08:00:03+00:00, last15m_closed_end=2026-10-27T08:00+00:00, prior8high=0.168170, depth_time=2026-10-27T08:00:28+00:00, book20_bid_proxy_usdt=49538, book20_ask_proxy_usdt=52906, funding_indicative=0.000059, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=19716659. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T08:00:02+00:00, last15m_closed_end=2026-10-27T08:00+00:00, prior8high=8.786000, depth_time=2026-10-27T08:00:31+00:00, book20_bid_proxy_usdt=932615, book20_ask_proxy_usdt=1213509, funding_indicative=-0.000078, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.33%, turnover=37867285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T08:00:03+00:00, last15m_closed_end=2026-10-27T08:00+00:00, prior8high=0.995000, depth_time=2026-10-27T08:00:17+00:00, book20_bid_proxy_usdt=281324, book20_ask_proxy_usdt=434866, funding_indicative=0.000002, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=10658099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T08:00:02+00:00, last15m_closed_end=2026-10-27T08:00+00:00, prior8high=0.209500, depth_time=2026-10-27T08:00:38+00:00, book20_bid_proxy_usdt=70437, book20_ask_proxy_usdt=173482, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=85655939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T08:00:03+00:00, last15m_closed_end=2026-10-27T08:00+00:00, prior8high=0.899400, depth_time=2026-10-27T08:00:21+00:00, book20_bid_proxy_usdt=1214298, book20_ask_proxy_usdt=1069646, funding_indicative=0.000010, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=6108552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T08:00:02+00:00, last15m_closed_end=2026-10-27T08:00+00:00, prior8high=0.029630, depth_time=2026-10-27T08:00:06+00:00, book20_bid_proxy_usdt=113349, book20_ask_proxy_usdt=103108, funding_indicative=-0.000731, next_funding_utc=2026-10-27T09:00:00+00:00, funding_cycle_h=1, 24h_change=-5.34%, turnover=7656850. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T08:00:02+00:00, last15m_closed_end=2026-10-27T08:00+00:00, prior8high=4.459000, depth_time=2026-10-27T08:00:13+00:00, book20_bid_proxy_usdt=3797720, book20_ask_proxy_usdt=3111009, funding_indicative=0.000064, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.16%, turnover=94013391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T08:00:03+00:00, last15m_closed_end=2026-10-27T08:00+00:00, prior8high=0.004181, depth_time=2026-10-27T08:00:16+00:00, book20_bid_proxy_usdt=2105450, book20_ask_proxy_usdt=2139768, funding_indicative=0.000029, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.92%, turnover=21414298. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-27T08:00:02+00:00, last15m_closed_end=2026-10-27T08:00+00:00, prior8high=53.540000, depth_time=2026-10-27T08:00:24+00:00, book20_bid_proxy_usdt=37506852, book20_ask_proxy_usdt=43502954, funding_indicative=0.000098, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.46%, turnover=254868856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T08:00:02+00:00, last15m_closed_end=2026-10-27T08:00+00:00, prior8high=100.260000, depth_time=2026-10-27T08:00:36+00:00, book20_bid_proxy_usdt=15945771, book20_ask_proxy_usdt=17939673, funding_indicative=0.000039, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=705748276. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T08:00:02+00:00, last15m_closed_end=2026-10-27T08:00+00:00, prior8high=249.330000, depth_time=2026-10-27T08:00:33+00:00, book20_bid_proxy_usdt=55517, book20_ask_proxy_usdt=117938, funding_indicative=0.000045, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.20%, turnover=45585280. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T08:00:02+00:00, last15m_closed_end=2026-10-27T08:00+00:00, prior8high=0.438400, depth_time=2026-10-27T08:00:26+00:00, book20_bid_proxy_usdt=2750970, book20_ask_proxy_usdt=3371480, funding_indicative=-0.000224, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=67475844. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
