# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T09:45:29Z**
- feed_generated_utc: 2026-10-18T09:45:31+00:00
- source_sha256: `e78819d811ca3025f18644d3d95e7ec73a9071e700dbef9230cc988144407f2d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T09:45+00:00, close=82164.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T09:00+00:00, close=81705.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.062900|-4.91|-32.67|-5.95|14806079|1.59|
|EIGEN_USDT|0.247700|-3.35|5.13|-4.39|6897617|4.04|
|FILECOIN_USDT|1.058500|-2.65|-6.14|-3.69|19255795|0.94|
|PUMPFUN_USDT|0.004324|-1.99|-24.47|-3.03|23831348|2.31|
|XPL_USDT|0.078700|-1.78|-9.28|-2.82|5711434|1.27|
|ZRO_USDT|1.857000|-1.50|-8.09|-2.54|7306474|1.62|
|OP_USDT|0.127360|-1.27|-8.07|-2.31|8756487|0.79|
|TIA_USDT|0.651500|-0.98|26.99|-2.02|60625381|1.53|
|DOT_USDT|1.115700|-0.15|-11.23|-1.19|16755210|0.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.115700|1.098300|1.116100|1.43|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.247700|0.245800|0.247800|6.16|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.058500|1.044000|1.058500|2.68|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.127360|0.125540|0.127380|2.02|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004324|0.004254|0.004324|6.78|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.062900|0.062410|0.062900|2.25|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.651500|0.626300|0.651500|2.91|N|N/Y|Y/Y|Y|N|
|XPL_USDT|0.078700|0.077860|0.078710|1.00|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.857000|1.823800|1.857000|1.28|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T09:45:01+00:00, last15m_closed_end=2026-10-18T09:45+00:00, prior8high=1.112700, depth_time=2026-10-18T09:45:27+00:00, book20_bid_proxy_usdt=310874, book20_ask_proxy_usdt=122444, funding_indicative=-0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.15%, turnover=16755210. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T09:45:01+00:00, last15m_closed_end=2026-10-18T09:45+00:00, prior8high=0.249100, depth_time=2026-10-18T09:45:11+00:00, book20_bid_proxy_usdt=567786, book20_ask_proxy_usdt=368392, funding_indicative=0.000016, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.35%, turnover=6897617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T09:45:01+00:00, last15m_closed_end=2026-10-18T09:45+00:00, prior8high=1.059600, depth_time=2026-10-18T09:45:13+00:00, book20_bid_proxy_usdt=776032, book20_ask_proxy_usdt=426028, funding_indicative=-0.000057, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.65%, turnover=19255795. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T09:45:01+00:00, last15m_closed_end=2026-10-18T09:45+00:00, prior8high=0.127200, depth_time=2026-10-18T09:45:23+00:00, book20_bid_proxy_usdt=105935, book20_ask_proxy_usdt=61002, funding_indicative=-0.000170, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=8756487. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T09:45:01+00:00, last15m_closed_end=2026-10-18T09:45+00:00, prior8high=0.004316, depth_time=2026-10-18T09:45:16+00:00, book20_bid_proxy_usdt=1807335, book20_ask_proxy_usdt=793361, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=23831348. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T09:45:01+00:00, last15m_closed_end=2026-10-18T09:45+00:00, prior8high=0.064850, depth_time=2026-10-18T09:45:08+00:00, book20_bid_proxy_usdt=885614, book20_ask_proxy_usdt=294095, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.91%, turnover=14806079. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T09:45:01+00:00, last15m_closed_end=2026-10-18T09:45+00:00, prior8high=0.664500, depth_time=2026-10-18T09:45:25+00:00, book20_bid_proxy_usdt=292752, book20_ask_proxy_usdt=307770, funding_indicative=-0.000094, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.98%, turnover=60625381. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T09:45:01+00:00, last15m_closed_end=2026-10-18T09:45+00:00, prior8high=0.078700, depth_time=2026-10-18T09:45:18+00:00, book20_bid_proxy_usdt=600642, book20_ask_proxy_usdt=532700, funding_indicative=0.000045, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=5711434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T09:45:01+00:00, last15m_closed_end=2026-10-18T09:45+00:00, prior8high=1.857500, depth_time=2026-10-18T09:45:20+00:00, book20_bid_proxy_usdt=61199, book20_ask_proxy_usdt=26356, funding_indicative=0.000030, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=7306474. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
