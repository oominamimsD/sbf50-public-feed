# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T08:45:31Z**
- feed_generated_utc: 2026-10-20T08:45:34+00:00
- source_sha256: `d2b90a6871b90155277467c18e0a2256317212ea2c96ac880902fca36c8361e3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T08:45+00:00, close=81522.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.068486|-21.31|311.03|-20.84|10913275|3.81|
|BTW_USDT|1.491000|-14.89|-15.08|-14.42|32414181|2.68|
|SAND_USDT|0.056630|-4.24|-8.79|-3.77|7300692|1.77|
|NEAR_USDT|4.736000|-3.42|-14.65|-2.95|165404281|2.11|
|ARB_USDT|0.189410|-3.17|0.49|-2.70|96864888|0.53|
|Q_USDT|0.122004|-3.15|296.23|-2.68|6728708|2.54|
|ATOM_USDT|1.724000|-2.92|-5.68|-2.45|5326926|5.80|
|UNI_USDT|7.144000|-1.97|-3.69|-1.50|10132049|1.40|
|TAO_USDT|263.270000|-1.87|-8.04|-1.40|57861887|1.14|
|QNT_USDT|192.480000|-1.64|-15.71|-1.17|81908651|1.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.068486|0.069563|0.068231|3.24|Y|Y/Y|N/N|Y|N|
|ARB_USDT|0.189410|0.190220|0.189350|1.41|Y|Y/Y|N/N|Y|N|
|ATOM_USDT|1.724000|1.728000|1.724000|4.37|Y|Y/N|N/N|Y|N|
|BTW_USDT|1.491000|1.519100|1.493200|2.61|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|4.736000|4.727000|4.735000|1.15|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|192.480000|189.730000|192.470000|0.97|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.122004|0.116790|0.121898|1.03|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.056630|0.056480|0.056630|0.05|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|263.270000|262.780000|263.160000|1.64|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.144000|7.145000|7.144000|2.97|Y|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T08:45:03+00:00, last15m_closed_end=2026-10-20T08:45+00:00, prior8high=0.084549, depth_time=2026-10-20T08:45:08+00:00, book20_bid_proxy_usdt=13090, book20_ask_proxy_usdt=8160, funding_indicative=0.000063, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.31%, turnover=10913275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T08:45:03+00:00, last15m_closed_end=2026-10-20T08:45+00:00, prior8high=0.199390, depth_time=2026-10-20T08:45:18+00:00, book20_bid_proxy_usdt=67378, book20_ask_proxy_usdt=126523, funding_indicative=-0.000006, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.17%, turnover=96864888. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T08:44:59+00:00, last15m_closed_end=2026-10-20T08:45+00:00, prior8high=1.757000, depth_time=2026-10-20T08:45:19+00:00, book20_bid_proxy_usdt=1270581, book20_ask_proxy_usdt=1343969, funding_indicative=0.000100, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=5326926. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T08:45:03+00:00, last15m_closed_end=2026-10-20T08:45+00:00, prior8high=1.749000, depth_time=2026-10-20T08:45:11+00:00, book20_bid_proxy_usdt=16528, book20_ask_proxy_usdt=19688, funding_indicative=-0.004832, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.89%, turnover=32414181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T08:45:03+00:00, last15m_closed_end=2026-10-20T08:45+00:00, prior8high=4.806000, depth_time=2026-10-20T08:45:16+00:00, book20_bid_proxy_usdt=4465999, book20_ask_proxy_usdt=3270270, funding_indicative=0.000001, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.42%, turnover=165404281. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T08:45:03+00:00, last15m_closed_end=2026-10-20T08:45+00:00, prior8high=194.060000, depth_time=2026-10-20T08:45:30+00:00, book20_bid_proxy_usdt=135662, book20_ask_proxy_usdt=111288, funding_indicative=0.000024, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=81908651. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T08:45:03+00:00, last15m_closed_end=2026-10-20T08:45+00:00, prior8high=0.122612, depth_time=2026-10-20T08:45:20+00:00, book20_bid_proxy_usdt=17990, book20_ask_proxy_usdt=18539, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.15%, turnover=6728708. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T08:44:59+00:00, last15m_closed_end=2026-10-20T08:45+00:00, prior8high=0.057290, depth_time=2026-10-20T08:45:13+00:00, book20_bid_proxy_usdt=1004283, book20_ask_proxy_usdt=999392, funding_indicative=-0.001411, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.24%, turnover=7300692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T08:45:03+00:00, last15m_closed_end=2026-10-20T08:45+00:00, prior8high=266.450000, depth_time=2026-10-20T08:45:28+00:00, book20_bid_proxy_usdt=171759, book20_ask_proxy_usdt=64750, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.87%, turnover=57861887. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T08:44:59+00:00, last15m_closed_end=2026-10-20T08:45+00:00, prior8high=7.224000, depth_time=2026-10-20T08:45:24+00:00, book20_bid_proxy_usdt=1706030, book20_ask_proxy_usdt=2082203, funding_indicative=0.000055, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=10132049. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
