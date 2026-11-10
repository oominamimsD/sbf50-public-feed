# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T00:45:18Z**
- feed_generated_utc: 2026-11-10T00:45:19+00:00
- source_sha256: `e24ddaa2f95e750a80d35817c5592e5b2c61e09a5ce72aa6c8bb310c09a7106a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T00:45+00:00, close=75007.5, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002648|-45.92|-51.87|-45.27|12176460|7.56|
|ARB_USDT|0.174260|-5.31|9.37|-4.66|31601814|0.57|
|ZEC_USDT|1169.410000|-4.59|-6.75|-3.94|2455554322|0.68|
|DOT_USDT|0.856000|-3.91|-8.36|-3.26|10788396|1.17|
|QNT_USDT|193.540000|-3.24|-4.40|-2.59|41236166|0.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002648|0.002154|0.002648|9.37|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.174260|0.173630|0.174260|0.70|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.856000|0.852500|0.856000|0.21|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.540000|193.630000|193.540000|0.98|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1169.410000|1152.430000|1169.410000|0.85|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T00:44:59+00:00, last15m_closed_end=2026-11-10T00:45+00:00, prior8high=0.005150, depth_time=2026-11-10T00:45:07+00:00, book20_bid_proxy_usdt=156243, book20_ask_proxy_usdt=29328, funding_indicative=-0.000771, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-45.92%, turnover=12176460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T00:44:59+00:00, last15m_closed_end=2026-11-10T00:45+00:00, prior8high=0.176000, depth_time=2026-11-10T00:45:08+00:00, book20_bid_proxy_usdt=62467, book20_ask_proxy_usdt=37226, funding_indicative=-0.000020, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.31%, turnover=31601814. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T00:44:59+00:00, last15m_closed_end=2026-11-10T00:45+00:00, prior8high=0.864400, depth_time=2026-11-10T00:45:14+00:00, book20_bid_proxy_usdt=787215, book20_ask_proxy_usdt=559566, funding_indicative=0.000067, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.91%, turnover=10788396. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T00:44:59+00:00, last15m_closed_end=2026-11-10T00:45+00:00, prior8high=197.070000, depth_time=2026-11-10T00:45:17+00:00, book20_bid_proxy_usdt=40023, book20_ask_proxy_usdt=97997, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.24%, turnover=41236166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T00:44:59+00:00, last15m_closed_end=2026-11-10T00:45+00:00, prior8high=1184.660000, depth_time=2026-11-10T00:45:12+00:00, book20_bid_proxy_usdt=235350, book20_ask_proxy_usdt=209049, funding_indicative=0.000096, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.59%, turnover=2455554322. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
