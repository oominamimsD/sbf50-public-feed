# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-12T17:45:44Z**
- feed_generated_utc: 2026-10-12T17:45:47+00:00
- source_sha256: `563dff2ed44d92a644ac4fcbb9c1184e205a3027b7d73316035c3a77957954b7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 21; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-12T17:45+00:00, close=82447.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-12T17:00+00:00, close=82473.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-12T16:00+00:00, close=82680.3, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CKB_USDT|0.001588|-4.02|19.85|-3.74|5699679|3.15|
|CRV_USDT|0.347800|-3.97|-6.93|-3.69|5791296|2.88|
|TIA_USDT|0.551500|-3.19|18.19|-2.91|42009360|1.81|
|INJ_USDT|7.628000|-2.97|1.78|-2.69|35529765|1.31|
|EIGEN_USDT|0.254300|-2.79|-2.04|-2.51|6730890|3.94|
|ZRO_USDT|2.202800|-2.57|7.68|-2.29|27573980|0.91|
|JUP_USDT|0.336100|-1.98|-0.53|-1.70|8592071|2.98|
|AVAX_USDT|10.470000|-1.97|-3.50|-1.69|64129406|0.95|
|DOT_USDT|1.212600|-1.92|1.56|-1.64|23256063|0.82|
|APT_USDT|0.826400|-1.89|1.39|-1.61|25004754|1.21|
|ZEC_USDT|1241.180000|-1.87|-4.14|-1.59|1472827850|0.08|
|RLC_USDT|0.970600|-1.82|77.11|-1.54|10661570|2.06|
|ARB_USDT|0.185110|-1.78|-8.70|-1.50|37664861|0.54|
|NEAR_USDT|5.452000|-1.74|8.56|-1.46|272979051|1.83|
|SUI_USDT|1.070000|-1.59|-9.72|-1.31|95739407|0.94|
|PUMPFUN_USDT|0.005227|-1.54|-17.49|-1.26|25814202|1.91|
|TAO_USDT|282.000000|-1.49|-5.88|-1.21|106931493|1.06|
|ETHFI_USDT|0.689600|-1.45|-8.63|-1.17|5584860|1.45|
|VIRTUAL_USDT|0.709000|-1.40|-15.36|-1.12|5859416|1.41|
|HBAR_USDT|0.089280|-1.34|-11.34|-1.06|14623357|1.12|
|SOL_USDT|107.410000|-1.32|-9.95|-1.04|811195442|0.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.826400|0.822600|0.826400|0.93|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.185110|0.184150|0.185110|1.57|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|10.470000|10.435000|10.470000|0.33|N|Y/Y|Y/N|Y|N|
|CKB_USDT|0.001588|0.001574|0.001588|0.27|N|Y/Y|N/N|Y|N|
|CRV_USDT|0.347800|0.346300|0.347800|6.99|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.212600|1.212700|1.212600|0.55|N|Y/Y|N/N|Y|N|
|EIGEN_USDT|0.254300|0.253000|0.254300|0.23|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.628000|7.506000|7.628000|0.26|N|Y/Y|N/N|Y|N|
|JUP_USDT|0.336100|0.335300|0.336200|0.55|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|5.452000|5.375000|5.452000|0.99|N|Y/Y|N/N|Y|N|
|RLC_USDT|0.970600|0.953600|0.970600|0.92|N|Y/Y|N/N|Y|N|
|SUI_USDT|1.070000|1.064000|1.070000|0.74|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.551500|0.545200|0.551500|0.42|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1241.180000|1231.440000|1241.070000|0.99|N|Y/Y|N/N|Y|N|
|ZRO_USDT|2.202800|2.176300|2.202800|0.67|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=0.847400, depth_time=2026-10-12T17:45:30+00:00, book20_bid_proxy_usdt=151921, book20_ask_proxy_usdt=194335, funding_indicative=-0.000129, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.89%, turnover=25004754. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=0.189740, depth_time=2026-10-12T17:45:38+00:00, book20_bid_proxy_usdt=221882, book20_ask_proxy_usdt=74120, funding_indicative=0.000100, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=37664861. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=10.733000, depth_time=2026-10-12T17:45:25+00:00, book20_bid_proxy_usdt=935533, book20_ask_proxy_usdt=611450, funding_indicative=-0.000015, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=64129406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CKB_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=0.001674, depth_time=2026-10-12T17:45:05+00:00, book20_bid_proxy_usdt=16240, book20_ask_proxy_usdt=12950, funding_indicative=-0.000660, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.02%, turnover=5699679. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=0.363800, depth_time=2026-10-12T17:45:09+00:00, book20_bid_proxy_usdt=846162, book20_ask_proxy_usdt=720648, funding_indicative=0.000003, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.97%, turnover=5791296. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=1.247900, depth_time=2026-10-12T17:45:28+00:00, book20_bid_proxy_usdt=382989, book20_ask_proxy_usdt=294384, funding_indicative=0.000100, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=23256063. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=0.264100, depth_time=2026-10-12T17:45:16+00:00, book20_bid_proxy_usdt=554964, book20_ask_proxy_usdt=476230, funding_indicative=0.000041, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=6730890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=7.887000, depth_time=2026-10-12T17:45:15+00:00, book20_bid_proxy_usdt=399335, book20_ask_proxy_usdt=177387, funding_indicative=0.000225, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=35529765. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=0.344900, depth_time=2026-10-12T17:45:20+00:00, book20_bid_proxy_usdt=557331, book20_ask_proxy_usdt=481297, funding_indicative=-0.000095, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.98%, turnover=8592071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-12T17:45:01+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=5.588000, depth_time=2026-10-12T17:45:40+00:00, book20_bid_proxy_usdt=1945192, book20_ask_proxy_usdt=1968632, funding_indicative=0.000003, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=272979051. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=1.013000, depth_time=2026-10-12T17:45:36+00:00, book20_bid_proxy_usdt=38615, book20_ask_proxy_usdt=44010, funding_indicative=-0.000897, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=10661570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=1.092900, depth_time=2026-10-12T17:45:43+00:00, book20_bid_proxy_usdt=1116444, book20_ask_proxy_usdt=1486710, funding_indicative=0.000047, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=95739407. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=0.580000, depth_time=2026-10-12T17:45:13+00:00, book20_bid_proxy_usdt=159144, book20_ask_proxy_usdt=138926, funding_indicative=0.000050, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.19%, turnover=42009360. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=1272.400000, depth_time=2026-10-12T17:45:34+00:00, book20_bid_proxy_usdt=259013, book20_ask_proxy_usdt=943345, funding_indicative=0.000062, next_funding_utc=2026-10-13T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=1472827850. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-12T17:45:02+00:00, last15m_closed_end=2026-10-12T17:45+00:00, prior8high=2.312600, depth_time=2026-10-12T17:45:21+00:00, book20_bid_proxy_usdt=40620, book20_ask_proxy_usdt=38299, funding_indicative=0.000049, next_funding_utc=2026-10-12T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=27573980. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
