# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T13:45:31Z**
- feed_generated_utc: 2026-10-29T13:45:33+00:00
- source_sha256: `39b2d5c8aaa31b89220cc5b9543081ccaefad572438877cc8f9b153d13d054ed`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T13:45+00:00, close=79930.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T13:00+00:00, close=80026.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.042320|-32.03|-63.57|-31.29|33884752|4.73|
|JASMY_USDT|0.003869|-8.68|-20.65|-7.94|7745243|2.58|
|DASH_USDT|50.290000|-5.18|-5.59|-4.44|14718873|1.99|
|BCH_USDT|278.470000|-4.93|-3.86|-4.19|5042628|3.59|
|NEAR_USDT|4.434000|-4.21|-17.66|-3.47|109136003|2.25|
|WLD_USDT|0.419700|-3.02|-26.83|-2.28|80259307|2.38|
|SILVER_USDT|52.170000|-2.79|-9.52|-2.05|545279312|1.92|
|HBAR_USDT|0.074160|-2.30|-13.70|-1.56|15539453|1.35|
|XRP_USDT|1.286000|-1.92|-6.83|-1.18|290892977|0.78|
|SEI_USDT|0.051900|-1.79|-17.68|-1.05|5161173|1.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|278.470000|278.330000|278.470000|3.66|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|50.290000|49.890000|50.290000|1.67|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.074160|0.073220|0.074160|1.06|N|Y/Y|Y/Y|Y|N|
|JASMY_USDT|0.003869|0.003809|0.003869|1.25|N|N/Y|Y/Y|Y|N|
|NEAR_USDT|4.434000|4.381000|4.434000|2.43|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.042320|0.039240|0.042320|0.60|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.051900|0.051480|0.051900|0.69|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.170000|52.350000|52.170000|20.49|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.419700|0.416800|0.419700|1.77|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.286000|1.285700|1.285900|2.17|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-29T13:44:59+00:00, last15m_closed_end=2026-10-29T13:45+00:00, prior8high=280.390000, depth_time=2026-10-29T13:45:12+00:00, book20_bid_proxy_usdt=54829, book20_ask_proxy_usdt=45311, funding_indicative=0.000040, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.93%, turnover=5042628. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-29T13:44:59+00:00, last15m_closed_end=2026-10-29T13:45+00:00, prior8high=50.620000, depth_time=2026-10-29T13:45:11+00:00, book20_bid_proxy_usdt=451468, book20_ask_proxy_usdt=553414, funding_indicative=0.000031, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.18%, turnover=14718873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T13:44:59+00:00, last15m_closed_end=2026-10-29T13:45+00:00, prior8high=0.074510, depth_time=2026-10-29T13:45:23+00:00, book20_bid_proxy_usdt=986911, book20_ask_proxy_usdt=895282, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.30%, turnover=15539453. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JASMY_USDT: quote_utc=2026-10-29T13:44:59+00:00, last15m_closed_end=2026-10-29T13:45+00:00, prior8high=0.003998, depth_time=2026-10-29T13:45:10+00:00, book20_bid_proxy_usdt=129143, book20_ask_proxy_usdt=122980, funding_indicative=-0.000334, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.68%, turnover=7745243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T13:44:59+00:00, last15m_closed_end=2026-10-29T13:45+00:00, prior8high=4.511000, depth_time=2026-10-29T13:45:17+00:00, book20_bid_proxy_usdt=569485, book20_ask_proxy_usdt=144771, funding_indicative=0.000079, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.21%, turnover=109136003. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T13:44:59+00:00, last15m_closed_end=2026-10-29T13:45+00:00, prior8high=0.042860, depth_time=2026-10-29T13:45:06+00:00, book20_bid_proxy_usdt=32706, book20_ask_proxy_usdt=51383, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-32.03%, turnover=33884752. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-29T13:44:59+00:00, last15m_closed_end=2026-10-29T13:45+00:00, prior8high=0.052330, depth_time=2026-10-29T13:45:30+00:00, book20_bid_proxy_usdt=188832, book20_ask_proxy_usdt=199807, funding_indicative=0.000095, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=5161173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T13:44:59+00:00, last15m_closed_end=2026-10-29T13:45+00:00, prior8high=52.940000, depth_time=2026-10-29T13:45:22+00:00, book20_bid_proxy_usdt=40630082, book20_ask_proxy_usdt=41881546, funding_indicative=0.000092, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=545279312. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T13:44:59+00:00, last15m_closed_end=2026-10-29T13:45+00:00, prior8high=0.424500, depth_time=2026-10-29T13:45:20+00:00, book20_bid_proxy_usdt=2337563, book20_ask_proxy_usdt=3366765, funding_indicative=0.000045, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.02%, turnover=80259307. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-10-29T13:44:59+00:00, last15m_closed_end=2026-10-29T13:45+00:00, prior8high=1.294800, depth_time=2026-10-29T13:45:28+00:00, book20_bid_proxy_usdt=3104052, book20_ask_proxy_usdt=2797690, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=290892977. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
