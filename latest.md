# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T05:00:28Z**
- feed_generated_utc: 2026-11-08T05:00:30+00:00
- source_sha256: `ec5966d360383dd8a8a0c5a820e36b9f7b24ed260f3a324c9b162987c686109c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T05:00+00:00, close=75830.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T05:00+00:00, close=75830.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001864|-8.47|58.75|-8.60|26761238|0.54|
|ENA_USDT|0.153880|-2.71|-20.68|-2.84|28304083|0.65|
|QNT_USDT|194.500000|-2.18|-3.25|-2.31|45725958|0.51|
|TIA_USDT|0.433300|-1.87|-11.58|-2.00|7387414|2.31|
|WLD_USDT|0.330500|-1.51|-18.27|-1.64|24579764|3.02|
|ONDO_USDT|0.357900|-1.43|-13.21|-1.56|8726202|2.79|
|AAVE_USDT|130.640000|-1.20|-3.59|-1.33|10424684|0.77|
|XLM_USDT|0.149700|-1.01|-12.83|-1.14|18294144|0.67|
|LINK_USDT|10.742000|-0.94|-7.16|-1.07|71005750|0.93|
|ADA_USDT|0.179900|-0.93|-7.07|-1.06|11577215|5.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.640000|130.740000|130.640000|3.57|Y|Y/N|N/N|Y|N|
|ADA_USDT|0.179900|0.179400|0.179900|6.06|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.153880|0.153430|0.153880|0.93|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.742000|10.739000|10.742000|0.59|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.357900|0.357900|0.357900|1.87|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001864|0.001804|0.001864|1.15|N|Y/Y|N/N|Y|N|
|QNT_USDT|194.500000|193.120000|194.510000|0.63|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.433300|0.434200|0.433300|3.04|Y|Y/Y|Y/N|Y|N|
|WLD_USDT|0.330500|0.329000|0.330500|0.55|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.149700|0.149790|0.149700|2.19|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T04:59:59+00:00, last15m_closed_end=2026-11-08T05:00+00:00, prior8high=132.290000, depth_time=2026-11-08T05:00:20+00:00, book20_bid_proxy_usdt=346824, book20_ask_proxy_usdt=594905, funding_indicative=0.000000, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=10424684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T04:59:59+00:00, last15m_closed_end=2026-11-08T05:00+00:00, prior8high=0.180900, depth_time=2026-11-08T05:00:26+00:00, book20_bid_proxy_usdt=10071802, book20_ask_proxy_usdt=9345576, funding_indicative=-0.000067, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=11577215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T04:59:59+00:00, last15m_closed_end=2026-11-08T05:00+00:00, prior8high=0.155430, depth_time=2026-11-08T05:00:08+00:00, book20_bid_proxy_usdt=162462, book20_ask_proxy_usdt=255724, funding_indicative=0.000018, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=28304083. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T04:59:59+00:00, last15m_closed_end=2026-11-08T05:00+00:00, prior8high=10.801000, depth_time=2026-11-08T05:00:22+00:00, book20_bid_proxy_usdt=932466, book20_ask_proxy_usdt=550924, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.94%, turnover=71005750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T04:59:59+00:00, last15m_closed_end=2026-11-08T05:00+00:00, prior8high=0.362000, depth_time=2026-11-08T05:00:17+00:00, book20_bid_proxy_usdt=1588879, book20_ask_proxy_usdt=2298972, funding_indicative=-0.000011, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=8726202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T04:59:59+00:00, last15m_closed_end=2026-11-08T05:00+00:00, prior8high=0.001974, depth_time=2026-11-08T05:00:06+00:00, book20_bid_proxy_usdt=21504, book20_ask_proxy_usdt=11138, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.47%, turnover=26761238. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T04:59:59+00:00, last15m_closed_end=2026-11-08T05:00+00:00, prior8high=195.100000, depth_time=2026-11-08T05:00:06+00:00, book20_bid_proxy_usdt=98126, book20_ask_proxy_usdt=98063, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=45725958. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T04:59:59+00:00, last15m_closed_end=2026-11-08T05:00+00:00, prior8high=0.438300, depth_time=2026-11-08T05:00:11+00:00, book20_bid_proxy_usdt=334767, book20_ask_proxy_usdt=325168, funding_indicative=-0.000012, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.87%, turnover=7387414. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T04:59:59+00:00, last15m_closed_end=2026-11-08T05:00+00:00, prior8high=0.332300, depth_time=2026-11-08T05:00:11+00:00, book20_bid_proxy_usdt=3819696, book20_ask_proxy_usdt=3569667, funding_indicative=-0.000144, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=24579764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-08T04:59:59+00:00, last15m_closed_end=2026-11-08T05:00+00:00, prior8high=0.150960, depth_time=2026-11-08T05:00:22+00:00, book20_bid_proxy_usdt=316979, book20_ask_proxy_usdt=220880, funding_indicative=-0.000080, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.01%, turnover=18294144. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
