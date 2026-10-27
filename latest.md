# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T07:00:41Z**
- feed_generated_utc: 2026-10-27T07:00:45+00:00
- source_sha256: `e296a5b5711d4b01ea5a6b24d71037ad685a64a968e88e706be05af1cea52e0b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T07:00+00:00, close=79629.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T07:00+00:00, close=79629.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.117270|-18.92|62.82|-17.97|11605625|5.11|
|QNT_USDT|200.190000|-6.12|2.29|-5.17|125026319|0.50|
|NEAR_USDT|4.418000|-5.09|-9.91|-4.14|94812990|4.53|
|PUMPFUN_USDT|0.004147|-4.81|-6.93|-3.86|21075508|2.41|
|AAVE_USDT|131.270000|-4.79|-10.83|-3.84|23897559|0.76|
|ONDO_USDT|0.407200|-3.62|-5.87|-2.67|22351049|2.46|
|FILECOIN_USDT|0.894700|-3.43|-11.59|-2.48|6131115|1.12|
|FET_USDT|0.171700|-3.37|-9.15|-2.42|6715014|5.82|
|DOT_USDT|0.990400|-3.14|-13.63|-2.19|10743344|1.01|
|WLD_USDT|0.434800|-2.98|-14.12|-2.03|67689211|2.30|
|ARB_USDT|0.167070|-2.80|-14.59|-1.85|19698901|0.60|
|AVAX_USDT|8.756000|-2.72|-8.42|-1.77|43121864|1.14|
|PENGU_USDT|0.007414|-2.60|-1.02|-1.65|5276060|2.70|
|SOL_USDT|99.530000|-2.50|-4.38|-1.55|682356156|1.00|
|SILVER_USDT|52.940000|-2.37|-7.72|-1.42|254471650|1.89|
|ZEC_USDT|1219.040000|-2.29|8.33|-1.34|1434352705|0.08|
|TIA_USDT|0.529400|-2.25|-12.99|-1.30|17780946|1.89|
|TAO_USDT|247.890000|-2.21|-7.60|-1.26|44718344|1.61|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.270000|131.230000|131.270000|1.36|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167070|0.166430|0.167070|0.12|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.756000|8.656000|8.756000|0.45|N|Y/Y|Y/Y|Y|N|
|BULLA_USDT|0.117270|0.091180|0.117350|9.01|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.990400|0.984100|0.990300|0.39|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.171700|0.171200|0.171700|0.83|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.894700|0.888900|0.894700|0.15|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.418000|4.405000|4.418000|0.81|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.407200|0.404900|0.407200|1.59|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007414|0.007397|0.007414|1.93|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004147|0.004134|0.004148|0.30|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|200.190000|196.820000|200.190000|0.57|N|Y/Y|N/N|Y|N|
|SILVER_USDT|52.940000|52.810000|52.950000|0.55|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|99.530000|99.690000|99.530000|2.44|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.434800|0.434300|0.434800|1.61|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T07:00:01+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=133.020000, depth_time=2026-10-27T07:00:17+00:00, book20_bid_proxy_usdt=679235, book20_ask_proxy_usdt=480973, funding_indicative=0.000073, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.79%, turnover=23897559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T07:00:00+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=0.168170, depth_time=2026-10-27T07:00:31+00:00, book20_bid_proxy_usdt=63098, book20_ask_proxy_usdt=83751, funding_indicative=0.000047, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=19698901. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T07:00:00+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=8.786000, depth_time=2026-10-27T07:00:33+00:00, book20_bid_proxy_usdt=1125991, book20_ask_proxy_usdt=1580413, funding_indicative=-0.000096, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.72%, turnover=43121864. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-27T07:00:00+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=0.148280, depth_time=2026-10-27T07:00:07+00:00, book20_bid_proxy_usdt=7643, book20_ask_proxy_usdt=6727, funding_indicative=-0.000300, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-18.92%, turnover=11605625. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T07:00:00+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=0.993400, depth_time=2026-10-27T07:00:26+00:00, book20_bid_proxy_usdt=302464, book20_ask_proxy_usdt=614823, funding_indicative=-0.000110, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.14%, turnover=10743344. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T07:00:01+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=0.173200, depth_time=2026-10-27T07:00:24+00:00, book20_bid_proxy_usdt=1353253, book20_ask_proxy_usdt=1059370, funding_indicative=-0.000031, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.37%, turnover=6715014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T07:00:01+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=0.899300, depth_time=2026-10-27T07:00:21+00:00, book20_bid_proxy_usdt=1176551, book20_ask_proxy_usdt=1137088, funding_indicative=-0.000007, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.43%, turnover=6131115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T07:00:00+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=4.459000, depth_time=2026-10-27T07:00:12+00:00, book20_bid_proxy_usdt=4352342, book20_ask_proxy_usdt=2881105, funding_indicative=0.000040, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.09%, turnover=94812990. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T07:00:00+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=0.408800, depth_time=2026-10-27T07:00:19+00:00, book20_bid_proxy_usdt=2431580, book20_ask_proxy_usdt=3398602, funding_indicative=0.000008, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.62%, turnover=22351049. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T07:00:01+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=0.007462, depth_time=2026-10-27T07:00:36+00:00, book20_bid_proxy_usdt=155302, book20_ask_proxy_usdt=247806, funding_indicative=0.000013, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=5276060. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T07:00:01+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=0.004181, depth_time=2026-10-27T07:00:15+00:00, book20_bid_proxy_usdt=2218450, book20_ask_proxy_usdt=2143508, funding_indicative=0.000019, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.81%, turnover=21075508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T07:00:00+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=200.820000, depth_time=2026-10-27T07:00:09+00:00, book20_bid_proxy_usdt=38469, book20_ask_proxy_usdt=55315, funding_indicative=-0.000118, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.12%, turnover=125026319. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-27T07:00:00+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=53.710000, depth_time=2026-10-27T07:00:39+00:00, book20_bid_proxy_usdt=54125665, book20_ask_proxy_usdt=50040908, funding_indicative=0.000120, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.37%, turnover=254471650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T07:00:00+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=100.330000, depth_time=2026-10-27T07:00:38+00:00, book20_bid_proxy_usdt=16866208, book20_ask_proxy_usdt=15434843, funding_indicative=0.000043, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=682356156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T07:00:00+00:00, last15m_closed_end=2026-10-27T07:00+00:00, prior8high=0.438400, depth_time=2026-10-27T07:00:28+00:00, book20_bid_proxy_usdt=2941186, book20_ask_proxy_usdt=3870310, funding_indicative=-0.000234, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.98%, turnover=67689211. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
