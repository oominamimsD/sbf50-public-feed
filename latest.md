# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T11:15:43Z**
- feed_generated_utc: 2026-11-09T11:15:45+00:00
- source_sha256: `0f93abea43e6b7a9d093b5258944b802d2fe4d14d1a87f84749a17b08a75c670`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T11:15+00:00, close=74098.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-09T11:00+00:00, close=74125.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T08:00+00:00, close=73840.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001535|-21.60|31.80|-19.05|6576671|0.65|
|ASTER_USDT|0.629400|-7.41|-10.00|-4.86|5541254|1.59|
|XRP_USDT|1.078200|-6.71|-13.73|-4.16|272107875|0.93|
|JCT_USDT|0.009177|-6.68|84.31|-4.13|71007156|1.09|
|ETH_USDT|2105.030000|-6.07|-7.09|-3.52|1521692639|0.05|
|HYPE_USDT|72.851000|-5.91|-16.92|-3.36|47338858|0.14|
|NEAR_USDT|3.491000|-5.67|-19.39|-3.12|45077624|5.73|
|ZEC_USDT|1203.220000|-5.30|-2.80|-2.75|2284140333|0.08|
|TRUMPOFFICIAL_USDT|1.126000|-5.29|-34.38|-2.74|6415174|8.88|
|PUMPFUN_USDT|0.003567|-4.54|-15.43|-1.99|10413291|2.80|
|TAO_USDT|216.120000|-4.38|-7.97|-1.83|52510885|1.39|
|SOL_USDT|85.870000|-4.24|-9.38|-1.69|703260351|1.17|
|XLM_USDT|0.145030|-4.08|-13.85|-1.53|27712790|1.38|
|DOGE_USDT|0.068510|-3.96|-9.42|-1.41|73438369|1.46|
|DOT_USDT|0.856500|-3.86|-9.55|-1.31|10324783|1.17|
|SUI_USDT|0.818900|-3.83|-9.05|-1.28|51694901|1.22|
|UNI_USDT|6.741000|-3.74|-7.09|-1.19|26808875|1.48|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ASTER_USDT|0.629400|0.623900|0.629400|1.45|N|Y/Y|Y/Y|Y|N|
|DOGE_USDT|0.068510|0.068630|0.068510|1.03|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.856500|0.854600|0.856500|0.02|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2105.030000|2098.500000|2105.030000|0.42|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|72.851000|72.807000|72.851000|0.58|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009177|0.008284|0.009177|0.84|N|N/Y|N/N|Y|N|
|NEAR_USDT|3.491000|3.480000|3.490000|1.60|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001535|0.001531|0.001535|1.22|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003567|0.003547|0.003568|0.23|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|85.870000|85.850000|85.870000|0.61|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|216.120000|215.040000|216.120000|0.93|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.126000|1.124000|1.126000|2.01|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.145030|0.145520|0.145040|0.85|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.078200|1.083500|1.078100|3.27|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1203.220000|1192.400000|1203.220000|0.76|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ASTER_USDT: quote_utc=2026-11-09T11:15:02+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=0.636600, depth_time=2026-11-09T11:15:06+00:00, book20_bid_proxy_usdt=578598, book20_ask_proxy_usdt=774527, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.41%, turnover=5541254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOGE_USDT: quote_utc=2026-11-09T11:15:01+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=0.069600, depth_time=2026-11-09T11:15:38+00:00, book20_bid_proxy_usdt=3793373, book20_ask_proxy_usdt=4691859, funding_indicative=0.000023, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.96%, turnover=73438369. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-09T11:15:02+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=0.872200, depth_time=2026-11-09T11:15:42+00:00, book20_bid_proxy_usdt=570357, book20_ask_proxy_usdt=815751, funding_indicative=0.000073, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=10324783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T11:15:01+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=2127.470000, depth_time=2026-11-09T11:15:18+00:00, book20_bid_proxy_usdt=3878965, book20_ask_proxy_usdt=2448664, funding_indicative=-0.000032, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.07%, turnover=1521692639. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T11:15:01+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=74.219000, depth_time=2026-11-09T11:15:20+00:00, book20_bid_proxy_usdt=106606, book20_ask_proxy_usdt=96256, funding_indicative=0.000042, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.91%, turnover=47338858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T11:15:01+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=0.009792, depth_time=2026-11-09T11:15:15+00:00, book20_bid_proxy_usdt=65312, book20_ask_proxy_usdt=60408, funding_indicative=0.001337, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.68%, turnover=71007156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T11:15:01+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=3.578000, depth_time=2026-11-09T11:15:22+00:00, book20_bid_proxy_usdt=2548103, book20_ask_proxy_usdt=2846788, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.67%, turnover=45077624. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T11:15:01+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=0.001610, depth_time=2026-11-09T11:15:07+00:00, book20_bid_proxy_usdt=18440, book20_ask_proxy_usdt=29041, funding_indicative=-0.000043, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.60%, turnover=6576671. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-09T11:15:02+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=0.003597, depth_time=2026-11-09T11:15:30+00:00, book20_bid_proxy_usdt=2588434, book20_ask_proxy_usdt=2897636, funding_indicative=0.000030, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.54%, turnover=10413291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T11:15:01+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=87.260000, depth_time=2026-11-09T11:15:35+00:00, book20_bid_proxy_usdt=17174698, book20_ask_proxy_usdt=17186700, funding_indicative=0.000012, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.24%, turnover=703260351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-09T11:15:01+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=218.060000, depth_time=2026-11-09T11:15:30+00:00, book20_bid_proxy_usdt=76706, book20_ask_proxy_usdt=148987, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.38%, turnover=52510885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T11:15:02+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=1.153000, depth_time=2026-11-09T11:15:28+00:00, book20_bid_proxy_usdt=2534812, book20_ask_proxy_usdt=2984880, funding_indicative=0.000050, next_funding_utc=2026-11-09T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.29%, turnover=6415174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-09T11:15:02+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=0.146950, depth_time=2026-11-09T11:15:38+00:00, book20_bid_proxy_usdt=183848, book20_ask_proxy_usdt=117145, funding_indicative=-0.000031, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.08%, turnover=27712790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T11:15:01+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=1.101300, depth_time=2026-11-09T11:15:12+00:00, book20_bid_proxy_usdt=5191405, book20_ask_proxy_usdt=3787366, funding_indicative=0.000092, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.71%, turnover=272107875. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T11:15:01+00:00, last15m_closed_end=2026-11-09T11:15+00:00, prior8high=1233.140000, depth_time=2026-11-09T11:15:24+00:00, book20_bid_proxy_usdt=269216, book20_ask_proxy_usdt=167132, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.30%, turnover=2284140333. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
