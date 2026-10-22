# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-22T00:45:47Z**
- feed_generated_utc: 2026-10-22T00:45:51+00:00
- source_sha256: `c7a7181ed9dfa8d57a770e55ab080f31d47b3c990b91fa209931d1361905ab6a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-22T00:45+00:00, close=84296.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-22T00:00+00:00, close=84050, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-22T00:00+00:00, close=84050, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IOST_USDT|0.000974|-33.50|21.63|-33.27|15176647|1.03|
|DOOD_USDT|0.002378|-16.38|67.70|-16.15|9123737|8.40|
|AKE_USDT|0.023937|-10.31|-7.51|-10.08|10959239|0.83|
|BR_USDT|0.488130|-9.86|19.71|-9.63|14460688|0.82|
|STRK_USDT|0.056830|-8.29|-26.36|-8.06|24785653|5.28|
|ZRO_USDT|1.939500|-7.51|2.40|-7.28|7428075|1.03|
|TIA_USDT|0.600900|-4.99|12.63|-4.76|40436566|1.66|
|ARB_USDT|0.189460|-3.63|4.01|-3.40|31855942|0.53|
|DOT_USDT|1.151900|-2.37|2.43|-2.14|17228971|0.87|
|ICP_USDT|2.896000|-2.36|-3.37|-2.13|5787282|3.45|
|AVAX_USDT|9.683000|-2.34|-1.36|-2.11|158662146|1.03|
|HBAR_USDT|0.084030|-2.22|0.03|-1.99|14133388|1.19|
|OP_USDT|0.128980|-2.21|-6.76|-1.98|6875873|0.78|
|FET_USDT|0.196200|-2.19|-3.77|-1.96|7801040|5.10|
|INJ_USDT|8.569000|-2.15|12.17|-1.92|50855193|1.17|
|LDO_USDT|0.406800|-2.02|0.24|-1.79|5251972|2.46|
|AAVE_USDT|155.440000|-1.93|-0.28|-1.70|133857098|0.64|
|TAO_USDT|272.430000|-1.83|1.66|-1.60|61945497|1.10|
|DOGE_USDT|0.082070|-1.65|0.10|-1.42|84260534|1.22|
|UNI_USDT|7.521000|-1.29|5.27|-1.06|26787957|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.023937|0.023696|0.023937|1.03|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.189460|0.187440|0.189460|0.62|N|Y/Y|Y/N|N|N|
|AVAX_USDT|9.683000|9.639000|9.683000|0.63|N|Y/Y|Y/N|N|N|
|BR_USDT|0.488130|0.479330|0.488130|0.35|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002378|0.002241|0.002378|1.02|N|Y/Y|N/N|N|N|
|DOT_USDT|1.151900|1.139000|1.151900|0.61|N|Y/Y|Y/N|N|N|
|FET_USDT|0.196200|0.195000|0.196200|2.82|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084030|0.083560|0.084030|0.28|N|Y/Y|Y/N|N|N|
|ICP_USDT|2.896000|2.880000|2.896000|1.63|N|Y/Y|Y/N|N|N|
|INJ_USDT|8.569000|8.558000|8.569000|0.77|N|Y/Y|Y/Y|N|N|
|IOST_USDT|0.000974|0.000946|0.000974|0.74|N|Y/Y|Y/N|N|N|
|OP_USDT|0.128980|0.128270|0.128980|0.45|N|Y/Y|Y/N|N|N|
|STRK_USDT|0.056830|0.056690|0.056850|1.22|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.600900|0.595900|0.600900|0.80|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.939500|1.935400|1.939500|0.64|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=0.024855, depth_time=2026-10-22T00:45:13+00:00, book20_bid_proxy_usdt=19535, book20_ask_proxy_usdt=10781, funding_indicative=0.000050, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.31%, turnover=10959239. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=0.191810, depth_time=2026-10-22T00:45:26+00:00, book20_bid_proxy_usdt=104638, book20_ask_proxy_usdt=61767, funding_indicative=-0.000008, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.63%, turnover=31855942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=9.775000, depth_time=2026-10-22T00:45:34+00:00, book20_bid_proxy_usdt=1148779, book20_ask_proxy_usdt=1709056, funding_indicative=0.000009, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.34%, turnover=158662146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=0.498100, depth_time=2026-10-22T00:45:16+00:00, book20_bid_proxy_usdt=3103, book20_ask_proxy_usdt=3444, funding_indicative=-0.000256, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.86%, turnover=14460688. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=0.002370, depth_time=2026-10-22T00:45:10+00:00, book20_bid_proxy_usdt=171578, book20_ask_proxy_usdt=161070, funding_indicative=-0.000198, next_funding_utc=2026-10-22T01:00:00+00:00, funding_cycle_h=1, 24h_change=-16.38%, turnover=9123737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=1.155200, depth_time=2026-10-22T00:45:29+00:00, book20_bid_proxy_usdt=293049, book20_ask_proxy_usdt=367999, funding_indicative=-0.000140, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.37%, turnover=17228971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=0.196800, depth_time=2026-10-22T00:45:39+00:00, book20_bid_proxy_usdt=1987736, book20_ask_proxy_usdt=1242594, funding_indicative=0.000100, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=7801040. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=0.084870, depth_time=2026-10-22T00:45:38+00:00, book20_bid_proxy_usdt=667360, book20_ask_proxy_usdt=1179058, funding_indicative=-0.000015, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.22%, turnover=14133388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=2.922000, depth_time=2026-10-22T00:45:31+00:00, book20_bid_proxy_usdt=838975, book20_ask_proxy_usdt=920977, funding_indicative=0.000047, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.36%, turnover=5787282. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=8.735000, depth_time=2026-10-22T00:45:46+00:00, book20_bid_proxy_usdt=204790, book20_ask_proxy_usdt=227569, funding_indicative=0.000208, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=50855193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IOST_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=0.001370, depth_time=2026-10-22T00:45:09+00:00, book20_bid_proxy_usdt=10595, book20_ask_proxy_usdt=15422, funding_indicative=-0.005624, next_funding_utc=2026-10-22T01:00:00+00:00, funding_cycle_h=1, 24h_change=-33.50%, turnover=15176647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=0.130200, depth_time=2026-10-22T00:45:41+00:00, book20_bid_proxy_usdt=68155, book20_ask_proxy_usdt=94531, funding_indicative=-0.000021, next_funding_utc=2026-10-22T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=6875873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=0.059630, depth_time=2026-10-22T00:45:19+00:00, book20_bid_proxy_usdt=462262, book20_ask_proxy_usdt=583149, funding_indicative=-0.000039, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.29%, turnover=24785653. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-22T00:44:59+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=0.611400, depth_time=2026-10-22T00:45:20+00:00, book20_bid_proxy_usdt=325490, book20_ask_proxy_usdt=284177, funding_indicative=-0.000151, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.99%, turnover=40436566. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-22T00:45:00+00:00, last15m_closed_end=2026-10-22T00:45+00:00, prior8high=1.962900, depth_time=2026-10-22T00:45:22+00:00, book20_bid_proxy_usdt=75968, book20_ask_proxy_usdt=33701, funding_indicative=0.000012, next_funding_utc=2026-10-22T04:00:00+00:00, funding_cycle_h=4, 24h_change=-7.51%, turnover=7428075. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
