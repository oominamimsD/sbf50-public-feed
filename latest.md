# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T02:45:35Z**
- feed_generated_utc: 2026-10-27T02:45:39+00:00
- source_sha256: `d06ee28efa26d74bf834ac52cb2bec378f667441e582c21a43e9649660384f9b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T02:45+00:00, close=79914.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T02:00+00:00, close=80041.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.614500|-5.42|-15.11|-4.82|5216777|0.62|
|PUMPFUN_USDT|0.004194|-3.09|-5.87|-2.49|21197135|2.39|
|NEAR_USDT|4.443000|-2.84|-9.40|-2.24|106701031|2.25|
|ONDO_USDT|0.408000|-2.57|-5.68|-1.97|22678151|2.45|
|DOT_USDT|0.997200|-2.48|-13.04|-1.88|10892787|1.00|
|AAVE_USDT|133.470000|-2.38|-9.33|-1.78|26584641|0.75|
|FET_USDT|0.172700|-2.20|-8.62|-1.60|6138272|5.79|
|FILECOIN_USDT|0.900800|-2.16|-10.98|-1.56|6464554|1.11|
|ICP_USDT|2.582000|-1.82|-9.49|-1.22|5243214|3.87|
|AVAX_USDT|8.838000|-1.76|-7.57|-1.16|71697247|1.13|
|TAO_USDT|249.030000|-1.76|-7.18|-1.16|46773448|1.21|
|LINK_USDT|11.331000|-1.70|-5.12|-1.10|106820633|0.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|133.470000|132.950000|133.470000|4.58|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.838000|8.845000|8.839000|6.25|Y|Y/N|Y/Y|Y|N|
|DOT_USDT|0.997200|0.995200|0.997200|0.46|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.172700|0.172700|0.172700|1.16|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.900800|0.900200|0.900900|0.13|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.582000|2.581000|2.583000|0.16|N|Y/N|Y/Y|Y|N|
|LINK_USDT|11.331000|11.299000|11.331000|1.46|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.443000|4.441000|4.443000|1.27|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.408000|0.407500|0.407900|1.33|N|Y/N|N/N|Y|N|
|PUMPFUN_USDT|0.004194|0.004193|0.004194|1.45|N|Y/N|Y/Y|Y|N|
|TAO_USDT|249.030000|248.490000|249.030000|0.86|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.614500|1.607900|1.614500|0.68|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T02:45:01+00:00, last15m_closed_end=2026-10-27T02:45+00:00, prior8high=136.000000, depth_time=2026-10-27T02:45:20+00:00, book20_bid_proxy_usdt=418576, book20_ask_proxy_usdt=474727, funding_indicative=0.000070, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=26584641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T02:45:01+00:00, last15m_closed_end=2026-10-27T02:45+00:00, prior8high=8.975000, depth_time=2026-10-27T02:45:29+00:00, book20_bid_proxy_usdt=1779054, book20_ask_proxy_usdt=905501, funding_indicative=0.000053, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=71697247. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T02:45:01+00:00, last15m_closed_end=2026-10-27T02:45+00:00, prior8high=1.011500, depth_time=2026-10-27T02:45:18+00:00, book20_bid_proxy_usdt=480560, book20_ask_proxy_usdt=512647, funding_indicative=-0.000073, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=10892787. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T02:45:01+00:00, last15m_closed_end=2026-10-27T02:45+00:00, prior8high=0.176400, depth_time=2026-10-27T02:45:22+00:00, book20_bid_proxy_usdt=1930201, book20_ask_proxy_usdt=1105457, funding_indicative=0.000100, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=6138272. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T02:45:01+00:00, last15m_closed_end=2026-10-27T02:45+00:00, prior8high=0.915800, depth_time=2026-10-27T02:45:25+00:00, book20_bid_proxy_usdt=1094902, book20_ask_proxy_usdt=1445472, funding_indicative=0.000041, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=6464554. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T02:45:01+00:00, last15m_closed_end=2026-10-27T02:45+00:00, prior8high=2.633000, depth_time=2026-10-27T02:45:25+00:00, book20_bid_proxy_usdt=1122984, book20_ask_proxy_usdt=1000238, funding_indicative=0.000100, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=5243214. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T02:45:01+00:00, last15m_closed_end=2026-10-27T02:45+00:00, prior8high=11.421000, depth_time=2026-10-27T02:45:35+00:00, book20_bid_proxy_usdt=518070, book20_ask_proxy_usdt=619964, funding_indicative=0.000057, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=106820633. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T02:45:01+00:00, last15m_closed_end=2026-10-27T02:45+00:00, prior8high=4.520000, depth_time=2026-10-27T02:45:13+00:00, book20_bid_proxy_usdt=5716527, book20_ask_proxy_usdt=4234056, funding_indicative=0.000057, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.84%, turnover=106701031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T02:45:01+00:00, last15m_closed_end=2026-10-27T02:45+00:00, prior8high=0.415000, depth_time=2026-10-27T02:45:11+00:00, book20_bid_proxy_usdt=2216805, book20_ask_proxy_usdt=3203493, funding_indicative=0.000034, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=22678151. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T02:45:01+00:00, last15m_closed_end=2026-10-27T02:45+00:00, prior8high=0.004310, depth_time=2026-10-27T02:45:11+00:00, book20_bid_proxy_usdt=2822295, book20_ask_proxy_usdt=1914886, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.09%, turnover=21197135. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T02:45:01+00:00, last15m_closed_end=2026-10-27T02:45+00:00, prior8high=252.300000, depth_time=2026-10-27T02:45:33+00:00, book20_bid_proxy_usdt=110232, book20_ask_proxy_usdt=112909, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.76%, turnover=46773448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T02:45:01+00:00, last15m_closed_end=2026-10-27T02:45+00:00, prior8high=1.640800, depth_time=2026-10-27T02:45:08+00:00, book20_bid_proxy_usdt=25788, book20_ask_proxy_usdt=15371, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.42%, turnover=5216777. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
