# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T19:30:16Z**
- feed_generated_utc: 2026-10-28T19:30:20+00:00
- source_sha256: `031e7d538fafe8e992c558bd7e6019d4bbaf88c0781165aa16616a2dad332d93`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T19:30+00:00, close=81163.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T19:00+00:00, close=80980.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-28T16:00+00:00, close=80528, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AIN_USDT|0.141100|-6.30|252.30|-7.08|7582050|2.83|
|BCH_USDT|287.320000|-1.91|-0.81|-2.69|5388940|0.35|
|XMR_USDT|598.410000|-0.94|0.36|-1.72|5500094|0.50|
|HBAR_USDT|0.075510|-0.52|-12.13|-1.30|12388830|1.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.141100|0.140860|0.140770|0.92|N|Y/Y|N/N|N|N|
|BCH_USDT|287.320000|282.710000|287.320000|0.40|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.075510|0.074570|0.075510|0.94|N|Y/Y|Y/Y|N|N|
|XMR_USDT|598.410000|598.000000|598.440000|0.11|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-10-28T19:30:01+00:00, last15m_closed_end=2026-10-28T19:30+00:00, prior8high=0.148000, depth_time=2026-10-28T19:30:08+00:00, book20_bid_proxy_usdt=8145, book20_ask_proxy_usdt=13703, funding_indicative=0.000776, next_funding_utc=2026-10-28T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.30%, turnover=7582050. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-10-28T19:30:01+00:00, last15m_closed_end=2026-10-28T19:30+00:00, prior8high=287.660000, depth_time=2026-10-28T19:30:11+00:00, book20_bid_proxy_usdt=36438, book20_ask_proxy_usdt=119281, funding_indicative=0.000026, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=5388940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-28T19:30:01+00:00, last15m_closed_end=2026-10-28T19:30+00:00, prior8high=0.075900, depth_time=2026-10-28T19:30:15+00:00, book20_bid_proxy_usdt=706840, book20_ask_proxy_usdt=720798, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.52%, turnover=12388830. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-28T19:30:01+00:00, last15m_closed_end=2026-10-28T19:30+00:00, prior8high=605.630000, depth_time=2026-10-28T19:30:12+00:00, book20_bid_proxy_usdt=11152, book20_ask_proxy_usdt=12832, funding_indicative=0.000100, next_funding_utc=2026-10-29T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.94%, turnover=5500094. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
