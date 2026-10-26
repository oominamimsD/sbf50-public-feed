# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T11:45:29Z**
- feed_generated_utc: 2026-10-26T11:45:33+00:00
- source_sha256: `9a6bdd133b62041b4aa8d97b342da7f3483f75675dc3987b9e46ea45e884cae9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T11:45+00:00, close=80352, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T11:00+00:00, close=80339.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.073650|-31.47|10.75|-31.16|7269570|2.71|
|IRYS_USDT|0.028720|-25.28|135.40|-24.97|12455148|3.48|
|APR_USDT|0.033930|-17.86|24.55|-17.55|8445735|2.95|
|BTW_USDT|1.472100|-11.26|-36.14|-10.95|11245390|2.04|
|WLD_USDT|0.439500|-3.74|-7.72|-3.43|64361053|2.27|
|XMR_USDT|589.520000|-2.92|1.20|-2.61|5855874|0.17|
|LIT_USDT|3.095500|-2.60|5.63|-2.29|5537121|0.32|
|STRK_USDT|0.044570|-2.55|-27.59|-2.24|10072556|2.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.033930|0.033120|0.033930|0.46|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.472100|1.480300|1.472100|2.49|Y|Y/Y|Y/Y|Y|Y|
|CAP_USDT|0.073650|0.075120|0.073650|0.48|N|Y/Y|N/N|Y|N|
|IRYS_USDT|0.028720|0.027970|0.028720|0.67|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.095500|3.066900|3.095500|1.68|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044570|0.044550|0.044570|0.14|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.439500|0.435800|0.439600|1.16|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|589.520000|588.180000|589.520000|0.70|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T11:45:01+00:00, last15m_closed_end=2026-10-26T11:45+00:00, prior8high=0.038620, depth_time=2026-10-26T11:45:14+00:00, book20_bid_proxy_usdt=72852, book20_ask_proxy_usdt=81173, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.86%, turnover=8445735. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T11:45:01+00:00, last15m_closed_end=2026-10-26T11:45+00:00, prior8high=1.527500, depth_time=2026-10-26T11:45:16+00:00, book20_bid_proxy_usdt=18233, book20_ask_proxy_usdt=14870, funding_indicative=-0.012404, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.26%, turnover=11245390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T11:45:01+00:00, last15m_closed_end=2026-10-26T11:45+00:00, prior8high=0.085830, depth_time=2026-10-26T11:45:08+00:00, book20_bid_proxy_usdt=55978, book20_ask_proxy_usdt=70629, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-31.47%, turnover=7269570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T11:45:01+00:00, last15m_closed_end=2026-10-26T11:45+00:00, prior8high=0.029760, depth_time=2026-10-26T11:45:11+00:00, book20_bid_proxy_usdt=60724, book20_ask_proxy_usdt=104944, funding_indicative=-0.000380, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=1, 24h_change=-25.28%, turnover=12455148. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T11:45:01+00:00, last15m_closed_end=2026-10-26T11:45+00:00, prior8high=3.116600, depth_time=2026-10-26T11:45:24+00:00, book20_bid_proxy_usdt=24394, book20_ask_proxy_usdt=16929, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=5537121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T11:45:01+00:00, last15m_closed_end=2026-10-26T11:45+00:00, prior8high=0.046320, depth_time=2026-10-26T11:45:27+00:00, book20_bid_proxy_usdt=981552, book20_ask_proxy_usdt=701770, funding_indicative=-0.000049, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.55%, turnover=10072556. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T11:45:01+00:00, last15m_closed_end=2026-10-26T11:45+00:00, prior8high=0.443600, depth_time=2026-10-26T11:45:19+00:00, book20_bid_proxy_usdt=2681502, book20_ask_proxy_usdt=2969948, funding_indicative=-0.000132, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.74%, turnover=64361053. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T11:45:01+00:00, last15m_closed_end=2026-10-26T11:45+00:00, prior8high=591.000000, depth_time=2026-10-26T11:45:22+00:00, book20_bid_proxy_usdt=25084, book20_ask_proxy_usdt=14073, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=5855874. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
