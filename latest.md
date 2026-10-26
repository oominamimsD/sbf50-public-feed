# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T23:00:43Z**
- feed_generated_utc: 2026-10-26T23:00:47+00:00
- source_sha256: `a1eb1e8c0ca52a22900e3ce453bafde111c84e113a376f892d2e67b9f23a4dd9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T23:00+00:00, close=79977.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T23:00+00:00, close=79977.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T20:00+00:00, close=79988.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.620000|-5.58|-14.82|-5.06|5359430|0.62|
|QNT_USDT|202.080000|-5.24|3.26|-4.72|117315039|0.49|
|LIT_USDT|3.004100|-4.61|-0.91|-4.09|5065279|0.33|
|NEAR_USDT|4.459000|-4.21|-9.07|-3.69|112127023|2.24|
|BR_USDT|0.480500|-3.80|-21.99|-3.28|10252556|2.08|
|PUMPFUN_USDT|0.004231|-2.89|-5.04|-2.37|21753718|2.36|
|ARB_USDT|0.167010|-2.84|-14.62|-2.32|20096332|0.60|
|FILECOIN_USDT|0.901200|-2.73|-10.94|-2.21|6339949|1.11|
|DOT_USDT|1.004800|-2.56|-12.38|-2.04|10363715|2.98|
|WLD_USDT|0.437900|-2.29|-13.50|-1.77|70806226|2.28|
|PEPE_USDT|0.000004|-2.19|3.88|-1.67|78494595|0.23|
|AAVE_USDT|134.860000|-2.19|-8.39|-1.67|25197979|0.74|
|LINK_USDT|11.317000|-2.14|-5.24|-1.62|97375266|0.88|
|SOL_USDT|100.340000|-1.71|-3.60|-1.19|672494519|1.00|
|TAO_USDT|249.650000|-1.52|-6.95|-1.00|46606305|1.20|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|134.860000|134.070000|134.860000|0.30|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167010|0.166370|0.167010|0.69|N|Y/Y|Y/Y|Y|N|
|BR_USDT|0.480500|0.472600|0.480400|1.22|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.004800|0.999300|1.004800|1.20|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.901200|0.895300|0.901200|1.93|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.317000|11.293000|11.317000|0.45|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.004100|2.972000|3.004100|0.17|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.459000|4.437000|4.459000|0.42|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.58|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004231|0.004178|0.004231|0.23|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|202.080000|200.670000|202.080000|0.42|N|Y/N|N/N|Y|N|
|SOL_USDT|100.340000|100.080000|100.340000|0.42|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|249.650000|248.420000|249.670000|2.23|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.437900|0.432200|0.437900|0.19|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.620000|1.608700|1.620000|0.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-26T23:00:00+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=135.610000, depth_time=2026-10-26T23:00:35+00:00, book20_bid_proxy_usdt=337649, book20_ask_proxy_usdt=392062, funding_indicative=0.000091, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=25197979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-26T23:00:00+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=0.168330, depth_time=2026-10-26T23:00:21+00:00, book20_bid_proxy_usdt=48918, book20_ask_proxy_usdt=75257, funding_indicative=-0.000024, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.84%, turnover=20096332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-26T23:00:00+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=0.487600, depth_time=2026-10-26T23:00:18+00:00, book20_bid_proxy_usdt=38002, book20_ask_proxy_usdt=41203, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.80%, turnover=10252556. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T23:00:00+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=1.011200, depth_time=2026-10-26T23:00:28+00:00, book20_bid_proxy_usdt=482591, book20_ask_proxy_usdt=359282, funding_indicative=-0.000052, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=10363715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T23:00:01+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=0.909400, depth_time=2026-10-26T23:00:21+00:00, book20_bid_proxy_usdt=953170, book20_ask_proxy_usdt=1518572, funding_indicative=0.000074, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=6339949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-26T23:00:00+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=11.397000, depth_time=2026-10-26T23:00:37+00:00, book20_bid_proxy_usdt=477098, book20_ask_proxy_usdt=541088, funding_indicative=0.000095, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.14%, turnover=97375266. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T23:00:00+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=3.019000, depth_time=2026-10-26T23:00:12+00:00, book20_bid_proxy_usdt=18839, book20_ask_proxy_usdt=22108, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.61%, turnover=5065279. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T23:00:00+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=4.492000, depth_time=2026-10-26T23:00:16+00:00, book20_bid_proxy_usdt=4797366, book20_ask_proxy_usdt=3975690, funding_indicative=0.000060, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.21%, turnover=112127023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T23:00:00+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=0.000004, depth_time=2026-10-26T23:00:33+00:00, book20_bid_proxy_usdt=52502, book20_ask_proxy_usdt=57831, funding_indicative=0.000082, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=78494595. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T23:00:00+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=0.004254, depth_time=2026-10-26T23:00:21+00:00, book20_bid_proxy_usdt=2675498, book20_ask_proxy_usdt=1542298, funding_indicative=-0.000006, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.89%, turnover=21753718. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-26T23:00:00+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=204.690000, depth_time=2026-10-26T23:00:11+00:00, book20_bid_proxy_usdt=64551, book20_ask_proxy_usdt=53237, funding_indicative=-0.000007, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.24%, turnover=117315039. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-26T23:00:00+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=100.800000, depth_time=2026-10-26T23:00:39+00:00, book20_bid_proxy_usdt=18037788, book20_ask_proxy_usdt=17571043, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=672494519. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-26T23:00:00+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=250.750000, depth_time=2026-10-26T23:00:41+00:00, book20_bid_proxy_usdt=149870, book20_ask_proxy_usdt=129859, funding_indicative=0.000050, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.52%, turnover=46606305. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T23:00:00+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=0.438800, depth_time=2026-10-26T23:00:31+00:00, book20_bid_proxy_usdt=2550748, book20_ask_proxy_usdt=2755737, funding_indicative=-0.000132, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.29%, turnover=70806226. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-26T23:00:01+00:00, last15m_closed_end=2026-10-26T23:00+00:00, prior8high=1.643300, depth_time=2026-10-26T23:00:08+00:00, book20_bid_proxy_usdt=30573, book20_ask_proxy_usdt=24549, funding_indicative=-0.000013, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=4, 24h_change=-5.58%, turnover=5359430. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
