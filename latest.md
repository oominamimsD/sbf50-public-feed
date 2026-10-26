# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T11:30:33Z**
- feed_generated_utc: 2026-10-26T11:30:37+00:00
- source_sha256: `bdf4f8dfd3f8b86943ec5a7769eebf853c3d0dd32bb65e51638681b70851c095`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T11:30+00:00, close=80315.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T11:00+00:00, close=80339.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.075250|-29.98|13.15|-29.63|7237196|1.33|
|IRYS_USDT|0.028390|-26.14|132.70|-25.79|12389597|7.05|
|APR_USDT|0.034140|-17.35|25.33|-17.00|8427843|2.93|
|BTW_USDT|1.496900|-9.76|-35.06|-9.41|11048379|3.34|
|WLD_USDT|0.437400|-4.20|-8.16|-3.85|63671727|2.29|
|LIT_USDT|3.081200|-3.05|5.14|-2.70|5507084|0.33|
|XMR_USDT|589.590000|-2.90|1.21|-2.55|5828145|0.17|
|STRK_USDT|0.044700|-2.27|-27.38|-1.92|10056172|2.24|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034140|0.033120|0.034140|0.94|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.496900|1.480300|1.496900|1.01|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.075250|0.075240|0.075250|0.42|N|Y/Y|N/N|Y|N|
|IRYS_USDT|0.028390|0.028070|0.028390|0.98|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.081200|3.066900|3.081100|1.13|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044700|0.044550|0.044700|0.47|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.437400|0.435800|0.437400|0.85|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|589.590000|588.070000|589.460000|0.88|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T11:30:03+00:00, last15m_closed_end=2026-10-26T11:30+00:00, prior8high=0.038620, depth_time=2026-10-26T11:30:16+00:00, book20_bid_proxy_usdt=80318, book20_ask_proxy_usdt=60963, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.35%, turnover=8427843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T11:30:04+00:00, last15m_closed_end=2026-10-26T11:30+00:00, prior8high=1.532000, depth_time=2026-10-26T11:30:20+00:00, book20_bid_proxy_usdt=20586, book20_ask_proxy_usdt=14942, funding_indicative=-0.012534, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.76%, turnover=11048379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T11:30:03+00:00, last15m_closed_end=2026-10-26T11:30+00:00, prior8high=0.087050, depth_time=2026-10-26T11:30:11+00:00, book20_bid_proxy_usdt=64483, book20_ask_proxy_usdt=69315, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-29.98%, turnover=7237196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T11:30:04+00:00, last15m_closed_end=2026-10-26T11:30+00:00, prior8high=0.029760, depth_time=2026-10-26T11:30:14+00:00, book20_bid_proxy_usdt=77721, book20_ask_proxy_usdt=133290, funding_indicative=-0.000449, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=1, 24h_change=-26.14%, turnover=12389597. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T11:30:04+00:00, last15m_closed_end=2026-10-26T11:30+00:00, prior8high=3.116600, depth_time=2026-10-26T11:30:26+00:00, book20_bid_proxy_usdt=29482, book20_ask_proxy_usdt=19635, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=5507084. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T11:30:04+00:00, last15m_closed_end=2026-10-26T11:30+00:00, prior8high=0.046320, depth_time=2026-10-26T11:30:32+00:00, book20_bid_proxy_usdt=849235, book20_ask_proxy_usdt=622034, funding_indicative=-0.000048, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.27%, turnover=10056172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T11:30:04+00:00, last15m_closed_end=2026-10-26T11:30+00:00, prior8high=0.443600, depth_time=2026-10-26T11:30:23+00:00, book20_bid_proxy_usdt=2751144, book20_ask_proxy_usdt=3233308, funding_indicative=-0.000135, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.20%, turnover=63671727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T11:30:04+00:00, last15m_closed_end=2026-10-26T11:30+00:00, prior8high=591.000000, depth_time=2026-10-26T11:30:30+00:00, book20_bid_proxy_usdt=27358, book20_ask_proxy_usdt=55422, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=5828145. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
