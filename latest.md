# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T10:30:35Z**
- feed_generated_utc: 2026-10-18T10:30:37+00:00
- source_sha256: `ce16e6b8ef1d4c505235b8414a0605f40af952c58c17b4d1c6633c0fb6f748bc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T10:30+00:00, close=82221.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T10:00+00:00, close=82122.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.062230|-5.92|-33.39|-7.04|15014026|1.61|
|EIGEN_USDT|0.246800|-3.70|4.75|-4.82|6661418|4.05|
|SAND_USDT|0.061310|-2.74|-8.88|-3.86|47512843|1.63|
|TIA_USDT|0.644100|-2.11|25.55|-3.23|61171361|1.55|
|FILECOIN_USDT|1.066000|-1.96|-5.47|-3.08|18354384|0.94|
|PUMPFUN_USDT|0.004331|-1.83|-24.34|-2.95|23406005|2.31|
|XPL_USDT|0.078780|-1.68|-9.19|-2.80|5812076|1.27|
|ZRO_USDT|1.854500|-1.63|-8.22|-2.75|7103955|0.54|
|OP_USDT|0.127030|-1.52|-8.31|-2.64|8633073|0.79|
|ICP_USDT|2.913000|-0.51|-7.49|-1.63|6003088|3.43|
|DOT_USDT|1.116300|-0.09|-11.18|-1.21|16681476|0.90|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.116300|1.098300|1.116000|0.66|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.246800|0.245800|0.246800|1.36|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.066000|1.044000|1.066000|0.53|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.913000|2.904000|2.913000|2.31|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.127030|0.125540|0.127030|1.42|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004331|0.004256|0.004327|1.97|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.061310|0.061340|0.061310|0.21|N|N/N|N/N|Y|N|
|STRK_USDT|0.062230|0.062680|0.062200|6.05|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.644100|0.636200|0.644100|1.74|N|N/Y|Y/Y|Y|N|
|XPL_USDT|0.078780|0.077860|0.078780|0.35|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.854500|1.823800|1.854800|1.12|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T10:30:02+00:00, last15m_closed_end=2026-10-18T10:30+00:00, prior8high=1.120400, depth_time=2026-10-18T10:30:34+00:00, book20_bid_proxy_usdt=265904, book20_ask_proxy_usdt=279602, funding_indicative=-0.000068, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.09%, turnover=16681476. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T10:30:02+00:00, last15m_closed_end=2026-10-18T10:30+00:00, prior8high=0.249900, depth_time=2026-10-18T10:30:12+00:00, book20_bid_proxy_usdt=587984, book20_ask_proxy_usdt=459813, funding_indicative=-0.000006, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.70%, turnover=6661418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T10:30:02+00:00, last15m_closed_end=2026-10-18T10:30+00:00, prior8high=1.067600, depth_time=2026-10-18T10:30:19+00:00, book20_bid_proxy_usdt=700332, book20_ask_proxy_usdt=390178, funding_indicative=-0.000043, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=18354384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T10:30:02+00:00, last15m_closed_end=2026-10-18T10:30+00:00, prior8high=2.941000, depth_time=2026-10-18T10:30:32+00:00, book20_bid_proxy_usdt=753629, book20_ask_proxy_usdt=817392, funding_indicative=-0.000010, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.51%, turnover=6003088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T10:30:02+00:00, last15m_closed_end=2026-10-18T10:30+00:00, prior8high=0.128100, depth_time=2026-10-18T10:30:30+00:00, book20_bid_proxy_usdt=56788, book20_ask_proxy_usdt=65379, funding_indicative=-0.000213, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=8633073. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T10:30:02+00:00, last15m_closed_end=2026-10-18T10:30+00:00, prior8high=0.004347, depth_time=2026-10-18T10:30:21+00:00, book20_bid_proxy_usdt=1511432, book20_ask_proxy_usdt=942359, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.83%, turnover=23406005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T10:30:02+00:00, last15m_closed_end=2026-10-18T10:30+00:00, prior8high=0.063750, depth_time=2026-10-18T10:30:14+00:00, book20_bid_proxy_usdt=382358, book20_ask_proxy_usdt=578933, funding_indicative=-0.008060, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=47512843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T10:30:02+00:00, last15m_closed_end=2026-10-18T10:30+00:00, prior8high=0.064850, depth_time=2026-10-18T10:30:09+00:00, book20_bid_proxy_usdt=314930, book20_ask_proxy_usdt=315721, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.92%, turnover=15014026. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T10:30:02+00:00, last15m_closed_end=2026-10-18T10:30+00:00, prior8high=0.665300, depth_time=2026-10-18T10:30:16+00:00, book20_bid_proxy_usdt=144039, book20_ask_proxy_usdt=280277, funding_indicative=-0.000078, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=61171361. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T10:30:02+00:00, last15m_closed_end=2026-10-18T10:30+00:00, prior8high=0.079050, depth_time=2026-10-18T10:30:24+00:00, book20_bid_proxy_usdt=534022, book20_ask_proxy_usdt=447020, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=5812076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T10:30:02+00:00, last15m_closed_end=2026-10-18T10:30+00:00, prior8high=1.874500, depth_time=2026-10-18T10:30:27+00:00, book20_bid_proxy_usdt=51390, book20_ask_proxy_usdt=57465, funding_indicative=-0.000013, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=7103955. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
