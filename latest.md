# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T09:00:26Z**
- feed_generated_utc: 2026-10-21T09:00:29+00:00
- source_sha256: `8971a69dfbec219435eb7b580be1902b9bf080faf1038b239baa8726deff70d4`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T09:00+00:00, close=83217, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T09:00+00:00, close=83217, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.044825|-29.60|177.09|-30.37|6641666|2.46|
|BAT_USDT|0.184170|-15.67|3.82|-16.44|10814823|1.63|
|BR_USDT|0.601600|-10.46|38.93|-11.23|26260405|2.65|
|XMR_USDT|585.890000|-5.58|10.98|-6.35|20438664|0.51|
|INJ_USDT|8.742000|-1.84|11.54|-2.61|64794582|1.14|
|SILVER_USDT|57.390000|-0.96|-3.36|-1.73|213174666|1.74|
|XAUT_USDT|4120.060000|-0.46|-0.88|-1.23|157678748|0.07|
|XAU_USDT|4127.520000|-0.28|-0.91|-1.05|378905557|0.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.044825|0.038698|0.044822|1.07|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.184170|0.181950|0.184170|1.03|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.601600|0.575440|0.601600|0.97|N|Y/Y|N/N|N|N|
|INJ_USDT|8.742000|8.717000|8.742000|0.49|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.390000|57.210000|57.400000|1.00|N|Y/Y|N/N|N|N|
|XAUT_USDT|4120.060000|4111.940000|4120.060000|1.11|N|Y/Y|Y/Y|N|N|
|XAU_USDT|4127.520000|4118.760000|4127.640000|0.67|N|Y/Y|Y/Y|N|N|
|XMR_USDT|585.890000|578.650000|586.030000|0.99|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T09:00:02+00:00, last15m_closed_end=2026-10-21T09:00+00:00, prior8high=0.046764, depth_time=2026-10-21T09:00:08+00:00, book20_bid_proxy_usdt=13913, book20_ask_proxy_usdt=15993, funding_indicative=0.000047, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-29.60%, turnover=6641666. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T09:00:02+00:00, last15m_closed_end=2026-10-21T09:00+00:00, prior8high=0.190510, depth_time=2026-10-21T09:00:10+00:00, book20_bid_proxy_usdt=35178, book20_ask_proxy_usdt=22904, funding_indicative=-0.000114, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.67%, turnover=10814823. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T09:00:02+00:00, last15m_closed_end=2026-10-21T09:00+00:00, prior8high=0.627970, depth_time=2026-10-21T09:00:12+00:00, book20_bid_proxy_usdt=3179, book20_ask_proxy_usdt=2442, funding_indicative=0.000036, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.46%, turnover=26260405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T09:00:02+00:00, last15m_closed_end=2026-10-21T09:00+00:00, prior8high=8.854000, depth_time=2026-10-21T09:00:18+00:00, book20_bid_proxy_usdt=208025, book20_ask_proxy_usdt=227411, funding_indicative=0.000108, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=64794582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T09:00:02+00:00, last15m_closed_end=2026-10-21T09:00+00:00, prior8high=57.550000, depth_time=2026-10-21T09:00:19+00:00, book20_bid_proxy_usdt=29860312, book20_ask_proxy_usdt=32298288, funding_indicative=0.000033, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=213174666. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-21T09:00:02+00:00, last15m_closed_end=2026-10-21T09:00+00:00, prior8high=4125.440000, depth_time=2026-10-21T09:00:22+00:00, book20_bid_proxy_usdt=188170, book20_ask_proxy_usdt=202230, funding_indicative=0.000038, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.46%, turnover=157678748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-21T09:00:02+00:00, last15m_closed_end=2026-10-21T09:00+00:00, prior8high=4132.430000, depth_time=2026-10-21T09:00:25+00:00, book20_bid_proxy_usdt=191195, book20_ask_proxy_usdt=1072741, funding_indicative=0.000067, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.28%, turnover=378905557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T09:00:02+00:00, last15m_closed_end=2026-10-21T09:00+00:00, prior8high=590.720000, depth_time=2026-10-21T09:00:13+00:00, book20_bid_proxy_usdt=13868, book20_ask_proxy_usdt=34593, funding_indicative=0.000100, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.58%, turnover=20438664. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
