# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T10:45:45Z**
- feed_generated_utc: 2026-10-30T10:45:48+00:00
- source_sha256: `3141da46702f7905efaab03cc17181bf465d170b5a09fd72d5f1f8c18fc821b1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T10:45+00:00, close=77662.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T10:00+00:00, close=77654.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T08:00+00:00, close=78147.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PYTH_USDT|0.061130|-16.47|-17.59|-11.50|5280727|3.27|
|CRV_USDT|0.284900|-15.20|-22.43|-10.23|9312327|3.51|
|TIA_USDT|0.468900|-14.62|-17.50|-9.65|20112958|2.13|
|LIT_USDT|2.804400|-13.89|-22.40|-8.92|18216190|0.36|
|FARTCOIN_USDT|0.117910|-12.26|-17.45|-7.29|15678875|0.85|
|LDO_USDT|0.332000|-12.26|-13.20|-7.29|6379925|3.01|
|INJ_USDT|7.156000|-12.00|-9.78|-7.03|32587599|1.40|
|PENGU_USDT|0.007182|-11.67|-7.06|-6.70|10157856|1.39|
|APT_USDT|0.623200|-11.38|-19.29|-6.41|12007152|1.60|
|FET_USDT|0.163900|-11.30|-11.54|-6.33|14187884|6.10|
|ETHFI_USDT|0.609100|-10.36|-8.03|-5.39|5864301|1.64|
|PUMPFUN_USDT|0.004071|-10.03|-12.99|-5.06|30544372|2.46|
|TAO_USDT|233.510000|-9.76|-9.36|-4.79|88227229|1.28|
|TRUMPOFFICIAL_USDT|1.560000|-9.72|-10.55|-4.75|11146505|6.41|
|JUP_USDT|0.255100|-9.47|-17.70|-4.50|7057565|3.92|
|ONDO_USDT|0.390100|-9.23|-9.48|-4.26|34445365|2.56|
|BTW_USDT|1.522400|-7.06|-14.94|-2.09|10315747|6.55|
|ZEC_USDT|1267.320000|-6.63|2.67|-1.66|2214411983|0.08|
|BNB_USDT|705.500000|-6.19|-3.52|-1.22|56794137|1.42|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.623200|0.612600|0.623200|1.30|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.284900|0.278500|0.284800|0.30|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.609100|0.603100|0.609100|0.30|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.117910|0.116180|0.117890|2.69|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.163900|0.163000|0.163900|1.02|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.156000|7.100000|7.155000|1.20|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.255100|0.252800|0.255100|0.08|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.332000|0.324500|0.332000|1.02|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.804400|2.789700|2.804400|0.51|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007182|0.007058|0.007183|4.87|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004071|0.004016|0.004068|0.30|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.061130|0.060550|0.061160|1.29|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|233.510000|231.840000|233.510000|1.54|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.468900|0.457700|0.469000|2.45|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.560000|1.531000|1.559000|2.37|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=0.622900, depth_time=2026-10-30T10:45:30+00:00, book20_bid_proxy_usdt=117420, book20_ask_proxy_usdt=109390, funding_indicative=0.000070, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.38%, turnover=12007152. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=0.286500, depth_time=2026-10-30T10:45:12+00:00, book20_bid_proxy_usdt=527722, book20_ask_proxy_usdt=587984, funding_indicative=-0.000229, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.20%, turnover=9312327. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=0.612200, depth_time=2026-10-30T10:45:34+00:00, book20_bid_proxy_usdt=258646, book20_ask_proxy_usdt=145143, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.36%, turnover=5864301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=0.117630, depth_time=2026-10-30T10:45:19+00:00, book20_bid_proxy_usdt=43075, book20_ask_proxy_usdt=35478, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.26%, turnover=15678875. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=0.165200, depth_time=2026-10-30T10:45:31+00:00, book20_bid_proxy_usdt=999011, book20_ask_proxy_usdt=577141, funding_indicative=0.000100, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.30%, turnover=14187884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=7.297000, depth_time=2026-10-30T10:45:25+00:00, book20_bid_proxy_usdt=238911, book20_ask_proxy_usdt=225918, funding_indicative=0.000077, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-12.00%, turnover=32587599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=0.255800, depth_time=2026-10-30T10:45:42+00:00, book20_bid_proxy_usdt=433213, book20_ask_proxy_usdt=493625, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.47%, turnover=7057565. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=0.331600, depth_time=2026-10-30T10:45:17+00:00, book20_bid_proxy_usdt=279154, book20_ask_proxy_usdt=244375, funding_indicative=0.000096, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-12.26%, turnover=6379925. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=2.860900, depth_time=2026-10-30T10:45:17+00:00, book20_bid_proxy_usdt=31842, book20_ask_proxy_usdt=26441, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.89%, turnover=18216190. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=0.007196, depth_time=2026-10-30T10:45:26+00:00, book20_bid_proxy_usdt=155281, book20_ask_proxy_usdt=97706, funding_indicative=0.000049, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.67%, turnover=10157856. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=0.004085, depth_time=2026-10-30T10:45:36+00:00, book20_bid_proxy_usdt=1734115, book20_ask_proxy_usdt=1131035, funding_indicative=0.000002, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.03%, turnover=30544372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=0.061710, depth_time=2026-10-30T10:45:09+00:00, book20_bid_proxy_usdt=224276, book20_ask_proxy_usdt=209453, funding_indicative=-0.000148, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-16.47%, turnover=5280727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=234.770000, depth_time=2026-10-30T10:45:39+00:00, book20_bid_proxy_usdt=85210, book20_ask_proxy_usdt=54339, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.76%, turnover=88227229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=0.469800, depth_time=2026-10-30T10:45:15+00:00, book20_bid_proxy_usdt=266805, book20_ask_proxy_usdt=359253, funding_indicative=-0.000032, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.62%, turnover=20112958. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T10:45:04+00:00, last15m_closed_end=2026-10-30T10:45+00:00, prior8high=1.557000, depth_time=2026-10-30T10:45:42+00:00, book20_bid_proxy_usdt=1581643, book20_ask_proxy_usdt=1351601, funding_indicative=-0.000114, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.72%, turnover=11146505. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
