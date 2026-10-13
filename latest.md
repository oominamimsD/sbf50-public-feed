# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T05:45:43Z**
- feed_generated_utc: 2026-10-13T05:45:46+00:00
- source_sha256: `d7df9460e5d82a2760f234f6ad15a1e708d076d2672392712032c4176235d2d3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T05:45+00:00, close=83556.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T05:00+00:00, close=83419.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOS_USDT|0.232900|-19.55|9.34|-20.60|9286651|4.29|
|ZRO_USDT|2.111000|-6.63|3.19|-7.68|30547123|0.47|
|LIT_USDT|3.454500|-4.70|-9.14|-5.75|11261593|0.29|
|NEAR_USDT|5.298000|-4.52|5.49|-5.57|285484313|1.89|
|PUMPFUN_USDT|0.005071|-4.48|-19.95|-5.53|32913131|1.97|
|ZEC_USDT|1210.490000|-4.30|-6.51|-5.35|1715610634|0.08|
|ENA_USDT|0.212760|-4.01|-13.36|-5.06|70245193|1.88|
|STRK_USDT|0.087110|-3.92|67.16|-4.97|65320148|1.15|
|ICP_USDT|3.174000|-3.67|-8.42|-4.72|16949619|3.15|
|SEI_USDT|0.064280|-3.14|-10.61|-4.19|9626994|1.56|
|RLC_USDT|0.957900|-3.10|74.79|-4.15|7259221|3.13|
|HBAR_USDT|0.087790|-2.99|-12.82|-4.04|22275765|1.14|
|ONDO_USDT|0.484100|-2.81|-0.96|-3.86|61863629|2.07|
|USELESS_USDT|0.177320|-2.35|-21.79|-3.40|6921387|1.69|
|JUP_USDT|0.335800|-2.07|-0.62|-3.12|9041647|2.98|
|PONS_USDT|0.289200|-1.86|-24.58|-2.91|6380321|3.46|
|LTC_USDT|61.940000|-1.62|-11.46|-2.67|22631272|1.61|
|FET_USDT|0.218500|-1.35|-12.35|-2.40|22186580|4.58|
|ATOM_USDT|1.818000|-0.54|2.02|-1.59|12846679|5.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.232900|0.231400|0.232900|0.72|N|Y/Y|Y/N|N|N|
|ENA_USDT|0.212760|0.210050|0.212730|0.78|N|Y/Y|Y/Y|N|N|
|HBAR_USDT|0.087790|0.087260|0.087790|1.58|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.174000|3.116000|3.174000|3.25|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.335800|0.332500|0.335800|0.35|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.454500|3.414500|3.454500|0.59|N|Y/Y|Y/Y|N|N|
|NEAR_USDT|5.298000|5.273000|5.298000|0.99|N|Y/Y|Y/Y|N|N|
|ONDO_USDT|0.484100|0.477700|0.484100|0.88|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005071|0.005026|0.005071|0.89|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.957900|0.939400|0.957900|0.83|N|Y/Y|Y/Y|N|N|
|SEI_USDT|0.064280|0.063050|0.064260|2.27|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.087110|0.082550|0.087110|0.51|N|Y/Y|Y/Y|N|N|
|USELESS_USDT|0.177320|0.173080|0.177320|1.19|N|Y/Y|Y/Y|N|N|
|ZEC_USDT|1210.490000|1204.670000|1210.200000|0.90|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.111000|2.098900|2.110900|0.78|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T05:45:01+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=0.251000, depth_time=2026-10-13T05:45:08+00:00, book20_bid_proxy_usdt=149591, book20_ask_proxy_usdt=71168, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.55%, turnover=9286651. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-13T05:45:01+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=0.214970, depth_time=2026-10-13T05:45:23+00:00, book20_bid_proxy_usdt=155903, book20_ask_proxy_usdt=161069, funding_indicative=-0.000031, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.01%, turnover=70245193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T05:45:02+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=0.088580, depth_time=2026-10-13T05:45:35+00:00, book20_bid_proxy_usdt=343755, book20_ask_proxy_usdt=898327, funding_indicative=0.000001, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.99%, turnover=22275765. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T05:45:02+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=3.205000, depth_time=2026-10-13T05:45:25+00:00, book20_bid_proxy_usdt=798704, book20_ask_proxy_usdt=810173, funding_indicative=-0.000063, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.67%, turnover=16949619. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T05:45:02+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=0.338400, depth_time=2026-10-13T05:45:41+00:00, book20_bid_proxy_usdt=538740, book20_ask_proxy_usdt=478579, funding_indicative=-0.000055, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=9041647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T05:45:02+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=3.476600, depth_time=2026-10-13T05:45:13+00:00, book20_bid_proxy_usdt=23693, book20_ask_proxy_usdt=38085, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.70%, turnover=11261593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-13T05:45:01+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=5.363000, depth_time=2026-10-13T05:45:16+00:00, book20_bid_proxy_usdt=2304027, book20_ask_proxy_usdt=2722133, funding_indicative=-0.000089, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.52%, turnover=285484313. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-13T05:45:01+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=0.488400, depth_time=2026-10-13T05:45:37+00:00, book20_bid_proxy_usdt=1682232, book20_ask_proxy_usdt=1825123, funding_indicative=0.000028, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=61863629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T05:45:02+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=0.005107, depth_time=2026-10-13T05:45:18+00:00, book20_bid_proxy_usdt=1617213, book20_ask_proxy_usdt=1245644, funding_indicative=0.000019, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.48%, turnover=32913131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T05:45:02+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=0.964300, depth_time=2026-10-13T05:45:32+00:00, book20_bid_proxy_usdt=63810, book20_ask_proxy_usdt=54964, funding_indicative=-0.000505, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.10%, turnover=7259221. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T05:45:02+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=0.064850, depth_time=2026-10-13T05:45:28+00:00, book20_bid_proxy_usdt=162384, book20_ask_proxy_usdt=223289, funding_indicative=-0.000067, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.14%, turnover=9626994. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T05:45:01+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=0.089670, depth_time=2026-10-13T05:45:26+00:00, book20_bid_proxy_usdt=159146, book20_ask_proxy_usdt=254833, funding_indicative=0.000032, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.92%, turnover=65320148. target_RR/account_short_permission/settled_funding=UNKNOWN.
- USELESS_USDT: quote_utc=2026-10-13T05:45:02+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=0.179140, depth_time=2026-10-13T05:45:40+00:00, book20_bid_proxy_usdt=21376, book20_ask_proxy_usdt=29298, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=6921387. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-13T05:45:01+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=1224.780000, depth_time=2026-10-13T05:45:21+00:00, book20_bid_proxy_usdt=490052, book20_ask_proxy_usdt=228198, funding_indicative=0.000027, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.30%, turnover=1715610634. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T05:45:02+00:00, last15m_closed_end=2026-10-13T05:45+00:00, prior8high=2.146800, depth_time=2026-10-13T05:45:10+00:00, book20_bid_proxy_usdt=55389, book20_ask_proxy_usdt=36429, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.63%, turnover=30547123. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
