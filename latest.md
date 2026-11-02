# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T23:00:43Z**
- feed_generated_utc: 2026-11-02T23:00:46+00:00
- source_sha256: `27f3498a96bfb1c5115bdb1f2f154a19a20cb682c1cd33431d0f3873b14c730b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T23:00+00:00, close=76916.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T23:00+00:00, close=76916.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T20:00+00:00, close=77068.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.115900|-14.21|-53.41|-13.45|6482958|8.63|
|BTW_USDT|0.981300|-10.00|-17.93|-9.24|9614127|3.07|
|ZEC_USDT|1154.460000|-7.94|-7.47|-7.18|1855553195|0.09|
|XPL_USDT|0.066900|-3.85|-9.94|-3.09|10447803|1.50|
|QNT_USDT|194.980000|-3.68|-7.27|-2.92|47605228|1.03|
|NEAR_USDT|3.873000|-3.41|-15.30|-2.65|80259049|2.58|
|PUMPFUN_USDT|0.003966|-3.36|-8.36|-2.60|9216652|2.52|
|INJ_USDT|6.950000|-3.12|-12.40|-2.36|20203849|1.44|
|DASH_USDT|46.200000|-3.12|-11.52|-2.36|10279315|2.17|
|ZRO_USDT|1.717600|-2.86|0.61|-2.10|6154812|0.58|
|AAVE_USDT|126.870000|-2.82|-7.21|-2.06|22930679|0.79|
|TIA_USDT|0.444500|-2.71|-17.02|-1.95|12371378|2.25|
|ENA_USDT|0.170680|-2.49|-18.86|-1.73|74536536|0.59|
|XLM_USDT|0.163510|-2.44|-3.58|-1.68|33143954|0.61|
|SOL_USDT|92.100000|-2.34|-9.56|-1.58|742554287|1.09|
|ARB_USDT|0.155670|-2.29|-8.42|-1.53|13226951|0.64|
|FET_USDT|0.155700|-1.95|-11.83|-1.19|5505482|6.42|
|OP_USDT|0.110290|-1.90|-1.26|-1.14|12094556|1.81|
|TRUMPOFFICIAL_USDT|1.605000|-1.83|-4.97|-1.07|11866859|6.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.870000|126.520000|126.950000|0.51|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.981300|0.957600|0.981300|2.31|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.200000|45.780000|46.200000|0.03|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.170680|0.169260|0.170790|0.12|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|6.950000|6.906000|6.950000|0.32|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.873000|3.856000|3.872000|0.19|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003966|0.003923|0.003969|1.08|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.980000|193.540000|195.020000|0.96|N|Y/Y|Y/N|Y|N|
|SOL_USDT|92.100000|91.380000|92.100000|0.70|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.444500|0.443600|0.444200|0.17|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.115900|0.112100|0.115900|0.67|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.163510|0.163010|0.163510|0.32|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.066900|0.066130|0.066910|0.08|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1154.460000|1136.000000|1155.850000|0.64|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.717600|1.692200|1.718100|1.38|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-02T23:00:03+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=128.160000, depth_time=2026-11-02T23:00:32+00:00, book20_bid_proxy_usdt=389087, book20_ask_proxy_usdt=342409, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=22930679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-02T23:00:03+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=1.085700, depth_time=2026-11-02T23:00:10+00:00, book20_bid_proxy_usdt=16651, book20_ask_proxy_usdt=14426, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.00%, turnover=9614127. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-02T23:00:04+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=46.500000, depth_time=2026-11-02T23:00:21+00:00, book20_bid_proxy_usdt=553464, book20_ask_proxy_usdt=329658, funding_indicative=0.000077, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=10279315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-02T23:00:03+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=0.172390, depth_time=2026-11-02T23:00:38+00:00, book20_bid_proxy_usdt=195321, book20_ask_proxy_usdt=114552, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=74536536. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-02T23:00:03+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=7.026000, depth_time=2026-11-02T23:00:24+00:00, book20_bid_proxy_usdt=290820, book20_ask_proxy_usdt=239222, funding_indicative=0.000008, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=20203849. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-02T23:00:03+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=3.921000, depth_time=2026-11-02T23:00:20+00:00, book20_bid_proxy_usdt=3787142, book20_ask_proxy_usdt=1139724, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.41%, turnover=80259049. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T23:00:03+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=0.003996, depth_time=2026-11-02T23:00:22+00:00, book20_bid_proxy_usdt=2616455, book20_ask_proxy_usdt=583874, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.36%, turnover=9216652. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T23:00:03+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=197.490000, depth_time=2026-11-02T23:00:17+00:00, book20_bid_proxy_usdt=56195, book20_ask_proxy_usdt=57619, funding_indicative=0.000090, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.68%, turnover=47605228. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-02T23:00:03+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=92.420000, depth_time=2026-11-02T23:00:42+00:00, book20_bid_proxy_usdt=11964701, book20_ask_proxy_usdt=11233119, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=742554287. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-02T23:00:04+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=0.452100, depth_time=2026-11-02T23:00:32+00:00, book20_bid_proxy_usdt=233255, book20_ask_proxy_usdt=248838, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=12371378. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T23:00:03+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=0.121600, depth_time=2026-11-02T23:00:06+00:00, book20_bid_proxy_usdt=177134, book20_ask_proxy_usdt=122918, funding_indicative=-0.000033, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-14.21%, turnover=6482958. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-02T23:00:04+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=0.165190, depth_time=2026-11-02T23:00:40+00:00, book20_bid_proxy_usdt=106809, book20_ask_proxy_usdt=107517, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=33143954. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T23:00:04+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=0.067370, depth_time=2026-11-02T23:00:13+00:00, book20_bid_proxy_usdt=307473, book20_ask_proxy_usdt=332499, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.85%, turnover=10447803. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T23:00:03+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=1162.310000, depth_time=2026-11-02T23:00:12+00:00, book20_bid_proxy_usdt=642541, book20_ask_proxy_usdt=508582, funding_indicative=0.000039, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-7.94%, turnover=1855553195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T23:00:04+00:00, last15m_closed_end=2026-11-02T23:00+00:00, prior8high=1.727400, depth_time=2026-11-02T23:00:29+00:00, book20_bid_proxy_usdt=39131, book20_ask_proxy_usdt=30257, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=6154812. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
