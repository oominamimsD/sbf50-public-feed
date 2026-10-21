# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T07:00:22Z**
- feed_generated_utc: 2026-10-21T07:00:24+00:00
- source_sha256: `b82d75b000c80cfb79710f38f7092b0939f7fde30fc500fa9b362d4bd18a48ea`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T07:00+00:00, close=82752, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T07:00+00:00, close=82752, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.183950|-14.74|3.70|-14.94|11075820|1.63|
|BR_USDT|0.584000|-10.24|34.86|-10.44|33611961|1.54|
|XMR_USDT|580.500000|-6.40|9.96|-6.60|21324743|0.17|
|STRK_USDT|0.056470|-1.63|-35.03|-1.83|17375358|3.54|
|PHA_USDT|0.057010|-1.40|3.59|-1.60|6810717|5.26|
|SILVER_USDT|57.240000|-1.22|-3.62|-1.42|228971608|1.75|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BAT_USDT|0.183950|0.182050|0.183950|1.48|N|Y/Y|Y/N|N|N|
|BR_USDT|0.584000|0.577560|0.584000|1.55|N|Y/Y|N/N|N|N|
|PHA_USDT|0.057010|0.055950|0.057010|0.28|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.240000|57.270000|57.240000|2.23|Y|Y/Y|Y/N|N|N|
|STRK_USDT|0.056470|0.055600|0.056470|0.85|N|Y/Y|Y/Y|N|N|
|XMR_USDT|580.500000|575.320000|580.500000|0.74|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BAT_USDT: quote_utc=2026-10-21T06:59:59+00:00, last15m_closed_end=2026-10-21T07:00+00:00, prior8high=0.186710, depth_time=2026-10-21T07:00:07+00:00, book20_bid_proxy_usdt=35749, book20_ask_proxy_usdt=28862, funding_indicative=-0.000132, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-14.74%, turnover=11075820. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T06:59:59+00:00, last15m_closed_end=2026-10-21T07:00+00:00, prior8high=0.595790, depth_time=2026-10-21T07:00:11+00:00, book20_bid_proxy_usdt=3081, book20_ask_proxy_usdt=2914, funding_indicative=0.000026, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.24%, turnover=33611961. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T06:59:59+00:00, last15m_closed_end=2026-10-21T07:00+00:00, prior8high=0.057320, depth_time=2026-10-21T07:00:17+00:00, book20_bid_proxy_usdt=92815, book20_ask_proxy_usdt=73670, funding_indicative=-0.000017, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=6810717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T06:59:59+00:00, last15m_closed_end=2026-10-21T07:00+00:00, prior8high=57.780000, depth_time=2026-10-21T07:00:20+00:00, book20_bid_proxy_usdt=37962588, book20_ask_proxy_usdt=37328408, funding_indicative=0.000042, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.22%, turnover=228971608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-21T07:00:00+00:00, last15m_closed_end=2026-10-21T07:00+00:00, prior8high=0.057190, depth_time=2026-10-21T07:00:15+00:00, book20_bid_proxy_usdt=673388, book20_ask_proxy_usdt=658858, funding_indicative=0.000000, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=17375358. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T06:59:59+00:00, last15m_closed_end=2026-10-21T07:00+00:00, prior8high=581.680000, depth_time=2026-10-21T07:00:12+00:00, book20_bid_proxy_usdt=24707, book20_ask_proxy_usdt=14147, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.40%, turnover=21324743. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
