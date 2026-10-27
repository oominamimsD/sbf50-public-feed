# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T04:15:38Z**
- feed_generated_utc: 2026-10-27T04:15:42+00:00
- source_sha256: `6fbafae9d357c06019dd2dc1dcae6a38d352df474e3f4cd14b8e77748f88d366`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T04:15+00:00, close=79800, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|200.140000|-4.82|2.26|-4.06|123648380|0.50|
|PUMPFUN_USDT|0.004156|-3.97|-6.73|-3.21|21088796|2.41|
|NEAR_USDT|4.424000|-3.25|-9.78|-2.49|101180114|2.26|
|DOT_USDT|0.991900|-3.00|-13.50|-2.24|10760247|1.01|
|AAVE_USDT|132.730000|-2.92|-9.84|-2.16|24935271|0.75|
|ONDO_USDT|0.406600|-2.91|-6.01|-2.15|22540717|2.46|
|FET_USDT|0.171700|-2.77|-9.15|-2.01|6515580|5.83|
|FILECOIN_USDT|0.896100|-2.67|-11.45|-1.91|6444170|1.12|
|AVAX_USDT|8.768000|-2.54|-8.30|-1.78|57598082|1.14|
|ICP_USDT|2.569000|-2.31|-9.95|-1.55|5021010|3.89|
|WLD_USDT|0.436200|-1.97|-13.84|-1.21|70342710|2.29|
|PENGU_USDT|0.007426|-1.95|-0.86|-1.19|5515708|1.35|
|ARB_USDT|0.166690|-1.94|-14.79|-1.18|20433027|0.60|
|TAO_USDT|248.800000|-1.85|-7.26|-1.09|46046078|0.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.730000|132.420000|132.730000|0.80|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.166690|0.165910|0.166690|0.15|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.768000|8.762000|8.774000|0.46|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.991900|0.988500|0.991900|0.52|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.171700|0.170600|0.171700|1.95|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.896100|0.892600|0.896100|0.34|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.569000|2.562000|2.569000|1.31|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.424000|4.389000|4.424000|0.44|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.406600|0.404300|0.406800|0.42|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007426|0.007387|0.007426|0.70|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004156|0.004118|0.004156|1.03|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|200.140000|200.410000|200.430000|1.36|N|Y/Y|N/N|Y|N|
|TAO_USDT|248.800000|247.350000|248.800000|0.43|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.436200|0.433900|0.436200|0.57|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T04:14:59+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=134.650000, depth_time=2026-10-27T04:15:17+00:00, book20_bid_proxy_usdt=318483, book20_ask_proxy_usdt=379955, funding_indicative=0.000086, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=24935271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T04:15:03+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=0.168370, depth_time=2026-10-27T04:15:35+00:00, book20_bid_proxy_usdt=109622, book20_ask_proxy_usdt=105720, funding_indicative=-0.000009, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=20433027. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T04:15:03+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=8.906000, depth_time=2026-10-27T04:15:25+00:00, book20_bid_proxy_usdt=2121972, book20_ask_proxy_usdt=1268343, funding_indicative=-0.000038, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=57598082. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T04:15:03+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=0.999600, depth_time=2026-10-27T04:15:14+00:00, book20_bid_proxy_usdt=306692, book20_ask_proxy_usdt=321988, funding_indicative=-0.000134, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=10760247. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T04:14:59+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=0.174000, depth_time=2026-10-27T04:15:20+00:00, book20_bid_proxy_usdt=1797328, book20_ask_proxy_usdt=1062459, funding_indicative=0.000070, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.77%, turnover=6515580. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T04:14:59+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=0.905200, depth_time=2026-10-27T04:15:23+00:00, book20_bid_proxy_usdt=1212192, book20_ask_proxy_usdt=1312648, funding_indicative=-0.000038, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.67%, turnover=6444170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T04:14:59+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=2.604000, depth_time=2026-10-27T04:15:28+00:00, book20_bid_proxy_usdt=1084037, book20_ask_proxy_usdt=1199575, funding_indicative=0.000057, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.31%, turnover=5021010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T04:15:03+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=4.479000, depth_time=2026-10-27T04:15:12+00:00, book20_bid_proxy_usdt=5062529, book20_ask_proxy_usdt=4337354, funding_indicative=0.000043, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.25%, turnover=101180114. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T04:15:03+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=0.410200, depth_time=2026-10-27T04:15:19+00:00, book20_bid_proxy_usdt=2235048, book20_ask_proxy_usdt=3474205, funding_indicative=0.000027, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.91%, turnover=22540717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T04:14:59+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=0.007494, depth_time=2026-10-27T04:15:32+00:00, book20_bid_proxy_usdt=303555, book20_ask_proxy_usdt=213520, funding_indicative=-0.000011, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=5515708. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T04:14:59+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=0.004246, depth_time=2026-10-27T04:15:10+00:00, book20_bid_proxy_usdt=1441216, book20_ask_proxy_usdt=1761767, funding_indicative=0.000026, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.97%, turnover=21088796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T04:15:03+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=205.330000, depth_time=2026-10-27T04:15:07+00:00, book20_bid_proxy_usdt=54068, book20_ask_proxy_usdt=54822, funding_indicative=-0.000113, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.82%, turnover=123648380. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T04:15:03+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=250.100000, depth_time=2026-10-27T04:15:36+00:00, book20_bid_proxy_usdt=162543, book20_ask_proxy_usdt=119148, funding_indicative=0.000022, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=46046078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T04:15:03+00:00, last15m_closed_end=2026-10-27T04:15+00:00, prior8high=0.440800, depth_time=2026-10-27T04:15:30+00:00, book20_bid_proxy_usdt=3595954, book20_ask_proxy_usdt=3278443, funding_indicative=-0.000201, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=70342710. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
