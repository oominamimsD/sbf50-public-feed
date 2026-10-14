# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T13:45:28Z**
- feed_generated_utc: 2026-10-14T13:45:30+00:00
- source_sha256: `9bd3c28469acb37bcdd94964c87ffe72d18964923bdf7966f8ca1c080a830b0d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T13:45+00:00, close=82853.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T13:00+00:00, close=82699.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T12:00+00:00, close=83424.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|W_USDT|0.015569|-7.34|7.28|-6.71|6386376|0.64|
|STRK_USDT|0.081200|-6.59|55.58|-5.96|27436670|1.23|
|TIA_USDT|0.553100|-4.19|16.12|-3.56|34804458|1.81|
|SILVER_USDT|57.070000|-3.90|-7.00|-3.27|348723608|1.75|
|UNI_USDT|7.315000|-3.39|-15.57|-2.76|21596340|1.37|
|RENDER_USDT|1.942000|-2.26|-8.82|-1.63|9095571|5.15|
|XLM_USDT|0.186970|-2.09|-12.50|-1.46|11420206|0.54|
|ONDO_USDT|0.457100|-1.82|-9.26|-1.19|32352235|2.19|
|AVAX_USDT|10.047000|-1.79|-12.67|-1.16|35612717|0.99|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AVAX_USDT|10.047000|9.881000|10.047000|1.76|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.457100|0.448400|0.457100|0.98|N|Y/Y|Y/Y|Y|N|
|RENDER_USDT|1.942000|1.917000|1.942000|2.14|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|57.070000|56.670000|57.060000|3.75|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.081200|0.077420|0.081200|3.61|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.553100|0.537800|0.553100|1.83|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.315000|7.166000|7.315000|2.93|N|Y/Y|Y/Y|Y|N|
|W_USDT|0.015569|0.015278|0.015569|0.83|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.186970|0.184930|0.186970|1.80|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AVAX_USDT: quote_utc=2026-10-14T13:45:00+00:00, last15m_closed_end=2026-10-14T13:45+00:00, prior8high=10.294000, depth_time=2026-10-14T13:45:27+00:00, book20_bid_proxy_usdt=437795, book20_ask_proxy_usdt=369480, funding_indicative=0.000001, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=35612717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-14T13:45:00+00:00, last15m_closed_end=2026-10-14T13:45+00:00, prior8high=0.467700, depth_time=2026-10-14T13:45:25+00:00, book20_bid_proxy_usdt=1037583, book20_ask_proxy_usdt=1522298, funding_indicative=-0.000044, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=32352235. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RENDER_USDT: quote_utc=2026-10-14T13:45:00+00:00, last15m_closed_end=2026-10-14T13:45+00:00, prior8high=2.007000, depth_time=2026-10-14T13:45:20+00:00, book20_bid_proxy_usdt=1868886, book20_ask_proxy_usdt=1400635, funding_indicative=0.000046, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=9095571. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T13:45:00+00:00, last15m_closed_end=2026-10-14T13:45+00:00, prior8high=58.910000, depth_time=2026-10-14T13:45:15+00:00, book20_bid_proxy_usdt=33670551, book20_ask_proxy_usdt=32554519, funding_indicative=0.000123, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.90%, turnover=348723608. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T13:45:00+00:00, last15m_closed_end=2026-10-14T13:45+00:00, prior8high=0.080580, depth_time=2026-10-14T13:45:10+00:00, book20_bid_proxy_usdt=334258, book20_ask_proxy_usdt=131480, funding_indicative=0.000050, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.59%, turnover=27436670. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T13:45:00+00:00, last15m_closed_end=2026-10-14T13:45+00:00, prior8high=0.560900, depth_time=2026-10-14T13:45:12+00:00, book20_bid_proxy_usdt=182748, book20_ask_proxy_usdt=216931, funding_indicative=0.000016, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.19%, turnover=34804458. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T13:45:00+00:00, last15m_closed_end=2026-10-14T13:45+00:00, prior8high=7.406000, depth_time=2026-10-14T13:45:17+00:00, book20_bid_proxy_usdt=1019835, book20_ask_proxy_usdt=1064761, funding_indicative=0.000074, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.39%, turnover=21596340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T13:45:00+00:00, last15m_closed_end=2026-10-14T13:45+00:00, prior8high=0.015989, depth_time=2026-10-14T13:45:08+00:00, book20_bid_proxy_usdt=25351, book20_ask_proxy_usdt=25570, funding_indicative=-0.000214, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.34%, turnover=6386376. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T13:45:00+00:00, last15m_closed_end=2026-10-14T13:45+00:00, prior8high=0.190870, depth_time=2026-10-14T13:45:21+00:00, book20_bid_proxy_usdt=105782, book20_ask_proxy_usdt=163654, funding_indicative=-0.000091, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=11420206. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
