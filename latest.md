# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T05:45:29Z**
- feed_generated_utc: 2026-10-21T05:45:31+00:00
- source_sha256: `85461119915d4a7dd93b56d682d887351187ca41ab5c2f0eef291031c7d4c7c5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T05:45+00:00, close=82688, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T05:00+00:00, close=82776.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.183550|-14.93|3.47|-15.05|10869173|0.55|
|BR_USDT|0.587500|-9.70|35.67|-9.82|34605431|3.06|
|XMR_USDT|579.010000|-6.64|9.67|-6.76|21207053|0.17|
|AGT_USDT|0.061149|-5.38|277.99|-5.50|6632237|1.64|
|Q_USDT|0.117404|-4.35|185.46|-4.47|5095396|0.77|
|PHA_USDT|0.056400|-2.45|2.48|-2.57|7640332|3.54|
|FILECOIN_USDT|1.025000|-1.44|-9.54|-1.56|9863795|0.98|
|TIA_USDT|0.614500|-1.31|6.44|-1.43|47666378|1.63|
|SEI_USDT|0.060860|-1.24|-2.42|-1.36|6258144|1.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061149|0.060783|0.061149|0.51|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.183550|0.183450|0.183550|0.94|N|Y/Y|Y/N|N|N|
|BR_USDT|0.587500|0.580080|0.587530|2.04|N|Y/Y|N/N|N|N|
|FILECOIN_USDT|1.025000|1.027700|1.025000|1.39|Y|N/N|Y/Y|N|N|
|PHA_USDT|0.056400|0.055950|0.056400|0.70|N|Y/Y|N/N|N|N|
|Q_USDT|0.117404|0.114853|0.117404|1.10|N|Y/Y|N/N|N|N|
|SEI_USDT|0.060860|0.060960|0.060860|0.49|N|Y/N|N/Y|N|N|
|TIA_USDT|0.614500|0.609200|0.614500|1.37|N|Y/Y|Y/Y|N|N|
|XMR_USDT|579.010000|571.180000|579.010000|0.52|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T05:45:00+00:00, last15m_closed_end=2026-10-21T05:45+00:00, prior8high=0.063888, depth_time=2026-10-21T05:45:15+00:00, book20_bid_proxy_usdt=25682, book20_ask_proxy_usdt=4777, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.38%, turnover=6632237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T05:45:00+00:00, last15m_closed_end=2026-10-21T05:45+00:00, prior8high=0.187530, depth_time=2026-10-21T05:45:09+00:00, book20_bid_proxy_usdt=19756, book20_ask_proxy_usdt=23797, funding_indicative=-0.000070, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-14.93%, turnover=10869173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T05:45:00+00:00, last15m_closed_end=2026-10-21T05:45+00:00, prior8high=0.623210, depth_time=2026-10-21T05:45:11+00:00, book20_bid_proxy_usdt=2260, book20_ask_proxy_usdt=2274, funding_indicative=0.000050, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.70%, turnover=34605431. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-21T05:45:00+00:00, last15m_closed_end=2026-10-21T05:45+00:00, prior8high=1.039400, depth_time=2026-10-21T05:45:23+00:00, book20_bid_proxy_usdt=408083, book20_ask_proxy_usdt=1066748, funding_indicative=-0.000025, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=9863795. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T05:45:00+00:00, last15m_closed_end=2026-10-21T05:45+00:00, prior8high=0.058490, depth_time=2026-10-21T05:45:20+00:00, book20_bid_proxy_usdt=91314, book20_ask_proxy_usdt=62641, funding_indicative=-0.000034, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.45%, turnover=7640332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T05:45:00+00:00, last15m_closed_end=2026-10-21T05:45+00:00, prior8high=0.125002, depth_time=2026-10-21T05:45:18+00:00, book20_bid_proxy_usdt=16961, book20_ask_proxy_usdt=17288, funding_indicative=-0.000094, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.35%, turnover=5095396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-21T05:45:00+00:00, last15m_closed_end=2026-10-21T05:45+00:00, prior8high=0.061440, depth_time=2026-10-21T05:45:28+00:00, book20_bid_proxy_usdt=273961, book20_ask_proxy_usdt=269556, funding_indicative=-0.000060, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.24%, turnover=6258144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T05:45:00+00:00, last15m_closed_end=2026-10-21T05:45+00:00, prior8high=0.621800, depth_time=2026-10-21T05:45:23+00:00, book20_bid_proxy_usdt=189656, book20_ask_proxy_usdt=206372, funding_indicative=-0.000084, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=47666378. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T05:45:00+00:00, last15m_closed_end=2026-10-21T05:45+00:00, prior8high=581.680000, depth_time=2026-10-21T05:45:12+00:00, book20_bid_proxy_usdt=14961, book20_ask_proxy_usdt=12122, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.64%, turnover=21207053. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
