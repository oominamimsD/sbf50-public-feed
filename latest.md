# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-09T13:30:40Z**
- feed_generated_utc: 2026-11-09T13:30:42+00:00
- source_sha256: `e4f7dcbc8f5f64b42fe28ca8ccd488c3f5111c491deb44804c48bf59effdb2e3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-09T13:30+00:00, close=74748.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-09T13:00+00:00, close=74895.8, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-09T12:00+00:00, close=74345.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001494|-23.72|28.25|-22.03|6244076|0.67|
|AKE_USDT|0.004815|-10.11|-47.43|-8.42|9170863|2.08|
|ASTER_USDT|0.640700|-5.75|-8.39|-4.06|5710297|1.56|
|ETH_USDT|2120.750000|-5.37|-6.40|-3.68|1602690158|0.05|
|HYPE_USDT|73.474000|-5.11|-16.20|-3.42|49780600|0.27|
|XRP_USDT|1.096800|-5.10|-12.24|-3.41|291059590|0.91|
|TRUMPOFFICIAL_USDT|1.132000|-4.79|-34.03|-3.10|6325871|8.84|
|ZEC_USDT|1217.940000|-4.15|-1.61|-2.46|2325025502|0.08|
|NEAR_USDT|3.552000|-4.02|-17.98|-2.33|47484833|2.82|
|AIOT_USDT|0.145670|-3.62|66.02|-1.93|7317054|4.79|
|JCT_USDT|0.009489|-3.50|90.58|-1.81|61172647|5.27|
|SOL_USDT|86.630000|-3.40|-8.57|-1.71|751701831|1.15|
|HOT_USDT|0.000415|-3.35|15.46|-1.66|6847611|4.82|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIOT_USDT|0.145670|0.143010|0.145670|0.56|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.004815|0.004635|0.004815|0.36|N|Y/N|N/Y|Y|N|
|ASTER_USDT|0.640700|0.628900|0.640700|0.37|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2120.750000|2104.860000|2120.750000|0.56|N|Y/Y|Y/Y|Y|N|
|HOT_USDT|0.000415|0.000411|0.000415|0.58|N|Y/N|N/N|Y|N|
|HYPE_USDT|73.474000|72.851000|73.474000|0.48|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.009489|0.008306|0.009490|1.97|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.552000|3.483000|3.552000|1.46|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001494|0.001487|0.001494|1.82|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|86.630000|85.820000|86.620000|0.42|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.132000|1.125000|1.132000|0.81|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.096800|1.077300|1.096800|0.93|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1217.940000|1201.310000|1217.950000|0.83|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AIOT_USDT: quote_utc=2026-11-09T13:29:58+00:00, last15m_closed_end=2026-11-09T13:30+00:00, prior8high=0.163100, depth_time=2026-11-09T13:30:32+00:00, book20_bid_proxy_usdt=6268, book20_ask_proxy_usdt=7103, funding_indicative=0.000170, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.62%, turnover=7317054. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-09T13:29:59+00:00, last15m_closed_end=2026-11-09T13:30+00:00, prior8high=0.005718, depth_time=2026-11-09T13:30:09+00:00, book20_bid_proxy_usdt=36348, book20_ask_proxy_usdt=45845, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.11%, turnover=9170863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ASTER_USDT: quote_utc=2026-11-09T13:29:59+00:00, last15m_closed_end=2026-11-09T13:30+00:00, prior8high=0.643800, depth_time=2026-11-09T13:30:11+00:00, book20_bid_proxy_usdt=681983, book20_ask_proxy_usdt=522157, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.75%, turnover=5710297. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-11-09T13:29:58+00:00, last15m_closed_end=2026-11-09T13:30+00:00, prior8high=2132.860000, depth_time=2026-11-09T13:30:15+00:00, book20_bid_proxy_usdt=3215076, book20_ask_proxy_usdt=1956362, funding_indicative=-0.000009, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.37%, turnover=1602690158. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-09T13:29:59+00:00, last15m_closed_end=2026-11-09T13:30+00:00, prior8high=0.000427, depth_time=2026-11-09T13:30:38+00:00, book20_bid_proxy_usdt=102524, book20_ask_proxy_usdt=128742, funding_indicative=-0.000890, next_funding_utc=2026-11-09T14:00:00+00:00, funding_cycle_h=1, 24h_change=-3.35%, turnover=6847611. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-09T13:29:59+00:00, last15m_closed_end=2026-11-09T13:30+00:00, prior8high=74.040000, depth_time=2026-11-09T13:30:18+00:00, book20_bid_proxy_usdt=90562, book20_ask_proxy_usdt=58143, funding_indicative=0.000050, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.11%, turnover=49780600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-09T13:29:58+00:00, last15m_closed_end=2026-11-09T13:30+00:00, prior8high=0.009812, depth_time=2026-11-09T13:30:34+00:00, book20_bid_proxy_usdt=43036, book20_ask_proxy_usdt=52099, funding_indicative=0.001230, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.50%, turnover=61172647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-09T13:29:59+00:00, last15m_closed_end=2026-11-09T13:30+00:00, prior8high=3.587000, depth_time=2026-11-09T13:30:29+00:00, book20_bid_proxy_usdt=1782044, book20_ask_proxy_usdt=2069369, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.02%, turnover=47484833. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-09T13:29:59+00:00, last15m_closed_end=2026-11-09T13:30+00:00, prior8high=0.001556, depth_time=2026-11-09T13:30:07+00:00, book20_bid_proxy_usdt=25594, book20_ask_proxy_usdt=18103, funding_indicative=0.000013, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.72%, turnover=6244076. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-09T13:29:59+00:00, last15m_closed_end=2026-11-09T13:30+00:00, prior8high=87.140000, depth_time=2026-11-09T13:30:36+00:00, book20_bid_proxy_usdt=14748988, book20_ask_proxy_usdt=16551159, funding_indicative=0.000015, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.40%, turnover=751701831. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-09T13:29:59+00:00, last15m_closed_end=2026-11-09T13:30+00:00, prior8high=1.148000, depth_time=2026-11-09T13:30:21+00:00, book20_bid_proxy_usdt=2093926, book20_ask_proxy_usdt=2901084, funding_indicative=0.000019, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.79%, turnover=6325871. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-09T13:29:59+00:00, last15m_closed_end=2026-11-09T13:30+00:00, prior8high=1.110100, depth_time=2026-11-09T13:30:21+00:00, book20_bid_proxy_usdt=2151859, book20_ask_proxy_usdt=4246571, funding_indicative=0.000087, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.10%, turnover=291059590. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-09T13:29:59+00:00, last15m_closed_end=2026-11-09T13:30+00:00, prior8high=1228.080000, depth_time=2026-11-09T13:30:26+00:00, book20_bid_proxy_usdt=153787, book20_ask_proxy_usdt=251785, funding_indicative=0.000100, next_funding_utc=2026-11-09T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.15%, turnover=2325025502. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
