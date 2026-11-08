# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T15:00:28Z**
- feed_generated_utc: 2026-11-08T15:00:29+00:00
- source_sha256: `c43b5de6e25ca537ba9cba18e74027c70cdade68dd3ed2d2d71a7ec760847cec`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T15:00+00:00, close=76006.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T15:00+00:00, close=76006.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005329|-11.07|-52.15|-11.44|24733462|1.88|
|ONE_USDT|0.001892|-7.11|61.11|-7.48|21922581|0.53|
|TIA_USDT|0.420800|-4.58|-14.13|-4.95|7007855|2.38|
|WLD_USDT|0.327600|-2.61|-18.99|-2.98|24306340|3.05|
|ENA_USDT|0.155030|-1.99|-20.09|-2.36|24135498|9.03|
|AAVE_USDT|129.120000|-1.99|-4.71|-2.36|9382252|0.77|
|LINK_USDT|10.735000|-1.55|-7.22|-1.92|57935086|0.93|
|DOT_USDT|0.889300|-1.23|-7.26|-1.60|6370893|1.12|
|ADA_USDT|0.180400|-0.66|-6.81|-1.03|10925405|5.54|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.120000|128.470000|129.120000|0.87|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.180400|0.179300|0.180500|2.29|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005329|0.005312|0.005331|0.77|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.889300|0.887600|0.889300|0.72|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.155030|0.152750|0.154910|1.38|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.735000|10.691000|10.735000|0.91|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001892|0.001818|0.001892|0.58|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.420800|0.419200|0.420800|0.61|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.327600|0.323500|0.327600|1.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T15:00:02+00:00, last15m_closed_end=2026-11-08T15:00+00:00, prior8high=131.400000, depth_time=2026-11-08T15:00:15+00:00, book20_bid_proxy_usdt=494293, book20_ask_proxy_usdt=466967, funding_indicative=0.000074, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.99%, turnover=9382252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T15:00:02+00:00, last15m_closed_end=2026-11-08T15:00+00:00, prior8high=0.181200, depth_time=2026-11-08T15:00:27+00:00, book20_bid_proxy_usdt=8343502, book20_ask_proxy_usdt=8478624, funding_indicative=-0.000014, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.66%, turnover=10925405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T15:00:02+00:00, last15m_closed_end=2026-11-08T15:00+00:00, prior8high=0.005559, depth_time=2026-11-08T15:00:07+00:00, book20_bid_proxy_usdt=22910, book20_ask_proxy_usdt=47764, funding_indicative=0.000050, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.07%, turnover=24733462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-08T15:00:02+00:00, last15m_closed_end=2026-11-08T15:00+00:00, prior8high=0.901900, depth_time=2026-11-08T15:00:24+00:00, book20_bid_proxy_usdt=354319, book20_ask_proxy_usdt=376220, funding_indicative=-0.000114, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=6370893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T15:00:02+00:00, last15m_closed_end=2026-11-08T15:00+00:00, prior8high=0.155690, depth_time=2026-11-08T15:00:16+00:00, book20_bid_proxy_usdt=211064, book20_ask_proxy_usdt=175423, funding_indicative=-0.000063, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=24135498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T15:00:02+00:00, last15m_closed_end=2026-11-08T15:00+00:00, prior8high=10.788000, depth_time=2026-11-08T15:00:14+00:00, book20_bid_proxy_usdt=442763, book20_ask_proxy_usdt=644432, funding_indicative=0.000011, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=57935086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T15:00:02+00:00, last15m_closed_end=2026-11-08T15:00+00:00, prior8high=0.001915, depth_time=2026-11-08T15:00:10+00:00, book20_bid_proxy_usdt=12297, book20_ask_proxy_usdt=11952, funding_indicative=-0.000902, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.11%, turnover=21922581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T15:00:02+00:00, last15m_closed_end=2026-11-08T15:00+00:00, prior8high=0.425000, depth_time=2026-11-08T15:00:08+00:00, book20_bid_proxy_usdt=296359, book20_ask_proxy_usdt=374739, funding_indicative=0.000023, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.58%, turnover=7007855. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T15:00:02+00:00, last15m_closed_end=2026-11-08T15:00+00:00, prior8high=0.328300, depth_time=2026-11-08T15:00:13+00:00, book20_bid_proxy_usdt=3812656, book20_ask_proxy_usdt=3780605, funding_indicative=-0.000044, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=24306340. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
