# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T13:15:30Z**
- feed_generated_utc: 2026-11-11T13:15:31+00:00
- source_sha256: `f5032d3e178354d601cbc0e9480bc444201201ffa5a50748472ff7da0806a5af`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T13:15+00:00, close=73948.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T13:00+00:00, close=73854.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T12:00+00:00, close=73963.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.161390|-35.68|20.01|-36.72|66598072|2.48|
|ONE_USDT|0.001541|-14.11|37.99|-15.15|7656900|0.65|
|AKE_USDT|0.002573|-11.70|-38.08|-12.74|8498292|3.89|
|ZEC_USDT|983.600000|-10.03|-18.29|-11.07|2162181872|0.10|
|BTW_USDT|1.081200|-9.79|2.10|-10.83|5983921|4.62|
|UNI_USDT|6.496000|-4.89|-11.65|-5.93|40761577|1.54|
|PEPE_USDT|0.000005|-4.74|2.24|-5.78|82064340|0.80|
|DASH_USDT|43.840000|-2.87|-4.98|-3.91|16842567|2.28|
|QNT_USDT|176.680000|-2.22|-9.58|-3.26|43742955|0.57|
|ARB_USDT|0.159970|-0.87|0.05|-1.91|26734078|0.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002573|0.002465|0.002573|1.25|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159970|0.158170|0.160000|0.89|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.081200|1.070000|1.081200|0.79|N|Y/Y|Y/N|Y|N|
|DASH_USDT|43.840000|43.670000|43.840000|0.03|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.161390|0.164780|0.161560|1.24|N|Y/Y|Y/N|Y|N|
|ONE_USDT|0.001541|0.001522|0.001541|1.19|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.36|N|Y/Y|Y/N|Y|N|
|QNT_USDT|176.680000|176.980000|176.870000|2.03|Y|Y/Y|Y/Y|Y|Y|
|UNI_USDT|6.496000|6.413000|6.496000|0.72|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|983.600000|975.170000|983.680000|1.37|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T13:15:02+00:00, last15m_closed_end=2026-11-11T13:15+00:00, prior8high=0.002605, depth_time=2026-11-11T13:15:12+00:00, book20_bid_proxy_usdt=74628, book20_ask_proxy_usdt=76558, funding_indicative=0.000050, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.70%, turnover=8498292. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T13:15:02+00:00, last15m_closed_end=2026-11-11T13:15+00:00, prior8high=0.161860, depth_time=2026-11-11T13:15:25+00:00, book20_bid_proxy_usdt=51712, book20_ask_proxy_usdt=40643, funding_indicative=-0.000163, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.87%, turnover=26734078. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T13:15:02+00:00, last15m_closed_end=2026-11-11T13:15+00:00, prior8high=1.095300, depth_time=2026-11-11T13:15:16+00:00, book20_bid_proxy_usdt=20824, book20_ask_proxy_usdt=24219, funding_indicative=-0.000397, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.79%, turnover=5983921. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T13:15:02+00:00, last15m_closed_end=2026-11-11T13:15+00:00, prior8high=44.430000, depth_time=2026-11-11T13:15:23+00:00, book20_bid_proxy_usdt=435133, book20_ask_proxy_usdt=579167, funding_indicative=0.000028, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.87%, turnover=16842567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T13:15:01+00:00, last15m_closed_end=2026-11-11T13:15+00:00, prior8high=0.190750, depth_time=2026-11-11T13:15:07+00:00, book20_bid_proxy_usdt=12437, book20_ask_proxy_usdt=18060, funding_indicative=-0.001874, next_funding_utc=2026-11-11T14:00:00+00:00, funding_cycle_h=1, 24h_change=-35.68%, turnover=66598072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T13:15:01+00:00, last15m_closed_end=2026-11-11T13:15+00:00, prior8high=0.001569, depth_time=2026-11-11T13:15:10+00:00, book20_bid_proxy_usdt=15506, book20_ask_proxy_usdt=20177, funding_indicative=-0.000634, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.11%, turnover=7656900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T13:15:02+00:00, last15m_closed_end=2026-11-11T13:15+00:00, prior8high=0.000005, depth_time=2026-11-11T13:15:22+00:00, book20_bid_proxy_usdt=32362, book20_ask_proxy_usdt=34980, funding_indicative=-0.000228, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.74%, turnover=82064340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T13:15:02+00:00, last15m_closed_end=2026-11-11T13:15+00:00, prior8high=178.870000, depth_time=2026-11-11T13:15:27+00:00, book20_bid_proxy_usdt=88990, book20_ask_proxy_usdt=79625, funding_indicative=-0.000131, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.22%, turnover=43742955. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T13:15:02+00:00, last15m_closed_end=2026-11-11T13:15+00:00, prior8high=6.492000, depth_time=2026-11-11T13:15:19+00:00, book20_bid_proxy_usdt=2377699, book20_ask_proxy_usdt=2499540, funding_indicative=-0.000002, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.89%, turnover=40761577. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T13:15:01+00:00, last15m_closed_end=2026-11-11T13:15+00:00, prior8high=994.360000, depth_time=2026-11-11T13:15:14+00:00, book20_bid_proxy_usdt=109594, book20_ask_proxy_usdt=134231, funding_indicative=0.000043, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.03%, turnover=2162181872. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
