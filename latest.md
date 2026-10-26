# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T00:45:23Z**
- feed_generated_utc: 2026-10-26T00:45:26+00:00
- source_sha256: `5e0f43c9b0d17ad85423b98efdcc06f1bf70558b284c5178157fed3b125b46f5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T00:45+00:00, close=80141.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005938|-14.83|222.19|-14.26|10276858|6.73|
|T_USDT|0.004941|-8.21|5.08|-7.64|8682995|6.07|
|IRYS_USDT|0.035760|-6.97|193.11|-6.40|20069293|2.81|
|BTW_USDT|1.611800|-2.83|-30.08|-2.26|12628600|0.62|
|PEPE_USDT|0.000004|-2.43|11.25|-1.86|75714377|0.23|
|XMR_USDT|594.770000|-2.05|2.10|-1.48|6657760|0.17|
|WLD_USDT|0.447600|-1.97|-6.02|-1.40|74551626|2.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.611800|1.614700|1.611800|1.11|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.035760|0.035210|0.035760|1.62|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005938|0.006069|0.005938|6.14|Y|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.46|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004941|0.004937|0.004941|1.06|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.447600|0.443500|0.447600|1.37|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|594.770000|589.580000|594.770000|0.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T00:44:59+00:00, last15m_closed_end=2026-10-26T00:45+00:00, prior8high=1.655700, depth_time=2026-10-26T00:45:13+00:00, book20_bid_proxy_usdt=11117, book20_ask_proxy_usdt=8389, funding_indicative=-0.007202, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.83%, turnover=12628600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T00:44:59+00:00, last15m_closed_end=2026-10-26T00:45+00:00, prior8high=0.039720, depth_time=2026-10-26T00:45:13+00:00, book20_bid_proxy_usdt=30966, book20_ask_proxy_usdt=47138, funding_indicative=-0.000348, next_funding_utc=2026-10-26T01:00:00+00:00, funding_cycle_h=1, 24h_change=-6.97%, turnover=20069293. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T00:44:59+00:00, last15m_closed_end=2026-10-26T00:45+00:00, prior8high=0.006760, depth_time=2026-10-26T00:45:07+00:00, book20_bid_proxy_usdt=28342, book20_ask_proxy_usdt=18220, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.83%, turnover=10276858. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T00:44:59+00:00, last15m_closed_end=2026-10-26T00:45+00:00, prior8high=0.000004, depth_time=2026-10-26T00:45:18+00:00, book20_bid_proxy_usdt=46758, book20_ask_proxy_usdt=127140, funding_indicative=0.000068, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=75714377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T00:44:59+00:00, last15m_closed_end=2026-10-26T00:45+00:00, prior8high=0.005411, depth_time=2026-10-26T00:45:10+00:00, book20_bid_proxy_usdt=74199, book20_ask_proxy_usdt=84515, funding_indicative=-0.004061, next_funding_utc=2026-10-26T01:00:00+00:00, funding_cycle_h=1, 24h_change=-8.21%, turnover=8682995. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T00:44:59+00:00, last15m_closed_end=2026-10-26T00:45+00:00, prior8high=0.454500, depth_time=2026-10-26T00:45:22+00:00, book20_bid_proxy_usdt=2165787, book20_ask_proxy_usdt=1951177, funding_indicative=0.000026, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=74551626. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T00:44:59+00:00, last15m_closed_end=2026-10-26T00:45+00:00, prior8high=596.250000, depth_time=2026-10-26T00:45:19+00:00, book20_bid_proxy_usdt=13529, book20_ask_proxy_usdt=7106, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=6657760. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
