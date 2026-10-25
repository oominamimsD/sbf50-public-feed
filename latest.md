# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T13:45:30Z**
- feed_generated_utc: 2026-10-25T13:45:34+00:00
- source_sha256: `e7594f8e21882cdd821f3209e1e1e1eaa432b3732269b249ee5849da65bf787c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T13:45+00:00, close=80362, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T13:00+00:00, close=80419.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T12:00+00:00, close=80542.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.046910|-30.40|51.56|-31.15|6734554|6.39|
|IRYS_USDT|0.035160|-23.64|175.54|-24.39|25848268|5.70|
|BTW_USDT|1.693400|-2.75|-25.38|-3.50|12677268|2.36|
|STRK_USDT|0.045480|-2.67|-31.24|-3.42|10314430|2.20|
|SUI_USDT|0.914400|-1.14|-6.86|-1.89|70745113|1.09|
|DOT_USDT|1.028300|-1.03|-7.97|-1.78|12716139|0.97|
|APT_USDT|0.695500|-0.91|-12.78|-1.66|6169231|1.44|
|PENGU_USDT|0.007379|-0.85|-0.99|-1.60|6090594|1.35|
|SEI_USDT|0.052490|-0.73|-15.35|-1.48|7828892|1.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.695500|0.689400|0.695500|2.15|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.693400|1.638700|1.695500|1.16|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.028300|1.014400|1.028300|1.02|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.035160|0.033150|0.035160|1.11|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.046910|0.045450|0.046910|0.70|N|Y/Y|N/N|Y|N|
|PENGU_USDT|0.007379|0.007338|0.007379|0.53|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.052490|0.052220|0.052490|1.45|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.045480|0.044870|0.045490|0.72|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.914400|0.910400|0.914400|0.98|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T13:45:03+00:00, last15m_closed_end=2026-10-25T13:45+00:00, prior8high=0.698900, depth_time=2026-10-25T13:45:24+00:00, book20_bid_proxy_usdt=177154, book20_ask_proxy_usdt=165774, funding_indicative=-0.000120, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.91%, turnover=6169231. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T13:45:03+00:00, last15m_closed_end=2026-10-25T13:45+00:00, prior8high=1.701100, depth_time=2026-10-25T13:45:12+00:00, book20_bid_proxy_usdt=13555, book20_ask_proxy_usdt=27477, funding_indicative=-0.009910, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=12677268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T13:45:03+00:00, last15m_closed_end=2026-10-25T13:45+00:00, prior8high=1.028700, depth_time=2026-10-25T13:45:22+00:00, book20_bid_proxy_usdt=318833, book20_ask_proxy_usdt=359614, funding_indicative=-0.000067, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.03%, turnover=12716139. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T13:45:03+00:00, last15m_closed_end=2026-10-25T13:45+00:00, prior8high=0.036030, depth_time=2026-10-25T13:45:11+00:00, book20_bid_proxy_usdt=52736, book20_ask_proxy_usdt=74312, funding_indicative=0.000012, next_funding_utc=2026-10-25T14:00:00+00:00, funding_cycle_h=1, 24h_change=-23.64%, turnover=25848268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T13:45:03+00:00, last15m_closed_end=2026-10-25T13:45+00:00, prior8high=0.048240, depth_time=2026-10-25T13:45:09+00:00, book20_bid_proxy_usdt=100394, book20_ask_proxy_usdt=71945, funding_indicative=-0.000754, next_funding_utc=2026-10-25T14:00:00+00:00, funding_cycle_h=1, 24h_change=-30.40%, turnover=6734554. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-25T13:45:03+00:00, last15m_closed_end=2026-10-25T13:45+00:00, prior8high=0.007422, depth_time=2026-10-25T13:45:27+00:00, book20_bid_proxy_usdt=192059, book20_ask_proxy_usdt=267280, funding_indicative=-0.000053, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.85%, turnover=6090594. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T13:45:03+00:00, last15m_closed_end=2026-10-25T13:45+00:00, prior8high=0.052880, depth_time=2026-10-25T13:45:29+00:00, book20_bid_proxy_usdt=173487, book20_ask_proxy_usdt=441092, funding_indicative=-0.000036, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.73%, turnover=7828892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T13:45:03+00:00, last15m_closed_end=2026-10-25T13:45+00:00, prior8high=0.046180, depth_time=2026-10-25T13:45:16+00:00, book20_bid_proxy_usdt=985890, book20_ask_proxy_usdt=700035, funding_indicative=0.000013, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=10314430. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T13:45:03+00:00, last15m_closed_end=2026-10-25T13:45+00:00, prior8high=0.920400, depth_time=2026-10-25T13:45:18+00:00, book20_bid_proxy_usdt=895820, book20_ask_proxy_usdt=1575956, funding_indicative=-0.000057, next_funding_utc=2026-10-25T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.14%, turnover=70745113. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
