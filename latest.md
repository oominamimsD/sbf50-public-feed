# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-02T17:30:43Z**
- feed_generated_utc: 2026-11-02T17:30:46+00:00
- source_sha256: `6fa8eac3d6c2694f462aad940140c6e1250de887119244948cee74d4b96f5dbb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-02T17:30+00:00, close=77136.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-02T17:00+00:00, close=77464.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-02T16:00+00:00, close=77479.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEC_USDT|1188.340000|-5.24|-4.75|-4.80|1612631020|0.08|
|UAI_USDT|0.127100|-4.22|-48.91|-3.78|7116005|7.87|
|PUMPFUN_USDT|0.003966|-3.36|-8.36|-2.92|10348155|2.52|
|ZRO_USDT|1.711700|-3.19|0.26|-2.75|7284189|0.58|
|ENA_USDT|0.170330|-2.69|-19.03|-2.25|67491151|0.59|
|QNT_USDT|197.370000|-2.50|-6.13|-2.06|48206952|2.53|
|AAVE_USDT|127.360000|-2.45|-6.85|-2.01|26098590|0.79|
|HYPE_USDT|83.867000|-2.15|6.91|-1.71|98052593|0.12|
|LIT_USDT|3.041000|-2.12|-2.47|-1.68|12089568|0.33|
|TIA_USDT|0.448100|-1.92|-16.35|-1.48|11096947|2.23|
|ESPORTS_USDT|0.014928|-1.89|89.20|-1.45|6208540|6.70|
|XPL_USDT|0.068280|-1.86|-8.08|-1.42|9612733|1.46|
|NEAR_USDT|3.940000|-1.74|-13.84|-1.30|72761873|2.54|
|WLD_USDT|0.374700|-1.70|-15.79|-1.26|50978750|2.67|
|ARB_USDT|0.156620|-1.70|-7.86|-1.26|13317635|0.64|
|DASH_USDT|46.410000|-1.67|-11.12|-1.23|9952091|2.15|
|OP_USDT|0.110590|-1.63|-0.99|-1.19|13357390|1.81|
|PEPE_USDT|0.000005|-1.59|5.29|-1.15|80546808|0.22|
|FARTCOIN_USDT|0.117470|-1.50|-8.46|-1.06|10113850|0.85|
|FET_USDT|0.155300|-1.45|-12.06|-1.01|5547926|6.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|127.360000|129.540000|127.390000|4.04|Y|Y/Y|Y/Y|Y|Y|
|ARB_USDT|0.156620|0.157860|0.156620|2.64|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.170330|0.170180|0.170370|1.11|N|Y/Y|Y/Y|Y|N|
|ESPORTS_USDT|0.014928|0.014590|0.014928|0.64|N|Y/Y|N/N|Y|N|
|HYPE_USDT|83.867000|84.258000|83.867000|2.81|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|3.041000|3.035100|3.041000|2.70|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.940000|3.967000|3.940000|1.72|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.003966|0.004003|0.003967|2.21|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|197.370000|199.120000|197.340000|3.67|Y|Y/N|N/N|Y|N|
|TIA_USDT|0.448100|0.451900|0.448100|2.24|Y|Y/Y|Y/Y|Y|Y|
|UAI_USDT|0.127100|0.126900|0.127100|0.39|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.374700|0.376800|0.374700|3.07|Y|Y/Y|Y/Y|Y|Y|
|XPL_USDT|0.068280|0.068180|0.068300|0.75|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1188.340000|1222.240000|1188.350000|1.76|Y|Y/Y|Y/N|Y|N|
|ZRO_USDT|1.711700|1.716800|1.711700|2.64|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=131.660000, depth_time=2026-11-02T17:30:22+00:00, book20_bid_proxy_usdt=519271, book20_ask_proxy_usdt=401659, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=26098590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=0.160550, depth_time=2026-11-02T17:30:42+00:00, book20_bid_proxy_usdt=77476, book20_ask_proxy_usdt=85834, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=13317635. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=0.177460, depth_time=2026-11-02T17:30:18+00:00, book20_bid_proxy_usdt=162412, book20_ask_proxy_usdt=128071, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=67491151. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ESPORTS_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=0.016564, depth_time=2026-11-02T17:30:32+00:00, book20_bid_proxy_usdt=8916, book20_ask_proxy_usdt=16182, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.89%, turnover=6208540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=86.537000, depth_time=2026-11-02T17:30:24+00:00, book20_bid_proxy_usdt=176296, book20_ask_proxy_usdt=124070, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.15%, turnover=98052593. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=3.165900, depth_time=2026-11-02T17:30:27+00:00, book20_bid_proxy_usdt=28087, book20_ask_proxy_usdt=29628, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=12089568. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=4.077000, depth_time=2026-11-02T17:30:37+00:00, book20_bid_proxy_usdt=4342615, book20_ask_proxy_usdt=4071312, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=72761873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=0.004222, depth_time=2026-11-02T17:30:13+00:00, book20_bid_proxy_usdt=1892805, book20_ask_proxy_usdt=350396, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.36%, turnover=10348155. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=204.870000, depth_time=2026-11-02T17:30:20+00:00, book20_bid_proxy_usdt=93875, book20_ask_proxy_usdt=68271, funding_indicative=0.000069, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=48206952. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-02T17:30:01+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=0.460300, depth_time=2026-11-02T17:30:30+00:00, book20_bid_proxy_usdt=229737, book20_ask_proxy_usdt=303360, funding_indicative=0.000045, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=11096947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=0.136800, depth_time=2026-11-02T17:30:10+00:00, book20_bid_proxy_usdt=132773, book20_ask_proxy_usdt=124390, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.22%, turnover=7116005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=0.385100, depth_time=2026-11-02T17:30:39+00:00, book20_bid_proxy_usdt=3783511, book20_ask_proxy_usdt=4498568, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=50978750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=0.070990, depth_time=2026-11-02T17:30:34+00:00, book20_bid_proxy_usdt=460107, book20_ask_proxy_usdt=518481, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.86%, turnover=9612733. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=1269.050000, depth_time=2026-11-02T17:30:08+00:00, book20_bid_proxy_usdt=65596, book20_ask_proxy_usdt=569731, funding_indicative=0.000100, next_funding_utc=2026-11-03T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.24%, turnover=1612631020. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-02T17:30:00+00:00, last15m_closed_end=2026-11-02T17:30+00:00, prior8high=1.795400, depth_time=2026-11-02T17:30:16+00:00, book20_bid_proxy_usdt=32357, book20_ask_proxy_usdt=96713, funding_indicative=0.000050, next_funding_utc=2026-11-02T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.19%, turnover=7284189. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
