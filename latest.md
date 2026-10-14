# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T09:15:20Z**
- feed_generated_utc: 2026-10-14T09:15:22+00:00
- source_sha256: `3bd68cf77ca2bf6698bbdd7fb7cb30705101ccc8e52f4e7a35d70534bb3c8ce8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T09:15+00:00, close=83440.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T09:00+00:00, close=83400.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.079520|-8.52|52.36|-8.57|29704152|1.26|
|TIA_USDT|0.552700|-4.26|16.04|-4.31|38492861|1.81|
|W_USDT|0.016274|-3.14|12.14|-3.19|6693671|1.23|
|UNI_USDT|7.355000|-2.86|-15.11|-2.91|19517599|1.36|
|DOT_USDT|1.142100|-1.27|-4.93|-1.32|19812866|1.75|
|SILVER_USDT|58.690000|-1.17|-4.36|-1.22|249865111|1.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.142100|1.142000|1.142200|3.39|N|Y/Y|Y/Y|N|N|
|SILVER_USDT|58.690000|58.560000|58.690000|0.57|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.079520|0.081200|0.079520|1.46|Y|Y/Y|Y/Y|N|Y|
|TIA_USDT|0.552700|0.547900|0.552700|1.18|N|Y/Y|Y/N|N|N|
|UNI_USDT|7.355000|7.339000|7.355000|0.34|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016274|0.016124|0.016274|1.04|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-14T09:14:59+00:00, last15m_closed_end=2026-10-14T09:15+00:00, prior8high=1.164200, depth_time=2026-10-14T09:15:17+00:00, book20_bid_proxy_usdt=351624, book20_ask_proxy_usdt=283921, funding_indicative=-0.000008, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.27%, turnover=19812866. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T09:14:59+00:00, last15m_closed_end=2026-10-14T09:15+00:00, prior8high=59.010000, depth_time=2026-10-14T09:15:19+00:00, book20_bid_proxy_usdt=48401763, book20_ask_proxy_usdt=33519025, funding_indicative=0.000073, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=249865111. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T09:14:59+00:00, last15m_closed_end=2026-10-14T09:15+00:00, prior8high=0.083840, depth_time=2026-10-14T09:15:07+00:00, book20_bid_proxy_usdt=210021, book20_ask_proxy_usdt=279610, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.52%, turnover=29704152. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T09:14:59+00:00, last15m_closed_end=2026-10-14T09:15+00:00, prior8high=0.564000, depth_time=2026-10-14T09:15:09+00:00, book20_bid_proxy_usdt=134058, book20_ask_proxy_usdt=200048, funding_indicative=0.000027, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.26%, turnover=38492861. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T09:14:59+00:00, last15m_closed_end=2026-10-14T09:15+00:00, prior8high=7.502000, depth_time=2026-10-14T09:15:15+00:00, book20_bid_proxy_usdt=1211201, book20_ask_proxy_usdt=1382205, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=19517599. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T09:14:59+00:00, last15m_closed_end=2026-10-14T09:15+00:00, prior8high=0.016686, depth_time=2026-10-14T09:15:12+00:00, book20_bid_proxy_usdt=35771, book20_ask_proxy_usdt=144776, funding_indicative=-0.000331, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.14%, turnover=6693671. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
