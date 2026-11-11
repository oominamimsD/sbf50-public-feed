# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T11:00:36Z**
- feed_generated_utc: 2026-11-11T11:00:37+00:00
- source_sha256: `30cb1034153a48dfc65fa3089a0d03c79682ca9a56329b78f455bfd37cb4b4c3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T11:00+00:00, close=74018, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T11:00+00:00, close=74018, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.181820|-27.54|35.20|-28.68|69065764|8.80|
|ONE_USDT|0.001548|-13.73|38.60|-14.87|11028847|0.65|
|AKE_USDT|0.002541|-12.80|-38.85|-13.94|9042647|3.94|
|ZEC_USDT|986.250000|-9.79|-18.07|-10.93|2194999430|0.10|
|UNI_USDT|6.462000|-8.53|-12.11|-9.67|41049511|1.55|
|DASH_USDT|43.740000|-6.03|-5.20|-7.17|16917545|2.29|
|BTW_USDT|1.075800|-5.39|1.59|-6.53|5980314|0.93|
|PEPE_USDT|0.000005|-4.21|2.81|-5.35|80428466|0.20|
|VVV_USDT|19.136000|-3.43|-14.42|-4.57|5420431|1.57|
|HBAR_USDT|0.065720|-1.79|-6.15|-2.93|6633278|1.52|
|ARB_USDT|0.158650|-1.69|-0.76|-2.83|28825548|0.63|
|QNT_USDT|178.770000|-1.06|-8.52|-2.20|45408770|0.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002541|0.002493|0.002541|0.96|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158650|0.158090|0.158650|0.98|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.075800|1.073000|1.075800|0.90|N|Y/Y|Y/N|Y|N|
|DASH_USDT|43.740000|42.990000|43.740000|0.06|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065720|0.065310|0.065720|1.29|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.181820|0.174240|0.181840|0.46|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001548|0.001533|0.001548|0.73|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.48|N|Y/Y|N/N|Y|N|
|QNT_USDT|178.770000|176.850000|178.770000|0.26|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.462000|6.336000|6.462000|0.38|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.136000|18.772000|19.136000|1.13|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|986.250000|960.750000|986.250000|0.77|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T10:59:59+00:00, last15m_closed_end=2026-11-11T11:00+00:00, prior8high=0.002623, depth_time=2026-11-11T11:00:13+00:00, book20_bid_proxy_usdt=79627, book20_ask_proxy_usdt=47924, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.80%, turnover=9042647. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T10:59:59+00:00, last15m_closed_end=2026-11-11T11:00+00:00, prior8high=0.160070, depth_time=2026-11-11T11:00:31+00:00, book20_bid_proxy_usdt=86538, book20_ask_proxy_usdt=67858, funding_indicative=-0.000052, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=28825548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T11:00:00+00:00, last15m_closed_end=2026-11-11T11:00+00:00, prior8high=1.136400, depth_time=2026-11-11T11:00:22+00:00, book20_bid_proxy_usdt=33932, book20_ask_proxy_usdt=21951, funding_indicative=-0.000504, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.39%, turnover=5980314. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T11:00:00+00:00, last15m_closed_end=2026-11-11T11:00+00:00, prior8high=44.240000, depth_time=2026-11-11T11:00:20+00:00, book20_bid_proxy_usdt=806071, book20_ask_proxy_usdt=725244, funding_indicative=-0.000029, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-6.03%, turnover=16917545. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T11:00:00+00:00, last15m_closed_end=2026-11-11T11:00+00:00, prior8high=0.066060, depth_time=2026-11-11T11:00:29+00:00, book20_bid_proxy_usdt=804267, book20_ask_proxy_usdt=874750, funding_indicative=0.000051, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=6633278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T10:59:59+00:00, last15m_closed_end=2026-11-11T11:00+00:00, prior8high=0.225680, depth_time=2026-11-11T11:00:08+00:00, book20_bid_proxy_usdt=22401, book20_ask_proxy_usdt=11598, funding_indicative=-0.006808, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=1, 24h_change=-27.54%, turnover=69065764. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T10:59:59+00:00, last15m_closed_end=2026-11-11T11:00+00:00, prior8high=0.001607, depth_time=2026-11-11T11:00:10+00:00, book20_bid_proxy_usdt=25629, book20_ask_proxy_usdt=37762, funding_indicative=-0.000419, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.73%, turnover=11028847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T10:59:59+00:00, last15m_closed_end=2026-11-11T11:00+00:00, prior8high=0.000005, depth_time=2026-11-11T11:00:24+00:00, book20_bid_proxy_usdt=27406, book20_ask_proxy_usdt=23042, funding_indicative=-0.000181, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.21%, turnover=80428466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T10:59:59+00:00, last15m_closed_end=2026-11-11T11:00+00:00, prior8high=179.750000, depth_time=2026-11-11T11:00:35+00:00, book20_bid_proxy_usdt=87991, book20_ask_proxy_usdt=64050, funding_indicative=-0.000180, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=45408770. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T11:00:00+00:00, last15m_closed_end=2026-11-11T11:00+00:00, prior8high=6.519000, depth_time=2026-11-11T11:00:18+00:00, book20_bid_proxy_usdt=2862559, book20_ask_proxy_usdt=2865926, funding_indicative=-0.000003, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.53%, turnover=41049511. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T11:00:00+00:00, last15m_closed_end=2026-11-11T11:00+00:00, prior8high=19.170000, depth_time=2026-11-11T11:00:28+00:00, book20_bid_proxy_usdt=15921, book20_ask_proxy_usdt=18268, funding_indicative=-0.000020, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.43%, turnover=5420431. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T10:59:59+00:00, last15m_closed_end=2026-11-11T11:00+00:00, prior8high=999.700000, depth_time=2026-11-11T11:00:15+00:00, book20_bid_proxy_usdt=444468, book20_ask_proxy_usdt=257890, funding_indicative=0.000033, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.79%, turnover=2194999430. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
