# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T11:45:43Z**
- feed_generated_utc: 2026-10-30T11:45:46+00:00
- source_sha256: `6e111fd65a71842bc9637a500588ec811d266dd2bd6d3a0f2a2c1e23634f7602`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T11:45+00:00, close=77409.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T11:00+00:00, close=77794.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T08:00+00:00, close=78147.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.338700|-18.27|-25.21|-12.99|9417119|5.96|
|PYTH_USDT|0.060420|-17.44|-18.54|-12.16|5356629|3.31|
|TIA_USDT|0.464200|-15.47|-18.33|-10.19|20291141|2.15|
|CRV_USDT|0.285300|-15.08|-22.32|-9.80|9303030|3.50|
|LIT_USDT|2.802500|-13.95|-22.45|-8.67|17866341|0.36|
|ENA_USDT|0.186290|-12.91|-6.17|-7.63|115537617|0.54|
|FARTCOIN_USDT|0.117880|-12.29|-17.47|-7.01|15680139|0.85|
|LDO_USDT|0.332900|-12.02|-12.96|-6.74|6325087|3.00|
|INJ_USDT|7.198000|-11.48|-9.25|-6.20|32186575|1.39|
|PENGU_USDT|0.007200|-11.45|-6.83|-6.17|10211399|1.39|
|APT_USDT|0.625500|-11.06|-18.99|-5.78|11655715|3.20|
|ETHFI_USDT|0.606900|-10.68|-8.36|-5.40|5891118|1.65|
|TAO_USDT|233.110000|-9.91|-9.52|-4.63|87802234|1.29|
|PUMPFUN_USDT|0.004077|-9.90|-12.86|-4.62|31072480|2.45|
|TRUMPOFFICIAL_USDT|1.559000|-9.78|-10.60|-4.50|10921398|6.42|
|JUP_USDT|0.255300|-9.40|-17.64|-4.12|6979548|3.92|
|SEI_USDT|0.048550|-9.15|-16.39|-3.87|7075277|2.06|
|ONDO_USDT|0.390500|-9.14|-9.39|-3.86|33841366|2.56|
|ZEC_USDT|1250.650000|-7.86|1.32|-2.58|2212468752|0.88|
|BNB_USDT|701.200000|-6.76|-4.11|-1.48|55743285|1.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.625500|0.612600|0.625200|0.75|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.338700|1.460300|1.320700|3.05|Y|Y/Y|Y/Y|Y|Y|
|CRV_USDT|0.285300|0.280800|0.285300|1.00|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.186290|0.185060|0.186190|0.97|N|N/Y|Y/Y|Y|N|
|ETHFI_USDT|0.606900|0.603900|0.606900|0.24|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.117880|0.116210|0.117880|0.52|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.198000|7.100000|7.201000|1.14|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.332900|0.326200|0.332900|0.94|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.802500|2.777900|2.801100|1.13|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007200|0.007058|0.007200|0.53|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004077|0.004016|0.004077|5.34|N|N/Y|Y/Y|Y|N|
|PYTH_USDT|0.060420|0.060500|0.060420|0.94|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|233.110000|231.840000|233.100000|0.84|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.464200|0.457700|0.464000|1.78|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.559000|1.537000|1.559000|1.12|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=0.629900, depth_time=2026-10-30T11:45:32+00:00, book20_bid_proxy_usdt=102802, book20_ask_proxy_usdt=93378, funding_indicative=0.000091, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.06%, turnover=11655715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=1.549900, depth_time=2026-10-30T11:45:08+00:00, book20_bid_proxy_usdt=14784, book20_ask_proxy_usdt=20015, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.27%, turnover=9417119. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=0.288000, depth_time=2026-10-30T11:45:14+00:00, book20_bid_proxy_usdt=519800, book20_ask_proxy_usdt=499469, funding_indicative=-0.000232, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.08%, turnover=9303030. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=0.191700, depth_time=2026-10-30T11:45:19+00:00, book20_bid_proxy_usdt=62685, book20_ask_proxy_usdt=174330, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.91%, turnover=115537617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=0.613800, depth_time=2026-10-30T11:45:34+00:00, book20_bid_proxy_usdt=216690, book20_ask_proxy_usdt=167045, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.68%, turnover=5891118. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=0.119010, depth_time=2026-10-30T11:45:21+00:00, book20_bid_proxy_usdt=32026, book20_ask_proxy_usdt=69265, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.29%, turnover=15680139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=7.256000, depth_time=2026-10-30T11:45:26+00:00, book20_bid_proxy_usdt=293846, book20_ask_proxy_usdt=214041, funding_indicative=0.000043, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.48%, turnover=32186575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=0.334600, depth_time=2026-10-30T11:45:24+00:00, book20_bid_proxy_usdt=273194, book20_ask_proxy_usdt=366723, funding_indicative=0.000085, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-12.02%, turnover=6325087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=2.848000, depth_time=2026-10-30T11:45:17+00:00, book20_bid_proxy_usdt=41294, book20_ask_proxy_usdt=26041, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.95%, turnover=17866341. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=0.007281, depth_time=2026-10-30T11:45:28+00:00, book20_bid_proxy_usdt=135086, book20_ask_proxy_usdt=127707, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.45%, turnover=10211399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=0.004139, depth_time=2026-10-30T11:45:40+00:00, book20_bid_proxy_usdt=1206778, book20_ask_proxy_usdt=1174116, funding_indicative=0.000003, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.90%, turnover=31072480. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=0.061880, depth_time=2026-10-30T11:45:10+00:00, book20_bid_proxy_usdt=209767, book20_ask_proxy_usdt=241381, funding_indicative=-0.000128, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.44%, turnover=5356629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=235.330000, depth_time=2026-10-30T11:45:37+00:00, book20_bid_proxy_usdt=39769, book20_ask_proxy_usdt=111445, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.91%, turnover=87802234. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=0.470200, depth_time=2026-10-30T11:45:12+00:00, book20_bid_proxy_usdt=198627, book20_ask_proxy_usdt=171705, funding_indicative=0.000018, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-15.47%, turnover=20291141. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T11:45:03+00:00, last15m_closed_end=2026-10-30T11:45+00:00, prior8high=1.573000, depth_time=2026-10-30T11:45:42+00:00, book20_bid_proxy_usdt=1622399, book20_ask_proxy_usdt=1457174, funding_indicative=-0.000065, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.78%, turnover=10921398. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
