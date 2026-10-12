# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-12T17:15:40Z**
- feed_generated_utc: 2026-10-12T17:15:43+00:00
- source_sha256: `e0d20d6603da789a45a1317d9f7790e92c7cf8c5759ea863d0194704e1b8dc8a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-12T17:15+00:00, close=82585.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-12T17:00+00:00, close=82473.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-12T16:00+00:00, close=82680.3, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CKB_USDT|0.001599|-3.34|20.70|-3.23|5684457|2.50|
|INJ_USDT|7.626000|-3.00|1.76|-2.89|34976194|1.31|
|TIA_USDT|0.553500|-2.84|18.62|-2.73|41131974|1.81|
|CRV_USDT|0.352200|-2.76|-5.75|-2.65|5324927|2.84|
|ZRO_USDT|2.209800|-2.26|8.02|-2.15|27239890|2.72|
|EIGEN_USDT|0.255900|-2.17|-1.42|-2.06|6708458|3.91|
|BAT_USDT|0.147100|-2.14|40.73|-2.03|5284136|2.72|
|ZEC_USDT|1245.020000|-1.57|-3.84|-1.46|1440968367|0.16|
|JUP_USDT|0.337500|-1.57|-0.11|-1.46|8456417|2.96|
|AVAX_USDT|10.517000|-1.53|-3.06|-1.42|63462299|0.95|
|NEAR_USDT|5.469000|-1.44|8.90|-1.33|268604870|1.83|
|MAGIC_USDT|0.120230|-1.41|93.95|-1.30|12309236|1.66|
|APT_USDT|0.830700|-1.38|1.92|-1.27|24428861|1.20|
|ARB_USDT|0.185930|-1.34|-8.30|-1.23|36595603|0.54|
|PUMPFUN_USDT|0.005238|-1.33|-17.31|-1.22|25295559|1.91|
|SUI_USDT|1.073900|-1.23|-9.39|-1.12|94598391|0.93|
|DOT_USDT|1.221200|-1.22|2.28|-1.11|22893948|0.82|
|HBAR_USDT|0.089460|-1.14|-11.16|-1.03|14214684|1.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.830700|0.824600|0.830700|0.96|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.185930|0.184160|0.185930|2.20|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|10.517000|10.449000|10.516000|0.93|N|Y/Y|Y/N|Y|N|
|BAT_USDT|0.147100|0.143660|0.147100|0.65|N|Y/Y|N/N|Y|N|
|CKB_USDT|0.001599|0.001576|0.001599|0.84|N|Y/Y|N/N|Y|N|
|CRV_USDT|0.352200|0.346300|0.352700|6.06|N|Y/Y|Y/N|Y|N|
|EIGEN_USDT|0.255900|0.254600|0.255900|1.26|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.626000|7.506000|7.626000|2.82|N|Y/Y|N/N|Y|N|
|JUP_USDT|0.337500|0.335900|0.337500|1.59|N|Y/Y|Y/Y|Y|N|
|MAGIC_USDT|0.120230|0.115400|0.120230|0.54|N|Y/Y|N/N|Y|N|
|NEAR_USDT|5.469000|5.375000|5.469000|1.11|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.005238|0.005183|0.005238|1.26|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.553500|0.548200|0.553500|0.47|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1245.020000|1237.400000|1245.020000|1.21|N|Y/Y|N/N|Y|N|
|ZRO_USDT|2.209800|2.200900|2.210400|0.56|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=0.850200, depth_time=2026-10-12T17:15:34+00:00, book20_bid_proxy_usdt=133628, book20_ask_proxy_usdt=103528, funding_indicative=-0.000129, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=24428861. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=0.189800, depth_time=2026-10-12T17:15:37+00:00, book20_bid_proxy_usdt=58179, book20_ask_proxy_usdt=111078, funding_indicative=0.000100, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=36595603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=10.733000, depth_time=2026-10-12T17:15:28+00:00, book20_bid_proxy_usdt=467465, book20_ask_proxy_usdt=632306, funding_indicative=-0.000012, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=63462299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=0.153140, depth_time=2026-10-12T17:15:17+00:00, book20_bid_proxy_usdt=18426, book20_ask_proxy_usdt=14254, funding_indicative=0.000100, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=5284136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CKB_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=0.001674, depth_time=2026-10-12T17:15:06+00:00, book20_bid_proxy_usdt=22816, book20_ask_proxy_usdt=16611, funding_indicative=-0.000716, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.34%, turnover=5684457. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-12T17:15:01+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=0.363800, depth_time=2026-10-12T17:15:11+00:00, book20_bid_proxy_usdt=519337, book20_ask_proxy_usdt=552444, funding_indicative=0.000042, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=5324927. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=0.264100, depth_time=2026-10-12T17:15:18+00:00, book20_bid_proxy_usdt=783400, book20_ask_proxy_usdt=659749, funding_indicative=0.000024, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=6708458. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=7.887000, depth_time=2026-10-12T17:15:09+00:00, book20_bid_proxy_usdt=172245, book20_ask_proxy_usdt=223691, funding_indicative=0.000225, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=34976194. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=0.345600, depth_time=2026-10-12T17:15:25+00:00, book20_bid_proxy_usdt=635064, book20_ask_proxy_usdt=501058, funding_indicative=-0.000093, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.57%, turnover=8456417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGIC_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=0.123510, depth_time=2026-10-12T17:15:32+00:00, book20_bid_proxy_usdt=167997, book20_ask_proxy_usdt=178367, funding_indicative=-0.000184, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.41%, turnover=12309236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=5.635000, depth_time=2026-10-12T17:15:30+00:00, book20_bid_proxy_usdt=2011862, book20_ask_proxy_usdt=2516570, funding_indicative=0.000008, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=268604870. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=0.005434, depth_time=2026-10-12T17:15:39+00:00, book20_bid_proxy_usdt=1014178, book20_ask_proxy_usdt=1329903, funding_indicative=-0.000030, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.33%, turnover=25295559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=0.580000, depth_time=2026-10-12T17:15:11+00:00, book20_bid_proxy_usdt=73855, book20_ask_proxy_usdt=130116, funding_indicative=0.000050, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=41131974. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=1273.660000, depth_time=2026-10-12T17:15:23+00:00, book20_bid_proxy_usdt=242612, book20_ask_proxy_usdt=325475, funding_indicative=0.000040, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=1440968367. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-12T17:15:00+00:00, last15m_closed_end=2026-10-12T17:15+00:00, prior8high=2.357200, depth_time=2026-10-12T17:15:16+00:00, book20_bid_proxy_usdt=61985, book20_ask_proxy_usdt=52597, funding_indicative=0.000042, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=27239890. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
