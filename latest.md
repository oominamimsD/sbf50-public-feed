# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T08:15:38Z**
- feed_generated_utc: 2026-10-27T08:15:42+00:00
- source_sha256: `d12597a5f41d2d8f08c30a8c665f4272b12bc5de0936e51637b86273fe4013a3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T08:15+00:00, close=79815.4, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.026370|-4.38|114.73|-3.66|7725833|7.58|
|AAVE_USDT|131.210000|-4.03|-10.87|-3.31|23783615|0.76|
|PUMPFUN_USDT|0.004195|-3.07|-5.85|-2.35|21466042|4.77|
|DOT_USDT|0.994200|-2.77|-13.30|-2.05|10774560|1.01|
|FILECOIN_USDT|0.899400|-2.31|-11.12|-1.59|6127980|1.11|
|AVAX_USDT|8.791000|-2.28|-8.06|-1.56|37964392|1.14|
|NEAR_USDT|4.469000|-2.27|-8.87|-1.55|94530000|2.24|
|SILVER_USDT|53.090000|-2.10|-7.46|-1.38|256075909|1.88|
|PEPE_USDT|0.000004|-2.01|4.01|-1.29|62015195|0.93|
|INJ_USDT|7.778000|-1.96|-9.03|-1.24|23510863|1.29|
|WLD_USDT|0.436400|-1.93|-13.80|-1.21|67790705|2.29|
|SOL_USDT|99.940000|-1.86|-3.98|-1.14|711289833|1.00|
|TAO_USDT|248.930000|-1.80|-7.21|-1.08|46182540|1.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.210000|131.060000|131.210000|0.84|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.791000|8.733000|8.791000|0.80|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.994200|0.986400|0.994100|2.02|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.899400|0.892900|0.899400|1.18|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.778000|7.725000|7.778000|0.94|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.026370|0.026260|0.026370|1.65|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.469000|4.405000|4.469000|1.57|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.89|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004195|0.004131|0.004193|2.05|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|53.090000|52.800000|53.090000|0.71|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|99.940000|99.380000|99.940000|0.96|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|248.930000|247.500000|249.000000|2.20|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.436400|0.432500|0.436400|1.26|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T08:15:01+00:00, last15m_closed_end=2026-10-27T08:15+00:00, prior8high=132.300000, depth_time=2026-10-27T08:15:10+00:00, book20_bid_proxy_usdt=391804, book20_ask_proxy_usdt=756716, funding_indicative=0.000070, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.03%, turnover=23783615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T08:15:01+00:00, last15m_closed_end=2026-10-27T08:15+00:00, prior8high=8.828000, depth_time=2026-10-27T08:15:19+00:00, book20_bid_proxy_usdt=1467955, book20_ask_proxy_usdt=928892, funding_indicative=-0.000069, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.28%, turnover=37964392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T08:15:01+00:00, last15m_closed_end=2026-10-27T08:15+00:00, prior8high=1.001200, depth_time=2026-10-27T08:15:15+00:00, book20_bid_proxy_usdt=336604, book20_ask_proxy_usdt=278696, funding_indicative=0.000003, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.77%, turnover=10774560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T08:15:01+00:00, last15m_closed_end=2026-10-27T08:15+00:00, prior8high=0.903000, depth_time=2026-10-27T08:15:16+00:00, book20_bid_proxy_usdt=1438148, book20_ask_proxy_usdt=1505774, funding_indicative=0.000016, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.31%, turnover=6127980. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-27T08:15:01+00:00, last15m_closed_end=2026-10-27T08:15+00:00, prior8high=7.851000, depth_time=2026-10-27T08:15:30+00:00, book20_bid_proxy_usdt=210465, book20_ask_proxy_usdt=488688, funding_indicative=0.000181, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=23510863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T08:15:01+00:00, last15m_closed_end=2026-10-27T08:15+00:00, prior8high=0.029280, depth_time=2026-10-27T08:15:08+00:00, book20_bid_proxy_usdt=138635, book20_ask_proxy_usdt=102859, funding_indicative=-0.000786, next_funding_utc=2026-10-27T09:00:00+00:00, funding_cycle_h=1, 24h_change=-4.38%, turnover=7725833. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T08:15:01+00:00, last15m_closed_end=2026-10-27T08:15+00:00, prior8high=4.488000, depth_time=2026-10-27T08:15:23+00:00, book20_bid_proxy_usdt=5721658, book20_ask_proxy_usdt=4840231, funding_indicative=0.000063, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=94530000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-27T08:15:01+00:00, last15m_closed_end=2026-10-27T08:15+00:00, prior8high=0.000004, depth_time=2026-10-27T08:15:28+00:00, book20_bid_proxy_usdt=63108, book20_ask_proxy_usdt=63015, funding_indicative=0.000061, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=62015195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T08:15:01+00:00, last15m_closed_end=2026-10-27T08:15+00:00, prior8high=0.004216, depth_time=2026-10-27T08:15:13+00:00, book20_bid_proxy_usdt=3019405, book20_ask_proxy_usdt=2201322, funding_indicative=0.000038, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=21466042. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-27T08:15:01+00:00, last15m_closed_end=2026-10-27T08:15+00:00, prior8high=53.480000, depth_time=2026-10-27T08:15:24+00:00, book20_bid_proxy_usdt=50355729, book20_ask_proxy_usdt=41486733, funding_indicative=0.000092, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.10%, turnover=256075909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T08:15:01+00:00, last15m_closed_end=2026-10-27T08:15+00:00, prior8high=100.360000, depth_time=2026-10-27T08:15:35+00:00, book20_bid_proxy_usdt=18977861, book20_ask_proxy_usdt=15459336, funding_indicative=0.000047, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=711289833. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T08:15:01+00:00, last15m_closed_end=2026-10-27T08:15+00:00, prior8high=250.230000, depth_time=2026-10-27T08:15:36+00:00, book20_bid_proxy_usdt=160343, book20_ask_proxy_usdt=148084, funding_indicative=0.000042, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.80%, turnover=46182540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T08:15:01+00:00, last15m_closed_end=2026-10-27T08:15+00:00, prior8high=0.439800, depth_time=2026-10-27T08:15:32+00:00, book20_bid_proxy_usdt=2628179, book20_ask_proxy_usdt=3541504, funding_indicative=-0.000220, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=67790705. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
