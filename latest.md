# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T09:15:30Z**
- feed_generated_utc: 2026-10-18T09:15:32+00:00
- source_sha256: `2d0237610e98e37074559fd2e3b8d5bc73347603131f4fc4abab483eba0a7be8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T09:15+00:00, close=81943.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T09:00+00:00, close=81705.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|EIGEN_USDT|0.248500|-3.04|5.47|-3.81|6751978|4.03|
|FILECOIN_USDT|1.055600|-2.92|-6.40|-3.69|18855030|0.95|
|PUMPFUN_USDT|0.004297|-2.60|-24.94|-3.37|23012525|2.33|
|STRK_USDT|0.064590|-2.35|-30.86|-3.12|14325821|1.55|
|XPL_USDT|0.078540|-1.98|-9.47|-2.75|5641415|1.27|
|ZRO_USDT|1.848500|-1.95|-8.51|-2.72|7248934|0.54|
|OP_USDT|0.126780|-1.72|-8.49|-2.49|8602078|2.37|
|DOT_USDT|1.110800|-0.59|-11.62|-1.36|16501494|0.90|
|ONDO_USDT|0.437900|-0.38|-11.46|-1.15|21933102|2.28|
|WLD_USDT|0.494000|-0.32|-11.62|-1.09|58423272|2.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.110800|1.098300|1.110500|2.51|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.248500|0.245800|0.248400|0.75|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.055600|1.044000|1.056100|1.65|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.437900|0.434200|0.437900|1.51|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.126780|0.125540|0.126780|0.43|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004297|0.004250|0.004297|0.79|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.064590|0.062200|0.064590|2.31|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.494000|0.487300|0.493800|2.09|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.078540|0.077860|0.078540|2.56|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.848500|1.823800|1.848500|9.28|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T09:15:02+00:00, last15m_closed_end=2026-10-18T09:15+00:00, prior8high=1.106900, depth_time=2026-10-18T09:15:24+00:00, book20_bid_proxy_usdt=342535, book20_ask_proxy_usdt=268510, funding_indicative=-0.000130, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.59%, turnover=16501494. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T09:15:02+00:00, last15m_closed_end=2026-10-18T09:15+00:00, prior8high=0.248500, depth_time=2026-10-18T09:15:05+00:00, book20_bid_proxy_usdt=704129, book20_ask_proxy_usdt=455109, funding_indicative=0.000014, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=6751978. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T09:15:02+00:00, last15m_closed_end=2026-10-18T09:15+00:00, prior8high=1.054600, depth_time=2026-10-18T09:15:10+00:00, book20_bid_proxy_usdt=731166, book20_ask_proxy_usdt=483131, funding_indicative=-0.000057, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=18855030. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-18T09:15:02+00:00, last15m_closed_end=2026-10-18T09:15+00:00, prior8high=0.439400, depth_time=2026-10-18T09:15:26+00:00, book20_bid_proxy_usdt=1633145, book20_ask_proxy_usdt=2003876, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.38%, turnover=21933102. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T09:15:02+00:00, last15m_closed_end=2026-10-18T09:15+00:00, prior8high=0.127170, depth_time=2026-10-18T09:15:20+00:00, book20_bid_proxy_usdt=60746, book20_ask_proxy_usdt=73548, funding_indicative=-0.000161, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=8602078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T09:15:02+00:00, last15m_closed_end=2026-10-18T09:15+00:00, prior8high=0.004295, depth_time=2026-10-18T09:15:13+00:00, book20_bid_proxy_usdt=1643736, book20_ask_proxy_usdt=1345066, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=23012525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T09:15:02+00:00, last15m_closed_end=2026-10-18T09:15+00:00, prior8high=0.064390, depth_time=2026-10-18T09:15:15+00:00, book20_bid_proxy_usdt=316509, book20_ask_proxy_usdt=114600, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=14325821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T09:15:02+00:00, last15m_closed_end=2026-10-18T09:15+00:00, prior8high=0.493400, depth_time=2026-10-18T09:15:29+00:00, book20_bid_proxy_usdt=1730336, book20_ask_proxy_usdt=1947331, funding_indicative=-0.000074, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.32%, turnover=58423272. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T09:15:03+00:00, last15m_closed_end=2026-10-18T09:15+00:00, prior8high=0.078880, depth_time=2026-10-18T09:15:17+00:00, book20_bid_proxy_usdt=439898, book20_ask_proxy_usdt=469420, funding_indicative=0.000037, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.98%, turnover=5641415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T09:15:02+00:00, last15m_closed_end=2026-10-18T09:15+00:00, prior8high=1.849400, depth_time=2026-10-18T09:15:20+00:00, book20_bid_proxy_usdt=84601, book20_ask_proxy_usdt=34419, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.95%, turnover=7248934. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
