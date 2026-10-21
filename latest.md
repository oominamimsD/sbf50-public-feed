# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T12:00:22Z**
- feed_generated_utc: 2026-10-21T12:00:24+00:00
- source_sha256: `8b15dfea4145bcb1f847529741b77adcd8793c71786dbd086a1e3e733c841494`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1206; contracts: 1198; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.180980|-16.12|2.02|-17.18|10918911|1.10|
|BTW_USDT|1.655600|-10.48|-15.20|-11.54|26161833|5.44|
|BR_USDT|0.596250|-8.36|37.69|-9.42|23467831|0.34|
|Q_USDT|0.119522|-2.63|190.61|-3.69|5442727|1.09|
|STRK_USDT|0.055920|-2.59|-35.67|-3.65|17885284|1.79|
|TIA_USDT|0.618700|-0.64|7.17|-1.70|47750744|1.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.180980|0.180140|0.180980|0.53|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.596250|0.566870|0.596250|1.79|N|Y/Y|N/N|N|N|
|BTW_USDT|1.655600|1.622700|1.656200|1.59|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.119522|0.117302|0.119522|0.51|N|Y/Y|N/N|N|N|
|STRK_USDT|0.055920|0.055040|0.055920|1.38|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.618700|0.614700|0.618700|0.44|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-21T11:59:59+00:00, last15m_closed_end=2026-10-21T12:00+00:00, prior8high=0.183270, depth_time=2026-10-21T12:00:08+00:00, book20_bid_proxy_usdt=27956, book20_ask_proxy_usdt=32766, funding_indicative=-0.000117, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-16.12%, turnover=10918911. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T11:59:59+00:00, last15m_closed_end=2026-10-21T12:00+00:00, prior8high=0.603450, depth_time=2026-10-21T12:00:14+00:00, book20_bid_proxy_usdt=8206, book20_ask_proxy_usdt=3145, funding_indicative=-0.000132, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.36%, turnover=23467831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T11:59:59+00:00, last15m_closed_end=2026-10-21T12:00+00:00, prior8high=2.103400, depth_time=2026-10-21T12:00:11+00:00, book20_bid_proxy_usdt=8925, book20_ask_proxy_usdt=10427, funding_indicative=-0.004135, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.48%, turnover=26161833. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T11:59:59+00:00, last15m_closed_end=2026-10-21T12:00+00:00, prior8high=0.120890, depth_time=2026-10-21T12:00:12+00:00, book20_bid_proxy_usdt=18962, book20_ask_proxy_usdt=62903, funding_indicative=0.000017, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.63%, turnover=5442727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-21T12:00:00+00:00, last15m_closed_end=2026-10-21T12:00+00:00, prior8high=0.056290, depth_time=2026-10-21T12:00:13+00:00, book20_bid_proxy_usdt=674708, book20_ask_proxy_usdt=687317, funding_indicative=-0.000021, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.59%, turnover=17885284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T11:59:59+00:00, last15m_closed_end=2026-10-21T12:00+00:00, prior8high=0.625900, depth_time=2026-10-21T12:00:21+00:00, book20_bid_proxy_usdt=261548, book20_ask_proxy_usdt=323167, funding_indicative=-0.000084, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.64%, turnover=47750744. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
