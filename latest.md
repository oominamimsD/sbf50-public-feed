# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T07:45:36Z**
- feed_generated_utc: 2026-10-31T07:45:38+00:00
- source_sha256: `07f30018004a5016e465aa1546b64330a3f58702e0dfe57b89a977e12757623a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T07:45+00:00, close=77292.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T07:00+00:00, close=77350.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T04:00+00:00, close=77131.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010333|-45.38|-70.47|-45.02|7665452|1.94|
|Q_USDT|0.032900|-30.70|-72.19|-30.34|19043674|3.04|
|BEAT_USDT|0.097140|-7.61|33.82|-7.25|8524156|3.09|
|EVAA_USDT|1.212100|-5.45|130.92|-5.09|5836071|2.46|
|HYPE_USDT|88.157000|-4.53|12.43|-4.17|106836541|0.11|
|TRX_USDT|0.321470|-4.18|-2.38|-3.82|6112888|0.31|
|WLD_USDT|0.397300|-3.54|-25.37|-3.18|48357444|2.52|
|ZRO_USDT|1.687700|-3.54|-6.72|-3.18|5561072|1.19|
|BTW_USDT|1.165900|-2.80|-31.51|-2.44|9563694|1.71|
|FET_USDT|0.162100|-2.70|-13.45|-2.34|6396633|6.17|
|DASH_USDT|47.750000|-2.63|-11.32|-2.27|14377580|2.09|
|LTC_USDT|54.860000|-1.54|-6.14|-1.18|6588078|3.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010333|0.011055|0.010390|6.90|Y|Y/Y|Y/Y|Y|Y|
|BEAT_USDT|0.097140|0.096280|0.097140|0.61|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.165900|1.124600|1.165900|1.04|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.750000|47.870000|47.750000|6.07|Y|Y/Y|Y/Y|Y|Y|
|EVAA_USDT|1.212100|1.168700|1.212100|1.09|N|Y/Y|N/N|Y|N|
|FET_USDT|0.162100|0.162200|0.162100|6.21|Y|Y/Y|Y/Y|Y|Y|
|HYPE_USDT|88.157000|88.038000|88.157000|1.51|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.860000|55.080000|54.870000|3.52|Y|Y/Y|Y/Y|Y|Y|
|Q_USDT|0.032900|0.027750|0.033020|0.37|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.321470|0.323000|0.321470|3.52|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.397300|0.395300|0.397300|1.44|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.687700|1.691100|1.687700|6.31|Y|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T07:45:01+00:00, last15m_closed_end=2026-10-31T07:45+00:00, prior8high=0.013029, depth_time=2026-10-31T07:45:08+00:00, book20_bid_proxy_usdt=4566, book20_ask_proxy_usdt=6105, funding_indicative=-0.000477, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-45.38%, turnover=7665452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T07:45:01+00:00, last15m_closed_end=2026-10-31T07:45+00:00, prior8high=0.098520, depth_time=2026-10-31T07:45:12+00:00, book20_bid_proxy_usdt=15802, book20_ask_proxy_usdt=14094, funding_indicative=0.000177, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.61%, turnover=8524156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T07:45:01+00:00, last15m_closed_end=2026-10-31T07:45+00:00, prior8high=1.176000, depth_time=2026-10-31T07:45:28+00:00, book20_bid_proxy_usdt=23908, book20_ask_proxy_usdt=15304, funding_indicative=-0.000528, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.80%, turnover=9563694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T07:45:02+00:00, last15m_closed_end=2026-10-31T07:45+00:00, prior8high=48.190000, depth_time=2026-10-31T07:45:31+00:00, book20_bid_proxy_usdt=758094, book20_ask_proxy_usdt=670963, funding_indicative=0.000067, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.63%, turnover=14377580. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T07:45:01+00:00, last15m_closed_end=2026-10-31T07:45+00:00, prior8high=1.242000, depth_time=2026-10-31T07:45:16+00:00, book20_bid_proxy_usdt=5006, book20_ask_proxy_usdt=8915, funding_indicative=0.000253, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.45%, turnover=5836071. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T07:45:02+00:00, last15m_closed_end=2026-10-31T07:45+00:00, prior8high=0.164200, depth_time=2026-10-31T07:45:28+00:00, book20_bid_proxy_usdt=1229465, book20_ask_proxy_usdt=906135, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.70%, turnover=6396633. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T07:45:01+00:00, last15m_closed_end=2026-10-31T07:45+00:00, prior8high=89.040000, depth_time=2026-10-31T07:45:18+00:00, book20_bid_proxy_usdt=135165, book20_ask_proxy_usdt=109939, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.53%, turnover=106836541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T07:45:02+00:00, last15m_closed_end=2026-10-31T07:45+00:00, prior8high=55.350000, depth_time=2026-10-31T07:45:30+00:00, book20_bid_proxy_usdt=1085283, book20_ask_proxy_usdt=1176393, funding_indicative=0.000024, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=6588078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T07:45:01+00:00, last15m_closed_end=2026-10-31T07:45+00:00, prior8high=0.033340, depth_time=2026-10-31T07:45:11+00:00, book20_bid_proxy_usdt=28202, book20_ask_proxy_usdt=52523, funding_indicative=-0.000766, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=1, 24h_change=-30.70%, turnover=19043674. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T07:45:01+00:00, last15m_closed_end=2026-10-31T07:45+00:00, prior8high=0.326220, depth_time=2026-10-31T07:45:21+00:00, book20_bid_proxy_usdt=114144, book20_ask_proxy_usdt=87903, funding_indicative=-0.000469, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.18%, turnover=6112888. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T07:45:01+00:00, last15m_closed_end=2026-10-31T07:45+00:00, prior8high=0.401700, depth_time=2026-10-31T07:45:23+00:00, book20_bid_proxy_usdt=3355383, book20_ask_proxy_usdt=2724448, funding_indicative=0.000100, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.54%, turnover=48357444. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-31T07:45:02+00:00, last15m_closed_end=2026-10-31T07:45+00:00, prior8high=1.728600, depth_time=2026-10-31T07:45:26+00:00, book20_bid_proxy_usdt=27875, book20_ask_proxy_usdt=44017, funding_indicative=0.000050, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.54%, turnover=5561072. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
