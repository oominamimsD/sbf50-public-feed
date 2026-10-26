# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T01:15:22Z**
- feed_generated_utc: 2026-10-26T01:15:25+00:00
- source_sha256: `e7fb264e477ce3998893ecf5ece79c545173c6675e175f8fbda138e7f8e7a296`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T01:15+00:00, close=80023.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T01:00+00:00, close=80135.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005810|-16.66|215.24|-15.95|10365055|3.44|
|T_USDT|0.004884|-9.26|3.87|-8.55|8010882|4.09|
|PEPE_USDT|0.000004|-2.53|11.15|-1.82|73616541|0.47|
|WLD_USDT|0.446400|-2.23|-6.27|-1.52|73199096|2.24|
|BTW_USDT|1.623000|-2.16|-29.60|-1.45|12246254|1.23|
|XMR_USDT|594.910000|-2.03|2.13|-1.32|6533334|0.17|
|DASH_USDT|51.440000|-1.85|7.43|-1.14|13577608|1.95|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.623000|1.606400|1.623000|0.90|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|51.440000|50.870000|51.440000|0.85|N|Y/Y|Y/N|Y|N|
|JCT_USDT|0.005810|0.005570|0.005800|5.49|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.52|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004884|0.004894|0.004885|0.92|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.446400|0.443500|0.446400|0.90|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|594.910000|589.580000|595.000000|0.95|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T01:15:01+00:00, last15m_closed_end=2026-10-26T01:15+00:00, prior8high=1.649200, depth_time=2026-10-26T01:15:15+00:00, book20_bid_proxy_usdt=17516, book20_ask_proxy_usdt=14296, funding_indicative=-0.007416, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.16%, turnover=12246254. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T01:15:01+00:00, last15m_closed_end=2026-10-26T01:15+00:00, prior8high=51.950000, depth_time=2026-10-26T01:15:21+00:00, book20_bid_proxy_usdt=694740, book20_ask_proxy_usdt=615367, funding_indicative=0.000096, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=13577608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T01:15:01+00:00, last15m_closed_end=2026-10-26T01:15+00:00, prior8high=0.006470, depth_time=2026-10-26T01:15:07+00:00, book20_bid_proxy_usdt=48103, book20_ask_proxy_usdt=24877, funding_indicative=0.000066, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-16.66%, turnover=10365055. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T01:15:01+00:00, last15m_closed_end=2026-10-26T01:15+00:00, prior8high=0.000004, depth_time=2026-10-26T01:15:12+00:00, book20_bid_proxy_usdt=30998, book20_ask_proxy_usdt=73556, funding_indicative=0.000082, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=73616541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T01:15:01+00:00, last15m_closed_end=2026-10-26T01:15+00:00, prior8high=0.005346, depth_time=2026-10-26T01:15:09+00:00, book20_bid_proxy_usdt=70175, book20_ask_proxy_usdt=68335, funding_indicative=-0.002344, next_funding_utc=2026-10-26T02:00:00+00:00, funding_cycle_h=1, 24h_change=-9.26%, turnover=8010882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T01:15:01+00:00, last15m_closed_end=2026-10-26T01:15+00:00, prior8high=0.453000, depth_time=2026-10-26T01:15:14+00:00, book20_bid_proxy_usdt=1519188, book20_ask_proxy_usdt=1944013, funding_indicative=0.000061, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=73199096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T01:15:01+00:00, last15m_closed_end=2026-10-26T01:15+00:00, prior8high=596.210000, depth_time=2026-10-26T01:15:19+00:00, book20_bid_proxy_usdt=16116, book20_ask_proxy_usdt=28552, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.03%, turnover=6533334. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
