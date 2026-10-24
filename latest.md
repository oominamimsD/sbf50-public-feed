# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-24T17:00:28Z**
- feed_generated_utc: 2026-10-24T17:00:31+00:00
- source_sha256: `f9f1d60e0e3447adf19ea4ad206c6026b7a4d3e619f6b594fcaf7e581d76a994`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-24T17:00+00:00, close=80182.5, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-24T17:00+00:00, close=80182.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-24T16:00+00:00, close=79763.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.064590|-9.19|-10.36|-9.71|10295951|9.30|
|BIRB_USDT|0.094390|-3.34|94.53|-3.86|11982014|2.12|
|TIA_USDT|0.522800|-2.09|-20.54|-2.61|30233482|1.91|
|DOT_USDT|1.030700|-1.75|-7.75|-2.27|13057605|0.97|
|PENGU_USDT|0.007483|-0.88|0.40|-1.40|6926093|1.34|
|ARB_USDT|0.165950|-0.73|-9.77|-1.25|23953790|0.60|
|UNI_USDT|6.661000|-0.58|-6.24|-1.10|13215255|1.50|
|INJ_USDT|7.543000|-0.50|-10.86|-1.02|14207364|1.33|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.064590|0.065380|0.064590|1.13|N|Y/Y|Y/N|Y|N|
|ARB_USDT|0.165950|0.163630|0.165950|1.11|N|Y/Y|Y/Y|Y|N|
|BIRB_USDT|0.094390|0.092210|0.094540|0.30|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.030700|1.022700|1.030700|1.14|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.543000|7.423000|7.543000|0.74|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007483|0.007348|0.007483|1.59|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.522800|0.516000|0.522800|1.17|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.661000|6.513000|6.661000|1.12|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-24T17:00:01+00:00, last15m_closed_end=2026-10-24T17:00+00:00, prior8high=0.071620, depth_time=2026-10-24T17:00:06+00:00, book20_bid_proxy_usdt=11175, book20_ask_proxy_usdt=12714, funding_indicative=0.000092, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.19%, turnover=10295951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-24T17:00:01+00:00, last15m_closed_end=2026-10-24T17:00+00:00, prior8high=0.167660, depth_time=2026-10-24T17:00:22+00:00, book20_bid_proxy_usdt=77058, book20_ask_proxy_usdt=85316, funding_indicative=0.000026, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.73%, turnover=23953790. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-24T17:00:01+00:00, last15m_closed_end=2026-10-24T17:00+00:00, prior8high=0.113230, depth_time=2026-10-24T17:00:11+00:00, book20_bid_proxy_usdt=15612, book20_ask_proxy_usdt=15016, funding_indicative=-0.008538, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.34%, turnover=11982014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-24T17:00:01+00:00, last15m_closed_end=2026-10-24T17:00+00:00, prior8high=1.051500, depth_time=2026-10-24T17:00:17+00:00, book20_bid_proxy_usdt=460212, book20_ask_proxy_usdt=251770, funding_indicative=-0.000128, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=13057605. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-24T17:00:01+00:00, last15m_closed_end=2026-10-24T17:00+00:00, prior8high=7.609000, depth_time=2026-10-24T17:00:27+00:00, book20_bid_proxy_usdt=504832, book20_ask_proxy_usdt=208244, funding_indicative=0.000252, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.50%, turnover=14207364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-24T17:00:01+00:00, last15m_closed_end=2026-10-24T17:00+00:00, prior8high=0.007583, depth_time=2026-10-24T17:00:19+00:00, book20_bid_proxy_usdt=145411, book20_ask_proxy_usdt=352671, funding_indicative=-0.000013, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.88%, turnover=6926093. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-24T17:00:01+00:00, last15m_closed_end=2026-10-24T17:00+00:00, prior8high=0.535500, depth_time=2026-10-24T17:00:13+00:00, book20_bid_proxy_usdt=237315, book20_ask_proxy_usdt=261130, funding_indicative=0.000001, next_funding_utc=2026-10-24T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=30233482. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-24T17:00:01+00:00, last15m_closed_end=2026-10-24T17:00+00:00, prior8high=6.728000, depth_time=2026-10-24T17:00:24+00:00, book20_bid_proxy_usdt=2212405, book20_ask_proxy_usdt=2444672, funding_indicative=-0.000027, next_funding_utc=2026-10-25T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.58%, turnover=13215255. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
