# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T00:30:43Z**
- feed_generated_utc: 2026-10-17T00:30:45+00:00
- source_sha256: `5993c9718685733756a9786027aa747c555ea4e1014f0ace60d927b60dc96180`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T00:30+00:00, close=81555.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.948100|-7.29|-4.35|-7.57|16627809|1.54|
|BAT_USDT|0.196460|-4.17|61.48|-4.45|16561612|2.54|
|INJ_USDT|8.624000|-3.94|24.46|-4.22|116321562|1.16|
|RIVER_USDT|1.084000|-3.73|-8.29|-4.01|5500087|9.23|
|ZEC_USDT|1149.490000|-3.24|-5.65|-3.52|1374877438|0.43|
|FILECOIN_USDT|1.135700|-2.66|6.14|-2.94|22628313|0.88|
|ARB_USDT|0.190130|-2.46|5.16|-2.74|31042834|0.53|
|AAVE_USDT|154.270000|-1.91|-9.16|-2.19|31316809|0.65|
|TAO_USDT|275.430000|-1.84|0.27|-2.12|83355583|0.73|
|STRK_USDT|0.072620|-1.79|-3.57|-2.07|21082145|1.38|
|APT_USDT|0.842400|-1.60|5.23|-1.88|12524563|1.19|
|AVAX_USDT|9.924000|-1.57|-2.62|-1.85|125974306|2.02|
|SUI_USDT|1.006200|-1.40|-4.86|-1.68|96387251|0.99|
|ENA_USDT|0.197390|-1.27|-8.43|-1.55|40749865|0.51|
|ONDO_USDT|0.451400|-1.24|-5.97|-1.52|28766680|2.21|
|ICP_USDT|3.009000|-0.95|-0.33|-1.23|8778375|3.32|
|HBAR_USDT|0.083380|-0.86|-8.23|-1.14|21188452|1.20|
|QNT_USDT|199.880000|-0.82|-19.86|-1.10|67438285|0.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.270000|154.690000|154.280000|1.03|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.842400|0.833500|0.842400|2.75|N|N/Y|N/N|Y|N|
|ARB_USDT|0.190130|0.190500|0.190130|1.48|Y|Y/Y|N/N|Y|N|
|AVAX_USDT|9.924000|9.919000|9.924000|0.86|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.196460|0.194970|0.196390|0.79|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.197390|0.198000|0.197380|2.19|Y|Y/Y|Y/Y|Y|Y|
|FILECOIN_USDT|1.135700|1.128700|1.135700|0.67|N|N/Y|N/N|Y|N|
|INJ_USDT|8.624000|8.609000|8.624000|0.61|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.451400|0.452500|0.451400|1.61|Y|Y/Y|Y/Y|Y|Y|
|RIVER_USDT|1.084000|1.084000|1.084000|1.91|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.072620|0.072680|0.072630|1.96|Y|Y/Y|Y/Y|Y|Y|
|SUI_USDT|1.006200|1.014300|1.006200|2.28|Y|Y/Y|Y/Y|Y|Y|
|TAO_USDT|275.430000|273.100000|275.440000|0.66|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1149.490000|1140.570000|1149.490000|0.76|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.948100|2.010000|1.947200|4.19|Y|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=155.320000, depth_time=2026-10-17T00:30:25+00:00, book20_bid_proxy_usdt=277882, book20_ask_proxy_usdt=347197, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=31316809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=0.848400, depth_time=2026-10-17T00:30:30+00:00, book20_bid_proxy_usdt=93129, book20_ask_proxy_usdt=162994, funding_indicative=0.000030, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=12524563. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=0.191870, depth_time=2026-10-17T00:30:21+00:00, book20_bid_proxy_usdt=69741, book20_ask_proxy_usdt=79907, funding_indicative=-0.000119, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=31042834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=9.997000, depth_time=2026-10-17T00:30:33+00:00, book20_bid_proxy_usdt=530557, book20_ask_proxy_usdt=887623, funding_indicative=0.000029, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=125974306. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=0.201600, depth_time=2026-10-17T00:30:10+00:00, book20_bid_proxy_usdt=24481, book20_ask_proxy_usdt=33446, funding_indicative=-0.000088, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.17%, turnover=16561612. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=0.199290, depth_time=2026-10-17T00:30:40+00:00, book20_bid_proxy_usdt=102210, book20_ask_proxy_usdt=252528, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=40749865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=1.159600, depth_time=2026-10-17T00:30:15+00:00, book20_bid_proxy_usdt=560160, book20_ask_proxy_usdt=692239, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=22628313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=8.739000, depth_time=2026-10-17T00:30:12+00:00, book20_bid_proxy_usdt=207871, book20_ask_proxy_usdt=323765, funding_indicative=-0.000135, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.94%, turnover=116321562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=0.456600, depth_time=2026-10-17T00:30:42+00:00, book20_bid_proxy_usdt=1746510, book20_ask_proxy_usdt=2378455, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=28766680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=1.102000, depth_time=2026-10-17T00:30:13+00:00, book20_bid_proxy_usdt=500941, book20_ask_proxy_usdt=300389, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.73%, turnover=5500087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=0.074200, depth_time=2026-10-17T00:30:30+00:00, book20_bid_proxy_usdt=329777, book20_ask_proxy_usdt=267699, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=21082145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=1.024100, depth_time=2026-10-17T00:30:37+00:00, book20_bid_proxy_usdt=514858, book20_ask_proxy_usdt=1626706, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.40%, turnover=96387251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=276.100000, depth_time=2026-10-17T00:30:26+00:00, book20_bid_proxy_usdt=109108, book20_ask_proxy_usdt=135536, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=83355583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=1153.000000, depth_time=2026-10-17T00:30:17+00:00, book20_bid_proxy_usdt=264089, book20_ask_proxy_usdt=123253, funding_indicative=0.000089, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.24%, turnover=1374877438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T00:30:01+00:00, last15m_closed_end=2026-10-17T00:30+00:00, prior8high=2.066300, depth_time=2026-10-17T00:30:07+00:00, book20_bid_proxy_usdt=45239, book20_ask_proxy_usdt=61398, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.29%, turnover=16627809. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
