# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T06:30:41Z**
- feed_generated_utc: 2026-10-27T06:30:45+00:00
- source_sha256: `f37c9bb96d2cf7090fc44b1f3b81bcdeff0d1fb6d6d5590fac95487e8a1d8f66`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T06:30+00:00, close=79724.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T06:00+00:00, close=79935.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.100450|-32.63|39.47|-31.80|11407515|3.00|
|QNT_USDT|198.600000|-5.55|1.48|-4.72|126090879|1.51|
|ZRO_USDT|1.612500|-5.54|-15.22|-4.71|5012162|0.62|
|PUMPFUN_USDT|0.004144|-4.25|-7.00|-3.42|21181622|2.41|
|AAVE_USDT|131.800000|-3.60|-10.47|-2.77|25139592|0.76|
|NEAR_USDT|4.417000|-3.41|-9.93|-2.58|98733530|4.53|
|DOT_USDT|0.989400|-3.24|-13.72|-2.41|11159592|1.01|
|FILECOIN_USDT|0.894500|-2.84|-11.61|-2.01|6442334|1.12|
|AVAX_USDT|8.753000|-2.71|-8.46|-1.88|49135915|1.14|
|ONDO_USDT|0.407500|-2.69|-5.80|-1.86|22626879|2.45|
|ZEC_USDT|1215.000000|-2.62|7.98|-1.79|1458112301|0.41|
|FET_USDT|0.172000|-2.60|-8.99|-1.77|6734815|5.82|
|INJ_USDT|7.736000|-2.49|-9.53|-1.66|24312629|1.29|
|SILVER_USDT|53.030000|-2.21|-7.56|-1.38|259061981|1.89|
|WLD_USDT|0.435900|-2.04|-13.90|-1.21|68920194|2.29|
|PENGU_USDT|0.007422|-2.00|-0.92|-1.17|5508063|1.35|
|SOL_USDT|99.810000|-1.99|-4.11|-1.16|683804180|1.00|
|TAO_USDT|248.800000|-1.85|-7.26|-1.02|45192539|1.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.800000|131.790000|131.790000|3.42|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.753000|8.656000|8.753000|1.01|N|Y/Y|Y/Y|Y|N|
|BULLA_USDT|0.100450|0.128820|0.100450|26.78|Y|Y/N|N/N|Y|N|
|DOT_USDT|0.989400|0.984100|0.989400|0.12|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.172000|0.171200|0.172000|1.01|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.894500|0.888900|0.894500|0.31|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.736000|7.726000|7.736000|0.70|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.417000|4.405000|4.417000|0.71|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.407500|0.404900|0.407500|0.63|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004144|0.004134|0.004144|0.54|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|198.600000|196.820000|198.600000|0.45|N|Y/Y|N/N|Y|N|
|SILVER_USDT|53.030000|52.840000|53.000000|1.31|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.435900|0.434300|0.435900|1.04|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1215.000000|1212.160000|1214.940000|1.24|N|Y/Y|N/N|Y|N|
|ZRO_USDT|1.612500|1.599400|1.612400|1.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T06:30:00+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=133.020000, depth_time=2026-10-27T06:30:17+00:00, book20_bid_proxy_usdt=370137, book20_ask_proxy_usdt=482015, funding_indicative=0.000075, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.60%, turnover=25139592. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T06:30:00+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=8.786000, depth_time=2026-10-27T06:30:25+00:00, book20_bid_proxy_usdt=1079962, book20_ask_proxy_usdt=1795181, funding_indicative=-0.000096, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.71%, turnover=49135915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-27T06:30:00+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=0.148910, depth_time=2026-10-27T06:30:07+00:00, book20_bid_proxy_usdt=235523, book20_ask_proxy_usdt=21258, funding_indicative=0.000050, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-32.63%, turnover=11407515. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T06:30:00+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=0.993400, depth_time=2026-10-27T06:30:21+00:00, book20_bid_proxy_usdt=287714, book20_ask_proxy_usdt=208916, funding_indicative=-0.000106, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.24%, turnover=11159592. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T06:30:01+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=0.173200, depth_time=2026-10-27T06:30:33+00:00, book20_bid_proxy_usdt=1893305, book20_ask_proxy_usdt=1127674, funding_indicative=-0.000036, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.60%, turnover=6734815. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T06:30:01+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=0.899300, depth_time=2026-10-27T06:30:22+00:00, book20_bid_proxy_usdt=1149748, book20_ask_proxy_usdt=1465708, funding_indicative=-0.000018, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.84%, turnover=6442334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T06:30:00+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=7.937000, depth_time=2026-10-27T06:30:35+00:00, book20_bid_proxy_usdt=216485, book20_ask_proxy_usdt=222620, funding_indicative=0.000184, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=24312629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T06:30:00+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=4.459000, depth_time=2026-10-27T06:30:19+00:00, book20_bid_proxy_usdt=5087414, book20_ask_proxy_usdt=4243469, funding_indicative=0.000024, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.41%, turnover=98733530. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T06:30:00+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=0.408800, depth_time=2026-10-27T06:30:29+00:00, book20_bid_proxy_usdt=2356705, book20_ask_proxy_usdt=3959588, funding_indicative=0.000008, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=22626879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T06:30:00+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=0.004181, depth_time=2026-10-27T06:30:15+00:00, book20_bid_proxy_usdt=1882624, book20_ask_proxy_usdt=2442898, funding_indicative=0.000016, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.25%, turnover=21181622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T06:30:00+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=202.240000, depth_time=2026-10-27T06:30:10+00:00, book20_bid_proxy_usdt=74028, book20_ask_proxy_usdt=66224, funding_indicative=-0.000116, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.55%, turnover=126090879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-27T06:30:00+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=53.920000, depth_time=2026-10-27T06:30:38+00:00, book20_bid_proxy_usdt=55720602, book20_ask_proxy_usdt=39162319, funding_indicative=0.000114, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.21%, turnover=259061981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T06:30:00+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=0.438400, depth_time=2026-10-27T06:30:40+00:00, book20_bid_proxy_usdt=3120828, book20_ask_proxy_usdt=3133806, funding_indicative=-0.000242, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.04%, turnover=68920194. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-27T06:30:00+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=1229.280000, depth_time=2026-10-27T06:30:30+00:00, book20_bid_proxy_usdt=508905, book20_ask_proxy_usdt=964427, funding_indicative=0.000063, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=1458112301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T06:30:01+00:00, last15m_closed_end=2026-10-27T06:30+00:00, prior8high=1.622400, depth_time=2026-10-27T06:30:12+00:00, book20_bid_proxy_usdt=33489, book20_ask_proxy_usdt=25195, funding_indicative=0.000027, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.54%, turnover=5012162. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
