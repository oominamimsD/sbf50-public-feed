# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T21:00:17Z**
- feed_generated_utc: 2026-11-08T21:00:18+00:00
- source_sha256: `c52c26b492156eab086c00e24ce8613ae9e78380b4b117e6ce3c04cefe82a10b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T21:00+00:00, close=75718.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T21:00+00:00, close=75718.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001683|-14.06|44.49|-13.66|14368950|0.59|
|ZEC_USDT|1243.540000|-2.13|0.45|-1.73|1448738668|0.08|
|NEAR_USDT|3.628000|-1.97|-16.23|-1.57|31119894|2.76|
|ARB_USDT|0.167180|-1.60|0.60|-1.20|17929940|0.60|
|HYPE_USDT|76.341000|-1.46|-12.94|-1.06|22226025|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.167180|0.166560|0.167080|0.81|N|Y/Y|N/N|Y|N|
|HYPE_USDT|76.341000|76.273000|76.341000|0.70|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.628000|3.611000|3.626000|0.73|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001683|0.001706|0.001678|1.74|Y|Y/Y|N/N|Y|N|
|ZEC_USDT|1243.540000|1246.550000|1242.730000|1.29|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-08T21:00:02+00:00, last15m_closed_end=2026-11-08T21:00+00:00, prior8high=0.168430, depth_time=2026-11-08T21:00:14+00:00, book20_bid_proxy_usdt=100078, book20_ask_proxy_usdt=84199, funding_indicative=-0.000017, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=17929940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-08T21:00:02+00:00, last15m_closed_end=2026-11-08T21:00+00:00, prior8high=77.207000, depth_time=2026-11-08T21:00:16+00:00, book20_bid_proxy_usdt=81221, book20_ask_proxy_usdt=295404, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=22226025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T21:00:02+00:00, last15m_closed_end=2026-11-08T21:00+00:00, prior8high=3.666000, depth_time=2026-11-08T21:00:12+00:00, book20_bid_proxy_usdt=2830703, book20_ask_proxy_usdt=3647510, funding_indicative=0.000100, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=31119894. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T21:00:02+00:00, last15m_closed_end=2026-11-08T21:00+00:00, prior8high=0.001814, depth_time=2026-11-08T21:00:07+00:00, book20_bid_proxy_usdt=9842, book20_ask_proxy_usdt=14333, funding_indicative=-0.000144, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-14.06%, turnover=14368950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T21:00:02+00:00, last15m_closed_end=2026-11-08T21:00+00:00, prior8high=1268.660000, depth_time=2026-11-08T21:00:09+00:00, book20_bid_proxy_usdt=1111821, book20_ask_proxy_usdt=218912, funding_indicative=0.000041, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=1448738668. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
