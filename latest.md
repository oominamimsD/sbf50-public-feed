# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T10:45:18Z**
- feed_generated_utc: 2026-11-06T10:45:19+00:00
- source_sha256: `f15461b9365cbd4bbd8dba508990411076d9fe3588dcecab862a9544708a511b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T10:45+00:00, close=76194.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T10:00+00:00, close=76151.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|268.040000|-3.96|-7.02|-4.19|7594922|3.36|
|XRP_USDT|1.199200|-3.64|-8.42|-3.87|481571807|0.83|
|XPL_USDT|0.057630|-1.62|-26.98|-1.85|12316451|3.47|
|QNT_USDT|189.280000|-1.32|-4.75|-1.55|36273669|1.58|
|ATOM_USDT|1.409000|-0.77|-13.61|-1.00|6999894|7.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ATOM_USDT|1.409000|1.409000|1.409000|0.73|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|268.040000|265.190000|268.040000|2.25|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|189.280000|188.370000|189.280000|1.03|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.057630|0.057370|0.057620|1.02|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.199200|1.187400|1.199200|1.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ATOM_USDT: quote_utc=2026-11-06T10:45:02+00:00, last15m_closed_end=2026-11-06T10:45+00:00, prior8high=1.423000, depth_time=2026-11-06T10:45:13+00:00, book20_bid_proxy_usdt=2231791, book20_ask_proxy_usdt=2348324, funding_indicative=0.000036, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.77%, turnover=6999894. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-06T10:45:02+00:00, last15m_closed_end=2026-11-06T10:45+00:00, prior8high=269.310000, depth_time=2026-11-06T10:45:07+00:00, book20_bid_proxy_usdt=47142, book20_ask_proxy_usdt=95799, funding_indicative=-0.000049, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.96%, turnover=7594922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-06T10:45:02+00:00, last15m_closed_end=2026-11-06T10:45+00:00, prior8high=189.850000, depth_time=2026-11-06T10:45:15+00:00, book20_bid_proxy_usdt=69852, book20_ask_proxy_usdt=115278, funding_indicative=0.000011, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.32%, turnover=36273669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T10:45:02+00:00, last15m_closed_end=2026-11-06T10:45+00:00, prior8high=0.057950, depth_time=2026-11-06T10:45:11+00:00, book20_bid_proxy_usdt=489750, book20_ask_proxy_usdt=392176, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.62%, turnover=12316451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T10:45:01+00:00, last15m_closed_end=2026-11-06T10:45+00:00, prior8high=1.201800, depth_time=2026-11-06T10:45:09+00:00, book20_bid_proxy_usdt=3219852, book20_ask_proxy_usdt=3762077, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.64%, turnover=481571807. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
