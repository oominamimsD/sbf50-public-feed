# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T12:30:24Z**
- feed_generated_utc: 2026-10-21T12:30:27+00:00
- source_sha256: `90a2109a7fb9483bbf28e8a41b02b50e0526e0f82733b3a944d05510abadc4b9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1206; contracts: 1198; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T12:30+00:00, close=83587.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.045696|-29.29|182.47|-30.50|6656015|4.60|
|BAT_USDT|0.181750|-15.76|2.46|-16.97|10652977|2.75|
|BTW_USDT|1.583900|-14.36|-18.87|-15.57|24753561|3.16|
|BR_USDT|0.606900|-6.72|40.15|-7.93|21005875|3.46|
|AKE_USDT|0.030311|-2.50|20.91|-3.71|8329743|6.93|
|Q_USDT|0.120478|-1.85|192.94|-3.06|5003525|3.32|
|SILVER_USDT|57.540000|-0.70|-3.11|-1.91|232439208|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.045696|0.044727|0.045729|0.74|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.030311|0.028134|0.030311|1.55|N|Y/N|Y/N|N|N|
|BAT_USDT|0.181750|0.180140|0.181710|0.63|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.606900|0.572580|0.606900|0.57|N|Y/Y|N/N|N|N|
|BTW_USDT|1.583900|1.612300|1.585200|2.61|Y|Y/Y|Y/Y|N|Y|
|Q_USDT|0.120478|0.117302|0.120478|0.61|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.540000|57.290000|57.550000|0.95|N|N/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T12:30:01+00:00, last15m_closed_end=2026-10-21T12:30+00:00, prior8high=0.050848, depth_time=2026-10-21T12:30:07+00:00, book20_bid_proxy_usdt=6899, book20_ask_proxy_usdt=4724, funding_indicative=0.000047, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-29.29%, turnover=6656015. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T12:30:01+00:00, last15m_closed_end=2026-10-21T12:30+00:00, prior8high=0.037005, depth_time=2026-10-21T12:30:19+00:00, book20_bid_proxy_usdt=12511, book20_ask_proxy_usdt=14456, funding_indicative=0.000050, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.50%, turnover=8329743. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T12:30:01+00:00, last15m_closed_end=2026-10-21T12:30+00:00, prior8high=0.183270, depth_time=2026-10-21T12:30:11+00:00, book20_bid_proxy_usdt=24449, book20_ask_proxy_usdt=85134, funding_indicative=-0.000132, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.76%, turnover=10652977. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T12:30:01+00:00, last15m_closed_end=2026-10-21T12:30+00:00, prior8high=0.611980, depth_time=2026-10-21T12:30:13+00:00, book20_bid_proxy_usdt=2628, book20_ask_proxy_usdt=4199, funding_indicative=-0.000083, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.72%, turnover=21005875. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T12:30:01+00:00, last15m_closed_end=2026-10-21T12:30+00:00, prior8high=1.787000, depth_time=2026-10-21T12:30:13+00:00, book20_bid_proxy_usdt=9433, book20_ask_proxy_usdt=9134, funding_indicative=-0.004894, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.36%, turnover=24753561. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T12:30:01+00:00, last15m_closed_end=2026-10-21T12:30+00:00, prior8high=0.120678, depth_time=2026-10-21T12:30:21+00:00, book20_bid_proxy_usdt=20935, book20_ask_proxy_usdt=15248, funding_indicative=0.000002, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.85%, turnover=5003525. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T12:30:01+00:00, last15m_closed_end=2026-10-21T12:30+00:00, prior8high=57.860000, depth_time=2026-10-21T12:30:22+00:00, book20_bid_proxy_usdt=31757211, book20_ask_proxy_usdt=38635096, funding_indicative=0.000030, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.70%, turnover=232439208. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
