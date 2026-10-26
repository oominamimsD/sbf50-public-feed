# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T01:45:33Z**
- feed_generated_utc: 2026-10-26T01:45:36+00:00
- source_sha256: `5bd2bdcc1342e257dd0f3e4e43f72e00de0dcb3de21c8dffa9b9e015fdf342d8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T01:45+00:00, close=79480.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T01:00+00:00, close=80135.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005694|-18.33|208.95|-16.94|10500150|3.51|
|APR_USDT|0.034330|-16.89|26.02|-15.50|11947395|2.90|
|T_USDT|0.004876|-9.41|3.70|-8.02|8025277|2.05|
|IRYS_USDT|0.036520|-4.99|199.34|-3.60|18267195|8.21|
|PEPE_USDT|0.000004|-3.67|9.84|-2.28|76027115|2.37|
|DASH_USDT|50.550000|-3.54|5.57|-2.15|14062083|1.98|
|WLD_USDT|0.443100|-2.95|-6.97|-1.56|74010219|2.26|
|XMR_USDT|589.390000|-2.94|1.18|-1.55|6723909|2.54|
|BTW_USDT|1.612100|-2.82|-30.07|-1.43|12358236|1.24|
|DOT_USDT|1.011200|-2.69|-5.44|-1.30|10615273|0.99|
|PUMPFUN_USDT|0.004177|-2.52|-0.42|-1.13|16058014|2.39|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034330|0.037400|0.034560|3.54|Y|Y/Y|N/N|Y|N|
|BTW_USDT|1.612100|1.606400|1.612100|1.55|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|50.550000|50.870000|50.550000|3.81|Y|Y/Y|Y/N|Y|N|
|DOT_USDT|1.011200|1.018100|1.011200|3.91|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.036520|0.034710|0.036520|1.68|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005694|0.005381|0.005694|1.63|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|2.83|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.004177|0.004185|0.004177|6.92|Y|Y/Y|Y/Y|Y|Y|
|T_USDT|0.004876|0.004881|0.004876|0.62|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.443100|0.443500|0.443100|0.70|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|589.390000|589.580000|589.420000|2.76|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T01:44:59+00:00, last15m_closed_end=2026-10-26T01:45+00:00, prior8high=0.041460, depth_time=2026-10-26T01:45:10+00:00, book20_bid_proxy_usdt=38753, book20_ask_proxy_usdt=61148, funding_indicative=0.000131, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-16.89%, turnover=11947395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T01:44:59+00:00, last15m_closed_end=2026-10-26T01:45+00:00, prior8high=1.645900, depth_time=2026-10-26T01:45:27+00:00, book20_bid_proxy_usdt=22288, book20_ask_proxy_usdt=19408, funding_indicative=-0.007063, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.82%, turnover=12358236. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T01:44:59+00:00, last15m_closed_end=2026-10-26T01:45+00:00, prior8high=51.950000, depth_time=2026-10-26T01:45:20+00:00, book20_bid_proxy_usdt=291869, book20_ask_proxy_usdt=484968, funding_indicative=0.000076, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.54%, turnover=14062083. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T01:44:59+00:00, last15m_closed_end=2026-10-26T01:45+00:00, prior8high=1.033700, depth_time=2026-10-26T01:45:30+00:00, book20_bid_proxy_usdt=222850, book20_ask_proxy_usdt=229542, funding_indicative=-0.000097, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.69%, turnover=10615273. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T01:44:59+00:00, last15m_closed_end=2026-10-26T01:45+00:00, prior8high=0.040190, depth_time=2026-10-26T01:45:15+00:00, book20_bid_proxy_usdt=36492, book20_ask_proxy_usdt=32190, funding_indicative=-0.000279, next_funding_utc=2026-10-26T02:00:00+00:00, funding_cycle_h=1, 24h_change=-4.99%, turnover=18267195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T01:44:59+00:00, last15m_closed_end=2026-10-26T01:45+00:00, prior8high=0.006255, depth_time=2026-10-26T01:45:07+00:00, book20_bid_proxy_usdt=36334, book20_ask_proxy_usdt=45976, funding_indicative=0.000110, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-18.33%, turnover=10500150. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T01:44:59+00:00, last15m_closed_end=2026-10-26T01:45+00:00, prior8high=0.000004, depth_time=2026-10-26T01:45:18+00:00, book20_bid_proxy_usdt=33819, book20_ask_proxy_usdt=59664, funding_indicative=0.000082, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.67%, turnover=76027115. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T01:44:59+00:00, last15m_closed_end=2026-10-26T01:45+00:00, prior8high=0.004276, depth_time=2026-10-26T01:45:32+00:00, book20_bid_proxy_usdt=1672468, book20_ask_proxy_usdt=1693474, funding_indicative=0.000003, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.52%, turnover=16058014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T01:44:59+00:00, last15m_closed_end=2026-10-26T01:45+00:00, prior8high=0.005307, depth_time=2026-10-26T01:45:12+00:00, book20_bid_proxy_usdt=54845, book20_ask_proxy_usdt=81213, funding_indicative=-0.001852, next_funding_utc=2026-10-26T02:00:00+00:00, funding_cycle_h=1, 24h_change=-9.41%, turnover=8025277. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T01:44:59+00:00, last15m_closed_end=2026-10-26T01:45+00:00, prior8high=0.452600, depth_time=2026-10-26T01:45:23+00:00, book20_bid_proxy_usdt=1765088, book20_ask_proxy_usdt=2384559, funding_indicative=0.000069, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.95%, turnover=74010219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T01:44:59+00:00, last15m_closed_end=2026-10-26T01:45+00:00, prior8high=597.180000, depth_time=2026-10-26T01:45:24+00:00, book20_bid_proxy_usdt=14140, book20_ask_proxy_usdt=30608, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=6723909. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
