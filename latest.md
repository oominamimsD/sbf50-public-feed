# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T21:30:44Z**
- feed_generated_utc: 2026-10-16T21:30:46+00:00
- source_sha256: `c5feda45f2bade5567c24d00846e8ae5e63c19a5a0d13caa23e80e26abdb07f1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T21:30+00:00, close=81694.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T21:00+00:00, close=81694.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INJ_USDT|8.575000|-4.48|23.75|-4.93|116926767|1.17|
|ZEC_USDT|1141.690000|-3.89|-6.29|-4.34|1457748285|0.09|
|BAT_USDT|0.197700|-3.57|62.50|-4.02|19057075|2.02|
|FILECOIN_USDT|1.129900|-3.16|5.59|-3.61|23334287|1.77|
|TAO_USDT|272.900000|-2.75|-0.64|-3.20|82369579|1.10|
|OP_USDT|0.136720|-2.34|10.95|-2.79|14667869|2.19|
|RIVER_USDT|1.104000|-1.95|-6.59|-2.40|5866113|9.05|
|ZRO_USDT|2.060900|-1.92|1.18|-2.37|15786863|2.42|
|ARB_USDT|0.191720|-1.65|6.03|-2.10|32916236|1.56|
|APT_USDT|0.842000|-1.64|5.18|-2.09|12518410|1.19|
|ICP_USDT|2.997000|-1.34|-0.72|-1.79|9157157|3.34|
|AAVE_USDT|155.190000|-1.32|-8.62|-1.77|31780476|1.29|
|AVAX_USDT|9.965000|-1.17|-2.22|-1.62|127125100|1.00|
|DOT_USDT|1.157200|-1.16|-2.59|-1.61|22322979|1.73|
|HBAR_USDT|0.083310|-0.95|-8.30|-1.40|20879276|1.20|
|FARTCOIN_USDT|0.153250|-0.95|-6.19|-1.40|7235066|0.65|
|ONDO_USDT|0.453100|-0.87|-5.62|-1.32|28675356|2.21|
|STRK_USDT|0.073310|-0.86|-2.65|-1.31|22856299|1.36|
|ENA_USDT|0.198480|-0.72|-7.93|-1.17|40794086|0.50|
|NEAR_USDT|5.010000|-0.71|5.45|-1.16|164715600|2.00|
|LTC_USDT|59.470000|-0.65|-6.49|-1.10|9808272|3.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.190000|154.930000|155.190000|0.88|N|Y/Y|Y/N|Y|N|
|APT_USDT|0.842000|0.834700|0.842000|0.32|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.191720|0.190740|0.191720|0.33|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.965000|9.924000|9.964000|0.65|N|Y/Y|Y/N|Y|N|
|BAT_USDT|0.197700|0.193970|0.197700|0.45|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.157200|1.145600|1.157200|1.47|N|Y/Y|N/N|Y|N|
|FILECOIN_USDT|1.129900|1.123800|1.129900|0.25|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.083310|0.082200|0.083280|0.78|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.997000|2.984000|2.997000|0.44|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.575000|8.469000|8.577000|0.85|N|Y/Y|N/N|Y|N|
|OP_USDT|0.136720|0.135160|0.136680|0.17|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.104000|1.071000|1.105000|0.35|N|Y/Y|Y/N|Y|N|
|TAO_USDT|272.900000|270.100000|272.900000|1.14|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1141.690000|1131.850000|1141.270000|0.65|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|2.060900|2.017100|2.061800|2.09|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=156.610000, depth_time=2026-10-16T21:30:35+00:00, book20_bid_proxy_usdt=460149, book20_ask_proxy_usdt=272500, funding_indicative=0.000069, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=31780476. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=0.848000, depth_time=2026-10-16T21:30:30+00:00, book20_bid_proxy_usdt=143384, book20_ask_proxy_usdt=104819, funding_indicative=0.000080, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=12518410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=0.194080, depth_time=2026-10-16T21:30:27+00:00, book20_bid_proxy_usdt=87432, book20_ask_proxy_usdt=33295, funding_indicative=-0.000054, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=32916236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=10.024000, depth_time=2026-10-16T21:30:37+00:00, book20_bid_proxy_usdt=804305, book20_ask_proxy_usdt=621770, funding_indicative=-0.000019, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.17%, turnover=127125100. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=0.199860, depth_time=2026-10-16T21:30:13+00:00, book20_bid_proxy_usdt=25230, book20_ask_proxy_usdt=26999, funding_indicative=-0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.57%, turnover=19057075. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=1.162700, depth_time=2026-10-16T21:30:40+00:00, book20_bid_proxy_usdt=203542, book20_ask_proxy_usdt=231461, funding_indicative=0.000071, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=22322979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=1.145500, depth_time=2026-10-16T21:30:15+00:00, book20_bid_proxy_usdt=661949, book20_ask_proxy_usdt=390088, funding_indicative=0.000090, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=23334287. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=0.083070, depth_time=2026-10-16T21:30:43+00:00, book20_bid_proxy_usdt=1266116, book20_ask_proxy_usdt=1128291, funding_indicative=0.000003, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.95%, turnover=20879276. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=3.024000, depth_time=2026-10-16T21:30:33+00:00, book20_bid_proxy_usdt=839147, book20_ask_proxy_usdt=1185663, funding_indicative=0.000097, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=9157157. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=8.745000, depth_time=2026-10-16T21:30:07+00:00, book20_bid_proxy_usdt=211820, book20_ask_proxy_usdt=322612, funding_indicative=-0.000026, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.48%, turnover=116926767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=0.137590, depth_time=2026-10-16T21:30:20+00:00, book20_bid_proxy_usdt=48249, book20_ask_proxy_usdt=56569, funding_indicative=0.000039, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=14667869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=1.102000, depth_time=2026-10-16T21:30:23+00:00, book20_bid_proxy_usdt=395016, book20_ask_proxy_usdt=510977, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=5866113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=276.400000, depth_time=2026-10-16T21:30:17+00:00, book20_bid_proxy_usdt=69989, book20_ask_proxy_usdt=70661, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=82369579. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=1153.360000, depth_time=2026-10-16T21:30:10+00:00, book20_bid_proxy_usdt=37421, book20_ask_proxy_usdt=275050, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.89%, turnover=1457748285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T21:30:01+00:00, last15m_closed_end=2026-10-16T21:30+00:00, prior8high=2.104200, depth_time=2026-10-16T21:30:25+00:00, book20_bid_proxy_usdt=38724, book20_ask_proxy_usdt=76292, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=15786863. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
