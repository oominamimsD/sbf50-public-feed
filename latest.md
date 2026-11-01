# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T07:00:34Z**
- feed_generated_utc: 2026-11-01T07:00:37+00:00
- source_sha256: `a93b8dac7f4049ce4aed3c34ab9c40bea679e24eae29bc81d0fb8b8f876a1eeb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T07:00+00:00, close=77974.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T07:00+00:00, close=77974.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.233640|-21.11|39.13|-21.65|31180127|1.71|
|AKE_USDT|0.009407|-15.54|-67.81|-16.08|11793344|3.19|
|BLESS_USDT|0.009440|-10.63|16.35|-11.17|6519775|4.24|
|XPL_USDT|0.073660|-9.40|2.00|-9.94|5784083|2.72|
|Q_USDT|0.029360|-8.47|-62.80|-9.01|5073548|3.41|
|ZEC_USDT|1244.500000|-3.11|8.67|-3.65|963522920|0.08|
|ENA_USDT|0.188160|-3.01|0.73|-3.55|45221164|0.53|
|NEAR_USDT|4.381000|-2.12|-0.47|-2.66|54330240|2.28|
|XLM_USDT|0.169140|-1.51|0.43|-2.05|20739014|0.59|
|BEAT_USDT|0.097240|-1.31|45.11|-1.85|6110346|1.03|
|TRX_USDT|0.310880|-0.46|-5.48|-1.00|11521889|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009407|0.009305|0.009407|1.20|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097240|0.096700|0.097240|1.06|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009440|0.009421|0.009440|1.62|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188160|0.187140|0.188160|0.96|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.233640|0.231890|0.233640|0.94|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.381000|4.363000|4.381000|0.71|N|Y/Y|N/N|Y|N|
|Q_USDT|0.029360|0.028170|0.029360|3.15|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.310880|0.308890|0.310880|2.41|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.169140|0.168210|0.169140|0.74|N|N/Y|Y/N|Y|N|
|XPL_USDT|0.073660|0.070180|0.073650|3.41|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1244.500000|1243.250000|1244.490000|0.83|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T06:59:59+00:00, last15m_closed_end=2026-11-01T07:00+00:00, prior8high=0.010385, depth_time=2026-11-01T07:00:11+00:00, book20_bid_proxy_usdt=3370, book20_ask_proxy_usdt=6552, funding_indicative=-0.001904, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-15.54%, turnover=11793344. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-01T06:59:59+00:00, last15m_closed_end=2026-11-01T07:00+00:00, prior8high=0.098520, depth_time=2026-11-01T07:00:28+00:00, book20_bid_proxy_usdt=9640, book20_ask_proxy_usdt=12499, funding_indicative=0.000159, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=6110346. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T06:59:59+00:00, last15m_closed_end=2026-11-01T07:00+00:00, prior8high=0.009785, depth_time=2026-11-01T07:00:13+00:00, book20_bid_proxy_usdt=15212, book20_ask_proxy_usdt=13752, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.63%, turnover=6519775. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T06:59:59+00:00, last15m_closed_end=2026-11-01T07:00+00:00, prior8high=0.190760, depth_time=2026-11-01T07:00:23+00:00, book20_bid_proxy_usdt=191634, book20_ask_proxy_usdt=101388, funding_indicative=-0.000015, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.01%, turnover=45221164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T06:59:59+00:00, last15m_closed_end=2026-11-01T07:00+00:00, prior8high=0.247730, depth_time=2026-11-01T07:00:08+00:00, book20_bid_proxy_usdt=17856, book20_ask_proxy_usdt=4354, funding_indicative=-0.002417, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-21.11%, turnover=31180127. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T06:59:59+00:00, last15m_closed_end=2026-11-01T07:00+00:00, prior8high=4.417000, depth_time=2026-11-01T07:00:26+00:00, book20_bid_proxy_usdt=3968186, book20_ask_proxy_usdt=3919023, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=54330240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-01T06:59:59+00:00, last15m_closed_end=2026-11-01T07:00+00:00, prior8high=0.031360, depth_time=2026-11-01T07:00:18+00:00, book20_bid_proxy_usdt=38489, book20_ask_proxy_usdt=66708, funding_indicative=-0.000714, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=1, 24h_change=-8.47%, turnover=5073548. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-11-01T06:59:59+00:00, last15m_closed_end=2026-11-01T07:00+00:00, prior8high=0.315760, depth_time=2026-11-01T07:00:29+00:00, book20_bid_proxy_usdt=149930, book20_ask_proxy_usdt=70890, funding_indicative=-0.000106, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.46%, turnover=11521889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T06:59:59+00:00, last15m_closed_end=2026-11-01T07:00+00:00, prior8high=0.169690, depth_time=2026-11-01T07:00:27+00:00, book20_bid_proxy_usdt=173538, book20_ask_proxy_usdt=140112, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=20739014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T06:59:59+00:00, last15m_closed_end=2026-11-01T07:00+00:00, prior8high=0.074870, depth_time=2026-11-01T07:00:16+00:00, book20_bid_proxy_usdt=398748, book20_ask_proxy_usdt=300887, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.40%, turnover=5784083. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T06:59:59+00:00, last15m_closed_end=2026-11-01T07:00+00:00, prior8high=1254.820000, depth_time=2026-11-01T07:00:20+00:00, book20_bid_proxy_usdt=500134, book20_ask_proxy_usdt=784532, funding_indicative=-0.000121, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=963522920. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
