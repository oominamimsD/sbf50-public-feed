# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T23:45:43Z**
- feed_generated_utc: 2026-11-02T23:45:45+00:00
- source_sha256: `755dfd6b87af29b16493dcd8e6a5e5d8d78f8d85f150b1d0d17e8d6ffdcae639`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T23:45+00:00, close=76815.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T23:00+00:00, close=76916.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T20:00+00:00, close=77068.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.114700|-13.56|-53.89|-12.71|6558937|8.71|
|BTW_USDT|0.962400|-12.25|-19.51|-11.40|9939948|2.08|
|ZEC_USDT|1136.160000|-9.40|-8.94|-8.55|1909709615|0.09|
|AKE_USDT|0.005110|-7.12|-83.39|-6.27|13988600|3.91|
|XPL_USDT|0.066480|-4.45|-10.51|-3.60|11313999|3.01|
|QNT_USDT|194.430000|-3.96|-7.53|-3.11|48675304|1.54|
|NEAR_USDT|3.867000|-3.56|-15.43|-2.71|81420569|2.59|
|PUMPFUN_USDT|0.003963|-3.43|-8.43|-2.58|9314690|2.52|
|AAVE_USDT|126.580000|-3.04|-7.42|-2.19|23985553|0.79|
|XLM_USDT|0.162800|-2.86|-4.00|-2.01|33868605|0.61|
|TIA_USDT|0.444700|-2.67|-16.98|-1.82|12611251|2.25|
|ENA_USDT|0.170470|-2.61|-18.96|-1.76|75498543|0.59|
|ZRO_USDT|1.723700|-2.51|0.97|-1.66|6273803|0.58|
|OP_USDT|0.109670|-2.45|-1.81|-1.60|12226762|0.91|
|ARB_USDT|0.155530|-2.38|-8.50|-1.53|13444463|0.64|
|TRUMPOFFICIAL_USDT|1.597000|-2.38|-5.44|-1.53|12057110|6.26|
|DASH_USDT|46.170000|-2.18|-11.58|-1.33|10398046|2.17|
|HYPE_USDT|84.070000|-1.91|7.17|-1.06|104322823|0.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|126.580000|126.520000|126.580000|0.81|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005110|0.005399|0.005099|4.36|Y|Y/Y|Y/Y|Y|Y|
|ARB_USDT|0.155530|0.155020|0.155530|0.63|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|0.962400|0.957600|0.962500|3.06|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.170470|0.169680|0.170470|0.17|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.867000|3.853000|3.867000|0.17|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.109670|0.109570|0.109670|0.25|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003963|0.003938|0.003963|0.40|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.430000|193.860000|194.430000|0.74|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.444700|0.443000|0.444700|0.16|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.114700|0.113200|0.114700|0.53|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.162800|0.162840|0.162800|0.57|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.066480|0.066280|0.066480|2.46|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1136.160000|1131.820000|1136.160000|0.53|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.723700|1.700500|1.723700|0.51|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-02T23:45:00+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=128.160000, depth_time=2026-11-02T23:45:26+00:00, book20_bid_proxy_usdt=546551, book20_ask_proxy_usdt=556120, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.04%, turnover=23985553. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-02T23:45:00+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=0.005937, depth_time=2026-11-02T23:45:15+00:00, book20_bid_proxy_usdt=19417, book20_ask_proxy_usdt=51946, funding_indicative=-0.004105, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.12%, turnover=13988600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-02T23:45:01+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=0.157480, depth_time=2026-11-02T23:45:41+00:00, book20_bid_proxy_usdt=98348, book20_ask_proxy_usdt=106128, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=13444463. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-02T23:45:00+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=1.065000, depth_time=2026-11-02T23:45:09+00:00, book20_bid_proxy_usdt=18451, book20_ask_proxy_usdt=37269, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-12.25%, turnover=9939948. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-02T23:45:00+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=0.172390, depth_time=2026-11-02T23:45:34+00:00, book20_bid_proxy_usdt=141275, book20_ask_proxy_usdt=259411, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.61%, turnover=75498543. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-02T23:45:00+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=3.921000, depth_time=2026-11-02T23:45:21+00:00, book20_bid_proxy_usdt=4386961, book20_ask_proxy_usdt=4923035, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.56%, turnover=81420569. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-02T23:45:01+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=0.111180, depth_time=2026-11-02T23:45:38+00:00, book20_bid_proxy_usdt=149421, book20_ask_proxy_usdt=120324, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=12226762. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T23:45:01+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=0.003996, depth_time=2026-11-02T23:45:23+00:00, book20_bid_proxy_usdt=2492455, book20_ask_proxy_usdt=2826441, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.43%, turnover=9314690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T23:45:00+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=197.490000, depth_time=2026-11-02T23:45:19+00:00, book20_bid_proxy_usdt=80665, book20_ask_proxy_usdt=88230, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.96%, turnover=48675304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-02T23:45:01+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=0.452100, depth_time=2026-11-02T23:45:32+00:00, book20_bid_proxy_usdt=277690, book20_ask_proxy_usdt=330334, funding_indicative=0.000039, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=12611251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T23:45:00+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=0.121600, depth_time=2026-11-02T23:45:06+00:00, book20_bid_proxy_usdt=227123, book20_ask_proxy_usdt=106438, funding_indicative=-0.000001, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-13.56%, turnover=6558937. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-02T23:45:01+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=0.164090, depth_time=2026-11-02T23:45:29+00:00, book20_bid_proxy_usdt=184304, book20_ask_proxy_usdt=257648, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=33868605. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T23:45:01+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=0.067370, depth_time=2026-11-02T23:45:17+00:00, book20_bid_proxy_usdt=321507, book20_ask_proxy_usdt=558166, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.45%, turnover=11313999. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T23:45:00+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=1162.310000, depth_time=2026-11-02T23:45:12+00:00, book20_bid_proxy_usdt=269081, book20_ask_proxy_usdt=978192, funding_indicative=0.000084, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-9.40%, turnover=1909709615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T23:45:01+00:00, last15m_closed_end=2026-11-02T23:45+00:00, prior8high=1.727400, depth_time=2026-11-02T23:45:36+00:00, book20_bid_proxy_usdt=107826, book20_ask_proxy_usdt=48275, funding_indicative=0.000050, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.51%, turnover=6273803. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
