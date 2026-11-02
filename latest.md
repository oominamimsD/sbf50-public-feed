# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T23:30:44Z**
- feed_generated_utc: 2026-11-02T23:30:47+00:00
- source_sha256: `1e110f609992240d81cb22dba9d222d8d693a46452cf97de85b062dad15ef390`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T23:30+00:00, close=76754.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T23:00+00:00, close=76916.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T20:00+00:00, close=77068.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|0.967200|-11.81|-19.11|-10.88|9797691|3.10|
|ZEC_USDT|1135.500000|-9.45|-8.99|-8.52|1898000634|0.35|
|XPL_USDT|0.066390|-4.58|-10.63|-3.65|10847097|1.51|
|QNT_USDT|194.290000|-4.03|-7.60|-3.10|48294431|0.52|
|NEAR_USDT|3.862000|-3.69|-15.54|-2.76|81238734|2.59|
|PUMPFUN_USDT|0.003962|-3.46|-8.45|-2.53|9285023|2.52|
|ZRO_USDT|1.714900|-3.01|0.45|-2.08|6241789|0.58|
|AAVE_USDT|126.830000|-2.85|-7.24|-1.92|23841691|0.79|
|TIA_USDT|0.444000|-2.82|-17.11|-1.89|12596206|2.25|
|XLM_USDT|0.162880|-2.81|-3.95|-1.88|33671728|0.61|
|ENA_USDT|0.170490|-2.59|-18.95|-1.66|75385767|0.59|
|ARB_USDT|0.155390|-2.47|-8.58|-1.54|13391415|0.64|
|OP_USDT|0.109670|-2.45|-1.81|-1.52|12211614|1.82|
|TRUMPOFFICIAL_USDT|1.596000|-2.44|-5.50|-1.51|12031769|6.26|
|DASH_USDT|46.130000|-2.26|-11.66|-1.33|10346828|2.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.830000|126.520000|126.810000|2.62|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.155390|0.155020|0.155390|0.84|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.967200|0.957600|0.967200|2.37|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.130000|45.780000|46.130000|0.09|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.170490|0.169560|0.170500|0.74|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.862000|3.853000|3.862000|0.17|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.109670|0.109830|0.109670|0.42|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003962|0.003929|0.003962|0.19|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.290000|193.940000|194.290000|0.48|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.444000|0.443400|0.444000|0.62|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.596000|1.593000|1.596000|0.48|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.162880|0.162930|0.162880|0.66|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.066390|0.066190|0.066390|1.18|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1135.500000|1139.270000|1135.760000|1.16|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.714900|1.698900|1.714300|0.36|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=128.160000, depth_time=2026-11-02T23:30:25+00:00, book20_bid_proxy_usdt=426814, book20_ask_proxy_usdt=1313730, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=23841691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=0.157480, depth_time=2026-11-02T23:30:35+00:00, book20_bid_proxy_usdt=107265, book20_ask_proxy_usdt=88886, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=13391415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=1.076000, depth_time=2026-11-02T23:30:07+00:00, book20_bid_proxy_usdt=17158, book20_ask_proxy_usdt=17487, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.81%, turnover=9797691. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=46.500000, depth_time=2026-11-02T23:30:40+00:00, book20_bid_proxy_usdt=760383, book20_ask_proxy_usdt=602910, funding_indicative=0.000093, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=10346828. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=0.172390, depth_time=2026-11-02T23:30:33+00:00, book20_bid_proxy_usdt=270465, book20_ask_proxy_usdt=220567, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=75385767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=3.921000, depth_time=2026-11-02T23:30:17+00:00, book20_bid_proxy_usdt=5195918, book20_ask_proxy_usdt=4012576, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=81238734. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=0.111180, depth_time=2026-11-02T23:30:39+00:00, book20_bid_proxy_usdt=158457, book20_ask_proxy_usdt=122600, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=12211614. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=0.003996, depth_time=2026-11-02T23:30:21+00:00, book20_bid_proxy_usdt=2967100, book20_ask_proxy_usdt=2496979, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=9285023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=197.490000, depth_time=2026-11-02T23:30:15+00:00, book20_bid_proxy_usdt=95084, book20_ask_proxy_usdt=85494, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.03%, turnover=48294431. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=0.452100, depth_time=2026-11-02T23:30:28+00:00, book20_bid_proxy_usdt=263919, book20_ask_proxy_usdt=359282, funding_indicative=0.000021, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=12596206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=1.612000, depth_time=2026-11-02T23:30:39+00:00, book20_bid_proxy_usdt=1809690, book20_ask_proxy_usdt=2077762, funding_indicative=0.000031, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=12031769. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=0.164700, depth_time=2026-11-02T23:30:31+00:00, book20_bid_proxy_usdt=182301, book20_ask_proxy_usdt=203012, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.81%, turnover=33671728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=0.067370, depth_time=2026-11-02T23:30:12+00:00, book20_bid_proxy_usdt=384244, book20_ask_proxy_usdt=367861, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.58%, turnover=10847097. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=1162.310000, depth_time=2026-11-02T23:30:09+00:00, book20_bid_proxy_usdt=238224, book20_ask_proxy_usdt=404765, funding_indicative=0.000049, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-9.45%, turnover=1898000634. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T23:30:02+00:00, last15m_closed_end=2026-11-02T23:30+00:00, prior8high=1.727400, depth_time=2026-11-02T23:30:23+00:00, book20_bid_proxy_usdt=58952, book20_ask_proxy_usdt=49699, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=6241789. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
