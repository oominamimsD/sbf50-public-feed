# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T03:00:44Z**
- feed_generated_utc: 2026-10-27T03:00:48+00:00
- source_sha256: `4979dd4059f0e29eb1f84514523b9d48e00c10e7ac44c59ec19ade61a31360e2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T03:00+00:00, close=79789.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T03:00+00:00, close=79789.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.619400|-5.62|-14.85|-4.87|5103041|1.24|
|PUMPFUN_USDT|0.004198|-3.64|-5.78|-2.89|20474237|2.38|
|DOT_USDT|0.995800|-3.43|-13.16|-2.68|10480135|1.00|
|ONDO_USDT|0.408400|-3.33|-5.59|-2.58|22197935|2.45|
|FET_USDT|0.172300|-3.03|-8.83|-2.28|6086988|5.80|
|FILECOIN_USDT|0.901000|-2.75|-10.96|-2.00|6327439|1.11|
|ARB_USDT|0.167490|-2.56|-14.38|-1.81|19921724|0.60|
|NEAR_USDT|4.457000|-2.53|-9.11|-1.78|102349469|2.24|
|AAVE_USDT|133.480000|-2.37|-9.33|-1.62|25837626|0.75|
|TAO_USDT|249.170000|-2.22|-7.13|-1.47|45729416|1.20|
|PENGU_USDT|0.007448|-2.15|-0.57|-1.40|5360331|1.34|
|AVAX_USDT|8.821000|-1.99|-7.74|-1.24|64086543|1.13|
|SOL_USDT|100.220000|-1.83|-3.71|-1.08|703561283|1.00|
|LINK_USDT|11.319000|-1.81|-5.22|-1.06|106243515|0.88|
|ICP_USDT|2.583000|-1.78|-9.46|-1.03|5115367|3.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|133.480000|132.850000|133.520000|0.54|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.167490|0.166980|0.167490|0.38|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.821000|8.828000|8.821000|1.65|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|0.995800|0.995200|0.995800|0.55|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.172300|0.172400|0.172300|7.46|Y|Y/Y|Y/Y|Y|Y|
|FILECOIN_USDT|0.901000|0.899200|0.901000|0.11|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.583000|2.581000|2.584000|2.79|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.319000|11.299000|11.315000|1.05|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.457000|4.431000|4.456000|0.22|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.408400|0.407200|0.408400|0.56|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007448|0.007446|0.007448|0.07|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004198|0.004187|0.004198|0.24|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|100.220000|100.250000|100.220000|0.99|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|249.170000|248.330000|249.170000|0.11|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.619400|1.607900|1.619400|0.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=135.630000, depth_time=2026-10-27T03:00:28+00:00, book20_bid_proxy_usdt=353105, book20_ask_proxy_usdt=521248, funding_indicative=0.000067, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.37%, turnover=25837626. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=0.169010, depth_time=2026-10-27T03:00:23+00:00, book20_bid_proxy_usdt=57505, book20_ask_proxy_usdt=90034, funding_indicative=-0.000022, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=19921724. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=8.961000, depth_time=2026-10-27T03:00:35+00:00, book20_bid_proxy_usdt=1301074, book20_ask_proxy_usdt=1353581, funding_indicative=0.000041, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=64086543. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=1.010000, depth_time=2026-10-27T03:00:13+00:00, book20_bid_proxy_usdt=298730, book20_ask_proxy_usdt=441530, funding_indicative=-0.000087, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.43%, turnover=10480135. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=0.176100, depth_time=2026-10-27T03:00:17+00:00, book20_bid_proxy_usdt=1354120, book20_ask_proxy_usdt=1095040, funding_indicative=0.000100, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.03%, turnover=6086988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=0.913700, depth_time=2026-10-27T03:00:18+00:00, book20_bid_proxy_usdt=1132057, book20_ask_proxy_usdt=1438494, funding_indicative=0.000029, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=6327439. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=2.629000, depth_time=2026-10-27T03:00:42+00:00, book20_bid_proxy_usdt=1005147, book20_ask_proxy_usdt=1122810, funding_indicative=0.000100, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=5115367. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=11.398000, depth_time=2026-10-27T03:00:40+00:00, book20_bid_proxy_usdt=536495, book20_ask_proxy_usdt=549703, funding_indicative=0.000040, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.81%, turnover=106243515. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=4.520000, depth_time=2026-10-27T03:00:26+00:00, book20_bid_proxy_usdt=4403950, book20_ask_proxy_usdt=3237629, funding_indicative=0.000061, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=102349469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=0.414000, depth_time=2026-10-27T03:00:15+00:00, book20_bid_proxy_usdt=1846548, book20_ask_proxy_usdt=3682865, funding_indicative=0.000034, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.33%, turnover=22197935. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=0.007542, depth_time=2026-10-27T03:00:33+00:00, book20_bid_proxy_usdt=225808, book20_ask_proxy_usdt=159793, funding_indicative=-0.000020, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.15%, turnover=5360331. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=0.004310, depth_time=2026-10-27T03:00:10+00:00, book20_bid_proxy_usdt=2072201, book20_ask_proxy_usdt=2317978, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.64%, turnover=20474237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=101.010000, depth_time=2026-10-27T03:00:38+00:00, book20_bid_proxy_usdt=26144844, book20_ask_proxy_usdt=19576985, funding_indicative=0.000100, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=703561283. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=251.960000, depth_time=2026-10-27T03:00:30+00:00, book20_bid_proxy_usdt=223512, book20_ask_proxy_usdt=189174, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=45729416. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T03:00:03+00:00, last15m_closed_end=2026-10-27T03:00+00:00, prior8high=1.634200, depth_time=2026-10-27T03:00:08+00:00, book20_bid_proxy_usdt=18521, book20_ask_proxy_usdt=65361, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.62%, turnover=5103041. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
