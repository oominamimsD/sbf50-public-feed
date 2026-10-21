# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T08:00:21Z**
- feed_generated_utc: 2026-10-21T08:00:23+00:00
- source_sha256: `6fe44136f7f006c6dc3e00b7deaed9754dd5bcce1e81870e8407ec84e84ffac2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.043950|-31.99|171.68|-32.63|7245428|4.10|
|BAT_USDT|0.188130|-12.80|6.06|-13.44|11161985|1.06|
|BR_USDT|0.582720|-10.44|34.57|-11.08|30480275|2.75|
|XMR_USDT|585.970000|-5.51|10.99|-6.15|21788624|0.17|
|PHA_USDT|0.057070|-1.29|3.70|-1.93|5922932|1.75|
|SILVER_USDT|57.520000|-0.74|-3.14|-1.38|224575461|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.043950|0.038698|0.043947|4.02|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.188130|0.181950|0.188190|1.44|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.582720|0.576660|0.582810|1.28|N|Y/Y|N/N|N|N|
|PHA_USDT|0.057070|0.056400|0.057070|0.36|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.520000|57.210000|57.520000|2.04|N|Y/Y|N/N|N|N|
|XMR_USDT|585.970000|576.740000|585.970000|0.55|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T07:59:59+00:00, last15m_closed_end=2026-10-21T08:00+00:00, prior8high=0.062194, depth_time=2026-10-21T08:00:07+00:00, book20_bid_proxy_usdt=10444, book20_ask_proxy_usdt=9815, funding_indicative=0.000053, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-31.99%, turnover=7245428. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T07:59:59+00:00, last15m_closed_end=2026-10-21T08:00+00:00, prior8high=0.189900, depth_time=2026-10-21T08:00:10+00:00, book20_bid_proxy_usdt=46960, book20_ask_proxy_usdt=14486, funding_indicative=-0.000139, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-12.80%, turnover=11161985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T07:59:59+00:00, last15m_closed_end=2026-10-21T08:00+00:00, prior8high=0.595260, depth_time=2026-10-21T08:00:10+00:00, book20_bid_proxy_usdt=2467, book20_ask_proxy_usdt=2842, funding_indicative=0.000050, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.44%, turnover=30480275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T07:59:59+00:00, last15m_closed_end=2026-10-21T08:00+00:00, prior8high=0.057200, depth_time=2026-10-21T08:00:12+00:00, book20_bid_proxy_usdt=72701, book20_ask_proxy_usdt=78642, funding_indicative=-0.000011, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.29%, turnover=5922932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T07:59:59+00:00, last15m_closed_end=2026-10-21T08:00+00:00, prior8high=57.540000, depth_time=2026-10-21T08:00:20+00:00, book20_bid_proxy_usdt=33911223, book20_ask_proxy_usdt=36558056, funding_indicative=0.000019, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.74%, turnover=224575461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T07:59:59+00:00, last15m_closed_end=2026-10-21T08:00+00:00, prior8high=588.220000, depth_time=2026-10-21T08:00:15+00:00, book20_bid_proxy_usdt=16776, book20_ask_proxy_usdt=45778, funding_indicative=0.000100, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.51%, turnover=21788624. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
