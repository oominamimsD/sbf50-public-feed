# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T17:30:39Z**
- feed_generated_utc: 2026-10-28T17:30:43+00:00
- source_sha256: `71d26eaadcbda330dbe6468d42a13c3b57dccbd9cf40a3cbb57d91fcaf078925`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T17:30+00:00, close=80538.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-28T17:00+00:00, close=80591.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.523600|-3.05|-17.21|-3.06|14662635|1.91|
|WLD_USDT|0.421700|-2.56|-26.48|-2.57|63963719|2.37|
|STRK_USDT|0.045610|-2.54|-26.39|-2.55|5222985|2.19|
|BULLA_USDT|0.060270|-2.11|-25.54|-2.12|5319811|1.66|
|APT_USDT|0.676100|-1.82|-19.08|-1.83|6194562|2.96|
|ARB_USDT|0.164700|-1.79|-16.22|-1.80|18345599|0.61|
|FET_USDT|0.178600|-1.70|-10.96|-1.71|6118363|5.60|
|ONDO_USDT|0.412300|-1.64|-11.63|-1.65|17038295|2.42|
|HBAR_USDT|0.074680|-1.62|-13.10|-1.63|11200434|1.34|
|DOT_USDT|0.988000|-1.55|-16.26|-1.56|12243248|1.01|
|OP_USDT|0.109370|-1.53|-17.08|-1.54|6346715|1.83|
|AAVE_USDT|130.950000|-1.32|-17.38|-1.33|15976551|0.76|
|NEAR_USDT|4.571000|-1.25|-15.11|-1.26|91278030|2.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.950000|131.290000|130.970000|0.97|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.676100|0.677300|0.676100|0.45|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164700|0.164410|0.164770|0.51|N|Y/Y|Y/Y|Y|N|
|BULLA_USDT|0.060270|0.059390|0.060270|0.30|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.988000|0.987000|0.988300|0.38|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.178600|0.178500|0.178600|1.85|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.074680|0.074680|0.074690|6.71|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.571000|4.557000|4.570000|0.81|N|Y/Y|N/N|Y|N|
|ONDO_USDT|0.412300|0.413000|0.412500|0.86|N|Y/Y|N/N|Y|N|
|OP_USDT|0.109370|0.109270|0.109370|0.21|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045610|0.045520|0.045610|0.52|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.523600|0.526600|0.523600|1.67|Y|Y/N|N/Y|Y|N|
|WLD_USDT|0.421700|0.416900|0.421900|0.49|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-28T17:30:04+00:00, last15m_closed_end=2026-10-28T17:30+00:00, prior8high=133.050000, depth_time=2026-10-28T17:30:35+00:00, book20_bid_proxy_usdt=393907, book20_ask_proxy_usdt=427521, funding_indicative=0.000086, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=15976551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-28T17:30:04+00:00, last15m_closed_end=2026-10-28T17:30+00:00, prior8high=0.690600, depth_time=2026-10-28T17:30:18+00:00, book20_bid_proxy_usdt=168415, book20_ask_proxy_usdt=153628, funding_indicative=-0.000137, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=6194562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-28T17:30:04+00:00, last15m_closed_end=2026-10-28T17:30+00:00, prior8high=0.167890, depth_time=2026-10-28T17:30:21+00:00, book20_bid_proxy_usdt=78878, book20_ask_proxy_usdt=92343, funding_indicative=-0.000043, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=18345599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-28T17:30:03+00:00, last15m_closed_end=2026-10-28T17:30+00:00, prior8high=0.064000, depth_time=2026-10-28T17:30:16+00:00, book20_bid_proxy_usdt=22650, book20_ask_proxy_usdt=10798, funding_indicative=0.000050, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=5319811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-28T17:30:04+00:00, last15m_closed_end=2026-10-28T17:30+00:00, prior8high=1.010500, depth_time=2026-10-28T17:30:30+00:00, book20_bid_proxy_usdt=234026, book20_ask_proxy_usdt=343279, funding_indicative=0.000000, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=12243248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-28T17:30:04+00:00, last15m_closed_end=2026-10-28T17:30+00:00, prior8high=0.182500, depth_time=2026-10-28T17:30:22+00:00, book20_bid_proxy_usdt=2059575, book20_ask_proxy_usdt=1059092, funding_indicative=0.000033, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=6118363. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T17:30:04+00:00, last15m_closed_end=2026-10-28T17:30+00:00, prior8high=0.075940, depth_time=2026-10-28T17:30:28+00:00, book20_bid_proxy_usdt=742011, book20_ask_proxy_usdt=1273889, funding_indicative=-0.000001, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.62%, turnover=11200434. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-28T17:30:03+00:00, last15m_closed_end=2026-10-28T17:30+00:00, prior8high=4.646000, depth_time=2026-10-28T17:30:38+00:00, book20_bid_proxy_usdt=3829193, book20_ask_proxy_usdt=3582150, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=91278030. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-28T17:30:04+00:00, last15m_closed_end=2026-10-28T17:30+00:00, prior8high=0.419600, depth_time=2026-10-28T17:30:23+00:00, book20_bid_proxy_usdt=1806187, book20_ask_proxy_usdt=1917820, funding_indicative=0.000050, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.64%, turnover=17038295. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-28T17:30:04+00:00, last15m_closed_end=2026-10-28T17:30+00:00, prior8high=0.111260, depth_time=2026-10-28T17:30:33+00:00, book20_bid_proxy_usdt=94427, book20_ask_proxy_usdt=106611, funding_indicative=-0.000064, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=6346715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-28T17:30:04+00:00, last15m_closed_end=2026-10-28T17:30+00:00, prior8high=0.047080, depth_time=2026-10-28T17:30:13+00:00, book20_bid_proxy_usdt=832961, book20_ask_proxy_usdt=675891, funding_indicative=0.000000, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.54%, turnover=5222985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-28T17:30:04+00:00, last15m_closed_end=2026-10-28T17:30+00:00, prior8high=0.546100, depth_time=2026-10-28T17:30:08+00:00, book20_bid_proxy_usdt=315068, book20_ask_proxy_usdt=292174, funding_indicative=0.000017, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=14662635. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-28T17:30:03+00:00, last15m_closed_end=2026-10-28T17:30+00:00, prior8high=0.435200, depth_time=2026-10-28T17:30:11+00:00, book20_bid_proxy_usdt=3343128, book20_ask_proxy_usdt=3802660, funding_indicative=0.000010, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=63963719. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
