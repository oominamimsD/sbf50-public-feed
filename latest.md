# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T23:15:45Z**
- feed_generated_utc: 2026-11-02T23:15:47+00:00
- source_sha256: `d0f2a164b3f2725a40992dd3105125b475d8fef6dc3415bd5bec045641116cd9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T23:15+00:00, close=76774.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T23:00+00:00, close=76916.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T20:00+00:00, close=77068.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|0.967200|-11.81|-19.11|-10.91|9690106|4.14|
|UAI_USDT|0.118300|-10.85|-52.45|-9.95|6515304|8.45|
|ZEC_USDT|1150.740000|-8.24|-7.77|-7.34|1872970278|0.09|
|QNT_USDT|194.200000|-4.07|-7.64|-3.17|48042501|0.52|
|XPL_USDT|0.066780|-4.02|-10.10|-3.12|10623706|1.50|
|NEAR_USDT|3.872000|-3.44|-15.32|-2.54|81030140|2.58|
|PUMPFUN_USDT|0.003980|-3.02|-8.04|-2.12|9269299|2.51|
|ZRO_USDT|1.721000|-2.66|0.81|-1.76|6218977|0.58|
|AAVE_USDT|127.120000|-2.63|-7.02|-1.73|23373110|0.79|
|TIA_USDT|0.445500|-2.49|-16.83|-1.59|12528711|2.25|
|XLM_USDT|0.163510|-2.44|-3.58|-1.54|33425869|3.06|
|ENA_USDT|0.171080|-2.26|-18.67|-1.36|74844669|0.58|
|ARB_USDT|0.155770|-2.23|-8.36|-1.33|13314632|0.64|
|OP_USDT|0.109930|-2.22|-1.58|-1.32|12168901|0.91|
|TRUMPOFFICIAL_USDT|1.603000|-2.01|-5.09|-1.11|11989505|6.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.120000|126.520000|127.060000|2.48|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.155770|0.155270|0.155770|0.92|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.967200|0.957600|0.967200|1.66|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.171080|0.169290|0.171090|0.39|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.872000|3.856000|3.871000|0.65|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.109930|0.109680|0.109890|1.38|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003980|0.003929|0.003980|0.60|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.200000|194.060000|194.120000|0.84|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.445500|0.443800|0.445500|1.46|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.603000|1.586000|1.603000|1.40|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.118300|0.113200|0.118300|0.50|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.163510|0.163010|0.163550|0.73|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.066780|0.066190|0.066780|0.89|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1150.740000|1138.650000|1150.670000|0.78|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.721000|1.694500|1.720600|1.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=128.160000, depth_time=2026-11-02T23:15:27+00:00, book20_bid_proxy_usdt=344855, book20_ask_proxy_usdt=422743, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.63%, turnover=23373110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=0.157480, depth_time=2026-11-02T23:15:36+00:00, book20_bid_proxy_usdt=95863, book20_ask_proxy_usdt=80714, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=13314632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=1.085700, depth_time=2026-11-02T23:15:08+00:00, book20_bid_proxy_usdt=14476, book20_ask_proxy_usdt=15377, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.81%, turnover=9690106. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=0.172390, depth_time=2026-11-02T23:15:35+00:00, book20_bid_proxy_usdt=120677, book20_ask_proxy_usdt=307709, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=74844669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=3.921000, depth_time=2026-11-02T23:15:20+00:00, book20_bid_proxy_usdt=4009611, book20_ask_proxy_usdt=5781087, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.44%, turnover=81030140. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=0.111180, depth_time=2026-11-02T23:15:41+00:00, book20_bid_proxy_usdt=148125, book20_ask_proxy_usdt=130963, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.22%, turnover=12168901. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=0.003996, depth_time=2026-11-02T23:15:20+00:00, book20_bid_proxy_usdt=2404658, book20_ask_proxy_usdt=2386470, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=9269299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=197.490000, depth_time=2026-11-02T23:15:14+00:00, book20_bid_proxy_usdt=49956, book20_ask_proxy_usdt=77340, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.07%, turnover=48042501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=0.452100, depth_time=2026-11-02T23:15:29+00:00, book20_bid_proxy_usdt=225105, book20_ask_proxy_usdt=284369, funding_indicative=0.000041, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=12528711. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=1.612000, depth_time=2026-11-02T23:15:40+00:00, book20_bid_proxy_usdt=2173491, book20_ask_proxy_usdt=1640747, funding_indicative=0.000028, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.01%, turnover=11989505. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=0.121600, depth_time=2026-11-02T23:15:10+00:00, book20_bid_proxy_usdt=213224, book20_ask_proxy_usdt=105888, funding_indicative=-0.000006, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.85%, turnover=6515304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=0.164740, depth_time=2026-11-02T23:15:31+00:00, book20_bid_proxy_usdt=174618, book20_ask_proxy_usdt=192800, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=33425869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=0.067370, depth_time=2026-11-02T23:15:18+00:00, book20_bid_proxy_usdt=442425, book20_ask_proxy_usdt=558297, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.02%, turnover=10623706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=1162.310000, depth_time=2026-11-02T23:15:13+00:00, book20_bid_proxy_usdt=548386, book20_ask_proxy_usdt=143774, funding_indicative=0.000039, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-8.24%, turnover=1872970278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T23:15:03+00:00, last15m_closed_end=2026-11-02T23:15+00:00, prior8high=1.727400, depth_time=2026-11-02T23:15:25+00:00, book20_bid_proxy_usdt=37041, book20_ask_proxy_usdt=38634, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.66%, turnover=6218977. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
