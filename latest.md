# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T06:45:27Z**
- feed_generated_utc: 2026-10-23T06:45:29+00:00
- source_sha256: `02cc0051193ddd77744d1476f2cfdda6eda92f1a783974f3ed499871a0823e72`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1214; contracts: 1206; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T06:45+00:00, close=81857.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T06:00+00:00, close=81812.9, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T04:00+00:00, close=81863.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004291|-6.87|116.17|-7.12|8512638|9.31|
|LIT_USDT|3.415100|-5.50|10.47|-5.75|10163695|0.29|
|STRK_USDT|0.052760|-2.94|-45.24|-3.19|10994498|1.90|
|SILVER_USDT|54.190000|-1.93|-5.16|-2.18|347828878|1.85|
|TIA_USDT|0.559000|-1.65|-7.21|-1.90|23846300|1.79|
|XAU_USDT|4023.770000|-0.88|-3.18|-1.13|686741841|0.03|
|XMR_USDT|607.710000|-0.85|11.71|-1.10|24128372|0.17|
|XAUT_USDT|4019.910000|-0.84|-3.01|-1.09|268348192|0.07|
|XPT_USDT|1574.680000|-0.76|-2.84|-1.01|5170695|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004291|0.004130|0.004291|1.12|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.415100|3.410200|3.415100|0.20|N|Y/Y|N/N|Y|N|
|SILVER_USDT|54.190000|53.720000|54.190000|1.32|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052760|0.052610|0.052760|4.56|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.559000|0.556900|0.559100|0.43|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4019.910000|4008.190000|4019.910000|1.09|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4023.770000|4010.840000|4023.770000|0.68|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|607.710000|606.240000|607.710000|0.80|N|N/N|N/Y|Y|N|
|XPT_USDT|1574.680000|1568.520000|1574.680000|0.68|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T06:44:59+00:00, last15m_closed_end=2026-10-23T06:45+00:00, prior8high=0.004429, depth_time=2026-10-23T06:45:06+00:00, book20_bid_proxy_usdt=32255, book20_ask_proxy_usdt=30651, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.87%, turnover=8512638. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T06:45:00+00:00, last15m_closed_end=2026-10-23T06:45+00:00, prior8high=3.477000, depth_time=2026-10-23T06:45:09+00:00, book20_bid_proxy_usdt=28098, book20_ask_proxy_usdt=29939, funding_indicative=0.000003, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.50%, turnover=10163695. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T06:44:59+00:00, last15m_closed_end=2026-10-23T06:45+00:00, prior8high=54.680000, depth_time=2026-10-23T06:45:15+00:00, book20_bid_proxy_usdt=34058861, book20_ask_proxy_usdt=29389419, funding_indicative=0.000122, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=347828878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T06:45:00+00:00, last15m_closed_end=2026-10-23T06:45+00:00, prior8high=0.053240, depth_time=2026-10-23T06:45:12+00:00, book20_bid_proxy_usdt=462625, book20_ask_proxy_usdt=626468, funding_indicative=-0.000023, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.94%, turnover=10994498. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T06:44:59+00:00, last15m_closed_end=2026-10-23T06:45+00:00, prior8high=0.561700, depth_time=2026-10-23T06:45:16+00:00, book20_bid_proxy_usdt=334230, book20_ask_proxy_usdt=363112, funding_indicative=-0.000046, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.65%, turnover=23846300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-23T06:44:59+00:00, last15m_closed_end=2026-10-23T06:45+00:00, prior8high=4032.400000, depth_time=2026-10-23T06:45:24+00:00, book20_bid_proxy_usdt=241980, book20_ask_proxy_usdt=66277, funding_indicative=0.000050, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=268348192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-23T06:44:59+00:00, last15m_closed_end=2026-10-23T06:45+00:00, prior8high=4036.730000, depth_time=2026-10-23T06:45:16+00:00, book20_bid_proxy_usdt=7294288, book20_ask_proxy_usdt=2084388, funding_indicative=0.000090, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=686741841. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T06:44:59+00:00, last15m_closed_end=2026-10-23T06:45+00:00, prior8high=616.370000, depth_time=2026-10-23T06:45:21+00:00, book20_bid_proxy_usdt=24143, book20_ask_proxy_usdt=13842, funding_indicative=0.000100, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.85%, turnover=24128372. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPT_USDT: quote_utc=2026-10-23T06:45:00+00:00, last15m_closed_end=2026-10-23T06:45+00:00, prior8high=1584.780000, depth_time=2026-10-23T06:45:25+00:00, book20_bid_proxy_usdt=366499, book20_ask_proxy_usdt=360219, funding_indicative=0.000000, next_funding_utc=2026-10-23T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.76%, turnover=5170695. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
