# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T11:15:59Z**
- feed_generated_utc: 2026-10-30T11:16:09+00:00
- source_sha256: `d2996877d55dd0a7c8659392970fdddd4ed89faff8a553dfd796b02d36d7f0ea`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.16 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T11:15+00:00, close=77669.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T11:00+00:00, close=77794.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T08:00+00:00, close=78147.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PYTH_USDT|0.061060|-16.57|-17.68|-11.60|5305020|3.28|
|TIA_USDT|0.465200|-15.29|-18.15|-10.32|19954087|2.15|
|CRV_USDT|0.287400|-14.46|-21.75|-9.49|9228086|3.48|
|LIT_USDT|2.832000|-13.04|-21.64|-8.07|17780387|0.35|
|FARTCOIN_USDT|0.118210|-12.04|-17.24|-7.07|15621394|0.85|
|LDO_USDT|0.334000|-11.73|-12.67|-6.76|6292350|2.99|
|PENGU_USDT|0.007228|-11.10|-6.46|-6.13|10105528|1.38|
|INJ_USDT|7.246000|-10.89|-8.64|-5.92|31868978|1.38|
|APT_USDT|0.626800|-10.87|-18.82|-5.90|11604647|3.19|
|FET_USDT|0.165200|-10.60|-10.84|-5.63|14006986|6.05|
|ETHFI_USDT|0.609700|-10.27|-7.94|-5.30|5862287|1.64|
|TRUMPOFFICIAL_USDT|1.562000|-9.60|-10.43|-4.63|10816667|6.40|
|PUMPFUN_USDT|0.004097|-9.45|-12.43|-4.48|30292732|2.44|
|TAO_USDT|234.640000|-9.32|-8.93|-4.35|87149876|0.85|
|JUP_USDT|0.256100|-9.11|-17.38|-4.14|6947124|3.91|
|BTW_USDT|1.517800|-7.34|-15.20|-2.37|9174549|1.98|
|ZEC_USDT|1266.000000|-6.73|2.57|-1.76|2181612393|0.08|
|BNB_USDT|701.700000|-6.70|-4.04|-1.73|55327799|1.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.626800|0.612600|0.627100|1.13|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.287400|0.280800|0.287600|0.20|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.609700|0.603900|0.609700|2.49|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118210|0.116190|0.118200|1.14|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.165200|0.163000|0.165300|1.10|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.246000|7.100000|7.248000|1.51|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.256100|0.252800|0.256100|0.84|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.334000|0.324500|0.334200|0.94|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.832000|2.777900|2.832000|0.60|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007228|0.007058|0.007230|2.02|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004097|0.004016|0.004102|0.71|N|N/Y|Y/Y|Y|N|
|PYTH_USDT|0.061060|0.060610|0.061060|2.73|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|234.640000|231.840000|234.610000|0.94|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.465200|0.457700|0.465400|1.24|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.562000|1.533000|1.562000|1.37|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=0.628500, depth_time=2026-10-30T11:15:39+00:00, book20_bid_proxy_usdt=112406, book20_ask_proxy_usdt=131253, funding_indicative=0.000078, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.87%, turnover=11604647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=0.287500, depth_time=2026-10-30T11:15:19+00:00, book20_bid_proxy_usdt=470366, book20_ask_proxy_usdt=300619, funding_indicative=-0.000223, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-14.46%, turnover=9228086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=0.613800, depth_time=2026-10-30T11:15:46+00:00, book20_bid_proxy_usdt=188641, book20_ask_proxy_usdt=181514, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.27%, turnover=5862287. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=0.118800, depth_time=2026-10-30T11:15:25+00:00, book20_bid_proxy_usdt=45156, book20_ask_proxy_usdt=34928, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.04%, turnover=15621394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=0.165700, depth_time=2026-10-30T11:15:42+00:00, book20_bid_proxy_usdt=867575, book20_ask_proxy_usdt=586186, funding_indicative=0.000100, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.60%, turnover=14006986. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=7.244000, depth_time=2026-10-30T11:15:37+00:00, book20_bid_proxy_usdt=361350, book20_ask_proxy_usdt=211000, funding_indicative=0.000061, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.89%, turnover=31868978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=0.256800, depth_time=2026-10-30T11:15:58+00:00, book20_bid_proxy_usdt=424871, book20_ask_proxy_usdt=392147, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.11%, turnover=6947124. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=0.334300, depth_time=2026-10-30T11:15:30+00:00, book20_bid_proxy_usdt=257107, book20_ask_proxy_usdt=661759, funding_indicative=0.000098, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.73%, turnover=6292350. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=2.848000, depth_time=2026-10-30T11:15:22+00:00, book20_bid_proxy_usdt=24760, book20_ask_proxy_usdt=24013, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.04%, turnover=17780387. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=0.007263, depth_time=2026-10-30T11:15:34+00:00, book20_bid_proxy_usdt=235429, book20_ask_proxy_usdt=120062, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.10%, turnover=10105528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=0.004139, depth_time=2026-10-30T11:15:52+00:00, book20_bid_proxy_usdt=1934717, book20_ask_proxy_usdt=1197709, funding_indicative=0.000000, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.45%, turnover=30292732. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=0.061880, depth_time=2026-10-30T11:15:16+00:00, book20_bid_proxy_usdt=294581, book20_ask_proxy_usdt=238708, funding_indicative=-0.000125, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-16.57%, turnover=5305020. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=235.000000, depth_time=2026-10-30T11:15:55+00:00, book20_bid_proxy_usdt=115281, book20_ask_proxy_usdt=84394, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.32%, turnover=87149876. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=0.470200, depth_time=2026-10-30T11:15:17+00:00, book20_bid_proxy_usdt=280429, book20_ask_proxy_usdt=315546, funding_indicative=-0.000012, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-15.29%, turnover=19954087. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T11:15:07+00:00, last15m_closed_end=2026-10-30T11:15+00:00, prior8high=1.571000, depth_time=2026-10-30T11:15:49+00:00, book20_bid_proxy_usdt=1510915, book20_ask_proxy_usdt=1563565, funding_indicative=-0.000086, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.60%, turnover=10816667. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
