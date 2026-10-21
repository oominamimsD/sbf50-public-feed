# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T04:45:25Z**
- feed_generated_utc: 2026-10-21T04:45:27+00:00
- source_sha256: `871333edcdbcfb2cecd8b6693016d936212a38c25413a2f277eb7320b44d7893`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T04:45+00:00, close=82742.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.184880|-14.31|4.22|-14.50|10753072|1.62|
|BR_USDT|0.588190|-9.60|35.83|-9.79|34989142|1.02|
|XMR_USDT|578.690000|-6.69|9.61|-6.88|20863529|0.17|
|Q_USDT|0.115310|-6.06|180.37|-6.25|5062793|0.69|
|AGT_USDT|0.061230|-5.25|278.50|-5.44|6895286|6.52|
|PHA_USDT|0.056800|-1.76|3.21|-1.95|8387413|1.76|
|TIA_USDT|0.612400|-1.65|6.08|-1.84|48297761|1.63|
|SILVER_USDT|57.440000|-0.88|-3.28|-1.07|230635484|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061230|0.060783|0.061230|0.43|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.184880|0.185380|0.184880|2.54|Y|Y/Y|Y/N|N|N|
|BR_USDT|0.588190|0.589660|0.587790|2.70|Y|Y/Y|N/N|N|N|
|PHA_USDT|0.056800|0.056320|0.056800|1.16|N|Y/Y|N/N|N|N|
|Q_USDT|0.115310|0.115264|0.115359|1.54|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.440000|57.440000|57.430000|1.09|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.612400|0.608800|0.612400|0.71|N|Y/Y|Y/Y|N|N|
|XMR_USDT|578.690000|571.180000|578.690000|0.65|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T04:45:01+00:00, last15m_closed_end=2026-10-21T04:45+00:00, prior8high=0.064193, depth_time=2026-10-21T04:45:14+00:00, book20_bid_proxy_usdt=3483, book20_ask_proxy_usdt=6924, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.25%, turnover=6895286. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T04:45:01+00:00, last15m_closed_end=2026-10-21T04:45+00:00, prior8high=0.188200, depth_time=2026-10-21T04:45:07+00:00, book20_bid_proxy_usdt=21672, book20_ask_proxy_usdt=28266, funding_indicative=-0.000039, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-14.31%, turnover=10753072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T04:45:01+00:00, last15m_closed_end=2026-10-21T04:45+00:00, prior8high=0.640830, depth_time=2026-10-21T04:45:10+00:00, book20_bid_proxy_usdt=2348, book20_ask_proxy_usdt=1664, funding_indicative=0.000043, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.60%, turnover=34989142. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T04:45:01+00:00, last15m_closed_end=2026-10-21T04:45+00:00, prior8high=0.058840, depth_time=2026-10-21T04:45:19+00:00, book20_bid_proxy_usdt=53724, book20_ask_proxy_usdt=75575, funding_indicative=0.000023, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.76%, turnover=8387413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T04:45:01+00:00, last15m_closed_end=2026-10-21T04:45+00:00, prior8high=0.120677, depth_time=2026-10-21T04:45:14+00:00, book20_bid_proxy_usdt=13902, book20_ask_proxy_usdt=17698, funding_indicative=-0.000214, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.06%, turnover=5062793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T04:45:01+00:00, last15m_closed_end=2026-10-21T04:45+00:00, prior8high=57.720000, depth_time=2026-10-21T04:45:22+00:00, book20_bid_proxy_usdt=44947623, book20_ask_proxy_usdt=30618527, funding_indicative=0.000021, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=230635484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T04:45:01+00:00, last15m_closed_end=2026-10-21T04:45+00:00, prior8high=0.621800, depth_time=2026-10-21T04:45:22+00:00, book20_bid_proxy_usdt=181814, book20_ask_proxy_usdt=220435, funding_indicative=-0.000070, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.65%, turnover=48297761. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T04:45:01+00:00, last15m_closed_end=2026-10-21T04:45+00:00, prior8high=580.750000, depth_time=2026-10-21T04:45:11+00:00, book20_bid_proxy_usdt=23353, book20_ask_proxy_usdt=12351, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.69%, turnover=20863529. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
