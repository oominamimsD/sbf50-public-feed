# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T09:45:20Z**
- feed_generated_utc: 2026-10-19T09:45:22+00:00
- source_sha256: `32b80fe465a40e4c1b7c5b3587569dc484ef26d996379c39e0105aed064a36a0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T09:45+00:00, close=82970.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T09:00+00:00, close=82786, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T08:00+00:00, close=82695, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|2.184400|-5.24|29.85|-7.49|21929955|1.83|
|STRK_USDT|0.059540|-3.28|-50.07|-5.53|18244127|1.68|
|HBAR_USDT|0.084570|-1.41|-9.82|-3.66|46703634|1.18|
|TIA_USDT|0.609600|-1.34|3.55|-3.59|56367923|1.64|
|ICNT_USDT|0.177600|-1.00|67.54|-3.25|6752460|5.63|
|SAND_USDT|0.058350|-0.69|-12.17|-2.94|17037465|1.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.184400|2.179000|2.187100|2.14|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084570|0.084210|0.084570|1.63|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.177600|0.165400|0.177600|3.20|N|Y/Y|Y/N|N|N|
|SAND_USDT|0.058350|0.058430|0.058380|1.48|Y|Y/Y|N/N|N|N|
|STRK_USDT|0.059540|0.059130|0.059540|1.24|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.609600|0.605200|0.609600|0.82|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T09:45:00+00:00, last15m_closed_end=2026-10-19T09:45+00:00, prior8high=2.310800, depth_time=2026-10-19T09:45:07+00:00, book20_bid_proxy_usdt=8567, book20_ask_proxy_usdt=10115, funding_indicative=-0.000522, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.24%, turnover=21929955. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T09:45:00+00:00, last15m_closed_end=2026-10-19T09:45+00:00, prior8high=0.085160, depth_time=2026-10-19T09:45:12+00:00, book20_bid_proxy_usdt=863490, book20_ask_proxy_usdt=769440, funding_indicative=-0.000063, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=46703634. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T09:45:00+00:00, last15m_closed_end=2026-10-19T09:45+00:00, prior8high=0.175400, depth_time=2026-10-19T09:45:16+00:00, book20_bid_proxy_usdt=121631, book20_ask_proxy_usdt=81728, funding_indicative=-0.000395, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.00%, turnover=6752460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-19T09:45:00+00:00, last15m_closed_end=2026-10-19T09:45+00:00, prior8high=0.061170, depth_time=2026-10-19T09:45:19+00:00, book20_bid_proxy_usdt=525168, book20_ask_proxy_usdt=590338, funding_indicative=-0.004588, next_funding_utc=2026-10-19T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.69%, turnover=17037465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T09:45:00+00:00, last15m_closed_end=2026-10-19T09:45+00:00, prior8high=0.060350, depth_time=2026-10-19T09:45:10+00:00, book20_bid_proxy_usdt=962078, book20_ask_proxy_usdt=692721, funding_indicative=0.000050, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=18244127. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T09:45:00+00:00, last15m_closed_end=2026-10-19T09:45+00:00, prior8high=0.620500, depth_time=2026-10-19T09:45:11+00:00, book20_bid_proxy_usdt=291702, book20_ask_proxy_usdt=262668, funding_indicative=-0.000008, next_funding_utc=2026-10-19T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=56367923. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
