# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T13:30:45Z**
- feed_generated_utc: 2026-10-18T13:30:48+00:00
- source_sha256: `ffcc289d6bb92ead9036346088c7b5162c0008b8ab994f2e41731f1d9c87e1a4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T13:30+00:00, close=81529.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T13:00+00:00, close=81952.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T12:00+00:00, close=82038.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EIGEN_USDT|0.237100|-7.49|0.63|-7.74|5940344|4.22|
|STRK_USDT|0.061420|-7.15|-34.26|-7.40|14826065|1.63|
|TIA_USDT|0.621600|-5.53|21.16|-5.78|60071565|3.22|
|FILECOIN_USDT|1.045900|-3.81|-7.26|-4.06|17577352|0.96|
|PUMPFUN_USDT|0.004251|-3.64|-25.74|-3.89|19481051|2.35|
|ZRO_USDT|1.819000|-3.51|-9.97|-3.76|6342466|2.75|
|XPL_USDT|0.077650|-3.09|-10.50|-3.34|5764183|1.29|
|TRUMPOFFICIAL_USDT|1.706000|-3.01|-9.87|-3.26|5503752|5.86|
|QNT_USDT|194.690000|-2.85|-20.57|-3.10|65503347|0.51|
|INJ_USDT|8.220000|-2.85|12.69|-3.10|39714981|1.22|
|OP_USDT|0.125670|-2.58|-9.29|-2.83|8467680|0.80|
|ZEC_USDT|1112.350000|-2.53|-9.69|-2.78|1221332131|0.09|
|DOT_USDT|1.093900|-2.10|-12.96|-2.35|15926646|0.92|
|ICP_USDT|2.878000|-1.70|-8.60|-1.95|5850586|3.48|
|ENA_USDT|0.186290|-1.51|-16.10|-1.76|26913251|0.54|
|AVAX_USDT|9.678000|-1.43|-8.04|-1.68|82207483|1.03|
|ONDO_USDT|0.433600|-1.36|-12.33|-1.61|20725319|2.31|
|APT_USDT|0.787800|-1.21|-4.71|-1.46|9777407|1.27|
|TAO_USDT|265.400000|-0.98|-6.58|-1.23|57586417|1.13|
|ICNT_USDT|0.183400|-0.97|85.06|-1.22|12917488|5.46|
|XRP_USDT|1.282400|-0.77|-8.88|-1.02|313835305|0.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.093900|1.097600|1.093900|1.98|Y|Y/Y|Y/Y|N|Y|
|EIGEN_USDT|0.237100|0.238500|0.237200|2.41|Y|Y/Y|Y/Y|N|Y|
|ENA_USDT|0.186290|0.187950|0.186310|4.15|Y|Y/Y|Y/Y|N|Y|
|FILECOIN_USDT|1.045900|1.053700|1.045900|5.29|Y|Y/Y|Y/Y|N|Y|
|ICP_USDT|2.878000|2.889000|2.878000|6.83|Y|Y/Y|Y/Y|N|Y|
|INJ_USDT|8.220000|8.230000|8.220000|1.93|Y|Y/Y|Y/N|N|N|
|OP_USDT|0.125670|0.125830|0.125650|1.38|Y|Y/Y|Y/Y|N|Y|
|PUMPFUN_USDT|0.004251|0.004241|0.004251|1.80|N|Y/Y|Y/Y|N|N|
|QNT_USDT|194.690000|195.690000|194.880000|1.75|Y|Y/N|Y/Y|N|N|
|STRK_USDT|0.061420|0.061150|0.061420|2.23|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.621600|0.620900|0.621800|1.35|N|Y/Y|N/Y|N|N|
|TRUMPOFFICIAL_USDT|1.706000|1.720000|1.706000|42.93|Y|Y/Y|Y/Y|N|Y|
|XPL_USDT|0.077650|0.077960|0.077650|6.36|Y|Y/Y|Y/Y|N|Y|
|ZEC_USDT|1112.350000|1118.270000|1113.400000|1.82|Y|Y/Y|Y/Y|N|Y|
|ZRO_USDT|1.819000|1.815400|1.820400|4.80|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=1.112100, depth_time=2026-10-18T13:30:39+00:00, book20_bid_proxy_usdt=120204, book20_ask_proxy_usdt=104307, funding_indicative=-0.000019, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=15926646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=0.242800, depth_time=2026-10-18T13:30:09+00:00, book20_bid_proxy_usdt=636323, book20_ask_proxy_usdt=435714, funding_indicative=0.000013, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.49%, turnover=5940344. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=0.190160, depth_time=2026-10-18T13:30:45+00:00, book20_bid_proxy_usdt=123533, book20_ask_proxy_usdt=158328, funding_indicative=-0.000026, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.51%, turnover=26913251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=1.064600, depth_time=2026-10-18T13:30:17+00:00, book20_bid_proxy_usdt=96587, book20_ask_proxy_usdt=732473, funding_indicative=0.000018, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.81%, turnover=17577352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=2.914000, depth_time=2026-10-18T13:30:41+00:00, book20_bid_proxy_usdt=512304, book20_ask_proxy_usdt=723605, funding_indicative=0.000058, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=5850586. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=8.489000, depth_time=2026-10-18T13:30:31+00:00, book20_bid_proxy_usdt=287544, book20_ask_proxy_usdt=181620, funding_indicative=-0.000122, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=39714981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=0.127610, depth_time=2026-10-18T13:30:34+00:00, book20_bid_proxy_usdt=22810, book20_ask_proxy_usdt=35839, funding_indicative=-0.000172, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.58%, turnover=8467680. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=0.004313, depth_time=2026-10-18T13:30:20+00:00, book20_bid_proxy_usdt=1719450, book20_ask_proxy_usdt=1239438, funding_indicative=0.000016, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.64%, turnover=19481051. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=199.700000, depth_time=2026-10-18T13:30:29+00:00, book20_bid_proxy_usdt=51122, book20_ask_proxy_usdt=60049, funding_indicative=-0.000034, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=65503347. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=0.062410, depth_time=2026-10-18T13:30:11+00:00, book20_bid_proxy_usdt=329590, book20_ask_proxy_usdt=384994, funding_indicative=0.000050, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.15%, turnover=14826065. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=0.658000, depth_time=2026-10-18T13:30:14+00:00, book20_bid_proxy_usdt=82436, book20_ask_proxy_usdt=129359, funding_indicative=-0.000056, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.53%, turnover=60071565. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-18T13:30:02+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=1.738000, depth_time=2026-10-18T13:30:26+00:00, book20_bid_proxy_usdt=1025884, book20_ask_proxy_usdt=2362033, funding_indicative=-0.000008, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=5503752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=0.078810, depth_time=2026-10-18T13:30:24+00:00, book20_bid_proxy_usdt=162131, book20_ask_proxy_usdt=345758, funding_indicative=0.000036, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.09%, turnover=5764183. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=1135.430000, depth_time=2026-10-18T13:30:37+00:00, book20_bid_proxy_usdt=623669, book20_ask_proxy_usdt=23902, funding_indicative=0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=1221332131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T13:30:01+00:00, last15m_closed_end=2026-10-18T13:30+00:00, prior8high=1.851100, depth_time=2026-10-18T13:30:22+00:00, book20_bid_proxy_usdt=19097, book20_ask_proxy_usdt=40340, funding_indicative=0.000003, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.51%, turnover=6342466. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
