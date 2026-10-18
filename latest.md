# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T10:00:30Z**
- feed_generated_utc: 2026-10-18T10:00:32+00:00
- source_sha256: `458fd561a5beced175478e28f95af2df5e7db5e74656b6f2f0b0725cfce9be93`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T10:00+00:00, close=82122.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T10:00+00:00, close=82122.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.063010|-4.74|-32.55|-5.73|14986559|1.59|
|EIGEN_USDT|0.248600|-3.00|5.51|-3.99|6961424|4.02|
|FILECOIN_USDT|1.062300|-2.30|-5.80|-3.29|19349505|0.94|
|PUMPFUN_USDT|0.004325|-1.97|-24.45|-2.96|23915044|2.31|
|XPL_USDT|0.078700|-1.78|-9.28|-2.77|5811569|1.27|
|ZRO_USDT|1.858700|-1.41|-8.01|-2.40|7511627|0.54|
|OP_USDT|0.127260|-1.34|-8.14|-2.33|8829345|0.79|
|TIA_USDT|0.655900|-0.31|27.85|-1.30|61204178|1.52|
|ICP_USDT|2.922000|-0.20|-7.20|-1.19|6069259|3.42|
|DOT_USDT|1.115700|-0.15|-11.23|-1.14|16885902|2.69|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.115700|1.098300|1.115700|0.98|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.248600|0.245800|0.248600|2.93|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.062300|1.044000|1.062300|0.71|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.922000|2.904000|2.922000|2.56|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.127260|0.125540|0.127290|1.03|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004325|0.004256|0.004324|0.89|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.063010|0.062630|0.063000|2.02|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.655900|0.627600|0.655900|1.08|N|N/Y|Y/Y|Y|N|
|XPL_USDT|0.078700|0.077860|0.078700|1.62|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.858700|1.823800|1.858700|8.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T09:59:59+00:00, last15m_closed_end=2026-10-18T10:00+00:00, prior8high=1.119600, depth_time=2026-10-18T10:00:28+00:00, book20_bid_proxy_usdt=440170, book20_ask_proxy_usdt=170016, funding_indicative=-0.000080, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.15%, turnover=16885902. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T09:59:59+00:00, last15m_closed_end=2026-10-18T10:00+00:00, prior8high=0.249900, depth_time=2026-10-18T10:00:09+00:00, book20_bid_proxy_usdt=694334, book20_ask_proxy_usdt=418577, funding_indicative=0.000022, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.00%, turnover=6961424. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T09:59:59+00:00, last15m_closed_end=2026-10-18T10:00+00:00, prior8high=1.065600, depth_time=2026-10-18T10:00:11+00:00, book20_bid_proxy_usdt=737789, book20_ask_proxy_usdt=552609, funding_indicative=-0.000057, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.30%, turnover=19349505. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T09:59:59+00:00, last15m_closed_end=2026-10-18T10:00+00:00, prior8high=2.937000, depth_time=2026-10-18T10:00:27+00:00, book20_bid_proxy_usdt=924960, book20_ask_proxy_usdt=892470, funding_indicative=-0.000041, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.20%, turnover=6069259. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T09:59:59+00:00, last15m_closed_end=2026-10-18T10:00+00:00, prior8high=0.128100, depth_time=2026-10-18T10:00:22+00:00, book20_bid_proxy_usdt=69715, book20_ask_proxy_usdt=38659, funding_indicative=-0.000175, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.34%, turnover=8829345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T09:59:59+00:00, last15m_closed_end=2026-10-18T10:00+00:00, prior8high=0.004345, depth_time=2026-10-18T10:00:14+00:00, book20_bid_proxy_usdt=2111510, book20_ask_proxy_usdt=1162509, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=23915044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T09:59:59+00:00, last15m_closed_end=2026-10-18T10:00+00:00, prior8high=0.064850, depth_time=2026-10-18T10:00:08+00:00, book20_bid_proxy_usdt=346543, book20_ask_proxy_usdt=267089, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.74%, turnover=14986559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T09:59:59+00:00, last15m_closed_end=2026-10-18T10:00+00:00, prior8high=0.665300, depth_time=2026-10-18T10:00:24+00:00, book20_bid_proxy_usdt=213926, book20_ask_proxy_usdt=150338, funding_indicative=-0.000088, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.31%, turnover=61204178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T09:59:59+00:00, last15m_closed_end=2026-10-18T10:00+00:00, prior8high=0.079030, depth_time=2026-10-18T10:00:17+00:00, book20_bid_proxy_usdt=480795, book20_ask_proxy_usdt=405654, funding_indicative=0.000044, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=5811569. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T09:59:59+00:00, last15m_closed_end=2026-10-18T10:00+00:00, prior8high=1.866000, depth_time=2026-10-18T10:00:18+00:00, book20_bid_proxy_usdt=70672, book20_ask_proxy_usdt=31109, funding_indicative=0.000026, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.41%, turnover=7511627. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
