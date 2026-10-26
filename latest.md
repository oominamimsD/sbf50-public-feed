# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T09:45:23Z**
- feed_generated_utc: 2026-10-26T09:45:26+00:00
- source_sha256: `ff38c842bde538178daca4534bea7c424526501e6c4d19c38fc6b9fa06461fc5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T09:45+00:00, close=80514.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T09:00+00:00, close=80203.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.029180|-24.08|139.18|-23.98|12996215|3.43|
|CAP_USDT|0.082880|-22.88|24.63|-22.78|7383802|4.83|
|APR_USDT|0.035400|-14.30|29.95|-14.20|8970216|5.65|
|BTW_USDT|1.494900|-9.88|-35.15|-9.78|11057852|1.34|
|WLD_USDT|0.442200|-3.15|-7.15|-3.05|66543394|2.26|
|LIT_USDT|3.080500|-3.08|5.12|-2.98|5736249|0.33|
|XMR_USDT|589.250000|-2.96|1.15|-2.86|6045680|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.035400|0.034280|0.035400|1.54|N|N/Y|N/N|Y|N|
|BTW_USDT|1.494900|1.440500|1.494900|1.02|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.082880|0.074320|0.082780|1.34|N|Y/Y|N/N|Y|N|
|IRYS_USDT|0.029180|0.028610|0.029180|1.17|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.080500|3.052200|3.080500|1.30|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.442200|0.434300|0.442200|1.36|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|589.250000|583.530000|589.250000|1.44|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T09:45:01+00:00, last15m_closed_end=2026-10-26T09:45+00:00, prior8high=0.039060, depth_time=2026-10-26T09:45:12+00:00, book20_bid_proxy_usdt=34149, book20_ask_proxy_usdt=62683, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.30%, turnover=8970216. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T09:45:01+00:00, last15m_closed_end=2026-10-26T09:45+00:00, prior8high=1.613000, depth_time=2026-10-26T09:45:15+00:00, book20_bid_proxy_usdt=11052, book20_ask_proxy_usdt=9121, funding_indicative=-0.009208, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.88%, turnover=11057852. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T09:45:01+00:00, last15m_closed_end=2026-10-26T09:45+00:00, prior8high=0.092720, depth_time=2026-10-26T09:45:10+00:00, book20_bid_proxy_usdt=54245, book20_ask_proxy_usdt=55491, funding_indicative=0.000065, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-22.88%, turnover=7383802. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T09:45:01+00:00, last15m_closed_end=2026-10-26T09:45+00:00, prior8high=0.031910, depth_time=2026-10-26T09:45:07+00:00, book20_bid_proxy_usdt=69117, book20_ask_proxy_usdt=84517, funding_indicative=-0.000299, next_funding_utc=2026-10-26T10:00:00+00:00, funding_cycle_h=1, 24h_change=-24.08%, turnover=12996215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T09:45:01+00:00, last15m_closed_end=2026-10-26T09:45+00:00, prior8high=3.121700, depth_time=2026-10-26T09:45:19+00:00, book20_bid_proxy_usdt=26846, book20_ask_proxy_usdt=21802, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.08%, turnover=5736249. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T09:45:01+00:00, last15m_closed_end=2026-10-26T09:45+00:00, prior8high=0.444800, depth_time=2026-10-26T09:45:17+00:00, book20_bid_proxy_usdt=2467472, book20_ask_proxy_usdt=1915719, funding_indicative=-0.000112, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.15%, turnover=66543394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T09:45:01+00:00, last15m_closed_end=2026-10-26T09:45+00:00, prior8high=592.000000, depth_time=2026-10-26T09:45:22+00:00, book20_bid_proxy_usdt=11010, book20_ask_proxy_usdt=3278, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.96%, turnover=6045680. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
