# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T19:00:30Z**
- feed_generated_utc: 2026-10-29T19:00:32+00:00
- source_sha256: `41f537817d909b951ed7a0e03cb902a2d873e3991d9697e73e9bff2b8be18310`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T19:00+00:00, close=80824.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-29T19:00+00:00, close=80824.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T16:00+00:00, close=81732.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.488700|-9.12|-16.83|-8.02|9615289|0.67|
|EVAA_USDT|1.105800|-6.73|112.65|-5.63|11923681|9.91|
|APT_USDT|0.669900|-4.74|-13.24|-3.64|9398541|1.49|
|Q_USDT|0.036860|-4.03|-71.39|-2.93|24885298|5.43|
|QNT_USDT|190.220000|-3.06|-0.25|-1.96|62596804|0.53|
|ICP_USDT|2.552000|-2.85|-7.09|-1.75|5223789|3.92|
|FET_USDT|0.178300|-2.72|-3.77|-1.62|9337039|5.61|
|TRUMPOFFICIAL_USDT|1.667000|-2.22|-4.41|-1.12|6287540|6.00|
|FILECOIN_USDT|0.892000|-2.13|-7.27|-1.03|9629685|1.12|
|NEAR_USDT|4.425000|-2.10|-10.49|-1.00|111147984|2.26|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.669900|0.667500|0.670000|0.29|N|Y/N|N/Y|N|N|
|BTW_USDT|1.488700|1.487000|1.488400|1.02|N|Y/Y|Y/N|N|N|
|EVAA_USDT|1.105800|1.080800|1.105800|0.44|N|Y/Y|N/N|N|N|
|FET_USDT|0.178300|0.176800|0.178300|0.45|N|Y/Y|N/N|N|N|
|FILECOIN_USDT|0.892000|0.887600|0.892000|0.45|N|Y/Y|N/Y|N|N|
|ICP_USDT|2.552000|2.541000|2.553000|2.11|N|Y/Y|N/Y|N|N|
|NEAR_USDT|4.425000|4.406000|4.425000|0.86|N|Y/Y|N/Y|N|N|
|QNT_USDT|190.220000|188.850000|190.220000|0.72|N|Y/Y|N/Y|N|N|
|Q_USDT|0.036860|0.035860|0.036900|0.53|N|Y/Y|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.667000|1.656000|1.667000|0.46|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-29T19:00:02+00:00, last15m_closed_end=2026-10-29T19:00+00:00, prior8high=0.694300, depth_time=2026-10-29T19:00:12+00:00, book20_bid_proxy_usdt=179790, book20_ask_proxy_usdt=156820, funding_indicative=0.000097, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.74%, turnover=9398541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T19:00:02+00:00, last15m_closed_end=2026-10-29T19:00+00:00, prior8high=1.602600, depth_time=2026-10-29T19:00:07+00:00, book20_bid_proxy_usdt=16978, book20_ask_proxy_usdt=15509, funding_indicative=-0.000003, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.12%, turnover=9615289. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T19:00:01+00:00, last15m_closed_end=2026-10-29T19:00+00:00, prior8high=1.173800, depth_time=2026-10-29T19:00:10+00:00, book20_bid_proxy_usdt=15076, book20_ask_proxy_usdt=11484, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.73%, turnover=11923681. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-29T19:00:02+00:00, last15m_closed_end=2026-10-29T19:00+00:00, prior8high=0.183000, depth_time=2026-10-29T19:00:20+00:00, book20_bid_proxy_usdt=1320769, book20_ask_proxy_usdt=1064553, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.72%, turnover=9337039. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-29T19:00:02+00:00, last15m_closed_end=2026-10-29T19:00+00:00, prior8high=0.913000, depth_time=2026-10-29T19:00:25+00:00, book20_bid_proxy_usdt=1225406, book20_ask_proxy_usdt=1087565, funding_indicative=0.000061, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=9629685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-29T19:00:02+00:00, last15m_closed_end=2026-10-29T19:00+00:00, prior8high=2.608000, depth_time=2026-10-29T19:00:19+00:00, book20_bid_proxy_usdt=1221453, book20_ask_proxy_usdt=1237532, funding_indicative=0.000034, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=5223789. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-29T19:00:01+00:00, last15m_closed_end=2026-10-29T19:00+00:00, prior8high=4.604000, depth_time=2026-10-29T19:00:29+00:00, book20_bid_proxy_usdt=4467979, book20_ask_proxy_usdt=4412958, funding_indicative=0.000100, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=111147984. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-29T19:00:02+00:00, last15m_closed_end=2026-10-29T19:00+00:00, prior8high=197.720000, depth_time=2026-10-29T19:00:17+00:00, book20_bid_proxy_usdt=92557, book20_ask_proxy_usdt=58504, funding_indicative=-0.000078, next_funding_utc=2026-10-30T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=62596804. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T19:00:01+00:00, last15m_closed_end=2026-10-29T19:00+00:00, prior8high=0.039520, depth_time=2026-10-29T19:00:14+00:00, book20_bid_proxy_usdt=101946, book20_ask_proxy_usdt=55764, funding_indicative=0.000035, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.03%, turnover=24885298. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-29T19:00:02+00:00, last15m_closed_end=2026-10-29T19:00+00:00, prior8high=1.708000, depth_time=2026-10-29T19:00:19+00:00, book20_bid_proxy_usdt=1867954, book20_ask_proxy_usdt=1709031, funding_indicative=0.000050, next_funding_utc=2026-10-29T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.22%, turnover=6287540. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
