# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T14:45:34Z**
- feed_generated_utc: 2026-10-25T14:45:37+00:00
- source_sha256: `6e44b8c4873db3db53242729182950606676e1beacd02a74b048f8007215f38a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T14:45+00:00, close=80388.6, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T14:00+00:00, close=80346.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.045920|-31.86|48.36|-32.64|5869696|8.70|
|IRYS_USDT|0.036990|-19.67|189.89|-20.45|25448813|2.70|
|BTW_USDT|1.667400|-4.24|-26.52|-5.02|12500256|3.00|
|STRK_USDT|0.044990|-3.72|-31.98|-4.50|10892636|2.22|
|WLD_USDT|0.448000|-3.03|-9.60|-3.81|96269749|2.23|
|SUI_USDT|0.911000|-1.51|-7.21|-2.29|72551549|1.10|
|DOT_USDT|1.024400|-1.41|-8.32|-2.19|12720252|1.95|
|APT_USDT|0.694000|-1.12|-12.97|-1.90|5957123|1.44|
|PENGU_USDT|0.007368|-1.00|-1.14|-1.78|6010081|1.36|
|SEI_USDT|0.052440|-0.83|-15.43|-1.61|6192448|1.91|
|LINK_USDT|11.350000|-0.28|-4.66|-1.06|48687365|0.88|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.694000|0.690500|0.693900|1.69|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.667400|1.669000|1.667600|1.00|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.024400|1.021400|1.024400|0.39|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.036990|0.033150|0.036850|1.41|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.350000|11.326000|11.350000|0.76|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.045920|0.045450|0.045920|0.69|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007368|0.007340|0.007368|0.55|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052440|0.052220|0.052440|0.64|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044990|0.044430|0.045000|2.75|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.911000|0.907700|0.911000|1.42|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.448000|0.445900|0.448000|0.65|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T14:45:02+00:00, last15m_closed_end=2026-10-25T14:45+00:00, prior8high=0.698000, depth_time=2026-10-25T14:45:25+00:00, book20_bid_proxy_usdt=175891, book20_ask_proxy_usdt=158051, funding_indicative=-0.000111, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=5957123. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T14:45:02+00:00, last15m_closed_end=2026-10-25T14:45+00:00, prior8high=1.701100, depth_time=2026-10-25T14:45:13+00:00, book20_bid_proxy_usdt=7807, book20_ask_proxy_usdt=14137, funding_indicative=-0.008785, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.24%, turnover=12500256. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T14:45:02+00:00, last15m_closed_end=2026-10-25T14:45+00:00, prior8high=1.031100, depth_time=2026-10-25T14:45:23+00:00, book20_bid_proxy_usdt=308658, book20_ask_proxy_usdt=327009, funding_indicative=-0.000128, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=12720252. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T14:45:01+00:00, last15m_closed_end=2026-10-25T14:45+00:00, prior8high=0.040280, depth_time=2026-10-25T14:45:11+00:00, book20_bid_proxy_usdt=37560, book20_ask_proxy_usdt=47997, funding_indicative=-0.000050, next_funding_utc=2026-10-25T15:00:00+00:00, funding_cycle_h=1, 24h_change=-19.67%, turnover=25448813. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-25T14:45:02+00:00, last15m_closed_end=2026-10-25T14:45+00:00, prior8high=11.417000, depth_time=2026-10-25T14:45:30+00:00, book20_bid_proxy_usdt=487716, book20_ask_proxy_usdt=412343, funding_indicative=-0.000048, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.28%, turnover=48687365. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T14:45:01+00:00, last15m_closed_end=2026-10-25T14:45+00:00, prior8high=0.048570, depth_time=2026-10-25T14:45:09+00:00, book20_bid_proxy_usdt=89938, book20_ask_proxy_usdt=133982, funding_indicative=-0.001081, next_funding_utc=2026-10-25T15:00:00+00:00, funding_cycle_h=1, 24h_change=-31.86%, turnover=5869696. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T14:45:02+00:00, last15m_closed_end=2026-10-25T14:45+00:00, prior8high=0.007403, depth_time=2026-10-25T14:45:25+00:00, book20_bid_proxy_usdt=186515, book20_ask_proxy_usdt=163264, funding_indicative=-0.000045, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.00%, turnover=6010081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T14:45:02+00:00, last15m_closed_end=2026-10-25T14:45+00:00, prior8high=0.052590, depth_time=2026-10-25T14:45:30+00:00, book20_bid_proxy_usdt=240572, book20_ask_proxy_usdt=289178, funding_indicative=0.000001, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.83%, turnover=6192448. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T14:45:02+00:00, last15m_closed_end=2026-10-25T14:45+00:00, prior8high=0.045750, depth_time=2026-10-25T14:45:15+00:00, book20_bid_proxy_usdt=536440, book20_ask_proxy_usdt=773239, funding_indicative=0.000017, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.72%, turnover=10892636. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T14:45:01+00:00, last15m_closed_end=2026-10-25T14:45+00:00, prior8high=0.919500, depth_time=2026-10-25T14:45:20+00:00, book20_bid_proxy_usdt=1156852, book20_ask_proxy_usdt=1121795, funding_indicative=-0.000047, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=72551549. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-25T14:45:01+00:00, last15m_closed_end=2026-10-25T14:45+00:00, prior8high=0.452300, depth_time=2026-10-25T14:45:18+00:00, book20_bid_proxy_usdt=1747908, book20_ask_proxy_usdt=1402952, funding_indicative=-0.000070, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.03%, turnover=96269749. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
