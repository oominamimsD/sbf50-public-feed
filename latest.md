# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T06:45:22Z**
- feed_generated_utc: 2026-10-20T06:45:25+00:00
- source_sha256: `74c045a9f6865e95eb6247983622f56184332e5b2a76c87da2ffdf7e992dcaff`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T06:45+00:00, close=81817, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T06:00+00:00, close=81684.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.308720|-6.47|-9.76|-6.36|5484403|1.62|
|Q_USDT|0.121725|-3.38|295.32|-3.27|9517139|4.60|
|SAND_USDT|0.057220|-3.24|-7.84|-3.13|8196466|1.75|
|NEAR_USDT|4.785000|-2.42|-13.76|-2.31|169731702|2.09|
|ZRO_USDT|1.859100|-2.25|-17.77|-2.14|7691510|1.61|
|BTW_USDT|1.727900|-1.37|-1.58|-1.26|30373068|1.16|
|UNI_USDT|7.193000|-1.30|-3.03|-1.19|10286085|1.39|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.727900|1.675200|1.727900|0.70|N|Y/Y|Y/Y|Y|N|
|CT_USDT|0.308720|0.301550|0.308720|2.01|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.785000|4.749000|4.785000|1.62|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.121725|0.110142|0.121880|1.35|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.057220|0.056650|0.057210|0.41|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.193000|7.119000|7.193000|3.52|N|Y/Y|N/N|Y|N|
|ZRO_USDT|1.859100|1.826700|1.859100|4.46|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-20T06:45:01+00:00, last15m_closed_end=2026-10-20T06:45+00:00, prior8high=1.882800, depth_time=2026-10-20T06:45:19+00:00, book20_bid_proxy_usdt=16546, book20_ask_proxy_usdt=6212, funding_indicative=-0.003869, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.37%, turnover=30373068. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-20T06:45:01+00:00, last15m_closed_end=2026-10-20T06:45+00:00, prior8high=0.321770, depth_time=2026-10-20T06:45:04+00:00, book20_bid_proxy_usdt=9419, book20_ask_proxy_usdt=11556, funding_indicative=-0.002576, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.47%, turnover=5484403. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T06:45:01+00:00, last15m_closed_end=2026-10-20T06:45+00:00, prior8high=4.836000, depth_time=2026-10-20T06:45:15+00:00, book20_bid_proxy_usdt=3283094, book20_ask_proxy_usdt=1968217, funding_indicative=-0.000006, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=169731702. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T06:45:01+00:00, last15m_closed_end=2026-10-20T06:45+00:00, prior8high=0.133766, depth_time=2026-10-20T06:45:10+00:00, book20_bid_proxy_usdt=15790, book20_ask_proxy_usdt=15454, funding_indicative=-0.000189, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=9517139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T06:45:02+00:00, last15m_closed_end=2026-10-20T06:45+00:00, prior8high=0.057650, depth_time=2026-10-20T06:45:12+00:00, book20_bid_proxy_usdt=767354, book20_ask_proxy_usdt=845511, funding_indicative=-0.001621, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.24%, turnover=8196466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T06:45:02+00:00, last15m_closed_end=2026-10-20T06:45+00:00, prior8high=7.310000, depth_time=2026-10-20T06:45:20+00:00, book20_bid_proxy_usdt=1660338, book20_ask_proxy_usdt=2253067, funding_indicative=0.000016, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=10286085. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T06:45:02+00:00, last15m_closed_end=2026-10-20T06:45+00:00, prior8high=1.877500, depth_time=2026-10-20T06:45:17+00:00, book20_bid_proxy_usdt=121066, book20_ask_proxy_usdt=42931, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.25%, turnover=7691510. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
