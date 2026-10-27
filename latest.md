# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T11:30:45Z**
- feed_generated_utc: 2026-10-27T11:30:49+00:00
- source_sha256: `d2f10dba0116311d466a3d79b90e51eeb551a85c4d7fd4feaae710f13038a714`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T11:30+00:00, close=79876.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T11:00+00:00, close=79941, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T08:00+00:00, close=79774.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.024910|-9.68|102.85|-9.04|7503000|4.01|
|ENA_USDT|0.201540|-4.19|7.24|-3.55|87783197|0.50|
|AAVE_USDT|131.310000|-3.96|-10.80|-3.32|27590890|0.76|
|PUMPFUN_USDT|0.004165|-3.76|-6.53|-3.12|20554410|2.40|
|DOT_USDT|0.985900|-3.58|-14.03|-2.94|11212175|1.01|
|QNT_USDT|202.840000|-3.53|3.64|-2.89|123196622|0.49|
|WLD_USDT|0.430700|-3.21|-14.93|-2.57|68337015|2.32|
|ZRO_USDT|1.653400|-3.14|-13.07|-2.50|5132217|0.60|
|FILECOIN_USDT|0.893400|-2.96|-11.71|-2.32|6396475|1.12|
|ONDO_USDT|0.407800|-2.62|-5.73|-1.98|23141238|2.45|
|AVAX_USDT|8.762000|-2.61|-8.36|-1.97|21483146|1.14|
|PEPE_USDT|0.000004|-2.14|3.87|-1.50|60088545|0.23|
|TIA_USDT|0.524800|-2.03|-13.75|-1.39|17488200|1.91|
|TAO_USDT|248.390000|-2.01|-7.42|-1.37|49939910|1.21|
|NEAR_USDT|4.483000|-1.96|-8.58|-1.32|93792249|2.23|
|HBAR_USDT|0.075840|-1.96|-7.36|-1.32|10917768|1.32|
|ARB_USDT|0.166820|-1.86|-14.72|-1.22|17951095|0.60|
|SOL_USDT|99.970000|-1.83|-3.95|-1.19|679818861|1.00|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.310000|129.420000|131.310000|0.29|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.762000|8.687000|8.762000|1.42|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.985900|0.979300|0.985900|1.00|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.201540|0.197200|0.201540|1.29|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|0.893400|0.884300|0.893100|2.84|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.024910|0.024760|0.024910|1.54|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.483000|4.389000|4.482000|3.74|N|N/Y|Y/Y|Y|N|
|ONDO_USDT|0.407800|0.402800|0.407800|0.77|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.11|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004165|0.004093|0.004165|0.65|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|202.840000|200.970000|202.840000|0.96|N|N/N|N/N|Y|N|
|TAO_USDT|248.390000|245.490000|248.340000|1.46|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.524800|0.519500|0.524800|2.90|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.430700|0.427500|0.430700|2.06|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.653400|1.605300|1.653600|0.56|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T11:30:00+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=131.800000, depth_time=2026-10-27T11:30:13+00:00, book20_bid_proxy_usdt=370902, book20_ask_proxy_usdt=800560, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.96%, turnover=27590890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T11:30:00+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=8.826000, depth_time=2026-10-27T11:30:33+00:00, book20_bid_proxy_usdt=977753, book20_ask_proxy_usdt=1762553, funding_indicative=0.000043, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=21483146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T11:30:00+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=0.992500, depth_time=2026-10-27T11:30:19+00:00, book20_bid_proxy_usdt=223375, book20_ask_proxy_usdt=272949, funding_indicative=-0.000079, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=11212175. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T11:30:00+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=0.205910, depth_time=2026-10-27T11:30:11+00:00, book20_bid_proxy_usdt=173637, book20_ask_proxy_usdt=162695, funding_indicative=0.000006, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.19%, turnover=87783197. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T11:30:01+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=0.900900, depth_time=2026-10-27T11:30:28+00:00, book20_bid_proxy_usdt=926310, book20_ask_proxy_usdt=1282141, funding_indicative=0.000051, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=6396475. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T11:30:00+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=0.026140, depth_time=2026-10-27T11:30:09+00:00, book20_bid_proxy_usdt=151934, book20_ask_proxy_usdt=156606, funding_indicative=-0.000671, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=1, 24h_change=-9.68%, turnover=7503000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T11:30:00+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=4.522000, depth_time=2026-10-27T11:30:43+00:00, book20_bid_proxy_usdt=3969432, book20_ask_proxy_usdt=4465239, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=93792249. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T11:30:00+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=0.411000, depth_time=2026-10-27T11:30:32+00:00, book20_bid_proxy_usdt=2301508, book20_ask_proxy_usdt=4095337, funding_indicative=0.000033, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.62%, turnover=23141238. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-27T11:30:00+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=0.000004, depth_time=2026-10-27T11:30:36+00:00, book20_bid_proxy_usdt=71638, book20_ask_proxy_usdt=63802, funding_indicative=0.000063, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=60088545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T11:30:00+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=0.004221, depth_time=2026-10-27T11:30:17+00:00, book20_bid_proxy_usdt=2309897, book20_ask_proxy_usdt=2473402, funding_indicative=0.000050, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.76%, turnover=20554410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T11:30:00+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=207.190000, depth_time=2026-10-27T11:30:22+00:00, book20_bid_proxy_usdt=58104, book20_ask_proxy_usdt=84896, funding_indicative=-0.000210, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.53%, turnover=123196622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T11:30:00+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=250.060000, depth_time=2026-10-27T11:30:41+00:00, book20_bid_proxy_usdt=84321, book20_ask_proxy_usdt=259730, funding_indicative=0.000027, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=49939910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T11:30:00+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=0.529500, depth_time=2026-10-27T11:30:39+00:00, book20_bid_proxy_usdt=413745, book20_ask_proxy_usdt=426547, funding_indicative=0.000016, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.03%, turnover=17488200. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T11:30:00+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=0.435500, depth_time=2026-10-27T11:30:24+00:00, book20_bid_proxy_usdt=2997134, book20_ask_proxy_usdt=3967192, funding_indicative=-0.000084, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=68337015. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T11:30:01+00:00, last15m_closed_end=2026-10-27T11:30+00:00, prior8high=1.668700, depth_time=2026-10-27T11:30:27+00:00, book20_bid_proxy_usdt=29249, book20_ask_proxy_usdt=16455, funding_indicative=0.000048, next_funding_utc=2026-10-27T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.14%, turnover=5132217. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
