# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T03:00:43Z**
- feed_generated_utc: 2026-10-17T03:00:45+00:00
- source_sha256: `a23de334a5e036183867f70beaea29e21bfcc97b02ea8ddb1d7aa114d6499a9e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T03:00+00:00, close=81449.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T03:00+00:00, close=81449.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T00:00+00:00, close=81578.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.954700|-6.97|-4.03|-7.13|15892529|0.51|
|RIVER_USDT|1.079000|-4.17|-8.71|-4.33|5426473|9.26|
|STRK_USDT|0.070990|-4.00|-5.73|-4.16|22120050|1.41|
|ZEC_USDT|1145.440000|-3.58|-5.98|-3.74|1406074891|0.09|
|BAT_USDT|0.197970|-3.44|62.72|-3.60|15190918|1.51|
|ARB_USDT|0.188670|-3.21|4.35|-3.37|33196872|0.53|
|TAO_USDT|274.150000|-2.30|-0.18|-2.46|80369134|1.09|
|APT_USDT|0.836700|-2.26|4.52|-2.42|12706819|1.20|
|FET_USDT|0.195200|-2.20|-10.04|-2.36|11531317|5.13|
|INJ_USDT|8.804000|-1.93|27.06|-2.09|114043058|1.14|
|DASH_USDT|48.760000|-1.81|-5.02|-1.97|10712886|2.05|
|JUP_USDT|0.301200|-1.66|-18.79|-1.82|6085286|3.32|
|AAVE_USDT|154.930000|-1.49|-8.77|-1.65|31175341|0.65|
|SUI_USDT|1.005600|-1.46|-4.91|-1.62|98041974|0.99|
|ENA_USDT|0.197310|-1.31|-8.47|-1.47|40865808|0.51|
|ICP_USDT|3.000000|-1.25|-0.62|-1.41|9148613|3.33|
|FARTCOIN_USDT|0.152790|-1.24|-6.47|-1.40|7184757|0.66|
|AVAX_USDT|9.967000|-1.15|-2.20|-1.31|125435327|1.00|
|ONDO_USDT|0.452500|-1.00|-5.74|-1.16|28897432|2.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.930000|153.940000|154.930000|0.83|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.836700|0.833600|0.836700|0.46|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.188670|0.187590|0.188670|1.37|N|Y/Y|N/N|Y|N|
|BAT_USDT|0.197970|0.197130|0.197970|0.24|N|Y/N|N/N|Y|N|
|DASH_USDT|48.760000|48.660000|48.760000|0.05|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.197310|0.196360|0.197310|0.19|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.195200|0.194100|0.195200|0.20|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.804000|8.668000|8.804000|0.93|N|N/N|N/N|Y|N|
|JUP_USDT|0.301200|0.300900|0.301200|8.06|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.079000|1.075000|1.079000|1.45|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.070990|0.070190|0.070990|2.78|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.005600|1.001200|1.005600|0.47|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|274.150000|273.080000|274.150000|0.36|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1145.440000|1140.370000|1145.440000|0.74|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.954700|1.944000|1.954700|0.49|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T02:59:59+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=155.480000, depth_time=2026-10-17T03:00:37+00:00, book20_bid_proxy_usdt=305381, book20_ask_proxy_usdt=266783, funding_indicative=0.000053, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=31175341. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T02:59:59+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=0.848700, depth_time=2026-10-17T03:00:25+00:00, book20_bid_proxy_usdt=171060, book20_ask_proxy_usdt=132350, funding_indicative=0.000056, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=12706819. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T02:59:59+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=0.190730, depth_time=2026-10-17T03:00:18+00:00, book20_bid_proxy_usdt=69710, book20_ask_proxy_usdt=73799, funding_indicative=-0.000083, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=33196872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-17T02:59:59+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=0.201540, depth_time=2026-10-17T03:00:17+00:00, book20_bid_proxy_usdt=21826, book20_ask_proxy_usdt=23601, funding_indicative=-0.000010, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.44%, turnover=15190918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-17T03:00:00+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=49.170000, depth_time=2026-10-17T03:00:32+00:00, book20_bid_proxy_usdt=1345943, book20_ask_proxy_usdt=836162, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=10712886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-17T02:59:59+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=0.198780, depth_time=2026-10-17T03:00:41+00:00, book20_bid_proxy_usdt=231410, book20_ask_proxy_usdt=210710, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=40865808. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T02:59:59+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=0.196800, depth_time=2026-10-17T03:00:27+00:00, book20_bid_proxy_usdt=1549959, book20_ask_proxy_usdt=1108670, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=11531317. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-17T02:59:59+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=8.886000, depth_time=2026-10-17T03:00:29+00:00, book20_bid_proxy_usdt=210671, book20_ask_proxy_usdt=297079, funding_indicative=0.000087, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=114043058. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-17T03:00:00+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=0.304100, depth_time=2026-10-17T03:00:29+00:00, book20_bid_proxy_usdt=459034, book20_ask_proxy_usdt=464340, funding_indicative=-0.000040, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.66%, turnover=6085286. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T02:59:59+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=1.093000, depth_time=2026-10-17T03:00:07+00:00, book20_bid_proxy_usdt=520369, book20_ask_proxy_usdt=373929, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.17%, turnover=5426473. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T02:59:59+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=0.074750, depth_time=2026-10-17T03:00:12+00:00, book20_bid_proxy_usdt=459602, book20_ask_proxy_usdt=224140, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.00%, turnover=22120050. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T02:59:59+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=1.010300, depth_time=2026-10-17T03:00:38+00:00, book20_bid_proxy_usdt=784875, book20_ask_proxy_usdt=1412122, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=98041974. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T02:59:59+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=275.370000, depth_time=2026-10-17T03:00:21+00:00, book20_bid_proxy_usdt=86720, book20_ask_proxy_usdt=64344, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.30%, turnover=80369134. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T02:59:59+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=1157.920000, depth_time=2026-10-17T03:00:15+00:00, book20_bid_proxy_usdt=921784, book20_ask_proxy_usdt=180358, funding_indicative=0.000069, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=1406074891. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T02:59:59+00:00, last15m_closed_end=2026-10-17T03:00+00:00, prior8high=1.978100, depth_time=2026-10-17T03:00:08+00:00, book20_bid_proxy_usdt=104002, book20_ask_proxy_usdt=29688, funding_indicative=0.000050, next_funding_utc=2026-10-17T04:00:00+00:00, funding_cycle_h=4, 24h_change=-6.97%, turnover=15892529. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
