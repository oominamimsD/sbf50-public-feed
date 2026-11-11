# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T12:30:31Z**
- feed_generated_utc: 2026-11-11T12:30:33+00:00
- source_sha256: `89abbbbeadb3558a295fd222c9b80daf5319e059e07bca57b404fa0e7c97d83d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T12:30+00:00, close=73920, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T12:00+00:00, close=73963.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T12:00+00:00, close=73963.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.177680|-29.19|32.12|-30.19|67596926|5.63|
|ONE_USDT|0.001540|-14.19|37.88|-15.19|8186667|0.65|
|AKE_USDT|0.002520|-13.52|-39.36|-14.52|8746177|3.97|
|ZEC_USDT|979.740000|-10.39|-18.61|-11.39|2163394494|0.10|
|BTW_USDT|1.081500|-9.76|2.13|-10.76|6058621|2.77|
|UNI_USDT|6.432000|-5.82|-12.52|-6.82|41118773|3.11|
|PEPE_USDT|0.000005|-5.46|1.46|-6.46|82201377|0.60|
|DASH_USDT|44.010000|-2.50|-4.61|-3.50|17057343|2.27|
|QNT_USDT|177.550000|-1.74|-9.14|-2.74|43865310|0.56|
|ARB_USDT|0.159700|-1.04|-0.11|-2.04|27263720|0.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002520|0.002465|0.002520|0.94|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159700|0.158170|0.159700|0.70|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.081500|1.070200|1.081500|1.02|N|Y/Y|Y/N|Y|N|
|DASH_USDT|44.010000|43.650000|44.030000|0.03|N|N/Y|Y/Y|Y|N|
|INIT_USDT|0.177680|0.175910|0.178420|0.89|N|Y/Y|Y/N|Y|N|
|ONE_USDT|0.001540|0.001528|0.001541|0.63|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.11|N|Y/Y|Y/N|Y|N|
|QNT_USDT|177.550000|176.950000|177.550000|1.02|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.432000|6.401000|6.432000|0.80|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|979.740000|979.590000|980.200000|1.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T12:30:01+00:00, last15m_closed_end=2026-11-11T12:30+00:00, prior8high=0.002623, depth_time=2026-11-11T12:30:12+00:00, book20_bid_proxy_usdt=51492, book20_ask_proxy_usdt=41437, funding_indicative=0.000050, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.52%, turnover=8746177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T12:30:02+00:00, last15m_closed_end=2026-11-11T12:30+00:00, prior8high=0.161860, depth_time=2026-11-11T12:30:27+00:00, book20_bid_proxy_usdt=146474, book20_ask_proxy_usdt=61724, funding_indicative=-0.000142, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=27263720. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T12:30:02+00:00, last15m_closed_end=2026-11-11T12:30+00:00, prior8high=1.096600, depth_time=2026-11-11T12:30:14+00:00, book20_bid_proxy_usdt=18660, book20_ask_proxy_usdt=12642, funding_indicative=-0.000328, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.76%, turnover=6058621. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T12:30:02+00:00, last15m_closed_end=2026-11-11T12:30+00:00, prior8high=44.430000, depth_time=2026-11-11T12:30:25+00:00, book20_bid_proxy_usdt=852481, book20_ask_proxy_usdt=722362, funding_indicative=-0.000006, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=17057343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T12:30:01+00:00, last15m_closed_end=2026-11-11T12:30+00:00, prior8high=0.190890, depth_time=2026-11-11T12:30:07+00:00, book20_bid_proxy_usdt=19932, book20_ask_proxy_usdt=16932, funding_indicative=-0.003263, next_funding_utc=2026-11-11T13:00:00+00:00, funding_cycle_h=1, 24h_change=-29.19%, turnover=67596926. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T12:30:01+00:00, last15m_closed_end=2026-11-11T12:30+00:00, prior8high=0.001563, depth_time=2026-11-11T12:30:10+00:00, book20_bid_proxy_usdt=33144, book20_ask_proxy_usdt=18863, funding_indicative=-0.000541, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.19%, turnover=8186667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T12:30:01+00:00, last15m_closed_end=2026-11-11T12:30+00:00, prior8high=0.000005, depth_time=2026-11-11T12:30:22+00:00, book20_bid_proxy_usdt=24561, book20_ask_proxy_usdt=22437, funding_indicative=-0.000206, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.46%, turnover=82201377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T12:30:02+00:00, last15m_closed_end=2026-11-11T12:30+00:00, prior8high=179.750000, depth_time=2026-11-11T12:30:26+00:00, book20_bid_proxy_usdt=98890, book20_ask_proxy_usdt=104203, funding_indicative=-0.000142, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=43865310. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T12:30:02+00:00, last15m_closed_end=2026-11-11T12:30+00:00, prior8high=6.519000, depth_time=2026-11-11T12:30:19+00:00, book20_bid_proxy_usdt=2319308, book20_ask_proxy_usdt=2914162, funding_indicative=-0.000024, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.82%, turnover=41118773. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T12:30:01+00:00, last15m_closed_end=2026-11-11T12:30+00:00, prior8high=999.700000, depth_time=2026-11-11T12:30:15+00:00, book20_bid_proxy_usdt=350643, book20_ask_proxy_usdt=582800, funding_indicative=0.000032, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.39%, turnover=2163394494. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
