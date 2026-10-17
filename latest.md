# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T04:30:30Z**
- feed_generated_utc: 2026-10-17T04:30:32+00:00
- source_sha256: `28d6c35d92854b9d9ea0fbbb85d6238409e390d33e1fcfd456f1f10edc2f2aa7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T04:30+00:00, close=81499, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BR_USDT|0.364720|-22.34|-28.11|-22.55|11558205|7.40|
|ZRO_USDT|1.980000|-5.77|-2.78|-5.98|14607084|0.51|
|RIVER_USDT|1.079000|-4.17|-8.71|-4.38|5128690|9.27|
|STRK_USDT|0.071850|-2.83|-4.59|-3.04|21771095|4.17|
|ZEC_USDT|1155.200000|-2.76|-5.18|-2.97|1379194558|0.09|
|ARB_USDT|0.190220|-2.42|5.21|-2.63|32937394|1.05|
|TAO_USDT|275.330000|-1.88|0.24|-2.09|76621149|1.09|
|APT_USDT|0.843200|-1.50|5.33|-1.71|12516024|1.19|
|FARTCOIN_USDT|0.153230|-0.96|-6.20|-1.17|7007224|1.30|
|AAVE_USDT|155.980000|-0.82|-8.16|-1.03|28825481|0.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|155.980000|154.410000|155.980000|0.64|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.843200|0.835000|0.843200|0.41|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.190220|0.187590|0.190200|0.32|N|Y/Y|Y/N|Y|N|
|BR_USDT|0.364720|0.356850|0.364720|0.22|N|Y/Y|Y/N|Y|N|
|FARTCOIN_USDT|0.153230|0.152200|0.153280|0.34|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.079000|1.071000|1.079000|0.53|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.071850|0.069640|0.071810|0.72|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.330000|273.190000|275.330000|0.72|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1155.200000|1140.370000|1155.200000|0.56|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.980000|1.943800|1.980000|0.31|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-17T04:30:01+00:00, last15m_closed_end=2026-10-17T04:30+00:00, prior8high=156.270000, depth_time=2026-10-17T04:30:29+00:00, book20_bid_proxy_usdt=397241, book20_ask_proxy_usdt=383118, funding_indicative=0.000051, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.82%, turnover=28825481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-17T04:30:01+00:00, last15m_closed_end=2026-10-17T04:30+00:00, prior8high=0.850100, depth_time=2026-10-17T04:30:25+00:00, book20_bid_proxy_usdt=117153, book20_ask_proxy_usdt=140461, funding_indicative=0.000058, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.50%, turnover=12516024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T04:30:01+00:00, last15m_closed_end=2026-10-17T04:30+00:00, prior8high=0.190460, depth_time=2026-10-17T04:30:20+00:00, book20_bid_proxy_usdt=65555, book20_ask_proxy_usdt=54733, funding_indicative=-0.000041, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=32937394. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-17T04:30:01+00:00, last15m_closed_end=2026-10-17T04:30+00:00, prior8high=0.387890, depth_time=2026-10-17T04:30:08+00:00, book20_bid_proxy_usdt=4120, book20_ask_proxy_usdt=2540, funding_indicative=-0.003032, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-22.34%, turnover=11558205. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T04:30:01+00:00, last15m_closed_end=2026-10-17T04:30+00:00, prior8high=0.154120, depth_time=2026-10-17T04:30:27+00:00, book20_bid_proxy_usdt=54579, book20_ask_proxy_usdt=59103, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=7007224. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T04:30:01+00:00, last15m_closed_end=2026-10-17T04:30+00:00, prior8high=1.090000, depth_time=2026-10-17T04:30:10+00:00, book20_bid_proxy_usdt=509439, book20_ask_proxy_usdt=455384, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.17%, turnover=5128690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T04:30:01+00:00, last15m_closed_end=2026-10-17T04:30+00:00, prior8high=0.073590, depth_time=2026-10-17T04:30:15+00:00, book20_bid_proxy_usdt=239121, book20_ask_proxy_usdt=244961, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.83%, turnover=21771095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T04:30:01+00:00, last15m_closed_end=2026-10-17T04:30+00:00, prior8high=277.190000, depth_time=2026-10-17T04:30:22+00:00, book20_bid_proxy_usdt=109558, book20_ask_proxy_usdt=103624, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.88%, turnover=76621149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T04:30:01+00:00, last15m_closed_end=2026-10-17T04:30+00:00, prior8high=1160.600000, depth_time=2026-10-17T04:30:17+00:00, book20_bid_proxy_usdt=350301, book20_ask_proxy_usdt=534703, funding_indicative=0.000036, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=1379194558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T04:30:01+00:00, last15m_closed_end=2026-10-17T04:30+00:00, prior8high=1.986600, depth_time=2026-10-17T04:30:09+00:00, book20_bid_proxy_usdt=64972, book20_ask_proxy_usdt=37673, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.77%, turnover=14607084. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
