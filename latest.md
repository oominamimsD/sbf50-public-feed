# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T17:15:16Z**
- feed_generated_utc: 2026-10-24T17:15:18+00:00
- source_sha256: `6adac204f4b43f498c324d091d2cff725f284b19137f8481e3560638d2f978ab`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T17:15+00:00, close=80120.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-24T17:00+00:00, close=80182.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.094160|-3.58|94.06|-4.02|12008801|2.12|
|DOT_USDT|1.025400|-1.31|-8.23|-1.75|13223781|0.97|
|TIA_USDT|0.521300|-0.83|-20.77|-1.27|30527865|1.92|
|AGT_USDT|0.066540|-0.58|-7.65|-1.02|10357003|7.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066540|0.064390|0.066590|0.92|N|Y/Y|Y/N|Y|N|
|BIRB_USDT|0.094160|0.092210|0.094350|0.57|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.025400|1.022700|1.025300|1.53|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.521300|0.516000|0.521300|0.96|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-24T17:15:02+00:00, last15m_closed_end=2026-10-24T17:15+00:00, prior8high=0.071620, depth_time=2026-10-24T17:15:15+00:00, book20_bid_proxy_usdt=5441, book20_ask_proxy_usdt=10572, funding_indicative=0.000108, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.58%, turnover=10357003. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-24T17:15:03+00:00, last15m_closed_end=2026-10-24T17:15+00:00, prior8high=0.110680, depth_time=2026-10-24T17:15:08+00:00, book20_bid_proxy_usdt=13642, book20_ask_proxy_usdt=11623, funding_indicative=-0.008205, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.58%, turnover=12008801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T17:15:03+00:00, last15m_closed_end=2026-10-24T17:15+00:00, prior8high=1.049400, depth_time=2026-10-24T17:15:10+00:00, book20_bid_proxy_usdt=294835, book20_ask_proxy_usdt=243820, funding_indicative=-0.000107, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=13223781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-24T17:15:03+00:00, last15m_closed_end=2026-10-24T17:15+00:00, prior8high=0.535500, depth_time=2026-10-24T17:15:13+00:00, book20_bid_proxy_usdt=203003, book20_ask_proxy_usdt=223002, funding_indicative=0.000000, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.83%, turnover=30527865. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
