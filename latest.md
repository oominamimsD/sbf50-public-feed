# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T07:15:42Z**
- feed_generated_utc: 2026-10-27T07:15:46+00:00
- source_sha256: `a36af85dac8645d646da7af4e0a55dee52c1bb53ebcefa122cec7a581ce51cea`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 16; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T07:15+00:00, close=79571.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T07:00+00:00, close=79629.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PUMPFUN_USDT|0.004142|-4.29|-7.04|-3.27|21324544|4.83|
|AAVE_USDT|131.150000|-4.08|-10.91|-3.06|24433093|0.76|
|QNT_USDT|202.740000|-3.58|3.59|-2.56|126055989|0.99|
|NEAR_USDT|4.410000|-3.56|-10.07|-2.54|95204340|2.27|
|IRYS_USDT|0.026700|-3.19|117.42|-2.17|8073552|3.75|
|DOT_USDT|0.990200|-3.16|-13.65|-2.14|10754923|1.01|
|FET_USDT|0.171400|-2.94|-9.31|-1.92|6734351|5.84|
|FILECOIN_USDT|0.894200|-2.87|-11.64|-1.85|6135510|1.12|
|ONDO_USDT|0.406900|-2.84|-5.94|-1.82|22580856|2.46|
|AVAX_USDT|8.757000|-2.66|-8.41|-1.64|43177332|1.14|
|WLD_USDT|0.434400|-2.38|-14.20|-1.36|67850659|2.30|
|SILVER_USDT|52.960000|-2.34|-7.68|-1.32|255710516|1.89|
|SOL_USDT|99.520000|-2.27|-4.39|-1.25|699893282|1.00|
|TAO_USDT|247.770000|-2.26|-7.65|-1.24|45099606|1.21|
|PENGU_USDT|0.007412|-2.13|-1.05|-1.11|5324495|1.35|
|ZEC_USDT|1221.640000|-2.09|8.57|-1.07|1448642181|0.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.150000|131.220000|131.150000|3.00|Y|Y/Y|Y/Y|Y|Y|
|AVAX_USDT|8.757000|8.656000|8.757000|0.37|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.990200|0.984100|0.990200|0.22|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.171400|0.171200|0.171300|0.55|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.894200|0.888900|0.894200|0.63|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026700|0.026960|0.026700|1.53|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.410000|4.405000|4.409000|1.22|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.406900|0.404900|0.406900|1.74|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007412|0.007397|0.007412|2.05|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004142|0.004134|0.004142|3.85|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|202.740000|196.820000|202.740000|1.58|N|Y/Y|N/N|Y|N|
|SILVER_USDT|52.960000|52.800000|52.960000|0.40|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|99.520000|99.380000|99.510000|4.00|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|247.770000|247.340000|247.770000|1.73|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.434400|0.432500|0.434400|0.62|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T07:15:00+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=133.020000, depth_time=2026-10-27T07:15:09+00:00, book20_bid_proxy_usdt=899008, book20_ask_proxy_usdt=389234, funding_indicative=0.000073, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.08%, turnover=24433093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T07:15:00+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=8.786000, depth_time=2026-10-27T07:15:30+00:00, book20_bid_proxy_usdt=954326, book20_ask_proxy_usdt=1014252, funding_indicative=-0.000092, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=43177332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T07:15:00+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=0.993400, depth_time=2026-10-27T07:15:20+00:00, book20_bid_proxy_usdt=413249, book20_ask_proxy_usdt=494031, funding_indicative=-0.000091, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=10754923. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T07:15:00+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=0.173200, depth_time=2026-10-27T07:15:23+00:00, book20_bid_proxy_usdt=1423983, book20_ask_proxy_usdt=1084761, funding_indicative=-0.000036, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=6734351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T07:15:01+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=0.899300, depth_time=2026-10-27T07:15:24+00:00, book20_bid_proxy_usdt=1336006, book20_ask_proxy_usdt=1422267, funding_indicative=-0.000002, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.87%, turnover=6135510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T07:15:00+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=0.030440, depth_time=2026-10-27T07:15:17+00:00, book20_bid_proxy_usdt=70080, book20_ask_proxy_usdt=103483, funding_indicative=-0.000580, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=1, 24h_change=-3.19%, turnover=8073552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T07:15:00+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=4.459000, depth_time=2026-10-27T07:15:15+00:00, book20_bid_proxy_usdt=5254354, book20_ask_proxy_usdt=3650995, funding_indicative=0.000052, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.56%, turnover=95204340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T07:15:00+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=0.408800, depth_time=2026-10-27T07:15:27+00:00, book20_bid_proxy_usdt=2265083, book20_ask_proxy_usdt=3862556, funding_indicative=0.000012, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=22580856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T07:15:01+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=0.007462, depth_time=2026-10-27T07:15:41+00:00, book20_bid_proxy_usdt=131074, book20_ask_proxy_usdt=274054, funding_indicative=0.000022, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.13%, turnover=5324495. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T07:15:00+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=0.004181, depth_time=2026-10-27T07:15:04+00:00, book20_bid_proxy_usdt=2185151, book20_ask_proxy_usdt=2001128, funding_indicative=0.000021, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.29%, turnover=21324544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T07:15:00+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=200.820000, depth_time=2026-10-27T07:15:13+00:00, book20_bid_proxy_usdt=71652, book20_ask_proxy_usdt=46584, funding_indicative=-0.000126, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=126055989. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-27T07:15:00+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=53.600000, depth_time=2026-10-27T07:15:33+00:00, book20_bid_proxy_usdt=51969211, book20_ask_proxy_usdt=48086462, funding_indicative=0.000117, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.34%, turnover=255710516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T07:15:00+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=100.330000, depth_time=2026-10-27T07:15:36+00:00, book20_bid_proxy_usdt=15762202, book20_ask_proxy_usdt=17783249, funding_indicative=0.000039, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=699893282. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T07:15:00+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=249.550000, depth_time=2026-10-27T07:15:39+00:00, book20_bid_proxy_usdt=132629, book20_ask_proxy_usdt=122316, funding_indicative=0.000038, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=45099606. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T07:15:00+00:00, last15m_closed_end=2026-10-27T07:15+00:00, prior8high=0.438400, depth_time=2026-10-27T07:15:32+00:00, book20_bid_proxy_usdt=2362174, book20_ask_proxy_usdt=3844999, funding_indicative=-0.000231, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=67850659. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
