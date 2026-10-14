# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T19:15:22Z**
- feed_generated_utc: 2026-10-14T19:15:24+00:00
- source_sha256: `5e2beb7458713dde8d33f3887e78f0c57b962790ecf041df438ddd9a7d81d9c2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T19:15+00:00, close=81750, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T19:00+00:00, close=81679.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T16:00+00:00, close=81600.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.197200|-7.63|77.72|-7.81|59358670|2.73|
|S_USDT|0.052960|-3.34|32.93|-3.52|6852401|3.78|
|FET_USDT|0.199000|-2.40|-12.14|-2.58|9677213|5.03|
|STRK_USDT|0.075420|-2.28|52.48|-2.46|23932663|1.33|
|BAT_USDT|0.172280|-1.22|73.73|-1.40|35475045|0.58|
|AAVE_USDT|154.490000|-0.89|-10.05|-1.07|23884903|0.65|
|NEAR_USDT|4.801000|-0.82|-4.62|-1.00|176225291|2.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|154.490000|153.970000|154.500000|1.57|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.172280|0.169480|0.172350|0.78|N|Y/Y|N/N|Y|N|
|BTW_USDT|2.197200|2.064400|2.197200|1.24|N|Y/Y|N/N|Y|N|
|FET_USDT|0.199000|0.200100|0.199000|2.71|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.801000|4.805000|4.801000|1.07|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.075420|0.075170|0.075420|0.66|N|Y/Y|Y/Y|Y|N|
|S_USDT|0.052960|0.052320|0.052960|0.34|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-14T19:15:00+00:00, last15m_closed_end=2026-10-14T19:15+00:00, prior8high=158.400000, depth_time=2026-10-14T19:15:19+00:00, book20_bid_proxy_usdt=224486, book20_ask_proxy_usdt=374481, funding_indicative=0.000031, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.89%, turnover=23884903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-14T19:15:00+00:00, last15m_closed_end=2026-10-14T19:15+00:00, prior8high=0.174590, depth_time=2026-10-14T19:15:17+00:00, book20_bid_proxy_usdt=29229, book20_ask_proxy_usdt=21870, funding_indicative=0.000063, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.22%, turnover=35475045. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-14T19:15:00+00:00, last15m_closed_end=2026-10-14T19:15+00:00, prior8high=2.279300, depth_time=2026-10-14T19:15:07+00:00, book20_bid_proxy_usdt=8778, book20_ask_proxy_usdt=12307, funding_indicative=-0.000007, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.63%, turnover=59358670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-14T19:15:00+00:00, last15m_closed_end=2026-10-14T19:15+00:00, prior8high=0.208600, depth_time=2026-10-14T19:15:11+00:00, book20_bid_proxy_usdt=1015264, book20_ask_proxy_usdt=1170947, funding_indicative=0.000009, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=9677213. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-14T19:15:00+00:00, last15m_closed_end=2026-10-14T19:15+00:00, prior8high=4.941000, depth_time=2026-10-14T19:15:21+00:00, book20_bid_proxy_usdt=372007, book20_ask_proxy_usdt=1583546, funding_indicative=0.000100, next_funding_utc=2026-10-15T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.82%, turnover=176225291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T19:15:00+00:00, last15m_closed_end=2026-10-14T19:15+00:00, prior8high=0.077570, depth_time=2026-10-14T19:15:14+00:00, book20_bid_proxy_usdt=245295, book20_ask_proxy_usdt=282236, funding_indicative=0.000043, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=23932663. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T19:15:00+00:00, last15m_closed_end=2026-10-14T19:15+00:00, prior8high=0.053900, depth_time=2026-10-14T19:15:09+00:00, book20_bid_proxy_usdt=129055, book20_ask_proxy_usdt=132439, funding_indicative=-0.000073, next_funding_utc=2026-10-14T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.34%, turnover=6852401. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
