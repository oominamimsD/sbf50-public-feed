# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-17T04:15:33Z**
- feed_generated_utc: 2026-10-17T04:15:35+00:00
- source_sha256: `fb52fb0a14366d156f9d364e76819821b478a2e974471dfaa0d0624cdd52f9c2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-17T04:15+00:00, close=81520.2, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-17T04:00+00:00, close=81534.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.982200|-5.66|-2.68|-5.90|14593405|0.51|
|RIVER_USDT|1.077000|-4.35|-8.88|-4.59|5121057|9.28|
|STRK_USDT|0.071440|-3.39|-5.13|-3.63|21682412|1.40|
|ZEC_USDT|1154.240000|-2.84|-5.26|-3.08|1374288393|0.17|
|ARB_USDT|0.189790|-2.64|4.97|-2.88|32883528|0.53|
|FET_USDT|0.194600|-2.50|-10.32|-2.74|11402336|5.14|
|TAO_USDT|275.070000|-1.97|0.14|-2.21|76454678|1.09|
|APT_USDT|0.841400|-1.71|5.10|-1.95|12496756|1.19|
|AVAX_USDT|9.985000|-0.97|-2.03|-1.21|121037495|2.00|
|SUI_USDT|1.012600|-0.77|-4.25|-1.01|93487852|0.99|
|FARTCOIN_USDT|0.153530|-0.76|-6.02|-1.00|7000368|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.841400|0.835000|0.841200|0.50|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189790|0.187590|0.189790|0.30|N|Y/Y|Y/N|Y|N|
|AVAX_USDT|9.985000|9.927000|9.985000|2.68|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.153530|0.152200|0.153530|2.07|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.194600|0.194200|0.194600|0.77|N|Y/Y|Y/Y|Y|N|
|RIVER_USDT|1.077000|1.074000|1.077000|3.07|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.071440|0.069640|0.071440|0.88|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|1.012600|1.001400|1.012600|1.26|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|275.070000|273.100000|275.070000|0.39|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1154.240000|1140.370000|1154.240000|0.81|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.982200|1.943800|1.982200|0.51|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-17T04:14:59+00:00, last15m_closed_end=2026-10-17T04:15+00:00, prior8high=0.850100, depth_time=2026-10-17T04:15:25+00:00, book20_bid_proxy_usdt=142945, book20_ask_proxy_usdt=110888, funding_indicative=0.000063, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=12496756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-17T04:14:59+00:00, last15m_closed_end=2026-10-17T04:15+00:00, prior8high=0.190730, depth_time=2026-10-17T04:15:16+00:00, book20_bid_proxy_usdt=72412, book20_ask_proxy_usdt=52349, funding_indicative=-0.000053, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.64%, turnover=32883528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-17T04:14:59+00:00, last15m_closed_end=2026-10-17T04:15+00:00, prior8high=10.018000, depth_time=2026-10-17T04:15:27+00:00, book20_bid_proxy_usdt=847969, book20_ask_proxy_usdt=624300, funding_indicative=0.000077, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.97%, turnover=121037495. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-17T04:15:00+00:00, last15m_closed_end=2026-10-17T04:15+00:00, prior8high=0.154120, depth_time=2026-10-17T04:15:31+00:00, book20_bid_proxy_usdt=60013, book20_ask_proxy_usdt=64400, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.76%, turnover=7000368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-17T04:14:59+00:00, last15m_closed_end=2026-10-17T04:15+00:00, prior8high=0.196500, depth_time=2026-10-17T04:15:20+00:00, book20_bid_proxy_usdt=1933802, book20_ask_proxy_usdt=1110877, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=11402336. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RIVER_USDT: quote_utc=2026-10-17T04:14:59+00:00, last15m_closed_end=2026-10-17T04:15+00:00, prior8high=1.090000, depth_time=2026-10-17T04:15:10+00:00, book20_bid_proxy_usdt=438257, book20_ask_proxy_usdt=399035, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.35%, turnover=5121057. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-17T04:14:59+00:00, last15m_closed_end=2026-10-17T04:15+00:00, prior8high=0.074750, depth_time=2026-10-17T04:15:12+00:00, book20_bid_proxy_usdt=195116, book20_ask_proxy_usdt=320233, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.39%, turnover=21682412. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-17T04:14:59+00:00, last15m_closed_end=2026-10-17T04:15+00:00, prior8high=1.015900, depth_time=2026-10-17T04:15:28+00:00, book20_bid_proxy_usdt=1033196, book20_ask_proxy_usdt=576470, funding_indicative=0.000100, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.77%, turnover=93487852. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-17T04:14:59+00:00, last15m_closed_end=2026-10-17T04:15+00:00, prior8high=277.190000, depth_time=2026-10-17T04:15:22+00:00, book20_bid_proxy_usdt=185573, book20_ask_proxy_usdt=48355, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=76454678. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-17T04:14:59+00:00, last15m_closed_end=2026-10-17T04:15+00:00, prior8high=1160.600000, depth_time=2026-10-17T04:15:15+00:00, book20_bid_proxy_usdt=1217393, book20_ask_proxy_usdt=222525, funding_indicative=0.000040, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.84%, turnover=1374288393. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-17T04:14:59+00:00, last15m_closed_end=2026-10-17T04:15+00:00, prior8high=1.984500, depth_time=2026-10-17T04:15:07+00:00, book20_bid_proxy_usdt=50264, book20_ask_proxy_usdt=31152, funding_indicative=0.000050, next_funding_utc=2026-10-17T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.66%, turnover=14593405. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
