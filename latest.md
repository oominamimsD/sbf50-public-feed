# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T09:00:43Z**
- feed_generated_utc: 2026-10-27T09:00:47+00:00
- source_sha256: `323826f02adb7417e858d04bbbe132b93f4851826a391d7c4489a826bf14cd74`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T09:00+00:00, close=79834.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T09:00+00:00, close=79834.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.118220|-20.72|64.14|-20.03|11710658|4.22|
|IRYS_USDT|0.025820|-6.38|110.26|-5.69|7438163|3.88|
|PUMPFUN_USDT|0.004172|-4.24|-6.37|-3.55|21177525|2.40|
|NEAR_USDT|4.462000|-4.14|-9.01|-3.45|91294713|2.24|
|AAVE_USDT|131.080000|-4.13|-10.96|-3.44|23649876|0.76|
|ONDO_USDT|0.408500|-3.31|-5.57|-2.62|22765614|2.45|
|QNT_USDT|206.530000|-3.15|5.53|-2.46|128946052|4.36|
|FILECOIN_USDT|0.897400|-3.14|-11.32|-2.45|5732894|1.11|
|ENA_USDT|0.204170|-2.97|8.64|-2.28|82808192|0.49|
|DOT_USDT|0.993900|-2.80|-13.33|-2.11|10432633|1.01|
|WLD_USDT|0.436000|-2.72|-13.88|-2.03|65301496|2.29|
|TIA_USDT|0.527900|-2.52|-13.24|-1.83|16590155|1.89|
|INJ_USDT|7.794000|-2.35|-8.85|-1.66|22131256|1.28|
|AVAX_USDT|8.800000|-2.23|-7.96|-1.54|29136271|1.14|
|SOL_USDT|99.900000|-2.14|-4.02|-1.45|661781623|1.00|
|SILVER_USDT|53.110000|-2.06|-7.42|-1.37|254348422|1.88|
|TAO_USDT|248.400000|-2.01|-7.41|-1.32|44063641|1.21|
|ARB_USDT|0.166960|-1.78|-14.65|-1.09|19741255|0.60|
|HBAR_USDT|0.076300|-1.77|-6.80|-1.08|9878524|1.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.080000|130.760000|131.070000|2.40|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.800000|8.743000|8.800000|0.34|N|Y/Y|Y/Y|Y|N|
|BULLA_USDT|0.118220|0.092630|0.118270|1.06|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.993900|0.988300|0.994000|1.11|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.204170|0.204830|0.204170|3.85|Y|Y/Y|N/N|Y|N|
|FILECOIN_USDT|0.897400|0.892900|0.897400|1.11|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.794000|7.750000|7.797000|0.65|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.025820|0.025760|0.025820|1.08|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.462000|4.405000|4.462000|0.77|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.408500|0.406100|0.408500|1.07|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004172|0.004131|0.004172|3.46|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|206.530000|199.860000|206.530000|0.76|N|N/N|N/N|Y|N|
|SOL_USDT|99.900000|99.380000|99.900000|0.39|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.527900|0.525700|0.527900|0.88|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.436000|0.432500|0.436000|0.36|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T09:00:03+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=132.300000, depth_time=2026-10-27T09:00:15+00:00, book20_bid_proxy_usdt=295263, book20_ask_proxy_usdt=392609, funding_indicative=0.000088, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.13%, turnover=23649876. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T09:00:03+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=8.828000, depth_time=2026-10-27T09:00:39+00:00, book20_bid_proxy_usdt=965839, book20_ask_proxy_usdt=1380460, funding_indicative=-0.000048, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=29136271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-27T09:00:02+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=0.133100, depth_time=2026-10-27T09:00:08+00:00, book20_bid_proxy_usdt=6891, book20_ask_proxy_usdt=10315, funding_indicative=-0.000491, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-20.72%, turnover=11710658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T09:00:03+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=1.001200, depth_time=2026-10-27T09:00:29+00:00, book20_bid_proxy_usdt=351442, book20_ask_proxy_usdt=318799, funding_indicative=-0.000056, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=10432633. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T09:00:02+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=0.208980, depth_time=2026-10-27T09:00:27+00:00, book20_bid_proxy_usdt=141592, book20_ask_proxy_usdt=119282, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.97%, turnover=82808192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T09:00:03+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=0.903000, depth_time=2026-10-27T09:00:25+00:00, book20_bid_proxy_usdt=1151198, book20_ask_proxy_usdt=1712673, funding_indicative=0.000024, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.14%, turnover=5732894. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T09:00:03+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=7.851000, depth_time=2026-10-27T09:00:37+00:00, book20_bid_proxy_usdt=210134, book20_ask_proxy_usdt=169511, funding_indicative=0.000186, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.35%, turnover=22131256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T09:00:02+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=0.027420, depth_time=2026-10-27T09:00:09+00:00, book20_bid_proxy_usdt=113104, book20_ask_proxy_usdt=111891, funding_indicative=-0.000526, next_funding_utc=2026-10-27T10:00:00+00:00, funding_cycle_h=1, 24h_change=-6.38%, turnover=7438163. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T09:00:02+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=4.488000, depth_time=2026-10-27T09:00:15+00:00, book20_bid_proxy_usdt=3847556, book20_ask_proxy_usdt=4554368, funding_indicative=0.000078, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.14%, turnover=91294713. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T09:00:02+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=0.411600, depth_time=2026-10-27T09:00:20+00:00, book20_bid_proxy_usdt=2168620, book20_ask_proxy_usdt=3714768, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.31%, turnover=22765614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T09:00:03+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=0.004216, depth_time=2026-10-27T09:00:12+00:00, book20_bid_proxy_usdt=2091814, book20_ask_proxy_usdt=2471044, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.24%, turnover=21177525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T09:00:02+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=211.660000, depth_time=2026-10-27T09:00:22+00:00, book20_bid_proxy_usdt=35598, book20_ask_proxy_usdt=101161, funding_indicative=-0.000265, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.15%, turnover=128946052. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T09:00:02+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=100.360000, depth_time=2026-10-27T09:00:42+00:00, book20_bid_proxy_usdt=20851133, book20_ask_proxy_usdt=20195965, funding_indicative=0.000052, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=661781623. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T09:00:03+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=0.533400, depth_time=2026-10-27T09:00:34+00:00, book20_bid_proxy_usdt=355179, book20_ask_proxy_usdt=463608, funding_indicative=0.000003, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=16590155. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T09:00:02+00:00, last15m_closed_end=2026-10-27T09:00+00:00, prior8high=0.439800, depth_time=2026-10-27T09:00:32+00:00, book20_bid_proxy_usdt=3473578, book20_ask_proxy_usdt=3658085, funding_indicative=-0.000200, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.72%, turnover=65301496. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
