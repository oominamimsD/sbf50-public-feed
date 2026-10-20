# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T06:30:24Z**
- feed_generated_utc: 2026-10-20T06:30:27+00:00
- source_sha256: `cfa2f75f42db7fbecc8b483243a2252a28f69d0fa9d6b8fb4ad549a1338db573`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T06:30+00:00, close=81749.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T06:00+00:00, close=81684.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.307170|-6.94|-10.21|-6.76|5461883|3.91|
|Q_USDT|0.120940|-4.00|292.77|-3.82|9474239|6.29|
|ZRO_USDT|1.834500|-3.54|-18.86|-3.36|7604072|2.73|
|SAND_USDT|0.057170|-3.33|-7.92|-3.15|8180745|1.75|
|NEAR_USDT|4.777000|-2.58|-13.91|-2.40|168277229|2.09|
|QNT_USDT|193.010000|-1.37|-15.48|-1.19|82682093|0.52|
|UNI_USDT|7.200000|-1.20|-2.93|-1.02|10147729|2.78|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.307170|0.301550|0.307370|3.09|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.777000|4.751000|4.777000|1.31|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.010000|191.100000|193.000000|1.00|N|Y/Y|N/Y|Y|N|
|Q_USDT|0.120940|0.110142|0.121334|2.79|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.057170|0.056650|0.057150|0.41|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.200000|7.119000|7.200000|2.49|N|Y/Y|N/N|Y|N|
|ZRO_USDT|1.834500|1.828800|1.832900|2.47|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-20T06:30:03+00:00, last15m_closed_end=2026-10-20T06:30+00:00, prior8high=0.325160, depth_time=2026-10-20T06:30:08+00:00, book20_bid_proxy_usdt=10851, book20_ask_proxy_usdt=15358, funding_indicative=-0.002588, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.94%, turnover=5461883. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T06:30:03+00:00, last15m_closed_end=2026-10-20T06:30+00:00, prior8high=4.872000, depth_time=2026-10-20T06:30:18+00:00, book20_bid_proxy_usdt=2581951, book20_ask_proxy_usdt=5087032, funding_indicative=-0.000008, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.58%, turnover=168277229. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T06:30:03+00:00, last15m_closed_end=2026-10-20T06:30+00:00, prior8high=198.680000, depth_time=2026-10-20T06:30:21+00:00, book20_bid_proxy_usdt=89779, book20_ask_proxy_usdt=97915, funding_indicative=-0.000002, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=82682093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T06:30:03+00:00, last15m_closed_end=2026-10-20T06:30+00:00, prior8high=0.133766, depth_time=2026-10-20T06:30:11+00:00, book20_bid_proxy_usdt=14835, book20_ask_proxy_usdt=15909, funding_indicative=-0.000220, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.00%, turnover=9474239. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T06:30:03+00:00, last15m_closed_end=2026-10-20T06:30+00:00, prior8high=0.057820, depth_time=2026-10-20T06:30:15+00:00, book20_bid_proxy_usdt=746180, book20_ask_proxy_usdt=877457, funding_indicative=-0.001687, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.33%, turnover=8180745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T06:30:03+00:00, last15m_closed_end=2026-10-20T06:30+00:00, prior8high=7.340000, depth_time=2026-10-20T06:30:24+00:00, book20_bid_proxy_usdt=1184250, book20_ask_proxy_usdt=2171910, funding_indicative=0.000015, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.20%, turnover=10147729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T06:30:03+00:00, last15m_closed_end=2026-10-20T06:30+00:00, prior8high=1.880400, depth_time=2026-10-20T06:30:13+00:00, book20_bid_proxy_usdt=54199, book20_ask_proxy_usdt=53763, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.54%, turnover=7604072. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
