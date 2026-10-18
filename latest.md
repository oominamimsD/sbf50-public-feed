# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T12:00:36Z**
- feed_generated_utc: 2026-10-18T12:00:38+00:00
- source_sha256: `4b8202f7568419c5b9e7b597f6617c69d5c9d732a0ede57f26356f3e0556c0b7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T12:00+00:00, close=82038.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T12:00+00:00, close=82038.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T12:00+00:00, close=82038.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.061900|-6.42|-33.74|-7.30|15637585|1.61|
|EIGEN_USDT|0.240900|-6.00|2.24|-6.88|6569868|4.15|
|SAND_USDT|0.060710|-3.69|-9.77|-4.57|47488878|3.29|
|PUMPFUN_USDT|0.004283|-2.92|-25.18|-3.80|23431684|2.33|
|ZRO_USDT|1.838300|-2.49|-9.02|-3.37|6575922|0.54|
|FILECOIN_USDT|1.060900|-2.43|-5.93|-3.31|18181889|0.94|
|XPL_USDT|0.078360|-2.20|-9.68|-3.08|5934410|1.28|
|OP_USDT|0.126760|-1.73|-8.50|-2.61|8882502|0.79|
|ZEC_USDT|1129.530000|-1.03|-8.30|-1.91|1224881677|0.27|
|DOT_USDT|1.106500|-0.97|-11.96|-1.85|16919212|0.90|
|ICP_USDT|2.902000|-0.88|-7.84|-1.76|6153496|3.45|
|INJ_USDT|8.421000|-0.48|15.45|-1.36|40273953|1.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.106500|1.102900|1.106500|1.06|N|Y/Y|Y/Y|N|N|
|EIGEN_USDT|0.240900|0.240200|0.240900|1.26|N|Y/Y|Y/Y|N|N|
|FILECOIN_USDT|1.060900|1.053700|1.060900|0.83|N|Y/Y|Y/Y|N|N|
|ICP_USDT|2.902000|2.889000|2.902000|2.94|N|Y/Y|Y/Y|N|N|
|INJ_USDT|8.421000|8.393000|8.421000|0.77|N|Y/Y|Y/N|N|N|
|OP_USDT|0.126760|0.125830|0.126760|1.16|N|Y/Y|Y/Y|N|N|
|PUMPFUN_USDT|0.004283|0.004269|0.004283|0.34|N|Y/Y|Y/Y|N|N|
|SAND_USDT|0.060710|0.060210|0.060710|0.15|N|Y/Y|N/N|N|N|
|STRK_USDT|0.061900|0.061570|0.061900|3.04|N|Y/Y|Y/Y|N|N|
|XPL_USDT|0.078360|0.078140|0.078360|0.87|N|Y/Y|Y/Y|N|N|
|ZEC_USDT|1129.530000|1123.060000|1129.530000|0.85|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.838300|1.829900|1.838300|0.22|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T11:59:59+00:00, last15m_closed_end=2026-10-18T12:00+00:00, prior8high=1.120400, depth_time=2026-10-18T12:00:30+00:00, book20_bid_proxy_usdt=328064, book20_ask_proxy_usdt=256158, funding_indicative=-0.000063, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.97%, turnover=16919212. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T11:59:59+00:00, last15m_closed_end=2026-10-18T12:00+00:00, prior8high=0.249700, depth_time=2026-10-18T12:00:09+00:00, book20_bid_proxy_usdt=430485, book20_ask_proxy_usdt=474676, funding_indicative=-0.000005, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.00%, turnover=6569868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T11:59:59+00:00, last15m_closed_end=2026-10-18T12:00+00:00, prior8high=1.069800, depth_time=2026-10-18T12:00:18+00:00, book20_bid_proxy_usdt=479412, book20_ask_proxy_usdt=431405, funding_indicative=0.000031, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=18181889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T11:59:59+00:00, last15m_closed_end=2026-10-18T12:00+00:00, prior8high=2.941000, depth_time=2026-10-18T12:00:33+00:00, book20_bid_proxy_usdt=1122133, book20_ask_proxy_usdt=1030312, funding_indicative=0.000036, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=6153496. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-18T11:59:59+00:00, last15m_closed_end=2026-10-18T12:00+00:00, prior8high=8.530000, depth_time=2026-10-18T12:00:35+00:00, book20_bid_proxy_usdt=248384, book20_ask_proxy_usdt=224405, funding_indicative=0.000232, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.48%, turnover=40273953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T11:59:59+00:00, last15m_closed_end=2026-10-18T12:00+00:00, prior8high=0.127970, depth_time=2026-10-18T12:00:25+00:00, book20_bid_proxy_usdt=78070, book20_ask_proxy_usdt=53958, funding_indicative=-0.000213, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=8882502. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T11:59:59+00:00, last15m_closed_end=2026-10-18T12:00+00:00, prior8high=0.004347, depth_time=2026-10-18T12:00:15+00:00, book20_bid_proxy_usdt=1812032, book20_ask_proxy_usdt=1256232, funding_indicative=0.000032, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.92%, turnover=23431684. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T11:59:59+00:00, last15m_closed_end=2026-10-18T12:00+00:00, prior8high=0.062200, depth_time=2026-10-18T12:00:13+00:00, book20_bid_proxy_usdt=540050, book20_ask_proxy_usdt=616514, funding_indicative=-0.005237, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.69%, turnover=47488878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T11:59:59+00:00, last15m_closed_end=2026-10-18T12:00+00:00, prior8high=0.063410, depth_time=2026-10-18T12:00:08+00:00, book20_bid_proxy_usdt=316638, book20_ask_proxy_usdt=286841, funding_indicative=0.000050, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.42%, turnover=15637585. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T11:59:59+00:00, last15m_closed_end=2026-10-18T12:00+00:00, prior8high=0.079080, depth_time=2026-10-18T12:00:23+00:00, book20_bid_proxy_usdt=617862, book20_ask_proxy_usdt=409508, funding_indicative=0.000046, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.20%, turnover=5934410. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T11:59:59+00:00, last15m_closed_end=2026-10-18T12:00+00:00, prior8high=1140.020000, depth_time=2026-10-18T12:00:28+00:00, book20_bid_proxy_usdt=148037, book20_ask_proxy_usdt=661413, funding_indicative=0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.03%, turnover=1224881677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T11:59:59+00:00, last15m_closed_end=2026-10-18T12:00+00:00, prior8high=1.874500, depth_time=2026-10-18T12:00:18+00:00, book20_bid_proxy_usdt=63543, book20_ask_proxy_usdt=27058, funding_indicative=-0.000024, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.49%, turnover=6575922. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
