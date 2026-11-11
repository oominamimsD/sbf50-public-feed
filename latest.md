# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T10:45:31Z**
- feed_generated_utc: 2026-11-11T10:45:33+00:00
- source_sha256: `bc25aef57ee57e429fe217061c30b8ff283e8df72c68ddca81fc3320cda87b69`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T10:45+00:00, close=73988, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T10:00+00:00, close=73761.1, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-11T08:00+00:00, close=74064.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.182050|-27.45|35.37|-28.55|68857968|2.75|
|ONE_USDT|0.001535|-14.45|37.45|-15.55|10980943|1.30|
|AKE_USDT|0.002542|-12.76|-38.83|-13.86|9008484|3.94|
|BTW_USDT|1.080400|-9.86|2.03|-10.96|6049678|1.85|
|ZEC_USDT|988.180000|-9.61|-17.91|-10.71|2180472147|0.10|
|UNI_USDT|6.482000|-5.09|-11.84|-6.19|41741773|1.54|
|PEPE_USDT|0.000005|-3.72|3.33|-4.82|80150147|0.79|
|DASH_USDT|43.810000|-2.94|-5.04|-4.04|17064343|2.28|
|ARB_USDT|0.158960|-1.49|-0.57|-2.59|28672001|0.63|
|VVV_USDT|19.014000|-1.16|-14.96|-2.26|5531534|2.63|
|QNT_USDT|178.620000|-1.15|-8.59|-2.25|45350014|0.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002542|0.002493|0.002543|1.52|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158960|0.158090|0.158960|0.79|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.080400|1.082700|1.080400|1.20|N|Y/Y|Y/N|Y|N|
|DASH_USDT|43.810000|42.990000|43.810000|0.78|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.182050|0.174240|0.182050|0.40|N|Y/Y|N/N|Y|N|
|ONE_USDT|0.001535|0.001533|0.001535|0.84|N|Y/Y|Y/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.64|N|Y/Y|N/N|Y|N|
|QNT_USDT|178.620000|176.850000|178.620000|0.95|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.482000|6.336000|6.482000|0.71|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.014000|18.772000|19.014000|0.90|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|988.180000|960.750000|988.180000|0.87|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-11T10:44:59+00:00, last15m_closed_end=2026-11-11T10:45+00:00, prior8high=0.002623, depth_time=2026-11-11T10:45:11+00:00, book20_bid_proxy_usdt=57004, book20_ask_proxy_usdt=48358, funding_indicative=0.000050, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.76%, turnover=9008484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-11T10:44:59+00:00, last15m_closed_end=2026-11-11T10:45+00:00, prior8high=0.159820, depth_time=2026-11-11T10:45:25+00:00, book20_bid_proxy_usdt=56716, book20_ask_proxy_usdt=84719, funding_indicative=-0.000044, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=28672001. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-11T10:44:59+00:00, last15m_closed_end=2026-11-11T10:45+00:00, prior8high=1.136400, depth_time=2026-11-11T10:45:13+00:00, book20_bid_proxy_usdt=18617, book20_ask_proxy_usdt=24809, funding_indicative=-0.000534, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.86%, turnover=6049678. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T10:45:00+00:00, last15m_closed_end=2026-11-11T10:45+00:00, prior8high=44.240000, depth_time=2026-11-11T10:45:24+00:00, book20_bid_proxy_usdt=792932, book20_ask_proxy_usdt=578372, funding_indicative=-0.000055, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=17064343. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T10:44:59+00:00, last15m_closed_end=2026-11-11T10:45+00:00, prior8high=0.225680, depth_time=2026-11-11T10:45:07+00:00, book20_bid_proxy_usdt=21357, book20_ask_proxy_usdt=10265, funding_indicative=-0.007025, next_funding_utc=2026-11-11T11:00:00+00:00, funding_cycle_h=1, 24h_change=-27.45%, turnover=68857968. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-11T10:44:59+00:00, last15m_closed_end=2026-11-11T10:45+00:00, prior8high=0.001607, depth_time=2026-11-11T10:45:09+00:00, book20_bid_proxy_usdt=34592, book20_ask_proxy_usdt=22475, funding_indicative=-0.000463, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.45%, turnover=10980943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-11T10:44:59+00:00, last15m_closed_end=2026-11-11T10:45+00:00, prior8high=0.000005, depth_time=2026-11-11T10:45:21+00:00, book20_bid_proxy_usdt=58117, book20_ask_proxy_usdt=18472, funding_indicative=-0.000167, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.72%, turnover=80150147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-11T10:44:59+00:00, last15m_closed_end=2026-11-11T10:45+00:00, prior8high=179.330000, depth_time=2026-11-11T10:45:30+00:00, book20_bid_proxy_usdt=85136, book20_ask_proxy_usdt=31629, funding_indicative=-0.000179, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=45350014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T10:44:59+00:00, last15m_closed_end=2026-11-11T10:45+00:00, prior8high=6.479000, depth_time=2026-11-11T10:45:17+00:00, book20_bid_proxy_usdt=3237519, book20_ask_proxy_usdt=2198679, funding_indicative=-0.000008, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.09%, turnover=41741773. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-11T10:45:00+00:00, last15m_closed_end=2026-11-11T10:45+00:00, prior8high=19.082000, depth_time=2026-11-11T10:45:26+00:00, book20_bid_proxy_usdt=11496, book20_ask_proxy_usdt=25063, funding_indicative=0.000001, next_funding_utc=2026-11-11T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.16%, turnover=5531534. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T10:44:59+00:00, last15m_closed_end=2026-11-11T10:45+00:00, prior8high=997.000000, depth_time=2026-11-11T10:45:16+00:00, book20_bid_proxy_usdt=206235, book20_ask_proxy_usdt=323306, funding_indicative=0.000029, next_funding_utc=2026-11-11T16:00:00+00:00, funding_cycle_h=8, 24h_change=-9.61%, turnover=2180472147. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
