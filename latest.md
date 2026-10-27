# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T07:30:41Z**
- feed_generated_utc: 2026-10-27T07:30:44+00:00
- source_sha256: `bc3429bbe2cd61fcd0c019b2dc183a15452c0b761dc2f1ffd3d4e7daf91d4a64`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T07:30+00:00, close=79687.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T07:00+00:00, close=79629.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T04:00+00:00, close=79790.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AAVE_USDT|131.310000|-3.96|-10.80|-3.08|24601413|0.76|
|PUMPFUN_USDT|0.004160|-3.88|-6.64|-3.00|21343729|2.40|
|NEAR_USDT|4.417000|-3.41|-9.93|-2.53|95527949|2.27|
|DOT_USDT|0.990800|-3.10|-13.60|-2.22|10788376|1.01|
|FILECOIN_USDT|0.895400|-2.74|-11.52|-1.86|6151842|1.12|
|ONDO_USDT|0.407600|-2.67|-5.77|-1.79|22919732|2.45|
|AVAX_USDT|8.762000|-2.61|-8.36|-1.73|43213900|1.14|
|SILVER_USDT|52.970000|-2.32|-7.66|-1.44|256528664|1.89|
|FET_USDT|0.172500|-2.32|-8.73|-1.44|6749580|5.80|
|SOL_USDT|99.690000|-2.11|-4.22|-1.23|710365151|1.00|
|PEPE_USDT|0.000004|-2.10|3.92|-1.22|65345075|0.47|
|WLD_USDT|0.435700|-2.08|-13.94|-1.20|68095881|2.30|
|PENGU_USDT|0.007420|-2.03|-0.94|-1.15|5357806|1.35|
|TAO_USDT|248.530000|-1.96|-7.36|-1.08|45535123|1.21|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.310000|131.060000|131.310000|0.94|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.762000|8.656000|8.762000|0.24|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.990800|0.984100|0.990800|0.76|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.172500|0.171200|0.172500|0.49|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.895400|0.888900|0.895400|2.52|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.417000|4.405000|4.417000|0.90|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.407600|0.404900|0.407600|2.56|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007420|0.007397|0.007419|1.14|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|2.00|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.004160|0.004131|0.004160|0.29|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.970000|52.800000|52.980000|0.28|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|99.690000|99.380000|99.690000|2.16|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|248.530000|247.340000|248.600000|1.96|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.435700|0.432500|0.435700|0.96|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T07:30:01+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=132.750000, depth_time=2026-10-27T07:30:06+00:00, book20_bid_proxy_usdt=833868, book20_ask_proxy_usdt=425898, funding_indicative=0.000069, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.96%, turnover=24601413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T07:30:01+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=8.786000, depth_time=2026-10-27T07:30:22+00:00, book20_bid_proxy_usdt=1090278, book20_ask_proxy_usdt=935891, funding_indicative=-0.000087, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=43213900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T07:30:01+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=0.992100, depth_time=2026-10-27T07:30:15+00:00, book20_bid_proxy_usdt=421189, book20_ask_proxy_usdt=446976, funding_indicative=-0.000069, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.10%, turnover=10788376. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T07:30:01+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=0.173200, depth_time=2026-10-27T07:30:26+00:00, book20_bid_proxy_usdt=1828128, book20_ask_proxy_usdt=764246, funding_indicative=-0.000027, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=6749580. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T07:30:01+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=0.899300, depth_time=2026-10-27T07:30:15+00:00, book20_bid_proxy_usdt=1177661, book20_ask_proxy_usdt=1126238, funding_indicative=0.000001, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=6151842. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T07:30:00+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=4.459000, depth_time=2026-10-27T07:30:11+00:00, book20_bid_proxy_usdt=4910482, book20_ask_proxy_usdt=5296433, funding_indicative=0.000059, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.41%, turnover=95527949. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T07:30:01+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=0.408800, depth_time=2026-10-27T07:30:19+00:00, book20_bid_proxy_usdt=2303391, book20_ask_proxy_usdt=2575320, funding_indicative=0.000015, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.67%, turnover=22919732. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-27T07:30:01+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=0.007461, depth_time=2026-10-27T07:30:37+00:00, book20_bid_proxy_usdt=200922, book20_ask_proxy_usdt=286228, funding_indicative=0.000032, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.03%, turnover=5357806. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-27T07:30:01+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=0.000004, depth_time=2026-10-27T07:30:32+00:00, book20_bid_proxy_usdt=47334, book20_ask_proxy_usdt=117544, funding_indicative=0.000088, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.10%, turnover=65345075. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T07:30:01+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=0.004181, depth_time=2026-10-27T07:30:09+00:00, book20_bid_proxy_usdt=2207116, book20_ask_proxy_usdt=2577310, funding_indicative=0.000027, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.88%, turnover=21343729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-27T07:30:00+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=53.550000, depth_time=2026-10-27T07:30:25+00:00, book20_bid_proxy_usdt=50961429, book20_ask_proxy_usdt=40036172, funding_indicative=0.000115, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.32%, turnover=256528664. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-10-27T07:30:00+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=100.260000, depth_time=2026-10-27T07:30:29+00:00, book20_bid_proxy_usdt=17641717, book20_ask_proxy_usdt=19457201, funding_indicative=0.000039, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=710365151. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T07:30:00+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=249.330000, depth_time=2026-10-27T07:30:40+00:00, book20_bid_proxy_usdt=102623, book20_ask_proxy_usdt=98002, funding_indicative=0.000046, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=45535123. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T07:30:00+00:00, last15m_closed_end=2026-10-27T07:30+00:00, prior8high=0.438400, depth_time=2026-10-27T07:30:35+00:00, book20_bid_proxy_usdt=2779401, book20_ask_proxy_usdt=3483140, funding_indicative=-0.000229, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=68095881. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
