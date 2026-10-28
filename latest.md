# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T23:30:19Z**
- feed_generated_utc: 2026-10-28T23:30:24+00:00
- source_sha256: `7257cdee8d43af3c64208b778a3de5d74649ff6acb5b5cf47c9e3e2a9874a83c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.08 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T23:30+00:00, close=81313.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T23:00+00:00, close=81236, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T20:00+00:00, close=81544.7, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.010820|-1.25|34.44|-2.22|23880901|9.25|
|HBAR_USDT|0.075000|-1.19|-12.72|-2.16|12345796|1.33|
|BTW_USDT|1.719000|-1.09|16.95|-2.06|11559149|0.58|
|BCH_USDT|289.820000|-1.06|0.04|-2.03|5894621|3.45|
|XMR_USDT|599.180000|-0.81|0.49|-1.78|5437367|2.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|289.820000|288.270000|289.820000|0.27|N|Y/Y|N/N|N|N|
|BLESS_USDT|0.010820|0.010625|0.010820|0.57|N|Y/N|N/N|N|N|
|BTW_USDT|1.719000|1.719100|1.719000|2.52|Y|N/N|N/N|N|N|
|HBAR_USDT|0.075000|0.074820|0.075000|0.30|N|Y/Y|Y/Y|N|N|
|XMR_USDT|599.180000|597.350000|599.180000|0.29|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-10-28T23:30:01+00:00, last15m_closed_end=2026-10-28T23:30+00:00, prior8high=291.470000, depth_time=2026-10-28T23:30:16+00:00, book20_bid_proxy_usdt=49276, book20_ask_proxy_usdt=74538, funding_indicative=-0.000002, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=5894621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-28T23:30:00+00:00, last15m_closed_end=2026-10-28T23:30+00:00, prior8high=0.011275, depth_time=2026-10-28T23:30:08+00:00, book20_bid_proxy_usdt=11086, book20_ask_proxy_usdt=7173, funding_indicative=0.000156, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.25%, turnover=23880901. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-28T23:30:00+00:00, last15m_closed_end=2026-10-28T23:30+00:00, prior8high=1.751000, depth_time=2026-10-28T23:30:12+00:00, book20_bid_proxy_usdt=17728, book20_ask_proxy_usdt=22401, funding_indicative=0.000050, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.09%, turnover=11559149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T23:30:01+00:00, last15m_closed_end=2026-10-28T23:30+00:00, prior8high=0.076200, depth_time=2026-10-28T23:30:11+00:00, book20_bid_proxy_usdt=1338390, book20_ask_proxy_usdt=971651, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.19%, turnover=12345796. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T23:30:01+00:00, last15m_closed_end=2026-10-28T23:30+00:00, prior8high=609.340000, depth_time=2026-10-28T23:30:17+00:00, book20_bid_proxy_usdt=5921, book20_ask_proxy_usdt=14917, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.81%, turnover=5437367. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
