# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T04:45:27Z**
- feed_generated_utc: 2026-11-08T04:45:28+00:00
- source_sha256: `1ec95445c2f9db2c9ad7facd0d6436f6c68de0b21ad4c9b920900f169f924cea`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T04:45+00:00, close=75869, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001848|-9.26|57.39|-9.44|26633875|0.54|
|ENA_USDT|0.153510|-2.95|-20.87|-3.13|28148686|0.65|
|QNT_USDT|194.100000|-2.38|-3.45|-2.56|45462308|0.52|
|TIA_USDT|0.434500|-1.60|-11.34|-1.78|7251490|2.30|
|WLD_USDT|0.330500|-1.51|-18.27|-1.69|24479709|3.03|
|ONDO_USDT|0.358000|-1.40|-13.19|-1.58|8629139|2.79|
|ADA_USDT|0.179900|-0.93|-7.07|-1.11|11384887|5.56|
|XLM_USDT|0.149870|-0.89|-12.73|-1.07|18035239|0.67|
|LINK_USDT|10.750000|-0.86|-7.09|-1.04|70768408|0.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.179900|0.179400|0.179900|0.98|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.153510|0.153550|0.153510|2.12|Y|Y/Y|Y/Y|Y|Y|
|LINK_USDT|10.750000|10.739000|10.750000|0.76|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.358000|0.358700|0.358000|4.11|Y|Y/Y|Y/Y|Y|Y|
|ONE_USDT|0.001848|0.001812|0.001848|1.15|N|Y/Y|N/N|Y|N|
|QNT_USDT|194.100000|193.120000|194.150000|1.01|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.434500|0.434500|0.434600|0.78|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.330500|0.329000|0.330500|0.54|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.149870|0.150140|0.149870|3.33|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-08T04:44:59+00:00, last15m_closed_end=2026-11-08T04:45+00:00, prior8high=0.180900, depth_time=2026-11-08T04:45:21+00:00, book20_bid_proxy_usdt=9883490, book20_ask_proxy_usdt=9975116, funding_indicative=-0.000069, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=11384887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T04:44:59+00:00, last15m_closed_end=2026-11-08T04:45+00:00, prior8high=0.155430, depth_time=2026-11-08T04:45:09+00:00, book20_bid_proxy_usdt=262320, book20_ask_proxy_usdt=224663, funding_indicative=0.000018, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.95%, turnover=28148686. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T04:44:59+00:00, last15m_closed_end=2026-11-08T04:45+00:00, prior8high=10.801000, depth_time=2026-11-08T04:45:24+00:00, book20_bid_proxy_usdt=1287842, book20_ask_proxy_usdt=334068, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=70768408. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T04:44:59+00:00, last15m_closed_end=2026-11-08T04:45+00:00, prior8high=0.362000, depth_time=2026-11-08T04:45:17+00:00, book20_bid_proxy_usdt=1510762, book20_ask_proxy_usdt=2317490, funding_indicative=-0.000011, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=8629139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T04:44:59+00:00, last15m_closed_end=2026-11-08T04:45+00:00, prior8high=0.001974, depth_time=2026-11-08T04:45:07+00:00, book20_bid_proxy_usdt=11429, book20_ask_proxy_usdt=14732, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.26%, turnover=26633875. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T04:44:59+00:00, last15m_closed_end=2026-11-08T04:45+00:00, prior8high=195.100000, depth_time=2026-11-08T04:45:05+00:00, book20_bid_proxy_usdt=92643, book20_ask_proxy_usdt=69127, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=45462308. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T04:44:59+00:00, last15m_closed_end=2026-11-08T04:45+00:00, prior8high=0.438500, depth_time=2026-11-08T04:45:12+00:00, book20_bid_proxy_usdt=338991, book20_ask_proxy_usdt=260750, funding_indicative=-0.000006, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.60%, turnover=7251490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T04:44:59+00:00, last15m_closed_end=2026-11-08T04:45+00:00, prior8high=0.332300, depth_time=2026-11-08T04:45:13+00:00, book20_bid_proxy_usdt=3632971, book20_ask_proxy_usdt=3363841, funding_indicative=-0.000150, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=24479709. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-08T04:44:59+00:00, last15m_closed_end=2026-11-08T04:45+00:00, prior8high=0.150960, depth_time=2026-11-08T04:45:21+00:00, book20_bid_proxy_usdt=188860, book20_ask_proxy_usdt=286909, funding_indicative=-0.000095, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.89%, turnover=18035239. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
