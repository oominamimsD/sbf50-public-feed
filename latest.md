# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T05:15:23Z**
- feed_generated_utc: 2026-10-21T05:15:25+00:00
- source_sha256: `1297f2bf9767d508da69eb9dc4ae615896fac062cc2271b047022aa301e8b394`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T05:15+00:00, close=82852.9, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T05:00+00:00, close=82776.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.184960|-14.27|4.27|-14.59|10728238|7.03|
|BR_USDT|0.581480|-10.63|34.28|-10.95|34388893|0.69|
|XMR_USDT|576.630000|-7.02|9.22|-7.34|20987540|0.17|
|AGT_USDT|0.061883|-4.24|282.53|-4.56|6593406|2.42|
|PHA_USDT|0.056890|-1.60|3.37|-1.92|7569990|5.28|
|TIA_USDT|0.614300|-1.34|6.40|-1.66|47372399|1.63|
|SILVER_USDT|57.520000|-0.74|-3.14|-1.06|230956440|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.061883|0.060783|0.061883|0.55|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.184960|0.184440|0.184910|4.61|N|Y/Y|Y/N|N|N|
|BR_USDT|0.581480|0.581680|0.581760|1.86|N|Y/Y|N/N|N|N|
|PHA_USDT|0.056890|0.056320|0.056890|1.15|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.520000|57.390000|57.520000|0.49|N|Y/Y|Y/N|N|N|
|TIA_USDT|0.614300|0.608800|0.614200|0.35|N|Y/Y|Y/Y|N|N|
|XMR_USDT|576.630000|571.180000|576.630000|0.48|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T05:15:00+00:00, last15m_closed_end=2026-10-21T05:15+00:00, prior8high=0.064103, depth_time=2026-10-21T05:15:14+00:00, book20_bid_proxy_usdt=9687, book20_ask_proxy_usdt=10034, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.24%, turnover=6593406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T05:15:00+00:00, last15m_closed_end=2026-10-21T05:15+00:00, prior8high=0.187530, depth_time=2026-10-21T05:15:07+00:00, book20_bid_proxy_usdt=41076, book20_ask_proxy_usdt=19121, funding_indicative=-0.000057, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-14.27%, turnover=10728238. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T05:15:00+00:00, last15m_closed_end=2026-10-21T05:15+00:00, prior8high=0.634770, depth_time=2026-10-21T05:15:10+00:00, book20_bid_proxy_usdt=4687, book20_ask_proxy_usdt=2489, funding_indicative=0.000050, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.63%, turnover=34388893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T05:15:00+00:00, last15m_closed_end=2026-10-21T05:15+00:00, prior8high=0.058680, depth_time=2026-10-21T05:15:16+00:00, book20_bid_proxy_usdt=90788, book20_ask_proxy_usdt=69759, funding_indicative=0.000013, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.60%, turnover=7569990. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T05:15:00+00:00, last15m_closed_end=2026-10-21T05:15+00:00, prior8high=57.720000, depth_time=2026-10-21T05:15:22+00:00, book20_bid_proxy_usdt=37459359, book20_ask_proxy_usdt=34590653, funding_indicative=0.000020, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.74%, turnover=230956440. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T05:15:00+00:00, last15m_closed_end=2026-10-21T05:15+00:00, prior8high=0.621800, depth_time=2026-10-21T05:15:19+00:00, book20_bid_proxy_usdt=189492, book20_ask_proxy_usdt=262774, funding_indicative=-0.000083, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=47372399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T05:15:00+00:00, last15m_closed_end=2026-10-21T05:15+00:00, prior8high=581.000000, depth_time=2026-10-21T05:15:12+00:00, book20_bid_proxy_usdt=17469, book20_ask_proxy_usdt=17193, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.02%, turnover=20987540. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
