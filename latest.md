# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T08:45:29Z**
- feed_generated_utc: 2026-10-21T08:45:31+00:00
- source_sha256: `8bc5427655b217972989dd6bfb1e3c0816e030549a3d9632891f617d1cf4781f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T08:45+00:00, close=83319.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.043582|-32.56|169.40|-33.48|7321052|1.83|
|BAT_USDT|0.185360|-14.09|4.49|-15.01|11220650|1.62|
|BR_USDT|0.600000|-7.78|38.56|-8.70|28580195|5.00|
|XMR_USDT|584.800000|-5.70|10.77|-6.62|21416056|2.05|
|PHA_USDT|0.057290|-0.91|4.10|-1.83|5162834|1.75|
|SILVER_USDT|57.430000|-0.89|-3.30|-1.81|214910925|1.74|
|XAU_USDT|4129.720000|-0.23|-0.86|-1.15|384286381|0.02|
|XAUT_USDT|4122.470000|-0.13|-0.82|-1.05|172221351|0.07|
|Q_USDT|0.122632|-0.10|198.17|-1.02|5881382|0.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.043582|0.038698|0.043582|3.92|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.185360|0.181950|0.185320|1.15|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.600000|0.575440|0.599300|3.24|N|Y/Y|N/N|N|N|
|PHA_USDT|0.057290|0.056570|0.057290|0.20|N|Y/Y|N/N|N|N|
|Q_USDT|0.122632|0.118451|0.122632|1.30|N|N/N|N/N|N|N|
|SILVER_USDT|57.430000|57.210000|57.430000|0.90|N|Y/Y|N/N|N|N|
|XAUT_USDT|4122.470000|4111.940000|4122.470000|0.83|N|N/Y|Y/Y|N|N|
|XAU_USDT|4129.720000|4118.760000|4129.720000|0.74|N|N/Y|Y/Y|N|N|
|XMR_USDT|584.800000|577.060000|584.690000|0.54|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T08:45:01+00:00, last15m_closed_end=2026-10-21T08:45+00:00, prior8high=0.048098, depth_time=2026-10-21T08:45:07+00:00, book20_bid_proxy_usdt=5763, book20_ask_proxy_usdt=10504, funding_indicative=0.000047, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-32.56%, turnover=7321052. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T08:45:01+00:00, last15m_closed_end=2026-10-21T08:45+00:00, prior8high=0.190510, depth_time=2026-10-21T08:45:11+00:00, book20_bid_proxy_usdt=25605, book20_ask_proxy_usdt=22275, funding_indicative=-0.000123, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-14.09%, turnover=11220650. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T08:45:01+00:00, last15m_closed_end=2026-10-21T08:45+00:00, prior8high=0.624800, depth_time=2026-10-21T08:45:12+00:00, book20_bid_proxy_usdt=1776, book20_ask_proxy_usdt=3431, funding_indicative=0.000050, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.78%, turnover=28580195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T08:45:01+00:00, last15m_closed_end=2026-10-21T08:45+00:00, prior8high=0.057670, depth_time=2026-10-21T08:45:18+00:00, book20_bid_proxy_usdt=103094, book20_ask_proxy_usdt=58382, funding_indicative=-0.000008, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.91%, turnover=5162834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T08:45:01+00:00, last15m_closed_end=2026-10-21T08:45+00:00, prior8high=0.146637, depth_time=2026-10-21T08:45:23+00:00, book20_bid_proxy_usdt=14361, book20_ask_proxy_usdt=16360, funding_indicative=0.000050, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.10%, turnover=5881382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T08:45:01+00:00, last15m_closed_end=2026-10-21T08:45+00:00, prior8high=57.550000, depth_time=2026-10-21T08:45:17+00:00, book20_bid_proxy_usdt=43318224, book20_ask_proxy_usdt=39719054, funding_indicative=0.000026, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.89%, turnover=214910925. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-21T08:45:01+00:00, last15m_closed_end=2026-10-21T08:45+00:00, prior8high=4125.440000, depth_time=2026-10-21T08:45:24+00:00, book20_bid_proxy_usdt=345375, book20_ask_proxy_usdt=132176, funding_indicative=0.000032, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.13%, turnover=172221351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-21T08:45:01+00:00, last15m_closed_end=2026-10-21T08:45+00:00, prior8high=4132.430000, depth_time=2026-10-21T08:45:20+00:00, book20_bid_proxy_usdt=596819, book20_ask_proxy_usdt=339072, funding_indicative=0.000067, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.23%, turnover=384286381. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T08:45:01+00:00, last15m_closed_end=2026-10-21T08:45+00:00, prior8high=590.720000, depth_time=2026-10-21T08:45:15+00:00, book20_bid_proxy_usdt=10327, book20_ask_proxy_usdt=18186, funding_indicative=0.000100, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.70%, turnover=21416056. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
