# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T19:30:31Z**
- feed_generated_utc: 2026-11-10T19:30:33+00:00
- source_sha256: `606620cdc1531327ef13f3e9ee84f47cff97fbe3390f0bb33aa79f28e388600a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T19:30+00:00, close=73391.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T19:00+00:00, close=73455.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.841200|-9.12|56.64|-9.40|8004064|3.26|
|ZEC_USDT|1029.270000|-5.86|-14.49|-6.14|2324917629|0.10|
|DASH_USDT|43.030000|-4.67|-6.74|-4.95|13555806|2.32|
|AKE_USDT|0.002829|-2.91|-31.92|-3.19|15865726|3.53|
|UNI_USDT|6.677000|-2.24|-9.19|-2.52|28683409|1.50|
|JCT_USDT|0.005171|-1.97|23.76|-2.25|21656609|3.86|
|ONDO_USDT|0.359600|-1.69|-7.60|-1.97|15141811|2.78|
|ANTHROPIC_USDT|1297.190000|-1.54|-22.50|-1.82|8031417|0.39|
|TIA_USDT|0.419300|-1.29|-3.78|-1.57|9569508|2.38|
|ENA_USDT|0.147830|-0.91|-14.14|-1.19|29831620|0.68|
|ARB_USDT|0.160120|-0.78|0.15|-1.06|34295504|1.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002829|0.002739|0.002829|0.59|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1297.190000|1285.250000|1297.190000|0.34|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.160120|0.155570|0.160120|0.42|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.030000|42.610000|43.030000|0.98|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.147830|0.146700|0.147830|0.88|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005171|0.005014|0.005171|0.97|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359600|0.358000|0.359600|1.15|N|Y/Y|Y/N|Y|N|
|PIEVERSE_USDT|1.841200|1.808000|1.841200|0.59|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.419300|0.415800|0.419300|0.68|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.677000|6.608000|6.677000|0.46|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1029.270000|1011.380000|1029.260000|0.62|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T19:30:00+00:00, last15m_closed_end=2026-11-10T19:30+00:00, prior8high=0.002954, depth_time=2026-11-10T19:30:13+00:00, book20_bid_proxy_usdt=31211, book20_ask_proxy_usdt=37937, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.91%, turnover=15865726. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T19:29:59+00:00, last15m_closed_end=2026-11-10T19:30+00:00, prior8high=1325.200000, depth_time=2026-11-10T19:30:23+00:00, book20_bid_proxy_usdt=12858, book20_ask_proxy_usdt=5442, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=8031417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T19:30:00+00:00, last15m_closed_end=2026-11-10T19:30+00:00, prior8high=0.160280, depth_time=2026-11-10T19:30:27+00:00, book20_bid_proxy_usdt=64662, book20_ask_proxy_usdt=986654, funding_indicative=-0.000188, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.78%, turnover=34295504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T19:30:00+00:00, last15m_closed_end=2026-11-10T19:30+00:00, prior8high=43.750000, depth_time=2026-11-10T19:30:11+00:00, book20_bid_proxy_usdt=663126, book20_ask_proxy_usdt=672452, funding_indicative=-0.000160, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.67%, turnover=13555806. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-10T19:30:00+00:00, last15m_closed_end=2026-11-10T19:30+00:00, prior8high=0.150710, depth_time=2026-11-10T19:30:25+00:00, book20_bid_proxy_usdt=159814, book20_ask_proxy_usdt=224861, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.91%, turnover=29831620. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T19:30:00+00:00, last15m_closed_end=2026-11-10T19:30+00:00, prior8high=0.005345, depth_time=2026-11-10T19:30:18+00:00, book20_bid_proxy_usdt=51974, book20_ask_proxy_usdt=46783, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.97%, turnover=21656609. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T19:30:00+00:00, last15m_closed_end=2026-11-10T19:30+00:00, prior8high=0.364800, depth_time=2026-11-10T19:30:20+00:00, book20_bid_proxy_usdt=2312884, book20_ask_proxy_usdt=2346609, funding_indicative=-0.000012, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.69%, turnover=15141811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T19:29:59+00:00, last15m_closed_end=2026-11-10T19:30+00:00, prior8high=1.876100, depth_time=2026-11-10T19:30:07+00:00, book20_bid_proxy_usdt=18836, book20_ask_proxy_usdt=19964, funding_indicative=0.000126, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.12%, turnover=8004064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-10T19:30:00+00:00, last15m_closed_end=2026-11-10T19:30+00:00, prior8high=0.426100, depth_time=2026-11-10T19:30:25+00:00, book20_bid_proxy_usdt=503764, book20_ask_proxy_usdt=525813, funding_indicative=0.000012, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.29%, turnover=9569508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T19:30:00+00:00, last15m_closed_end=2026-11-10T19:30+00:00, prior8high=6.745000, depth_time=2026-11-10T19:30:16+00:00, book20_bid_proxy_usdt=2634220, book20_ask_proxy_usdt=2747408, funding_indicative=-0.000027, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.24%, turnover=28683409. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T19:30:00+00:00, last15m_closed_end=2026-11-10T19:30+00:00, prior8high=1045.180000, depth_time=2026-11-10T19:30:10+00:00, book20_bid_proxy_usdt=78497, book20_ask_proxy_usdt=167718, funding_indicative=-0.000021, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.86%, turnover=2324917629. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
