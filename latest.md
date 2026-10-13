# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T05:00:42Z**
- feed_generated_utc: 2026-10-13T05:00:45+00:00
- source_sha256: `4c47abf85f10df968a2209410407b72a46dfb9bea055dbb85bb25d88519849fa`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T05:00+00:00, close=83419.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T05:00+00:00, close=83419.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T04:00+00:00, close=83297.9, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|W_USDT|0.019280|-19.86|36.32|-20.75|35184581|8.82|
|DOS_USDT|0.246500|-16.83|15.72|-17.72|9231994|8.10|
|RSR_USDT|0.002092|-10.97|22.98|-11.86|19333424|4.78|
|ZRO_USDT|2.112800|-9.96|3.28|-10.85|30229602|1.42|
|RLC_USDT|0.954700|-7.00|74.21|-7.89|7104129|1.05|
|PUMPFUN_USDT|0.005081|-6.35|-19.79|-7.24|32448104|1.97|
|PONS_USDT|0.283500|-5.24|-26.07|-6.13|6291330|7.06|
|DOT_USDT|1.180400|-4.76|-1.13|-5.65|24089622|0.85|
|LIT_USDT|3.448600|-4.72|-9.29|-5.61|11178449|0.29|
|SEI_USDT|0.063850|-3.91|-11.20|-4.80|9450480|1.57|
|ENA_USDT|0.213090|-3.87|-13.22|-4.76|69331048|0.47|
|ICP_USDT|3.189000|-3.71|-7.99|-4.60|16131382|3.14|
|HBAR_USDT|0.087840|-2.79|-12.77|-3.68|21785067|1.14|
|STRK_USDT|0.088170|-2.75|69.19|-3.64|64705315|1.14|
|JUP_USDT|0.335700|-2.32|-0.65|-3.21|8825503|2.98|
|HYPE_USDT|82.561000|-2.14|-10.88|-3.03|85082890|0.61|
|USELESS_USDT|0.177700|-2.14|-21.63|-3.03|6850995|0.56|
|FET_USDT|0.216900|-2.07|-12.99|-2.96|21661365|4.61|
|ATOM_USDT|1.817000|-1.46|1.96|-2.35|12488903|5.50|
|QNT_USDT|227.510000|-0.38|-11.39|-1.27|78898526|1.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOS_USDT|0.246500|0.229000|0.246500|1.64|N|Y/Y|Y/N|N|N|
|DOT_USDT|1.180400|1.148900|1.180400|0.60|N|Y/Y|Y/Y|N|N|
|ENA_USDT|0.213090|0.206920|0.213070|0.47|N|Y/Y|Y/Y|N|N|
|HBAR_USDT|0.087840|0.086850|0.087840|0.51|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.189000|3.085000|3.189000|0.47|N|Y/Y|Y/Y|N|N|
|JUP_USDT|0.335700|0.331800|0.335700|0.11|N|Y/Y|Y/Y|N|N|
|LIT_USDT|3.448600|3.303200|3.448600|0.13|N|Y/Y|Y/Y|N|N|
|PONS_USDT|0.283500|0.276900|0.283500|0.19|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.005081|0.004970|0.005081|0.22|N|Y/Y|Y/Y|N|N|
|RLC_USDT|0.954700|0.939400|0.954700|0.74|N|Y/Y|Y/Y|N|N|
|RSR_USDT|0.002092|0.001985|0.002089|1.91|N|Y/Y|N/N|N|N|
|SEI_USDT|0.063850|0.062450|0.063850|0.71|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.088170|0.082550|0.088060|0.39|N|Y/Y|Y/Y|N|N|
|W_USDT|0.019280|0.018313|0.019303|0.75|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|2.112800|2.089500|2.113300|0.82|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOS_USDT: quote_utc=2026-10-13T05:00:02+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=0.251000, depth_time=2026-10-13T05:00:11+00:00, book20_bid_proxy_usdt=42495, book20_ask_proxy_usdt=38552, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.83%, turnover=9231994. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-13T05:00:03+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=1.185500, depth_time=2026-10-13T05:00:25+00:00, book20_bid_proxy_usdt=300527, book20_ask_proxy_usdt=322852, funding_indicative=0.000053, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.76%, turnover=24089622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-13T05:00:02+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=0.213120, depth_time=2026-10-13T05:00:30+00:00, book20_bid_proxy_usdt=268491, book20_ask_proxy_usdt=108870, funding_indicative=-0.000038, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.87%, turnover=69331048. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-13T05:00:03+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=0.087920, depth_time=2026-10-13T05:00:36+00:00, book20_bid_proxy_usdt=490884, book20_ask_proxy_usdt=966870, funding_indicative=0.000004, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=21785067. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-13T05:00:03+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=3.191000, depth_time=2026-10-13T05:00:33+00:00, book20_bid_proxy_usdt=803562, book20_ask_proxy_usdt=935014, funding_indicative=-0.000046, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.71%, turnover=16131382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-13T05:00:03+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=0.337300, depth_time=2026-10-13T05:00:41+00:00, book20_bid_proxy_usdt=531988, book20_ask_proxy_usdt=464954, funding_indicative=-0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.32%, turnover=8825503. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-13T05:00:03+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=3.472500, depth_time=2026-10-13T05:00:25+00:00, book20_bid_proxy_usdt=20573, book20_ask_proxy_usdt=27088, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.72%, turnover=11178449. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-13T05:00:03+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=0.284600, depth_time=2026-10-13T05:00:22+00:00, book20_bid_proxy_usdt=225090, book20_ask_proxy_usdt=216386, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.24%, turnover=6291330. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-13T05:00:03+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=0.005092, depth_time=2026-10-13T05:00:20+00:00, book20_bid_proxy_usdt=1957845, book20_ask_proxy_usdt=1304559, funding_indicative=0.000003, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.35%, turnover=32448104. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T05:00:03+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=0.984900, depth_time=2026-10-13T05:00:17+00:00, book20_bid_proxy_usdt=64392, book20_ask_proxy_usdt=49390, funding_indicative=-0.000486, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.00%, turnover=7104129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RSR_USDT: quote_utc=2026-10-13T05:00:02+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=0.002194, depth_time=2026-10-13T05:00:13+00:00, book20_bid_proxy_usdt=99911, book20_ask_proxy_usdt=195213, funding_indicative=-0.011135, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-10.97%, turnover=19333424. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-13T05:00:03+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=0.063850, depth_time=2026-10-13T05:00:29+00:00, book20_bid_proxy_usdt=189687, book20_ask_proxy_usdt=251517, funding_indicative=-0.000080, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.91%, turnover=9450480. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T05:00:02+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=0.089670, depth_time=2026-10-13T05:00:38+00:00, book20_bid_proxy_usdt=166736, book20_ask_proxy_usdt=161374, funding_indicative=0.000018, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=64705315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-13T05:00:02+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=0.019413, depth_time=2026-10-13T05:00:07+00:00, book20_bid_proxy_usdt=18512, book20_ask_proxy_usdt=28616, funding_indicative=-0.000441, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.86%, turnover=35184581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-13T05:00:03+00:00, last15m_closed_end=2026-10-13T05:00+00:00, prior8high=2.133900, depth_time=2026-10-13T05:00:16+00:00, book20_bid_proxy_usdt=33785, book20_ask_proxy_usdt=29518, funding_indicative=0.000050, next_funding_utc=2026-10-13T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.96%, turnover=30229602. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
