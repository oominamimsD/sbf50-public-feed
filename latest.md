# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T19:00:36Z**
- feed_generated_utc: 2026-10-26T19:00:40+00:00
- source_sha256: `4c7fbb23de031c17f5c8a7301ec31e48e17ba93ff213bd08d8adcd7cfb72f1e2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T19:00+00:00, close=79961.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T19:00+00:00, close=79961.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T16:00+00:00, close=80399.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.026540|-4.80|116.12|-4.24|9576767|7.54|
|ARB_USDT|0.167250|-2.70|-14.50|-2.14|20212371|0.60|
|DOT_USDT|1.004200|-2.61|-12.43|-2.05|9762019|1.00|
|NEAR_USDT|4.459000|-2.49|-9.07|-1.93|117202585|4.48|
|PUMPFUN_USDT|0.004222|-2.44|-5.25|-1.88|21739489|2.37|
|WLD_USDT|0.437400|-2.40|-13.60|-1.84|71909282|2.29|
|BTW_USDT|1.168800|-2.24|-33.28|-1.68|20055110|5.13|
|FILECOIN_USDT|0.905800|-2.23|-10.49|-1.67|5985204|1.10|
|LINK_USDT|11.364000|-1.73|-4.84|-1.17|89384466|0.88|
|SOL_USDT|100.410000|-1.64|-3.53|-1.08|634870270|1.00|
|NIL_USDT|0.088350|-1.64|0.99|-1.08|5093321|3.40|
|FET_USDT|0.173800|-1.58|-8.04|-1.02|5695309|5.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.167250|0.167170|0.167250|0.26|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.168800|0.876100|1.176800|0.38|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.004200|1.005600|1.004200|0.77|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.173800|0.173400|0.173900|0.37|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.905800|0.905200|0.905800|0.10|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.026540|0.026060|0.026540|0.36|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.364000|11.399000|11.364000|0.72|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.459000|4.465000|4.460000|0.64|N|Y/Y|Y/Y|Y|N|
|NIL_USDT|0.088350|0.088500|0.088350|0.26|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004222|0.004225|0.004222|1.41|Y|Y/Y|N/Y|Y|N|
|SOL_USDT|100.410000|100.630000|100.410000|0.53|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.437400|0.435500|0.437400|1.29|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-26T19:00:02+00:00, last15m_closed_end=2026-10-26T19:00+00:00, prior8high=0.169580, depth_time=2026-10-26T19:00:11+00:00, book20_bid_proxy_usdt=60470, book20_ask_proxy_usdt=87773, funding_indicative=-0.000033, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=20212371. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T19:00:01+00:00, last15m_closed_end=2026-10-26T19:00+00:00, prior8high=1.304000, depth_time=2026-10-26T19:00:23+00:00, book20_bid_proxy_usdt=7606, book20_ask_proxy_usdt=7734, funding_indicative=0.000050, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=20055110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T19:00:02+00:00, last15m_closed_end=2026-10-26T19:00+00:00, prior8high=1.020300, depth_time=2026-10-26T19:00:14+00:00, book20_bid_proxy_usdt=365367, book20_ask_proxy_usdt=319200, funding_indicative=-0.000055, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=9762019. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-26T19:00:02+00:00, last15m_closed_end=2026-10-26T19:00+00:00, prior8high=0.176700, depth_time=2026-10-26T19:00:35+00:00, book20_bid_proxy_usdt=1690460, book20_ask_proxy_usdt=1284245, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=5695309. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-26T19:00:02+00:00, last15m_closed_end=2026-10-26T19:00+00:00, prior8high=0.922000, depth_time=2026-10-26T19:00:26+00:00, book20_bid_proxy_usdt=1019624, book20_ask_proxy_usdt=1809532, funding_indicative=0.000069, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=5985204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T19:00:01+00:00, last15m_closed_end=2026-10-26T19:00+00:00, prior8high=0.027470, depth_time=2026-10-26T19:00:08+00:00, book20_bid_proxy_usdt=114950, book20_ask_proxy_usdt=93272, funding_indicative=-0.000682, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=1, 24h_change=-4.80%, turnover=9576767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-26T19:00:02+00:00, last15m_closed_end=2026-10-26T19:00+00:00, prior8high=11.541000, depth_time=2026-10-26T19:00:27+00:00, book20_bid_proxy_usdt=913706, book20_ask_proxy_usdt=602233, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=89384466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-26T19:00:01+00:00, last15m_closed_end=2026-10-26T19:00+00:00, prior8high=4.569000, depth_time=2026-10-26T19:00:16+00:00, book20_bid_proxy_usdt=5074762, book20_ask_proxy_usdt=2763715, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=117202585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-26T19:00:02+00:00, last15m_closed_end=2026-10-26T19:00+00:00, prior8high=0.092070, depth_time=2026-10-26T19:00:33+00:00, book20_bid_proxy_usdt=39682, book20_ask_proxy_usdt=19734, funding_indicative=0.000012, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.64%, turnover=5093321. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T19:00:02+00:00, last15m_closed_end=2026-10-26T19:00+00:00, prior8high=0.004332, depth_time=2026-10-26T19:00:19+00:00, book20_bid_proxy_usdt=2255672, book20_ask_proxy_usdt=1533168, funding_indicative=0.000050, next_funding_utc=2026-10-26T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=21739489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-26T19:00:01+00:00, last15m_closed_end=2026-10-26T19:00+00:00, prior8high=101.920000, depth_time=2026-10-26T19:00:30+00:00, book20_bid_proxy_usdt=26134884, book20_ask_proxy_usdt=17259427, funding_indicative=0.000100, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=634870270. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T19:00:01+00:00, last15m_closed_end=2026-10-26T19:00+00:00, prior8high=0.445400, depth_time=2026-10-26T19:00:21+00:00, book20_bid_proxy_usdt=3329356, book20_ask_proxy_usdt=2279800, funding_indicative=-0.000130, next_funding_utc=2026-10-27T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=71909282. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
