# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T12:00:39Z**
- feed_generated_utc: 2026-11-09T12:00:41+00:00
- source_sha256: `baaaf14f0a7bff51f27e0ad77c3ca2359f56119067aa765afcfd97ef843c35b2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1204; contracts: 1196; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001500|-23.39|28.81|-21.17|6781292|0.67|
|JCT_USDT|0.008471|-13.86|70.13|-11.64|71692330|4.72|
|ASTER_USDT|0.633600|-6.79|-9.40|-4.57|5621079|1.58|
|XRP_USDT|1.080500|-6.51|-13.55|-4.29|282649064|0.93|
|ETH_USDT|2112.360000|-5.74|-6.77|-3.52|1583295752|0.05|
|HYPE_USDT|73.065000|-5.63|-16.67|-3.41|49373220|0.14|
|NEAR_USDT|3.510000|-5.16|-18.95|-2.94|47059546|2.85|
|ZEC_USDT|1206.590000|-5.04|-2.53|-2.82|2342324070|0.08|
|TRUMPOFFICIAL_USDT|1.129000|-5.04|-34.20|-2.82|6522222|8.86|
|SOL_USDT|86.070000|-4.02|-9.17|-1.80|740373759|1.16|
|XLM_USDT|0.145670|-3.66|-13.47|-1.44|28322360|0.69|
|DOGE_USDT|0.068790|-3.57|-9.05|-1.35|75397325|1.45|
|DOT_USDT|0.861800|-3.26|-8.99|-1.04|10459087|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.633600|0.623900|0.633600|1.40|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.068790|0.068500|0.068790|0.80|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.861800|0.854600|0.861700|0.27|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2112.360000|2098.500000|2112.370000|0.57|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|73.065000|72.747000|73.065000|0.42|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008471|0.008481|0.008471|0.66|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.510000|3.480000|3.510000|0.74|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001500|0.001508|0.001500|1.06|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.070000|85.770000|86.070000|1.37|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.129000|1.124000|1.129000|0.74|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.145670|0.144930|0.145670|0.69|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.080500|1.076200|1.080500|1.37|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1206.590000|1192.400000|1206.600000|0.68|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-11-09T11:59:59+00:00, last15m_closed_end=2026-11-09T12:00+00:00, prior8high=0.633800, depth_time=2026-11-09T12:00:11+00:00, book20_bid_proxy_usdt=550726, book20_ask_proxy_usdt=912861, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.79%, turnover=5621079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-09T11:59:59+00:00, last15m_closed_end=2026-11-09T12:00+00:00, prior8high=0.069470, depth_time=2026-11-09T12:00:32+00:00, book20_bid_proxy_usdt=4551990, book20_ask_proxy_usdt=3762268, funding_indicative=0.000035, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.57%, turnover=75397325. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T11:59:59+00:00, last15m_closed_end=2026-11-09T12:00+00:00, prior8high=0.868900, depth_time=2026-11-09T12:00:37+00:00, book20_bid_proxy_usdt=849906, book20_ask_proxy_usdt=716837, funding_indicative=0.000093, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.26%, turnover=10459087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T11:59:58+00:00, last15m_closed_end=2026-11-09T12:00+00:00, prior8high=2132.860000, depth_time=2026-11-09T12:00:18+00:00, book20_bid_proxy_usdt=6131247, book20_ask_proxy_usdt=1923428, funding_indicative=-0.000027, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.74%, turnover=1583295752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T11:59:59+00:00, last15m_closed_end=2026-11-09T12:00+00:00, prior8high=74.029000, depth_time=2026-11-09T12:00:19+00:00, book20_bid_proxy_usdt=74274, book20_ask_proxy_usdt=94255, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.63%, turnover=49373220. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T11:59:58+00:00, last15m_closed_end=2026-11-09T12:00+00:00, prior8high=0.009762, depth_time=2026-11-09T12:00:10+00:00, book20_bid_proxy_usdt=73495, book20_ask_proxy_usdt=47078, funding_indicative=0.001287, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.86%, turnover=71692330. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T11:59:59+00:00, last15m_closed_end=2026-11-09T12:00+00:00, prior8high=3.570000, depth_time=2026-11-09T12:00:22+00:00, book20_bid_proxy_usdt=2769586, book20_ask_proxy_usdt=2297809, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.16%, turnover=47059546. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T11:59:59+00:00, last15m_closed_end=2026-11-09T12:00+00:00, prior8high=0.001610, depth_time=2026-11-09T12:00:07+00:00, book20_bid_proxy_usdt=21660, book20_ask_proxy_usdt=25210, funding_indicative=0.000032, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.39%, turnover=6781292. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T11:59:59+00:00, last15m_closed_end=2026-11-09T12:00+00:00, prior8high=87.140000, depth_time=2026-11-09T12:00:30+00:00, book20_bid_proxy_usdt=13986828, book20_ask_proxy_usdt=13448832, funding_indicative=0.000012, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.02%, turnover=740373759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T11:59:59+00:00, last15m_closed_end=2026-11-09T12:00+00:00, prior8high=1.148000, depth_time=2026-11-09T12:00:28+00:00, book20_bid_proxy_usdt=2695572, book20_ask_proxy_usdt=2187998, funding_indicative=-0.000002, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.04%, turnover=6522222. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-09T11:59:59+00:00, last15m_closed_end=2026-11-09T12:00+00:00, prior8high=0.146930, depth_time=2026-11-09T12:00:31+00:00, book20_bid_proxy_usdt=139015, book20_ask_proxy_usdt=131282, funding_indicative=-0.000030, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.66%, turnover=28322360. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T11:59:59+00:00, last15m_closed_end=2026-11-09T12:00+00:00, prior8high=1.093100, depth_time=2026-11-09T12:00:14+00:00, book20_bid_proxy_usdt=5841045, book20_ask_proxy_usdt=3312811, funding_indicative=0.000095, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.51%, turnover=282649064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T11:59:59+00:00, last15m_closed_end=2026-11-09T12:00+00:00, prior8high=1225.880000, depth_time=2026-11-09T12:00:25+00:00, book20_bid_proxy_usdt=258547, book20_ask_proxy_usdt=405424, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.04%, turnover=2342324070. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
