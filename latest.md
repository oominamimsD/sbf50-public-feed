# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T11:00:26Z**
- feed_generated_utc: 2026-10-26T11:00:29+00:00
- source_sha256: `ff94858fe4650cb3b6734bdb51808ee8ee670e86ac244e6e53c168a58b27dd0e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T11:00+00:00, close=80339.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T11:00+00:00, close=80339.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.028260|-26.48|131.63|-26.15|12188778|3.53|
|CAP_USDT|0.078290|-25.83|17.72|-25.50|7152706|5.12|
|APR_USDT|0.034160|-17.30|25.40|-16.97|8348956|5.86|
|BTW_USDT|1.499900|-9.58|-34.93|-9.25|11277534|2.00|
|WLD_USDT|0.439400|-3.76|-7.74|-3.43|61331136|4.55|
|LIT_USDT|3.083500|-2.98|5.22|-2.65|5606451|0.32|
|XMR_USDT|589.230000|-2.96|1.15|-2.63|5982741|1.70|
|DOT_USDT|1.020100|-1.83|-4.61|-1.50|10071180|0.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034160|0.033760|0.034150|0.34|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.499900|1.480300|1.499900|1.00|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.078290|0.074320|0.078290|0.54|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.020100|1.015900|1.020100|0.80|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.028260|0.028610|0.028350|1.21|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.083500|3.066900|3.083500|0.24|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.439400|0.437300|0.439600|0.56|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|589.230000|588.070000|589.230000|0.55|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T11:00:03+00:00, last15m_closed_end=2026-10-26T11:00+00:00, prior8high=0.038620, depth_time=2026-10-26T11:00:13+00:00, book20_bid_proxy_usdt=44190, book20_ask_proxy_usdt=79353, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.30%, turnover=8348956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T10:59:59+00:00, last15m_closed_end=2026-10-26T11:00+00:00, prior8high=1.532000, depth_time=2026-10-26T11:00:16+00:00, book20_bid_proxy_usdt=10812, book20_ask_proxy_usdt=17298, funding_indicative=-0.012480, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.58%, turnover=11277534. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T11:00:03+00:00, last15m_closed_end=2026-10-26T11:00+00:00, prior8high=0.087050, depth_time=2026-10-26T11:00:11+00:00, book20_bid_proxy_usdt=60655, book20_ask_proxy_usdt=67698, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-25.83%, turnover=7152706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T10:59:59+00:00, last15m_closed_end=2026-10-26T11:00+00:00, prior8high=1.025400, depth_time=2026-10-26T11:00:25+00:00, book20_bid_proxy_usdt=428529, book20_ask_proxy_usdt=191359, funding_indicative=-0.000114, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=10071180. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T11:00:03+00:00, last15m_closed_end=2026-10-26T11:00+00:00, prior8high=0.029970, depth_time=2026-10-26T11:00:08+00:00, book20_bid_proxy_usdt=86487, book20_ask_proxy_usdt=93492, funding_indicative=-0.000679, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=1, 24h_change=-26.48%, turnover=12188778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T11:00:00+00:00, last15m_closed_end=2026-10-26T11:00+00:00, prior8high=3.121700, depth_time=2026-10-26T11:00:20+00:00, book20_bid_proxy_usdt=16182, book20_ask_proxy_usdt=17047, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.98%, turnover=5606451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T11:00:03+00:00, last15m_closed_end=2026-10-26T11:00+00:00, prior8high=0.444800, depth_time=2026-10-26T11:00:18+00:00, book20_bid_proxy_usdt=2693177, book20_ask_proxy_usdt=2620273, funding_indicative=-0.000141, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.76%, turnover=61331136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T10:59:59+00:00, last15m_closed_end=2026-10-26T11:00+00:00, prior8high=592.000000, depth_time=2026-10-26T11:00:20+00:00, book20_bid_proxy_usdt=15788, book20_ask_proxy_usdt=10496, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=5982741. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
