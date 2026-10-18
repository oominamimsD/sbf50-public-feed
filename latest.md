# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T11:30:36Z**
- feed_generated_utc: 2026-10-18T11:30:38+00:00
- source_sha256: `ffef9e47e00f3256a17b7a0d1047f58db14d826b2bd016ccc9702bed2286093b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T11:30+00:00, close=82072.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T11:00+00:00, close=82060.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-18T08:00+00:00, close=81644.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.062050|-6.19|-33.58|-7.12|15000908|1.61|
|EIGEN_USDT|0.242100|-5.54|2.75|-6.47|6510166|4.13|
|SAND_USDT|0.060750|-3.63|-9.71|-4.56|47244843|1.65|
|FILECOIN_USDT|1.059800|-2.53|-6.02|-3.46|18021372|1.89|
|PUMPFUN_USDT|0.004309|-2.33|-24.73|-3.26|23268235|2.32|
|ZRO_USDT|1.844600|-2.15|-8.71|-3.08|6554648|0.54|
|XPL_USDT|0.078440|-2.10|-9.58|-3.03|5830289|2.55|
|TIA_USDT|0.645000|-1.97|25.73|-2.90|58735505|4.65|
|OP_USDT|0.126700|-1.78|-8.55|-2.71|8702259|0.79|
|ZEC_USDT|1128.680000|-1.10|-8.37|-2.03|1206881893|0.09|
|DOT_USDT|1.107000|-0.93|-11.92|-1.86|16714779|1.81|
|ICP_USDT|2.904000|-0.81|-7.78|-1.74|6022396|3.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.107000|1.103200|1.107000|0.41|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.242100|0.242100|0.242100|2.90|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.059800|1.054000|1.059800|0.26|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.904000|2.889000|2.905000|0.84|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.126700|0.126120|0.126730|0.36|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004309|0.004272|0.004309|2.13|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.060750|0.060750|0.060750|0.41|N|Y/N|N/N|Y|N|
|STRK_USDT|0.062050|0.061570|0.062050|0.79|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.645000|0.632400|0.644900|0.67|N|Y/N|Y/Y|Y|N|
|XPL_USDT|0.078440|0.078400|0.078440|0.08|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1128.680000|1124.560000|1129.000000|0.90|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.844600|1.829900|1.844600|0.40|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-18T11:30:01+00:00, last15m_closed_end=2026-10-18T11:30+00:00, prior8high=1.120400, depth_time=2026-10-18T11:30:32+00:00, book20_bid_proxy_usdt=280688, book20_ask_proxy_usdt=258829, funding_indicative=-0.000070, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=16714779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T11:30:01+00:00, last15m_closed_end=2026-10-18T11:30+00:00, prior8high=0.249900, depth_time=2026-10-18T11:30:09+00:00, book20_bid_proxy_usdt=544785, book20_ask_proxy_usdt=410493, funding_indicative=-0.000015, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.54%, turnover=6510166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T11:30:01+00:00, last15m_closed_end=2026-10-18T11:30+00:00, prior8high=1.069800, depth_time=2026-10-18T11:30:14+00:00, book20_bid_proxy_usdt=678860, book20_ask_proxy_usdt=670209, funding_indicative=0.000012, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.53%, turnover=18021372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-18T11:30:01+00:00, last15m_closed_end=2026-10-18T11:30+00:00, prior8high=2.941000, depth_time=2026-10-18T11:30:34+00:00, book20_bid_proxy_usdt=892917, book20_ask_proxy_usdt=981442, funding_indicative=0.000036, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.81%, turnover=6022396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-18T11:30:01+00:00, last15m_closed_end=2026-10-18T11:30+00:00, prior8high=0.128100, depth_time=2026-10-18T11:30:27+00:00, book20_bid_proxy_usdt=81309, book20_ask_proxy_usdt=93997, funding_indicative=-0.000219, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=8702259. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T11:30:01+00:00, last15m_closed_end=2026-10-18T11:30+00:00, prior8high=0.004347, depth_time=2026-10-18T11:30:16+00:00, book20_bid_proxy_usdt=1855385, book20_ask_proxy_usdt=1053701, funding_indicative=0.000039, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.33%, turnover=23268235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T11:30:01+00:00, last15m_closed_end=2026-10-18T11:30+00:00, prior8high=0.062600, depth_time=2026-10-18T11:30:12+00:00, book20_bid_proxy_usdt=424612, book20_ask_proxy_usdt=518887, funding_indicative=-0.006063, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.63%, turnover=47244843. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T11:30:01+00:00, last15m_closed_end=2026-10-18T11:30+00:00, prior8high=0.064650, depth_time=2026-10-18T11:30:08+00:00, book20_bid_proxy_usdt=375730, book20_ask_proxy_usdt=360322, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.19%, turnover=15000908. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T11:30:01+00:00, last15m_closed_end=2026-10-18T11:30+00:00, prior8high=0.665300, depth_time=2026-10-18T11:30:25+00:00, book20_bid_proxy_usdt=217298, book20_ask_proxy_usdt=183287, funding_indicative=-0.000058, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=58735505. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T11:30:01+00:00, last15m_closed_end=2026-10-18T11:30+00:00, prior8high=0.079080, depth_time=2026-10-18T11:30:22+00:00, book20_bid_proxy_usdt=434833, book20_ask_proxy_usdt=512978, funding_indicative=0.000050, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.10%, turnover=5830289. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-18T11:30:01+00:00, last15m_closed_end=2026-10-18T11:30+00:00, prior8high=1143.000000, depth_time=2026-10-18T11:30:29+00:00, book20_bid_proxy_usdt=694986, book20_ask_proxy_usdt=93237, funding_indicative=0.000100, next_funding_utc=2026-10-18T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=1206881893. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-18T11:30:01+00:00, last15m_closed_end=2026-10-18T11:30+00:00, prior8high=1.874500, depth_time=2026-10-18T11:30:20+00:00, book20_bid_proxy_usdt=64112, book20_ask_proxy_usdt=50277, funding_indicative=-0.000027, next_funding_utc=2026-10-18T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.15%, turnover=6554648. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
