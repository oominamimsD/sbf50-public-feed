# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T03:45:36Z**
- feed_generated_utc: 2026-10-27T03:45:39+00:00
- source_sha256: `5ddf820383f4d7326ef48f3c027dcf4bc3c4286565efec8dd5547dcc3d42ca10`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T03:45+00:00, close=79900, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T03:00+00:00, close=79789.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.619600|-5.12|-14.84|-4.50|5120026|1.85|
|PUMPFUN_USDT|0.004171|-3.62|-6.39|-3.00|21599334|2.40|
|NEAR_USDT|4.440000|-2.90|-9.46|-2.28|104896268|2.25|
|AAVE_USDT|132.820000|-2.85|-9.78|-2.23|26399004|0.75|
|FET_USDT|0.171600|-2.83|-9.20|-2.21|6659822|5.83|
|DOT_USDT|0.994000|-2.79|-13.32|-2.17|10938702|1.01|
|ONDO_USDT|0.407200|-2.76|-5.87|-2.14|23030975|2.46|
|APT_USDT|0.683300|-2.66|-10.43|-2.04|5000325|1.46|
|FILECOIN_USDT|0.899800|-2.27|-11.08|-1.65|6436130|1.11|
|AVAX_USDT|8.807000|-2.11|-7.89|-1.49|65096832|1.14|
|ICP_USDT|2.577000|-2.01|-9.67|-1.39|5188628|3.88|
|TAO_USDT|248.990000|-1.78|-7.19|-1.16|46743005|1.21|
|PENGU_USDT|0.007439|-1.78|-0.69|-1.16|5578958|2.69|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.820000|132.420000|132.820000|0.97|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.683300|0.676900|0.683300|1.21|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.807000|8.762000|8.807000|0.89|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.994000|0.988500|0.994000|0.12|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.171600|0.170600|0.171600|3.37|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.899800|0.892600|0.899800|0.83|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.577000|2.562000|2.577000|0.55|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.440000|4.389000|4.440000|0.48|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.407200|0.404300|0.407200|3.61|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007439|0.007387|0.007439|1.34|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004171|0.004118|0.004171|0.80|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|248.990000|247.350000|248.990000|0.72|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.619600|1.606400|1.619600|0.72|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T03:45:00+00:00, last15m_closed_end=2026-10-27T03:45+00:00, prior8high=135.600000, depth_time=2026-10-27T03:45:14+00:00, book20_bid_proxy_usdt=286795, book20_ask_proxy_usdt=430730, funding_indicative=0.000075, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=26399004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-27T03:45:00+00:00, last15m_closed_end=2026-10-27T03:45+00:00, prior8high=0.691600, depth_time=2026-10-27T03:45:23+00:00, book20_bid_proxy_usdt=169753, book20_ask_proxy_usdt=158527, funding_indicative=-0.000066, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.66%, turnover=5000325. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T03:45:00+00:00, last15m_closed_end=2026-10-27T03:45+00:00, prior8high=8.934000, depth_time=2026-10-27T03:45:28+00:00, book20_bid_proxy_usdt=2019006, book20_ask_proxy_usdt=1061868, funding_indicative=-0.000004, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=65096832. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T03:45:00+00:00, last15m_closed_end=2026-10-27T03:45+00:00, prior8high=1.004700, depth_time=2026-10-27T03:45:19+00:00, book20_bid_proxy_usdt=351368, book20_ask_proxy_usdt=423878, funding_indicative=-0.000109, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.79%, turnover=10938702. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T03:45:00+00:00, last15m_closed_end=2026-10-27T03:45+00:00, prior8high=0.175300, depth_time=2026-10-27T03:45:16+00:00, book20_bid_proxy_usdt=1769376, book20_ask_proxy_usdt=1252638, funding_indicative=0.000100, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.83%, turnover=6659822. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T03:45:00+00:00, last15m_closed_end=2026-10-27T03:45+00:00, prior8high=0.911400, depth_time=2026-10-27T03:45:25+00:00, book20_bid_proxy_usdt=1337283, book20_ask_proxy_usdt=1216206, funding_indicative=-0.000007, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.27%, turnover=6436130. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T03:45:00+00:00, last15m_closed_end=2026-10-27T03:45+00:00, prior8high=2.622000, depth_time=2026-10-27T03:45:30+00:00, book20_bid_proxy_usdt=1075478, book20_ask_proxy_usdt=1129822, funding_indicative=0.000090, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.01%, turnover=5188628. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T03:45:00+00:00, last15m_closed_end=2026-10-27T03:45+00:00, prior8high=4.520000, depth_time=2026-10-27T03:45:11+00:00, book20_bid_proxy_usdt=3954647, book20_ask_proxy_usdt=2343058, funding_indicative=0.000046, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=104896268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T03:45:00+00:00, last15m_closed_end=2026-10-27T03:45+00:00, prior8high=0.412900, depth_time=2026-10-27T03:45:21+00:00, book20_bid_proxy_usdt=2030569, book20_ask_proxy_usdt=3072388, funding_indicative=0.000028, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.76%, turnover=23030975. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T03:45:00+00:00, last15m_closed_end=2026-10-27T03:45+00:00, prior8high=0.007532, depth_time=2026-10-27T03:45:33+00:00, book20_bid_proxy_usdt=212994, book20_ask_proxy_usdt=251539, funding_indicative=-0.000009, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=5578958. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T03:45:00+00:00, last15m_closed_end=2026-10-27T03:45+00:00, prior8high=0.004281, depth_time=2026-10-27T03:45:07+00:00, book20_bid_proxy_usdt=1540839, book20_ask_proxy_usdt=2031141, funding_indicative=0.000032, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.62%, turnover=21599334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T03:45:00+00:00, last15m_closed_end=2026-10-27T03:45+00:00, prior8high=251.150000, depth_time=2026-10-27T03:45:32+00:00, book20_bid_proxy_usdt=146080, book20_ask_proxy_usdt=164043, funding_indicative=0.000037, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=46743005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T03:45:00+00:00, last15m_closed_end=2026-10-27T03:45+00:00, prior8high=1.634200, depth_time=2026-10-27T03:45:07+00:00, book20_bid_proxy_usdt=24360, book20_ask_proxy_usdt=32451, funding_indicative=0.000038, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.12%, turnover=5120026. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
