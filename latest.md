# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T00:15:20Z**
- feed_generated_utc: 2026-10-26T00:15:22+00:00
- source_sha256: `6932d93d969e95757becf1579335bca17a2c9346a6c3292f266fde4b04d29e42`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T00:15+00:00, close=80071.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.006233|-10.59|238.19|-9.93|10020260|1.61|
|T_USDT|0.005001|-7.09|6.35|-6.43|8667244|2.00|
|IRYS_USDT|0.036620|-4.73|200.16|-4.07|19898911|2.73|
|PEPE_USDT|0.000004|-2.32|11.39|-1.66|75083207|0.23|
|XMR_USDT|594.000000|-2.18|1.97|-1.52|6598391|0.67|
|BTW_USDT|1.630500|-1.71|-29.27|-1.05|12526017|1.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.630500|1.633300|1.630600|4.14|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.036620|0.036300|0.036580|3.60|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.006233|0.006069|0.006233|2.15|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.53|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.005001|0.005155|0.005001|6.07|Y|Y/Y|N/N|Y|N|
|XMR_USDT|594.000000|589.580000|594.000000|0.70|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T00:15:01+00:00, last15m_closed_end=2026-10-26T00:15+00:00, prior8high=1.660100, depth_time=2026-10-26T00:15:19+00:00, book20_bid_proxy_usdt=16604, book20_ask_proxy_usdt=16629, funding_indicative=-0.007084, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=12526017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T00:15:01+00:00, last15m_closed_end=2026-10-26T00:15+00:00, prior8high=0.039720, depth_time=2026-10-26T00:15:12+00:00, book20_bid_proxy_usdt=36941, book20_ask_proxy_usdt=27815, funding_indicative=-0.000391, next_funding_utc=2026-10-26T01:00:00+00:00, funding_cycle_h=1, 24h_change=-4.73%, turnover=19898911. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T00:15:01+00:00, last15m_closed_end=2026-10-26T00:15+00:00, prior8high=0.006991, depth_time=2026-10-26T00:15:07+00:00, book20_bid_proxy_usdt=22371, book20_ask_proxy_usdt=18387, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.59%, turnover=10020260. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T00:15:01+00:00, last15m_closed_end=2026-10-26T00:15+00:00, prior8high=0.000004, depth_time=2026-10-26T00:15:14+00:00, book20_bid_proxy_usdt=64655, book20_ask_proxy_usdt=39172, funding_indicative=0.000066, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=75083207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T00:15:01+00:00, last15m_closed_end=2026-10-26T00:15+00:00, prior8high=0.005411, depth_time=2026-10-26T00:15:10+00:00, book20_bid_proxy_usdt=57184, book20_ask_proxy_usdt=99964, funding_indicative=-0.005300, next_funding_utc=2026-10-26T01:00:00+00:00, funding_cycle_h=1, 24h_change=-7.09%, turnover=8667244. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T00:15:01+00:00, last15m_closed_end=2026-10-26T00:15+00:00, prior8high=598.500000, depth_time=2026-10-26T00:15:14+00:00, book20_bid_proxy_usdt=76909, book20_ask_proxy_usdt=11013, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=6598391. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
