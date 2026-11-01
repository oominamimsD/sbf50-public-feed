# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T04:30:28Z**
- feed_generated_utc: 2026-11-01T04:30:31+00:00
- source_sha256: `9a4776d417bd9065dff3c1c94734f4056792fd6a8c7cb18b675bad4a85c8fabf`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T04:30+00:00, close=77789.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.239420|-19.15|42.57|-19.44|30177574|1.67|
|AKE_USDT|0.009143|-17.91|-68.72|-18.20|11622798|3.28|
|BLESS_USDT|0.009530|-9.78|17.46|-10.07|6883971|5.24|
|ZEC_USDT|1247.310000|-2.89|8.91|-3.18|968256400|0.08|
|ENA_USDT|0.188510|-2.83|0.92|-3.12|42679173|0.53|
|XLM_USDT|0.168540|-1.86|0.07|-2.15|20362631|0.59|
|BTW_USDT|1.103500|-1.64|-36.62|-1.93|5220099|1.81|
|TRX_USDT|0.309320|-0.96|-5.96|-1.25|10890170|0.32|
|TAO_USDT|235.850000|-0.71|-3.96|-1.00|22674527|1.27|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009143|0.008372|0.009143|1.14|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009530|0.009219|0.009530|1.64|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.103500|1.091400|1.103500|0.60|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188510|0.185670|0.188510|1.10|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.239420|0.226590|0.239600|1.14|N|Y/Y|N/N|Y|N|
|TAO_USDT|235.850000|234.870000|235.850000|1.25|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.309320|0.307330|0.309320|0.91|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.168540|0.167510|0.168540|0.91|N|Y/Y|Y/N|Y|N|
|ZEC_USDT|1247.310000|1238.800000|1247.310000|0.69|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T04:30:01+00:00, last15m_closed_end=2026-11-01T04:30+00:00, prior8high=0.010444, depth_time=2026-11-01T04:30:10+00:00, book20_bid_proxy_usdt=14502, book20_ask_proxy_usdt=9832, funding_indicative=-0.003530, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-17.91%, turnover=11622798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T04:30:01+00:00, last15m_closed_end=2026-11-01T04:30+00:00, prior8high=0.009822, depth_time=2026-11-01T04:30:13+00:00, book20_bid_proxy_usdt=18584, book20_ask_proxy_usdt=14094, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.78%, turnover=6883971. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-01T04:30:00+00:00, last15m_closed_end=2026-11-01T04:30+00:00, prior8high=1.139700, depth_time=2026-11-01T04:30:23+00:00, book20_bid_proxy_usdt=11574, book20_ask_proxy_usdt=12036, funding_indicative=-0.000069, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.64%, turnover=5220099. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T04:30:00+00:00, last15m_closed_end=2026-11-01T04:30+00:00, prior8high=0.189100, depth_time=2026-11-01T04:30:18+00:00, book20_bid_proxy_usdt=241773, book20_ask_proxy_usdt=195432, funding_indicative=-0.000002, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.83%, turnover=42679173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T04:30:00+00:00, last15m_closed_end=2026-11-01T04:30+00:00, prior8high=0.235770, depth_time=2026-11-01T04:30:08+00:00, book20_bid_proxy_usdt=4530, book20_ask_proxy_usdt=8084, funding_indicative=-0.000844, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.15%, turnover=30177574. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-11-01T04:30:01+00:00, last15m_closed_end=2026-11-01T04:30+00:00, prior8high=236.900000, depth_time=2026-11-01T04:30:28+00:00, book20_bid_proxy_usdt=143751, book20_ask_proxy_usdt=125162, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.71%, turnover=22674527. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T04:30:01+00:00, last15m_closed_end=2026-11-01T04:30+00:00, prior8high=0.309960, depth_time=2026-11-01T04:30:23+00:00, book20_bid_proxy_usdt=155760, book20_ask_proxy_usdt=53248, funding_indicative=-0.001145, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.96%, turnover=10890170. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T04:30:01+00:00, last15m_closed_end=2026-11-01T04:30+00:00, prior8high=0.169260, depth_time=2026-11-01T04:30:19+00:00, book20_bid_proxy_usdt=172880, book20_ask_proxy_usdt=170280, funding_indicative=0.000022, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=20362631. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T04:30:00+00:00, last15m_closed_end=2026-11-01T04:30+00:00, prior8high=1256.180000, depth_time=2026-11-01T04:30:15+00:00, book20_bid_proxy_usdt=841831, book20_ask_proxy_usdt=538504, funding_indicative=-0.000125, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.89%, turnover=968256400. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
