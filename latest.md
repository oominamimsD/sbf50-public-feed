# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T02:15:33Z**
- feed_generated_utc: 2026-10-26T02:15:37+00:00
- source_sha256: `34539ad7293d0e8d2bf9dcb467b89fb49270865658da6d8a7fc5a3ca9fd1ed3f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T02:15+00:00, close=79760.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T02:00+00:00, close=79714.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004934|-29.23|167.71|-28.18|10419373|6.08|
|APR_USDT|0.034470|-16.55|26.54|-15.50|12068057|2.90|
|T_USDT|0.004942|-8.19|5.10|-7.14|7342681|2.02|
|DASH_USDT|50.680000|-3.30|5.84|-2.25|13696860|3.95|
|PEPE_USDT|0.000004|-3.07|10.53|-2.02|73067786|0.71|
|WLD_USDT|0.444000|-2.75|-6.78|-1.70|73224993|2.25|
|XMR_USDT|590.560000|-2.75|1.38|-1.70|6721624|0.51|
|IRYS_USDT|0.037430|-2.62|206.80|-1.57|17797896|2.67|
|BTW_USDT|1.616300|-2.56|-29.89|-1.51|12132726|0.62|
|PUMPFUN_USDT|0.004183|-2.38|-0.28|-1.33|16863881|2.39|
|DOT_USDT|1.016600|-2.17|-4.93|-1.12|10753982|1.97|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034470|0.033170|0.034470|4.09|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.616300|1.603000|1.617500|1.25|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|50.680000|50.550000|50.680000|0.11|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.016600|1.010100|1.016600|0.94|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.037430|0.034710|0.037470|1.85|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004934|0.005381|0.004945|2.51|Y|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.58|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004183|0.004164|0.004183|2.90|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004942|0.004873|0.004940|1.89|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.444000|0.442200|0.443900|0.69|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|590.560000|588.410000|590.560000|1.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T02:15:00+00:00, last15m_closed_end=2026-10-26T02:15+00:00, prior8high=0.041460, depth_time=2026-10-26T02:15:11+00:00, book20_bid_proxy_usdt=85861, book20_ask_proxy_usdt=64472, funding_indicative=0.000111, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-16.55%, turnover=12068057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T02:15:00+00:00, last15m_closed_end=2026-10-26T02:15+00:00, prior8high=1.635900, depth_time=2026-10-26T02:15:26+00:00, book20_bid_proxy_usdt=14196, book20_ask_proxy_usdt=15022, funding_indicative=-0.006484, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=12132726. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T02:15:00+00:00, last15m_closed_end=2026-10-26T02:15+00:00, prior8high=51.950000, depth_time=2026-10-26T02:15:15+00:00, book20_bid_proxy_usdt=735258, book20_ask_proxy_usdt=621351, funding_indicative=0.000071, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.30%, turnover=13696860. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T02:15:00+00:00, last15m_closed_end=2026-10-26T02:15+00:00, prior8high=1.033700, depth_time=2026-10-26T02:15:32+00:00, book20_bid_proxy_usdt=301622, book20_ask_proxy_usdt=613376, funding_indicative=-0.000074, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=10753982. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T02:15:00+00:00, last15m_closed_end=2026-10-26T02:15+00:00, prior8high=0.040400, depth_time=2026-10-26T02:15:25+00:00, book20_bid_proxy_usdt=23650, book20_ask_proxy_usdt=31142, funding_indicative=-0.000471, next_funding_utc=2026-10-26T03:00:00+00:00, funding_cycle_h=1, 24h_change=-2.62%, turnover=17797896. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T02:15:00+00:00, last15m_closed_end=2026-10-26T02:15+00:00, prior8high=0.006255, depth_time=2026-10-26T02:15:08+00:00, book20_bid_proxy_usdt=19152, book20_ask_proxy_usdt=21072, funding_indicative=0.000104, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-29.23%, turnover=10419373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T02:15:00+00:00, last15m_closed_end=2026-10-26T02:15+00:00, prior8high=0.000004, depth_time=2026-10-26T02:15:18+00:00, book20_bid_proxy_usdt=62435, book20_ask_proxy_usdt=37412, funding_indicative=0.000058, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.07%, turnover=73067786. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T02:15:00+00:00, last15m_closed_end=2026-10-26T02:15+00:00, prior8high=0.004276, depth_time=2026-10-26T02:15:30+00:00, book20_bid_proxy_usdt=1786282, book20_ask_proxy_usdt=1920465, funding_indicative=0.000024, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.38%, turnover=16863881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T02:15:00+00:00, last15m_closed_end=2026-10-26T02:15+00:00, prior8high=0.005269, depth_time=2026-10-26T02:15:13+00:00, book20_bid_proxy_usdt=78800, book20_ask_proxy_usdt=105460, funding_indicative=-0.001824, next_funding_utc=2026-10-26T03:00:00+00:00, funding_cycle_h=1, 24h_change=-8.19%, turnover=7342681. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T02:15:00+00:00, last15m_closed_end=2026-10-26T02:15+00:00, prior8high=0.452600, depth_time=2026-10-26T02:15:21+00:00, book20_bid_proxy_usdt=2136393, book20_ask_proxy_usdt=2134468, funding_indicative=0.000089, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=73224993. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T02:15:00+00:00, last15m_closed_end=2026-10-26T02:15+00:00, prior8high=597.180000, depth_time=2026-10-26T02:15:23+00:00, book20_bid_proxy_usdt=9503, book20_ask_proxy_usdt=23256, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=6721624. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
