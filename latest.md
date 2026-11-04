# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T23:15:27Z**
- feed_generated_utc: 2026-11-04T23:15:29+00:00
- source_sha256: `5d1617b026c2183281d0d91ddc28eeec9f1b650d5b1127cfe14ea253df059319`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T23:15+00:00, close=80496.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T23:00+00:00, close=80682, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T20:00+00:00, close=79956.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.281000|-10.04|-25.04|-10.30|26774432|7.81|
|AKE_USDT|0.002543|-9.50|-87.34|-9.76|16459920|3.93|
|IDOL_USDT|0.021429|-8.68|147.53|-8.94|6240482|3.27|
|BTW_USDT|1.031500|-6.14|-40.65|-6.40|6099281|4.85|
|CLANKER_USDT|17.750000|-4.62|32.85|-4.88|19216086|5.65|
|PUMPFUN_USDT|0.004278|-3.86|1.68|-4.12|18610436|2.34|
|WLD_USDT|0.377300|-3.77|-12.82|-4.03|73254245|2.65|
|ZRO_USDT|1.830800|-1.81|6.93|-2.07|11213692|1.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002543|0.002479|0.002545|0.44|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.031500|1.026000|1.027700|1.59|N|Y/Y|Y/N|N|N|
|CLANKER_USDT|17.750000|17.580000|17.650000|0.89|N|Y/N|N/N|N|N|
|IDOL_USDT|0.021429|0.020994|0.021429|0.24|N|Y/Y|N/N|N|N|
|PUMPFUN_USDT|0.004278|0.004191|0.004278|0.30|N|N/Y|Y/N|N|N|
|TRUMPOFFICIAL_USDT|1.281000|1.257000|1.282000|1.34|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.377300|0.374500|0.377800|1.10|N|N/Y|Y/N|N|N|
|ZRO_USDT|1.830800|1.794100|1.830800|2.15|N|N/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-04T23:15:03+00:00, last15m_closed_end=2026-11-04T23:15+00:00, prior8high=0.002701, depth_time=2026-11-04T23:15:10+00:00, book20_bid_proxy_usdt=106372, book20_ask_proxy_usdt=110178, funding_indicative=-0.000958, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.50%, turnover=16459920. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-04T23:15:04+00:00, last15m_closed_end=2026-11-04T23:15+00:00, prior8high=1.044500, depth_time=2026-11-04T23:15:16+00:00, book20_bid_proxy_usdt=34795, book20_ask_proxy_usdt=17898, funding_indicative=0.000046, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.14%, turnover=6099281. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-04T23:15:03+00:00, last15m_closed_end=2026-11-04T23:15+00:00, prior8high=25.880000, depth_time=2026-11-04T23:15:19+00:00, book20_bid_proxy_usdt=170557, book20_ask_proxy_usdt=145616, funding_indicative=0.000409, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.62%, turnover=19216086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-04T23:15:03+00:00, last15m_closed_end=2026-11-04T23:15+00:00, prior8high=0.021651, depth_time=2026-11-04T23:15:12+00:00, book20_bid_proxy_usdt=8803, book20_ask_proxy_usdt=4934, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.68%, turnover=6240482. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-04T23:15:03+00:00, last15m_closed_end=2026-11-04T23:15+00:00, prior8high=0.004318, depth_time=2026-11-04T23:15:21+00:00, book20_bid_proxy_usdt=2420415, book20_ask_proxy_usdt=1985930, funding_indicative=0.000026, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.86%, turnover=18610436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T23:15:03+00:00, last15m_closed_end=2026-11-04T23:15+00:00, prior8high=1.294000, depth_time=2026-11-04T23:15:08+00:00, book20_bid_proxy_usdt=915017, book20_ask_proxy_usdt=1069819, funding_indicative=-0.000225, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.04%, turnover=26774432. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-04T23:15:03+00:00, last15m_closed_end=2026-11-04T23:15+00:00, prior8high=0.384000, depth_time=2026-11-04T23:15:23+00:00, book20_bid_proxy_usdt=3124832, book20_ask_proxy_usdt=2831975, funding_indicative=-0.000455, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.77%, turnover=73254245. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-04T23:15:04+00:00, last15m_closed_end=2026-11-04T23:15+00:00, prior8high=1.856300, depth_time=2026-11-04T23:15:26+00:00, book20_bid_proxy_usdt=52680, book20_ask_proxy_usdt=35832, funding_indicative=0.000050, next_funding_utc=2026-11-05T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=11213692. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
