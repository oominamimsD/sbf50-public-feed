# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T02:15:23Z**
- feed_generated_utc: 2026-11-08T02:15:24+00:00
- source_sha256: `f0a5bf092d9ea4754808cfabfb1640e256be321f6a3d8e8a5bca3ba43008f758`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T02:15+00:00, close=75656, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T02:00+00:00, close=75713.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001986|-2.48|69.15|-2.39|26580676|0.50|
|QNT_USDT|194.150000|-2.36|-3.43|-2.27|42884108|1.03|
|ENA_USDT|0.155530|-1.67|-19.83|-1.58|27719702|0.64|
|WLD_USDT|0.330500|-1.51|-18.27|-1.42|25373177|3.03|
|ZEC_USDT|1241.930000|-1.26|-3.31|-1.17|1789999755|0.08|
|TIA_USDT|0.436400|-1.17|-10.95|-1.08|6930707|2.29|
|PEPE_USDT|0.000005|-1.16|-2.85|-1.07|38556630|0.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.155530|0.155520|0.155530|1.55|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001986|0.001939|0.001986|0.64|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|2.02|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.150000|193.700000|194.140000|0.57|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.436400|0.435700|0.436400|0.43|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.330500|0.330100|0.330500|0.46|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1241.930000|1246.710000|1241.930000|1.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-08T02:15:00+00:00, last15m_closed_end=2026-11-08T02:15+00:00, prior8high=0.158870, depth_time=2026-11-08T02:15:09+00:00, book20_bid_proxy_usdt=253050, book20_ask_proxy_usdt=283041, funding_indicative=-0.000081, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.67%, turnover=27719702. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T02:15:00+00:00, last15m_closed_end=2026-11-08T02:15+00:00, prior8high=0.002162, depth_time=2026-11-08T02:15:06+00:00, book20_bid_proxy_usdt=13127, book20_ask_proxy_usdt=13038, funding_indicative=-0.000071, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.48%, turnover=26580676. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-08T02:15:00+00:00, last15m_closed_end=2026-11-08T02:15+00:00, prior8high=0.000005, depth_time=2026-11-08T02:15:22+00:00, book20_bid_proxy_usdt=35852, book20_ask_proxy_usdt=55006, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=38556630. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T02:15:00+00:00, last15m_closed_end=2026-11-08T02:15+00:00, prior8high=196.770000, depth_time=2026-11-08T02:15:08+00:00, book20_bid_proxy_usdt=75406, book20_ask_proxy_usdt=70838, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.36%, turnover=42884108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T02:15:00+00:00, last15m_closed_end=2026-11-08T02:15+00:00, prior8high=0.442000, depth_time=2026-11-08T02:15:19+00:00, book20_bid_proxy_usdt=455138, book20_ask_proxy_usdt=269419, funding_indicative=0.000008, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=6930707. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T02:15:00+00:00, last15m_closed_end=2026-11-08T02:15+00:00, prior8high=0.335400, depth_time=2026-11-08T02:15:13+00:00, book20_bid_proxy_usdt=3939486, book20_ask_proxy_usdt=3343923, funding_indicative=-0.000111, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=25373177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T02:15:00+00:00, last15m_closed_end=2026-11-08T02:15+00:00, prior8high=1260.660000, depth_time=2026-11-08T02:15:17+00:00, book20_bid_proxy_usdt=733917, book20_ask_proxy_usdt=333079, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=1789999755. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
