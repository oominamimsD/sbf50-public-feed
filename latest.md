# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T11:15:32Z**
- feed_generated_utc: 2026-10-26T11:15:35+00:00
- source_sha256: `b05f5b19ce328cf4470207520ea8be73d164fb9c72de9f614d4af532149721ca`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T11:15+00:00, close=80241.7, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T11:00+00:00, close=80339.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.075960|-29.32|14.22|-28.88|7207526|1.31|
|IRYS_USDT|0.028200|-26.63|131.14|-26.19|12293704|3.54|
|APR_USDT|0.033350|-19.26|22.43|-18.82|8391895|3.00|
|BTW_USDT|1.510600|-8.93|-34.47|-8.49|10968375|1.32|
|WLD_USDT|0.436900|-4.31|-8.27|-3.87|63166269|2.29|
|LIT_USDT|3.078400|-3.14|5.05|-2.70|5486864|0.33|
|XMR_USDT|589.670000|-2.89|1.23|-2.45|5793112|2.04|
|STRK_USDT|0.044620|-2.44|-27.51|-2.00|9999908|2.24|
|DOT_USDT|1.017200|-2.11|-4.88|-1.67|9552816|0.98|
|PUMPFUN_USDT|0.004219|-1.54|0.57|-1.10|18796215|2.37|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.033350|0.033760|0.033230|1.22|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.510600|1.480300|1.510000|0.76|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.075960|0.075150|0.075960|0.79|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.017200|1.015900|1.017200|1.28|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.028200|0.028190|0.028180|1.07|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.078400|3.066900|3.078400|0.28|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004219|0.004212|0.004219|6.48|N|N/N|Y/Y|Y|N|
|STRK_USDT|0.044620|0.044760|0.044640|3.59|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.436900|0.437300|0.436900|3.10|Y|Y/Y|Y/Y|Y|Y|
|XMR_USDT|589.670000|588.070000|589.670000|0.23|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T11:15:02+00:00, last15m_closed_end=2026-10-26T11:15+00:00, prior8high=0.038620, depth_time=2026-10-26T11:15:13+00:00, book20_bid_proxy_usdt=61649, book20_ask_proxy_usdt=79848, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.26%, turnover=8391895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T11:15:02+00:00, last15m_closed_end=2026-10-26T11:15+00:00, prior8high=1.532000, depth_time=2026-10-26T11:15:16+00:00, book20_bid_proxy_usdt=11051, book20_ask_proxy_usdt=12884, funding_indicative=-0.012581, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.93%, turnover=10968375. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T11:15:02+00:00, last15m_closed_end=2026-10-26T11:15+00:00, prior8high=0.087050, depth_time=2026-10-26T11:15:09+00:00, book20_bid_proxy_usdt=70244, book20_ask_proxy_usdt=61977, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-29.32%, turnover=7207526. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T11:15:02+00:00, last15m_closed_end=2026-10-26T11:15+00:00, prior8high=1.024700, depth_time=2026-10-26T11:15:28+00:00, book20_bid_proxy_usdt=300323, book20_ask_proxy_usdt=472177, funding_indicative=-0.000116, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=9552816. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T11:15:02+00:00, last15m_closed_end=2026-10-26T11:15+00:00, prior8high=0.029970, depth_time=2026-10-26T11:15:11+00:00, book20_bid_proxy_usdt=173921, book20_ask_proxy_usdt=78422, funding_indicative=-0.000598, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=1, 24h_change=-26.63%, turnover=12293704. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T11:15:02+00:00, last15m_closed_end=2026-10-26T11:15+00:00, prior8high=3.116600, depth_time=2026-10-26T11:15:21+00:00, book20_bid_proxy_usdt=20717, book20_ask_proxy_usdt=20845, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.14%, turnover=5486864. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T11:15:02+00:00, last15m_closed_end=2026-10-26T11:15+00:00, prior8high=0.004284, depth_time=2026-10-26T11:15:31+00:00, book20_bid_proxy_usdt=2159527, book20_ask_proxy_usdt=2135372, funding_indicative=-0.000003, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.54%, turnover=18796215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T11:15:02+00:00, last15m_closed_end=2026-10-26T11:15+00:00, prior8high=0.046320, depth_time=2026-10-26T11:15:25+00:00, book20_bid_proxy_usdt=996356, book20_ask_proxy_usdt=637751, funding_indicative=-0.000052, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=9999908. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T11:15:02+00:00, last15m_closed_end=2026-10-26T11:15+00:00, prior8high=0.443600, depth_time=2026-10-26T11:15:18+00:00, book20_bid_proxy_usdt=2779332, book20_ask_proxy_usdt=2946944, funding_indicative=-0.000140, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.31%, turnover=63166269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T11:15:02+00:00, last15m_closed_end=2026-10-26T11:15+00:00, prior8high=591.730000, depth_time=2026-10-26T11:15:23+00:00, book20_bid_proxy_usdt=16797, book20_ask_proxy_usdt=15057, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.89%, turnover=5793112. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
