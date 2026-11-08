# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T03:45:17Z**
- feed_generated_utc: 2026-11-08T03:45:18+00:00
- source_sha256: `2e3a2996f8f2aca3a31c451ebd2e13293d9d3568983023d17d1ab49cdbf4d6cc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T03:45+00:00, close=75843, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T03:00+00:00, close=75758, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001840|-9.65|56.71|-9.80|26747581|0.54|
|QNT_USDT|194.320000|-2.27|-3.34|-2.42|44069035|1.03|
|ENA_USDT|0.154860|-2.09|-20.17|-2.24|28425438|0.65|
|WLD_USDT|0.330800|-1.43|-18.19|-1.58|25095681|3.02|
|TIA_USDT|0.436700|-1.10|-10.89|-1.25|7252629|2.29|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.154860|0.153550|0.154860|1.49|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001840|0.001864|0.001840|1.26|N|Y/Y|N/N|Y|N|
|QNT_USDT|194.320000|193.120000|194.320000|0.87|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.436700|0.434500|0.436700|0.23|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.330800|0.329000|0.330800|0.70|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-08T03:44:59+00:00, last15m_closed_end=2026-11-08T03:45+00:00, prior8high=0.156520, depth_time=2026-11-08T03:45:11+00:00, book20_bid_proxy_usdt=130158, book20_ask_proxy_usdt=142128, funding_indicative=-0.000019, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=28425438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T03:44:59+00:00, last15m_closed_end=2026-11-08T03:45+00:00, prior8high=0.002086, depth_time=2026-11-08T03:45:07+00:00, book20_bid_proxy_usdt=10521, book20_ask_proxy_usdt=12227, funding_indicative=-0.000030, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.65%, turnover=26747581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T03:44:59+00:00, last15m_closed_end=2026-11-08T03:45+00:00, prior8high=195.280000, depth_time=2026-11-08T03:45:09+00:00, book20_bid_proxy_usdt=74847, book20_ask_proxy_usdt=87794, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=44069035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T03:44:59+00:00, last15m_closed_end=2026-11-08T03:45+00:00, prior8high=0.438500, depth_time=2026-11-08T03:45:13+00:00, book20_bid_proxy_usdt=386109, book20_ask_proxy_usdt=255945, funding_indicative=0.000029, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=7252629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T03:44:59+00:00, last15m_closed_end=2026-11-08T03:45+00:00, prior8high=0.332300, depth_time=2026-11-08T03:45:11+00:00, book20_bid_proxy_usdt=3283002, book20_ask_proxy_usdt=3803856, funding_indicative=-0.000094, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=25095681. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
