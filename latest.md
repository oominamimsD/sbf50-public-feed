# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T21:00:37Z**
- feed_generated_utc: 2026-10-14T21:00:39+00:00
- source_sha256: `176cd866f96e731fe6008a52bcb4569729f8f40b565ae099bc19e2485758b4fb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T21:00+00:00, close=81735.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T21:00+00:00, close=81735.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T20:00+00:00, close=81798.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FET_USDT|0.196000|-5.81|-13.46|-5.97|10758976|5.10|
|BTW_USDT|2.261400|-4.93|82.91|-5.09|61026572|0.44|
|S_USDT|0.053340|-3.96|33.88|-4.12|5687189|1.87|
|INJ_USDT|7.584000|-3.24|3.76|-3.40|35734973|1.32|
|BAT_USDT|0.169620|-2.75|71.05|-2.91|29460013|0.59|
|ENA_USDT|0.194950|-1.87|-14.54|-2.03|36621712|0.51|
|AAVE_USDT|154.090000|-1.70|-10.28|-1.86|24108405|1.30|
|OP_USDT|0.138870|-1.48|16.24|-1.64|40306114|0.72|
|ETHFI_USDT|0.624200|-1.43|-11.91|-1.59|5221237|1.60|
|NEAR_USDT|4.788000|-1.09|-4.88|-1.25|176601091|2.09|
|COPPER_USDT|6.626000|-0.95|-0.88|-1.11|6288020|1.51|
|FILECOIN_USDT|1.086000|-0.94|4.41|-1.10|20767490|0.92|
|ZRO_USDT|1.909200|-0.84|-9.49|-1.00|10252807|1.57|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.090000|153.860000|154.090000|1.59|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.169620|0.167120|0.169610|0.74|N|Y/Y|Y/N|Y|N|
|BTW_USDT|2.261400|2.065400|2.270400|0.66|N|Y/Y|N/N|Y|N|
|COPPER_USDT|6.626000|6.606000|6.626000|0.64|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.194950|0.194310|0.194950|0.85|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.624200|0.618500|0.624200|0.28|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.196000|0.192700|0.196000|0.39|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|1.086000|1.080100|1.086000|3.60|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.584000|7.560000|7.584000|0.84|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.788000|4.765000|4.786000|0.26|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.138870|0.138950|0.138870|0.51|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.053340|0.052430|0.053340|0.28|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.909200|1.892200|1.909200|0.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T21:00:01+00:00, last15m_closed_end=2026-10-14T21:00+00:00, prior8high=155.360000, depth_time=2026-10-14T21:00:21+00:00, book20_bid_proxy_usdt=298112, book20_ask_proxy_usdt=384284, funding_indicative=0.000064, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=24108405. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T21:00:01+00:00, last15m_closed_end=2026-10-14T21:00+00:00, prior8high=0.172860, depth_time=2026-10-14T21:00:17+00:00, book20_bid_proxy_usdt=24796, book20_ask_proxy_usdt=22690, funding_indicative=0.000023, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=29460013. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T21:00:00+00:00, last15m_closed_end=2026-10-14T21:00+00:00, prior8high=2.275500, depth_time=2026-10-14T21:00:10+00:00, book20_bid_proxy_usdt=22800, book20_ask_proxy_usdt=14467, funding_indicative=0.000050, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=61026572. target_RR/account_short_permission/settled_funding=UNKNOWN.
- COPPER_USDT: quote_utc=2026-10-14T21:00:01+00:00, last15m_closed_end=2026-10-14T21:00+00:00, prior8high=6.630000, depth_time=2026-10-14T21:00:28+00:00, book20_bid_proxy_usdt=923895, book20_ask_proxy_usdt=916398, funding_indicative=0.000000, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.95%, turnover=6288020. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-14T21:00:01+00:00, last15m_closed_end=2026-10-14T21:00+00:00, prior8high=0.196930, depth_time=2026-10-14T21:00:19+00:00, book20_bid_proxy_usdt=96137, book20_ask_proxy_usdt=116197, funding_indicative=0.000026, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.87%, turnover=36621712. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-14T21:00:01+00:00, last15m_closed_end=2026-10-14T21:00+00:00, prior8high=0.631300, depth_time=2026-10-14T21:00:25+00:00, book20_bid_proxy_usdt=287794, book20_ask_proxy_usdt=238710, funding_indicative=-0.000005, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=5221237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T21:00:01+00:00, last15m_closed_end=2026-10-14T21:00+00:00, prior8high=0.201900, depth_time=2026-10-14T21:00:07+00:00, book20_bid_proxy_usdt=1115395, book20_ask_proxy_usdt=1043404, funding_indicative=0.000066, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.81%, turnover=10758976. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-14T21:00:01+00:00, last15m_closed_end=2026-10-14T21:00+00:00, prior8high=1.093100, depth_time=2026-10-14T21:00:32+00:00, book20_bid_proxy_usdt=470509, book20_ask_proxy_usdt=435553, funding_indicative=0.000007, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.94%, turnover=20767490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-14T21:00:01+00:00, last15m_closed_end=2026-10-14T21:00+00:00, prior8high=7.795000, depth_time=2026-10-14T21:00:15+00:00, book20_bid_proxy_usdt=332141, book20_ask_proxy_usdt=233750, funding_indicative=0.000116, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.24%, turnover=35734973. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-14T21:00:00+00:00, last15m_closed_end=2026-10-14T21:00+00:00, prior8high=4.849000, depth_time=2026-10-14T21:00:28+00:00, book20_bid_proxy_usdt=1370880, book20_ask_proxy_usdt=1369025, funding_indicative=0.000100, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=176601091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-14T21:00:01+00:00, last15m_closed_end=2026-10-14T21:00+00:00, prior8high=0.141610, depth_time=2026-10-14T21:00:24+00:00, book20_bid_proxy_usdt=26561, book20_ask_proxy_usdt=65046, funding_indicative=-0.000211, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=40306114. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T21:00:01+00:00, last15m_closed_end=2026-10-14T21:00+00:00, prior8high=0.053720, depth_time=2026-10-14T21:00:12+00:00, book20_bid_proxy_usdt=206405, book20_ask_proxy_usdt=123925, funding_indicative=-0.000095, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.96%, turnover=5687189. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-14T21:00:01+00:00, last15m_closed_end=2026-10-14T21:00+00:00, prior8high=1.931900, depth_time=2026-10-14T21:00:36+00:00, book20_bid_proxy_usdt=39194, book20_ask_proxy_usdt=34741, funding_indicative=0.000028, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=10252807. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
