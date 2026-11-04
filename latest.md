# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T23:30:25Z**
- feed_generated_utc: 2026-11-04T23:30:27+00:00
- source_sha256: `6614a14a8f0026893455793a877462cf1e469425f7d45e5c743271fbe4e4d48a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T23:30+00:00, close=80440.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T23:00+00:00, close=80682, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.284000|-9.83|-24.86|-10.03|26953192|7.80|
|IDOL_USDT|0.021479|-8.47|148.11|-8.67|6252805|2.79|
|BTW_USDT|1.029900|-6.28|-40.74|-6.48|6169247|0.97|
|PUMPFUN_USDT|0.004267|-4.11|1.42|-4.31|18627707|2.34|
|WLD_USDT|0.377600|-3.69|-12.75|-3.89|73659113|2.65|
|HYPE_USDT|83.836000|-2.40|4.98|-2.60|94532205|0.12|
|ZRO_USDT|1.827900|-1.97|6.76|-2.17|11226628|0.55|
|CLANKER_USDT|18.290000|-1.71|36.90|-1.91|19482715|5.47|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.029900|1.026000|1.029900|2.68|N|Y/Y|Y/N|N|N|
|CLANKER_USDT|18.290000|17.160000|18.290000|0.65|N|Y/N|N/N|N|N|
|HYPE_USDT|83.836000|82.778000|83.836000|0.76|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.021479|0.020994|0.021479|0.35|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004267|0.004191|0.004267|0.15|N|N/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.284000|1.257000|1.284000|0.77|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.377600|0.374500|0.377600|0.88|N|N/Y|Y/N|N|N|
|ZRO_USDT|1.827900|1.794100|1.827900|0.16|N|N/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-11-04T23:30:00+00:00, last15m_closed_end=2026-11-04T23:30+00:00, prior8high=1.044500, depth_time=2026-11-04T23:30:13+00:00, book20_bid_proxy_usdt=27236, book20_ask_proxy_usdt=21321, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.28%, turnover=6169247. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-04T23:30:00+00:00, last15m_closed_end=2026-11-04T23:30+00:00, prior8high=25.880000, depth_time=2026-11-04T23:30:24+00:00, book20_bid_proxy_usdt=172825, book20_ask_proxy_usdt=148340, funding_indicative=0.000333, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=19482715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T23:30:00+00:00, last15m_closed_end=2026-11-04T23:30+00:00, prior8high=84.362000, depth_time=2026-11-04T23:30:19+00:00, book20_bid_proxy_usdt=253857, book20_ask_proxy_usdt=231608, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.40%, turnover=94532205. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-04T23:30:00+00:00, last15m_closed_end=2026-11-04T23:30+00:00, prior8high=0.021651, depth_time=2026-11-04T23:30:10+00:00, book20_bid_proxy_usdt=5362, book20_ask_proxy_usdt=10865, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.47%, turnover=6252805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T23:30:00+00:00, last15m_closed_end=2026-11-04T23:30+00:00, prior8high=0.004318, depth_time=2026-11-04T23:30:14+00:00, book20_bid_proxy_usdt=2712289, book20_ask_proxy_usdt=2232066, funding_indicative=0.000026, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.11%, turnover=18627707. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T23:30:00+00:00, last15m_closed_end=2026-11-04T23:30+00:00, prior8high=1.284000, depth_time=2026-11-04T23:30:07+00:00, book20_bid_proxy_usdt=1161712, book20_ask_proxy_usdt=1050861, funding_indicative=-0.000248, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.83%, turnover=26953192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-04T23:30:00+00:00, last15m_closed_end=2026-11-04T23:30+00:00, prior8high=0.384000, depth_time=2026-11-04T23:30:17+00:00, book20_bid_proxy_usdt=2540570, book20_ask_proxy_usdt=2607692, funding_indicative=-0.000444, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=73659113. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T23:30:00+00:00, last15m_closed_end=2026-11-04T23:30+00:00, prior8high=1.856300, depth_time=2026-11-04T23:30:20+00:00, book20_bid_proxy_usdt=143245, book20_ask_proxy_usdt=35986, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=11226628. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
