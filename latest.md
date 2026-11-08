# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T14:45:25Z**
- feed_generated_utc: 2026-11-08T14:45:26+00:00
- source_sha256: `69d9743ab0da64462540efb23a6e3dafdca43a2edba2bff1ec20a4cfbb4fef42`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T14:45+00:00, close=75971.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T14:00+00:00, close=75895.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005420|-9.40|-51.33|-9.72|26919576|3.69|
|IDOL_USDT|0.030666|-7.90|75.02|-8.22|15777405|8.48|
|ONE_USDT|0.001906|-6.41|62.32|-6.73|23269693|0.53|
|TIA_USDT|0.421600|-4.52|-13.97|-4.84|7191174|2.37|
|WLD_USDT|0.326500|-2.71|-19.26|-3.03|25184802|3.06|
|AAVE_USDT|129.250000|-2.25|-4.61|-2.57|9700531|1.55|
|ENA_USDT|0.154970|-2.02|-20.12|-2.34|29732202|0.65|
|LINK_USDT|10.733000|-1.02|-7.24|-1.34|61919893|0.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.250000|128.470000|129.250000|1.00|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.005420|0.005312|0.005420|0.46|N|Y/N|N/N|Y|N|
|ENA_USDT|0.154970|0.152750|0.154970|0.81|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.030666|0.028891|0.030621|0.64|N|Y/Y|N/N|Y|N|
|LINK_USDT|10.733000|10.691000|10.733000|0.96|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001906|0.001820|0.001908|1.54|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.421600|0.419200|0.421500|0.75|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.326500|0.323500|0.326500|1.29|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T14:45:02+00:00, last15m_closed_end=2026-11-08T14:45+00:00, prior8high=131.400000, depth_time=2026-11-08T14:45:16+00:00, book20_bid_proxy_usdt=313082, book20_ask_proxy_usdt=501663, funding_indicative=0.000071, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=9700531. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T14:45:02+00:00, last15m_closed_end=2026-11-08T14:45+00:00, prior8high=0.005562, depth_time=2026-11-08T14:45:07+00:00, book20_bid_proxy_usdt=35502, book20_ask_proxy_usdt=57385, funding_indicative=0.000050, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.40%, turnover=26919576. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T14:45:02+00:00, last15m_closed_end=2026-11-08T14:45+00:00, prior8high=0.155690, depth_time=2026-11-08T14:45:22+00:00, book20_bid_proxy_usdt=376904, book20_ask_proxy_usdt=218447, funding_indicative=-0.000093, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.02%, turnover=29732202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T14:45:02+00:00, last15m_closed_end=2026-11-08T14:45+00:00, prior8high=0.031239, depth_time=2026-11-08T14:45:10+00:00, book20_bid_proxy_usdt=5972, book20_ask_proxy_usdt=5230, funding_indicative=0.000997, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.90%, turnover=15777405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T14:45:02+00:00, last15m_closed_end=2026-11-08T14:45+00:00, prior8high=10.788000, depth_time=2026-11-08T14:45:21+00:00, book20_bid_proxy_usdt=335633, book20_ask_proxy_usdt=456716, funding_indicative=0.000007, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.02%, turnover=61919893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T14:45:02+00:00, last15m_closed_end=2026-11-08T14:45+00:00, prior8high=0.001923, depth_time=2026-11-08T14:45:12+00:00, book20_bid_proxy_usdt=12928, book20_ask_proxy_usdt=14410, funding_indicative=-0.000819, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.41%, turnover=23269693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T14:45:02+00:00, last15m_closed_end=2026-11-08T14:45+00:00, prior8high=0.425000, depth_time=2026-11-08T14:45:14+00:00, book20_bid_proxy_usdt=213535, book20_ask_proxy_usdt=364577, funding_indicative=0.000000, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.52%, turnover=7191174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T14:45:02+00:00, last15m_closed_end=2026-11-08T14:45+00:00, prior8high=0.328300, depth_time=2026-11-08T14:45:16+00:00, book20_bid_proxy_usdt=3563311, book20_ask_proxy_usdt=3843164, funding_indicative=-0.000059, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.71%, turnover=25184802. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
