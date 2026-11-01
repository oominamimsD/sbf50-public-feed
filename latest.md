# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T06:15:21Z**
- feed_generated_utc: 2026-11-01T06:15:23+00:00
- source_sha256: `21623e87a9d2360dfd0ce4123ddf6a0e599215c9fee8e99bb4927844607d0fe7`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T06:15+00:00, close=77988, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T06:00+00:00, close=77875.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.238940|-19.32|42.29|-19.87|30822535|2.93|
|AKE_USDT|0.009886|-11.24|-66.17|-11.79|11585801|4.04|
|XPL_USDT|0.073460|-9.65|1.73|-10.20|5286365|1.36|
|BLESS_USDT|0.009713|-8.05|19.72|-8.60|6311905|4.12|
|ZEC_USDT|1254.740000|-2.32|9.56|-2.87|942482060|0.40|
|BEAT_USDT|0.097790|-0.76|45.93|-1.31|5957630|3.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.009886|0.009000|0.009907|0.94|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.097790|0.096700|0.097780|1.52|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009713|0.009370|0.009715|0.59|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.238940|0.229900|0.238130|0.81|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.073460|0.069100|0.073500|2.43|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1254.740000|1238.800000|1254.470000|1.11|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-01T06:15:01+00:00, last15m_closed_end=2026-11-01T06:15+00:00, prior8high=0.010385, depth_time=2026-11-01T06:15:10+00:00, book20_bid_proxy_usdt=5953, book20_ask_proxy_usdt=16079, funding_indicative=-0.002382, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.24%, turnover=11585801. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-01T06:15:02+00:00, last15m_closed_end=2026-11-01T06:15+00:00, prior8high=0.099240, depth_time=2026-11-01T06:15:19+00:00, book20_bid_proxy_usdt=11438, book20_ask_proxy_usdt=16724, funding_indicative=0.000227, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.76%, turnover=5957630. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T06:15:01+00:00, last15m_closed_end=2026-11-01T06:15+00:00, prior8high=0.009822, depth_time=2026-11-01T06:15:16+00:00, book20_bid_proxy_usdt=12336, book20_ask_proxy_usdt=15750, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-8.05%, turnover=6311905. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T06:15:01+00:00, last15m_closed_end=2026-11-01T06:15+00:00, prior8high=0.247730, depth_time=2026-11-01T06:15:08+00:00, book20_bid_proxy_usdt=4500, book20_ask_proxy_usdt=10615, funding_indicative=-0.002632, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-19.32%, turnover=30822535. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T06:15:02+00:00, last15m_closed_end=2026-11-01T06:15+00:00, prior8high=0.086230, depth_time=2026-11-01T06:15:13+00:00, book20_bid_proxy_usdt=356387, book20_ask_proxy_usdt=294113, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.65%, turnover=5286365. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T06:15:01+00:00, last15m_closed_end=2026-11-01T06:15+00:00, prior8high=1251.980000, depth_time=2026-11-01T06:15:17+00:00, book20_bid_proxy_usdt=573069, book20_ask_proxy_usdt=313649, funding_indicative=-0.000129, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=942482060. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
