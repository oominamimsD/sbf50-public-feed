# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T10:30:38Z**
- feed_generated_utc: 2026-11-11T10:30:41+00:00
- source_sha256: `5f8c96c35a49fe46a0c5cd3c0830e595246be042bec1473e93ca8461d506f704`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T10:30+00:00, close=73975, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T10:00+00:00, close=73761.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.185620|-26.03|38.02|-27.11|68677172|1.62|
|ONE_USDT|0.001542|-14.03|38.12|-15.11|10924363|0.65|
|AKE_USDT|0.002551|-12.45|-38.61|-13.53|8954260|3.92|
|BTW_USDT|1.083800|-9.57|2.35|-10.65|6010207|0.92|
|ZEC_USDT|996.030000|-8.90|-17.26|-9.98|2162975374|0.10|
|UNI_USDT|6.479000|-5.13|-11.88|-6.21|41485349|1.54|
|PEPE_USDT|0.000005|-4.04|2.98|-5.12|79750653|0.20|
|DASH_USDT|44.030000|-2.45|-4.57|-3.53|16971946|2.27|
|ARB_USDT|0.159190|-1.35|-0.43|-2.43|28547475|1.26|
|QNT_USDT|179.130000|-0.86|-8.33|-1.94|45129404|0.56|
|VVV_USDT|19.082000|-0.81|-14.66|-1.89|5496010|3.14|
|HBAR_USDT|0.065690|-0.13|-6.19|-1.21|6520543|1.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002551|0.002493|0.002551|2.50|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159190|0.158090|0.159190|0.44|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.083800|1.085000|1.083800|1.02|N|Y/Y|Y/N|Y|N|
|DASH_USDT|44.030000|42.990000|44.030000|0.44|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065690|0.065210|0.065690|3.14|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.185620|0.174240|0.185440|0.31|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001542|0.001541|0.001542|1.27|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.87|N|Y/Y|N/N|Y|N|
|QNT_USDT|179.130000|176.850000|179.130000|1.07|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.479000|6.336000|6.479000|0.96|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.082000|18.772000|19.082000|0.93|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|996.030000|960.750000|996.220000|0.80|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T10:30:01+00:00, last15m_closed_end=2026-11-11T10:30+00:00, prior8high=0.002590, depth_time=2026-11-11T10:30:12+00:00, book20_bid_proxy_usdt=50745, book20_ask_proxy_usdt=52734, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.45%, turnover=8954260. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T10:30:01+00:00, last15m_closed_end=2026-11-11T10:30+00:00, prior8high=0.160150, depth_time=2026-11-11T10:30:29+00:00, book20_bid_proxy_usdt=86805, book20_ask_proxy_usdt=62359, funding_indicative=-0.000034, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=28547475. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T10:30:01+00:00, last15m_closed_end=2026-11-11T10:30+00:00, prior8high=1.136400, depth_time=2026-11-11T10:30:15+00:00, book20_bid_proxy_usdt=26096, book20_ask_proxy_usdt=13345, funding_indicative=-0.000531, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.57%, turnover=6010207. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T10:30:01+00:00, last15m_closed_end=2026-11-11T10:30+00:00, prior8high=44.240000, depth_time=2026-11-11T10:30:26+00:00, book20_bid_proxy_usdt=612859, book20_ask_proxy_usdt=647036, funding_indicative=-0.000061, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.45%, turnover=16971946. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-11T10:30:01+00:00, last15m_closed_end=2026-11-11T10:30+00:00, prior8high=0.065760, depth_time=2026-11-11T10:30:34+00:00, book20_bid_proxy_usdt=733048, book20_ask_proxy_usdt=613409, funding_indicative=0.000049, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.13%, turnover=6520543. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T10:30:00+00:00, last15m_closed_end=2026-11-11T10:30+00:00, prior8high=0.225680, depth_time=2026-11-11T10:30:07+00:00, book20_bid_proxy_usdt=11526, book20_ask_proxy_usdt=9012, funding_indicative=-0.007975, next_funding_utc=2026-11-11T11:00:00+00:00, funding_cycle_h=1, 24h_change=-26.03%, turnover=68677172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T10:30:00+00:00, last15m_closed_end=2026-11-11T10:30+00:00, prior8high=0.001607, depth_time=2026-11-11T10:30:09+00:00, book20_bid_proxy_usdt=25565, book20_ask_proxy_usdt=25140, funding_indicative=-0.000578, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.03%, turnover=10924363. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T10:30:00+00:00, last15m_closed_end=2026-11-11T10:30+00:00, prior8high=0.000005, depth_time=2026-11-11T10:30:20+00:00, book20_bid_proxy_usdt=32338, book20_ask_proxy_usdt=18393, funding_indicative=-0.000155, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.04%, turnover=79750653. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T10:30:01+00:00, last15m_closed_end=2026-11-11T10:30+00:00, prior8high=179.330000, depth_time=2026-11-11T10:30:31+00:00, book20_bid_proxy_usdt=98054, book20_ask_proxy_usdt=87181, funding_indicative=-0.000177, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=45129404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T10:30:01+00:00, last15m_closed_end=2026-11-11T10:30+00:00, prior8high=6.467000, depth_time=2026-11-11T10:30:20+00:00, book20_bid_proxy_usdt=2656380, book20_ask_proxy_usdt=3077264, funding_indicative=-0.000017, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.13%, turnover=41485349. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T10:30:01+00:00, last15m_closed_end=2026-11-11T10:30+00:00, prior8high=19.142000, depth_time=2026-11-11T10:30:34+00:00, book20_bid_proxy_usdt=15559, book20_ask_proxy_usdt=25867, funding_indicative=0.000012, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.81%, turnover=5496010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T10:30:00+00:00, last15m_closed_end=2026-11-11T10:30+00:00, prior8high=999.680000, depth_time=2026-11-11T10:30:18+00:00, book20_bid_proxy_usdt=369080, book20_ask_proxy_usdt=178484, funding_indicative=0.000027, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.90%, turnover=2162975374. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
