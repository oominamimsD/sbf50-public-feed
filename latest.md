# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T02:45:34Z**
- feed_generated_utc: 2026-11-10T02:45:36+00:00
- source_sha256: `2edb490988f7e5ce59c10a3a6bfdb6148524204b5236fc077e77749a93738bda`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T02:45+00:00, close=74804.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T02:00+00:00, close=75046.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002483|-49.29|-54.87|-48.37|14471659|4.02|
|JCT_USDT|0.009018|-10.98|108.89|-10.06|28622718|4.43|
|ARB_USDT|0.172630|-6.19|8.34|-5.27|31513324|0.58|
|ZEC_USDT|1156.050000|-5.68|-7.81|-4.76|2408256415|0.09|
|DOT_USDT|0.852700|-4.28|-8.71|-3.36|10614783|1.17|
|QNT_USDT|193.180000|-3.42|-4.57|-2.50|38648025|1.55|
|PUMPFUN_USDT|0.003563|-3.23|-13.18|-2.31|8340764|2.81|
|DASH_USDT|46.160000|-3.06|-2.20|-2.14|15684701|2.17|
|WLD_USDT|0.316100|-3.00|-17.07|-2.08|26504778|3.16|
|HBAR_USDT|0.066570|-2.77|-5.53|-1.85|8328263|1.50|
|INJ_USDT|7.992000|-2.26|14.02|-1.34|19544332|1.25|
|SOL_USDT|85.990000|-2.16|-8.04|-1.24|641254014|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002483|0.002304|0.002483|0.76|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.172630|0.172770|0.172630|0.87|N|Y/Y|N/N|Y|N|
|DASH_USDT|46.160000|46.010000|46.180000|0.66|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.852700|0.850800|0.852700|0.92|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.066570|0.066450|0.066570|1.58|N|Y/Y|Y/N|Y|N|
|INJ_USDT|7.992000|7.923000|7.992000|0.67|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.009018|0.008752|0.009022|1.29|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003563|0.003555|0.003563|0.26|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.180000|193.060000|193.180000|1.02|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|85.990000|85.860000|85.990000|0.63|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.316100|0.314400|0.316100|1.26|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1156.050000|1150.050000|1156.050000|1.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T02:45:00+00:00, last15m_closed_end=2026-11-10T02:45+00:00, prior8high=0.002982, depth_time=2026-11-10T02:45:07+00:00, book20_bid_proxy_usdt=63912, book20_ask_proxy_usdt=41049, funding_indicative=0.000006, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-49.29%, turnover=14471659. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T02:45:00+00:00, last15m_closed_end=2026-11-10T02:45+00:00, prior8high=0.175390, depth_time=2026-11-10T02:45:12+00:00, book20_bid_proxy_usdt=45260, book20_ask_proxy_usdt=54512, funding_indicative=-0.000015, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.19%, turnover=31513324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T02:45:00+00:00, last15m_closed_end=2026-11-10T02:45+00:00, prior8high=47.310000, depth_time=2026-11-10T02:45:23+00:00, book20_bid_proxy_usdt=715246, book20_ask_proxy_usdt=623553, funding_indicative=0.000019, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.06%, turnover=15684701. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T02:45:00+00:00, last15m_closed_end=2026-11-10T02:45+00:00, prior8high=0.858400, depth_time=2026-11-10T02:45:13+00:00, book20_bid_proxy_usdt=520368, book20_ask_proxy_usdt=720905, funding_indicative=0.000013, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.28%, turnover=10614783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T02:45:00+00:00, last15m_closed_end=2026-11-10T02:45+00:00, prior8high=0.067110, depth_time=2026-11-10T02:45:26+00:00, book20_bid_proxy_usdt=612826, book20_ask_proxy_usdt=811979, funding_indicative=0.000078, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.77%, turnover=8328263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-10T02:45:00+00:00, last15m_closed_end=2026-11-10T02:45+00:00, prior8high=8.108000, depth_time=2026-11-10T02:45:29+00:00, book20_bid_proxy_usdt=137043, book20_ask_proxy_usdt=373971, funding_indicative=-0.000048, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=19544332. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T02:45:00+00:00, last15m_closed_end=2026-11-10T02:45+00:00, prior8high=0.011124, depth_time=2026-11-10T02:45:10+00:00, book20_bid_proxy_usdt=19071, book20_ask_proxy_usdt=14979, funding_indicative=0.001059, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.98%, turnover=28622718. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T02:45:00+00:00, last15m_closed_end=2026-11-10T02:45+00:00, prior8high=0.003615, depth_time=2026-11-10T02:45:20+00:00, book20_bid_proxy_usdt=2266912, book20_ask_proxy_usdt=2944966, funding_indicative=0.000027, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=8340764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T02:45:00+00:00, last15m_closed_end=2026-11-10T02:45+00:00, prior8high=195.180000, depth_time=2026-11-10T02:45:18+00:00, book20_bid_proxy_usdt=35526, book20_ask_proxy_usdt=115809, funding_indicative=0.000079, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.42%, turnover=38648025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T02:45:00+00:00, last15m_closed_end=2026-11-10T02:45+00:00, prior8high=86.740000, depth_time=2026-11-10T02:45:33+00:00, book20_bid_proxy_usdt=18937445, book20_ask_proxy_usdt=16449396, funding_indicative=0.000013, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=641254014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T02:45:00+00:00, last15m_closed_end=2026-11-10T02:45+00:00, prior8high=0.319200, depth_time=2026-11-10T02:45:23+00:00, book20_bid_proxy_usdt=4233916, book20_ask_proxy_usdt=5023050, funding_indicative=0.000014, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=26504778. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T02:45:00+00:00, last15m_closed_end=2026-11-10T02:45+00:00, prior8high=1178.530000, depth_time=2026-11-10T02:45:14+00:00, book20_bid_proxy_usdt=195384, book20_ask_proxy_usdt=166755, funding_indicative=0.000075, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.68%, turnover=2408256415. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
