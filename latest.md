# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T12:00:36Z**
- feed_generated_utc: 2026-10-14T12:00:39+00:00
- source_sha256: `39a0aafdbf9f10bcb9110e59a788eb6ffc9d417ee50eb48eeb2f5e2eca4eb964`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T12:00+00:00, close=83424.1, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T12:00+00:00, close=83424.1, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T12:00+00:00, close=83424.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.056200|-20.39|28.60|-20.42|24123317|1.78|
|W_USDT|0.015757|-12.32|8.57|-12.35|6190731|2.54|
|STRK_USDT|0.078150|-8.51|49.74|-8.54|26767166|1.28|
|TIA_USDT|0.555500|-3.77|16.62|-3.80|33074417|3.60|
|DOT_USDT|1.149700|-2.93|-4.30|-2.96|19411315|0.87|
|UNI_USDT|7.358000|-2.23|-15.08|-2.26|17338528|1.36|
|RENDER_USDT|1.983000|-1.78|-6.90|-1.81|8159474|5.04|
|SILVER_USDT|58.580000|-1.72|-4.54|-1.75|264318890|1.71|
|ICP_USDT|3.093000|-1.52|-9.08|-1.55|8296023|3.23|
|ZRO_USDT|1.979100|-1.38|-12.09|-1.41|8741750|2.02|
|XLM_USDT|0.189580|-1.26|-11.27|-1.29|9289721|0.53|
|HBAR_USDT|0.086320|-1.13|-13.74|-1.16|12515736|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.149700|1.129300|1.149700|0.49|N|Y/Y|Y/Y|N|N|
|HBAR_USDT|0.086320|0.085850|0.086320|0.62|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.093000|3.053000|3.093000|0.17|N|Y/Y|Y/Y|N|N|
|RENDER_USDT|1.983000|1.953000|1.983000|0.56|N|Y/Y|Y/Y|N|N|
|SILVER_USDT|58.580000|58.480000|58.580000|1.31|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.078150|0.077420|0.078150|1.43|N|Y/Y|Y/Y|N|N|
|S_USDT|0.056200|0.055670|0.056200|1.07|N|Y/Y|N/N|N|N|
|TIA_USDT|0.555500|0.540100|0.555900|1.19|N|Y/Y|Y/Y|N|N|
|UNI_USDT|7.358000|7.313000|7.358000|1.18|N|Y/Y|Y/Y|N|N|
|W_USDT|0.015757|0.015764|0.015757|0.56|N|Y/Y|Y/Y|N|N|
|XLM_USDT|0.189580|0.188240|0.189580|6.44|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.979100|1.961100|1.979100|0.21|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-14T12:00:01+00:00, last15m_closed_end=2026-10-14T12:00+00:00, prior8high=1.152500, depth_time=2026-10-14T12:00:17+00:00, book20_bid_proxy_usdt=158833, book20_ask_proxy_usdt=316917, funding_indicative=-0.000007, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.93%, turnover=19411315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-14T12:00:01+00:00, last15m_closed_end=2026-10-14T12:00+00:00, prior8high=0.086470, depth_time=2026-10-14T12:00:34+00:00, book20_bid_proxy_usdt=482911, book20_ask_proxy_usdt=800203, funding_indicative=0.000058, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=12515736. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T12:00:01+00:00, last15m_closed_end=2026-10-14T12:00+00:00, prior8high=3.101000, depth_time=2026-10-14T12:00:26+00:00, book20_bid_proxy_usdt=740977, book20_ask_proxy_usdt=847031, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.52%, turnover=8296023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RENDER_USDT: quote_utc=2026-10-14T12:00:01+00:00, last15m_closed_end=2026-10-14T12:00+00:00, prior8high=1.990000, depth_time=2026-10-14T12:00:22+00:00, book20_bid_proxy_usdt=2074462, book20_ask_proxy_usdt=1576809, funding_indicative=0.000004, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=8159474. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T12:00:00+00:00, last15m_closed_end=2026-10-14T12:00+00:00, prior8high=58.790000, depth_time=2026-10-14T12:00:24+00:00, book20_bid_proxy_usdt=49796517, book20_ask_proxy_usdt=44348037, funding_indicative=0.000101, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.72%, turnover=264318890. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T12:00:00+00:00, last15m_closed_end=2026-10-14T12:00+00:00, prior8high=0.079950, depth_time=2026-10-14T12:00:12+00:00, book20_bid_proxy_usdt=292178, book20_ask_proxy_usdt=413042, funding_indicative=0.000050, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.51%, turnover=26767166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T12:00:00+00:00, last15m_closed_end=2026-10-14T12:00+00:00, prior8high=0.057120, depth_time=2026-10-14T12:00:07+00:00, book20_bid_proxy_usdt=46266, book20_ask_proxy_usdt=133834, funding_indicative=-0.000054, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.39%, turnover=24123317. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T12:00:00+00:00, last15m_closed_end=2026-10-14T12:00+00:00, prior8high=0.554200, depth_time=2026-10-14T12:00:15+00:00, book20_bid_proxy_usdt=146917, book20_ask_proxy_usdt=178412, funding_indicative=-0.000048, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.77%, turnover=33074417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T12:00:00+00:00, last15m_closed_end=2026-10-14T12:00+00:00, prior8high=7.381000, depth_time=2026-10-14T12:00:20+00:00, book20_bid_proxy_usdt=1570932, book20_ask_proxy_usdt=1595604, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.23%, turnover=17338528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T12:00:00+00:00, last15m_closed_end=2026-10-14T12:00+00:00, prior8high=0.016220, depth_time=2026-10-14T12:00:10+00:00, book20_bid_proxy_usdt=33891, book20_ask_proxy_usdt=26751, funding_indicative=-0.000229, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.32%, turnover=6190731. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T12:00:01+00:00, last15m_closed_end=2026-10-14T12:00+00:00, prior8high=0.189950, depth_time=2026-10-14T12:00:31+00:00, book20_bid_proxy_usdt=154181, book20_ask_proxy_usdt=179185, funding_indicative=-0.000086, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=9289721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-14T12:00:01+00:00, last15m_closed_end=2026-10-14T12:00+00:00, prior8high=2.009900, depth_time=2026-10-14T12:00:29+00:00, book20_bid_proxy_usdt=25577, book20_ask_proxy_usdt=45237, funding_indicative=-0.000030, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.38%, turnover=8741750. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
