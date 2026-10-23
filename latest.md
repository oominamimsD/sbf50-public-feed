# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T09:00:25Z**
- feed_generated_utc: 2026-10-23T09:00:27+00:00
- source_sha256: `cfae665514bf7876f4c9dc82def65f2782757dcdc783fe19fe74ec832a328f75`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T09:00+00:00, close=81725, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T09:00+00:00, close=81725, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004181|-16.54|110.62|-16.63|7807536|7.17|
|LIT_USDT|3.415600|-6.17|10.48|-6.26|9413889|0.29|
|STRK_USDT|0.052350|-4.71|-45.67|-4.80|11579673|1.91|
|QNT_USDT|187.330000|-2.89|-9.89|-2.98|46741599|0.53|
|TIA_USDT|0.554500|-2.44|-7.96|-2.53|24360948|1.80|
|SILVER_USDT|54.020000|-2.24|-5.46|-2.33|332523508|1.85|
|PUMPFUN_USDT|0.004635|-1.40|2.40|-1.49|35685326|2.16|
|XMR_USDT|614.370000|-0.99|12.94|-1.08|18627141|0.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004181|0.004176|0.004181|1.32|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.415600|3.399900|3.416300|1.31|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004635|0.004580|0.004635|1.28|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|187.330000|186.600000|187.330000|0.88|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.020000|53.870000|54.020000|0.40|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052350|0.052510|0.052350|7.28|Y|Y/Y|Y/Y|Y|Y|
|TIA_USDT|0.554500|0.551500|0.554300|0.40|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|614.370000|604.400000|614.420000|0.65|N|N/Y|N/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T09:00:01+00:00, last15m_closed_end=2026-10-23T09:00+00:00, prior8high=0.004316, depth_time=2026-10-23T09:00:07+00:00, book20_bid_proxy_usdt=47844, book20_ask_proxy_usdt=36048, funding_indicative=0.000124, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-16.54%, turnover=7807536. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T09:00:02+00:00, last15m_closed_end=2026-10-23T09:00+00:00, prior8high=3.450000, depth_time=2026-10-23T09:00:08+00:00, book20_bid_proxy_usdt=26653, book20_ask_proxy_usdt=20850, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.17%, turnover=9413889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T09:00:02+00:00, last15m_closed_end=2026-10-23T09:00+00:00, prior8high=0.004672, depth_time=2026-10-23T09:00:22+00:00, book20_bid_proxy_usdt=2369877, book20_ask_proxy_usdt=1512238, funding_indicative=0.000011, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.40%, turnover=35685326. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T09:00:02+00:00, last15m_closed_end=2026-10-23T09:00+00:00, prior8high=189.800000, depth_time=2026-10-23T09:00:14+00:00, book20_bid_proxy_usdt=60478, book20_ask_proxy_usdt=131621, funding_indicative=-0.000151, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.89%, turnover=46741599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T09:00:01+00:00, last15m_closed_end=2026-10-23T09:00+00:00, prior8high=54.240000, depth_time=2026-10-23T09:00:19+00:00, book20_bid_proxy_usdt=33183081, book20_ask_proxy_usdt=34910513, funding_indicative=0.000151, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=332523508. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T09:00:02+00:00, last15m_closed_end=2026-10-23T09:00+00:00, prior8high=0.053510, depth_time=2026-10-23T09:00:12+00:00, book20_bid_proxy_usdt=636245, book20_ask_proxy_usdt=628202, funding_indicative=-0.000019, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.71%, turnover=11579673. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T09:00:02+00:00, last15m_closed_end=2026-10-23T09:00+00:00, prior8high=0.562000, depth_time=2026-10-23T09:00:16+00:00, book20_bid_proxy_usdt=343639, book20_ask_proxy_usdt=427368, funding_indicative=-0.000009, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=24360948. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-23T09:00:02+00:00, last15m_closed_end=2026-10-23T09:00+00:00, prior8high=617.990000, depth_time=2026-10-23T09:00:24+00:00, book20_bid_proxy_usdt=8166, book20_ask_proxy_usdt=23904, funding_indicative=0.000100, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=18627141. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
