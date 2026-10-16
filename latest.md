# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T23:00:41Z**
- feed_generated_utc: 2026-10-16T23:00:44+00:00
- source_sha256: `edc050b63643e2c6938e9f910a10629d46b23cfdb11e2119466e74001a3d0ebe`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T23:00+00:00, close=81750.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T23:00+00:00, close=81750.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-16T20:00+00:00, close=81561.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.196500|-4.16|61.51|-4.68|18460724|2.04|
|ZEC_USDT|1145.380000|-3.58|-5.99|-4.10|1446866925|0.09|
|INJ_USDT|8.665000|-3.48|25.05|-4.00|117943254|4.62|
|RIVER_USDT|1.095000|-2.75|-7.36|-3.27|5701884|9.14|
|FILECOIN_USDT|1.136000|-2.63|6.16|-3.15|23502472|0.88|
|ZRO_USDT|2.049000|-2.48|0.59|-3.00|16126749|0.49|
|TAO_USDT|274.200000|-2.28|-0.17|-2.80|82585857|1.09|
|APT_USDT|0.837300|-2.19|4.59|-2.71|12452595|1.19|
|OP_USDT|0.137020|-2.12|11.19|-2.64|14908156|0.73|
|ARB_USDT|0.191020|-2.01|5.65|-2.53|32734150|0.52|
|AAVE_USDT|154.860000|-1.53|-8.82|-2.05|32111716|0.65|
|STRK_USDT|0.073010|-1.27|-3.05|-1.79|21982184|1.37|
|AVAX_USDT|9.970000|-1.12|-2.17|-1.64|128541337|1.00|
|ICP_USDT|3.005000|-1.08|-0.46|-1.60|8862271|3.33|
|DOT_USDT|1.159000|-1.00|-2.44|-1.52|21998442|0.86|
|QNT_USDT|199.940000|-0.79|-19.84|-1.31|68393027|1.00|
|HBAR_USDT|0.083470|-0.76|-8.13|-1.28|20934580|1.20|
|ENA_USDT|0.198490|-0.72|-7.92|-1.24|41018999|0.50|
|FARTCOIN_USDT|0.153930|-0.51|-5.77|-1.03|7144434|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.860000|153.830000|154.860000|0.78|N|Y/Y|Y/N|Y|N|
|APT_USDT|0.837300|0.833500|0.837300|0.12|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.191020|0.190740|0.191020|0.44|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.970000|9.920000|9.970000|0.31|N|Y/Y|Y/N|Y|N|
|BAT_USDT|0.196500|0.195540|0.196530|0.64|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.159000|1.145400|1.159000|0.58|N|N/Y|N/N|Y|N|
|FILECOIN_USDT|1.136000|1.120000|1.136000|0.59|N|Y/Y|N/N|Y|N|
|ICP_USDT|3.005000|2.984000|3.006000|0.42|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.665000|8.469000|8.668000|0.49|N|Y/Y|N/N|Y|N|
|OP_USDT|0.137020|0.135200|0.137020|0.85|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.095000|1.088000|1.095000|0.23|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.073010|0.072510|0.073010|0.53|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|274.200000|270.100000|274.200000|0.25|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1145.380000|1134.590000|1145.380000|0.40|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|2.049000|2.027800|2.049000|0.75|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=156.060000, depth_time=2026-10-16T23:00:27+00:00, book20_bid_proxy_usdt=372718, book20_ask_proxy_usdt=375091, funding_indicative=0.000064, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=32111716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=0.844800, depth_time=2026-10-16T23:00:23+00:00, book20_bid_proxy_usdt=125335, book20_ask_proxy_usdt=142104, funding_indicative=0.000060, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=12452595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=0.192520, depth_time=2026-10-16T23:00:27+00:00, book20_bid_proxy_usdt=45947, book20_ask_proxy_usdt=42089, funding_indicative=-0.000110, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=32734150. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=10.009000, depth_time=2026-10-16T23:00:36+00:00, book20_bid_proxy_usdt=661348, book20_ask_proxy_usdt=754962, funding_indicative=-0.000006, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=128541337. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=0.202830, depth_time=2026-10-16T23:00:07+00:00, book20_bid_proxy_usdt=14256, book20_ask_proxy_usdt=29602, funding_indicative=-0.000113, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.16%, turnover=18460724. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=1.161000, depth_time=2026-10-16T23:00:39+00:00, book20_bid_proxy_usdt=280095, book20_ask_proxy_usdt=303128, funding_indicative=0.000057, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=21998442. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=1.137900, depth_time=2026-10-16T23:00:16+00:00, book20_bid_proxy_usdt=622945, book20_ask_proxy_usdt=604206, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.63%, turnover=23502472. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=3.014000, depth_time=2026-10-16T23:00:37+00:00, book20_bid_proxy_usdt=955562, book20_ask_proxy_usdt=1157933, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.08%, turnover=8862271. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=8.710000, depth_time=2026-10-16T23:00:12+00:00, book20_bid_proxy_usdt=241711, book20_ask_proxy_usdt=225046, funding_indicative=-0.000088, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=117943254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=0.137470, depth_time=2026-10-16T23:00:26+00:00, book20_bid_proxy_usdt=51472, book20_ask_proxy_usdt=67900, funding_indicative=0.000052, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=14908156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=1.112000, depth_time=2026-10-16T23:00:10+00:00, book20_bid_proxy_usdt=689540, book20_ask_proxy_usdt=341930, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=5701884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=0.073820, depth_time=2026-10-16T23:00:33+00:00, book20_bid_proxy_usdt=387764, book20_ask_proxy_usdt=237541, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=21982184. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=274.250000, depth_time=2026-10-16T23:00:21+00:00, book20_bid_proxy_usdt=69687, book20_ask_proxy_usdt=128642, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=82585857. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=1148.950000, depth_time=2026-10-16T23:00:09+00:00, book20_bid_proxy_usdt=47490, book20_ask_proxy_usdt=763596, funding_indicative=0.000100, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.58%, turnover=1446866925. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-16T22:59:59+00:00, last15m_closed_end=2026-10-16T23:00+00:00, prior8high=2.113300, depth_time=2026-10-16T23:00:19+00:00, book20_bid_proxy_usdt=38526, book20_ask_proxy_usdt=78414, funding_indicative=0.000050, next_funding_utc=2026-10-17T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.48%, turnover=16126749. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
