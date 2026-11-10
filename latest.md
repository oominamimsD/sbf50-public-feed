# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T03:15:35Z**
- feed_generated_utc: 2026-11-10T03:15:37+00:00
- source_sha256: `b7ef77c67089bf253109743dd3b05092fcb38e41e48ed5b0007111d59256d406`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T03:15+00:00, close=74742.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T03:00+00:00, close=74843.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002364|-51.72|-57.03|-50.72|14724528|4.22|
|JCT_USDT|0.008290|-18.17|92.03|-17.17|27593288|2.41|
|ARB_USDT|0.172090|-6.49|8.00|-5.49|31268267|0.58|
|ZEC_USDT|1154.820000|-5.78|-7.91|-4.78|2379175411|0.09|
|DOT_USDT|0.850700|-4.51|-8.92|-3.51|10709671|1.18|
|DASH_USDT|45.970000|-3.46|-2.60|-2.46|15186147|2.17|
|QNT_USDT|193.130000|-3.45|-4.60|-2.45|36981040|0.52|
|PUMPFUN_USDT|0.003574|-2.93|-12.91|-1.93|7961983|2.80|
|WLD_USDT|0.316400|-2.91|-16.99|-1.91|26113756|3.16|
|HYPE_USDT|74.136000|-2.85|-13.50|-1.85|45816940|0.14|
|HBAR_USDT|0.066740|-2.52|-5.29|-1.52|9359237|1.50|
|SOL_USDT|86.080000|-2.05|-7.94|-1.05|628747882|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002364|0.002304|0.002365|0.95|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.172090|0.172130|0.172130|0.79|N|Y/Y|N/N|Y|N|
|DASH_USDT|45.970000|45.970000|45.970000|0.03|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.850700|0.850200|0.850700|2.04|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.066740|0.066500|0.066740|31.63|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|74.136000|73.740000|74.136000|0.81|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.008290|0.008752|0.008282|1.71|Y|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003574|0.003550|0.003574|0.26|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.130000|192.510000|193.130000|0.46|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.080000|85.840000|86.080000|2.65|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.316400|0.314400|0.316400|0.50|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1154.820000|1141.980000|1154.450000|1.06|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T03:15:01+00:00, last15m_closed_end=2026-11-10T03:15+00:00, prior8high=0.002982, depth_time=2026-11-10T03:15:07+00:00, book20_bid_proxy_usdt=88749, book20_ask_proxy_usdt=31732, funding_indicative=0.000050, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-51.72%, turnover=14724528. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T03:15:01+00:00, last15m_closed_end=2026-11-10T03:15+00:00, prior8high=0.175390, depth_time=2026-11-10T03:15:12+00:00, book20_bid_proxy_usdt=56640, book20_ask_proxy_usdt=61168, funding_indicative=-0.000008, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.49%, turnover=31268267. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T03:15:02+00:00, last15m_closed_end=2026-11-10T03:15+00:00, prior8high=47.310000, depth_time=2026-11-10T03:15:18+00:00, book20_bid_proxy_usdt=689192, book20_ask_proxy_usdt=591163, funding_indicative=-0.000002, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.46%, turnover=15186147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T03:15:01+00:00, last15m_closed_end=2026-11-10T03:15+00:00, prior8high=0.858400, depth_time=2026-11-10T03:15:17+00:00, book20_bid_proxy_usdt=623321, book20_ask_proxy_usdt=734299, funding_indicative=0.000005, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.51%, turnover=10709671. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T03:15:01+00:00, last15m_closed_end=2026-11-10T03:15+00:00, prior8high=0.067110, depth_time=2026-11-10T03:15:27+00:00, book20_bid_proxy_usdt=708011, book20_ask_proxy_usdt=706940, funding_indicative=0.000061, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.52%, turnover=9359237. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T03:15:01+00:00, last15m_closed_end=2026-11-10T03:15+00:00, prior8high=75.171000, depth_time=2026-11-10T03:15:30+00:00, book20_bid_proxy_usdt=146815, book20_ask_proxy_usdt=76190, funding_indicative=0.000034, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.85%, turnover=45816940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T03:15:01+00:00, last15m_closed_end=2026-11-10T03:15+00:00, prior8high=0.011124, depth_time=2026-11-10T03:15:10+00:00, book20_bid_proxy_usdt=13944, book20_ask_proxy_usdt=17051, funding_indicative=0.000764, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-18.17%, turnover=27593288. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T03:15:01+00:00, last15m_closed_end=2026-11-10T03:15+00:00, prior8high=0.003615, depth_time=2026-11-10T03:15:22+00:00, book20_bid_proxy_usdt=2633218, book20_ask_proxy_usdt=2832052, funding_indicative=0.000028, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.93%, turnover=7961983. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T03:15:01+00:00, last15m_closed_end=2026-11-10T03:15+00:00, prior8high=195.180000, depth_time=2026-11-10T03:15:19+00:00, book20_bid_proxy_usdt=35278, book20_ask_proxy_usdt=120910, funding_indicative=0.000039, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.45%, turnover=36981040. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T03:15:01+00:00, last15m_closed_end=2026-11-10T03:15+00:00, prior8high=86.740000, depth_time=2026-11-10T03:15:34+00:00, book20_bid_proxy_usdt=20500735, book20_ask_proxy_usdt=18218032, funding_indicative=0.000008, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=628747882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T03:15:01+00:00, last15m_closed_end=2026-11-10T03:15+00:00, prior8high=0.319100, depth_time=2026-11-10T03:15:26+00:00, book20_bid_proxy_usdt=4813124, book20_ask_proxy_usdt=5430718, funding_indicative=0.000029, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=26113756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T03:15:01+00:00, last15m_closed_end=2026-11-10T03:15+00:00, prior8high=1178.530000, depth_time=2026-11-10T03:15:15+00:00, book20_bid_proxy_usdt=369342, book20_ask_proxy_usdt=118238, funding_indicative=0.000070, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.78%, turnover=2379175411. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
