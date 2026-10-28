# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T11:04:17Z**
- feed_generated_utc: 2026-10-28T11:05:18+00:00
- source_sha256: `9733953fe6e43ed0d1dc71fb9d208aa4a7d1c7b3ced059a8238ddc68fd4509f6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 1.01 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T11:00+00:00, close=81460.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T11:00+00:00, close=81460.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.057530|-9.52|-53.13|-10.62|20313466|5.21|
|BEAT_USDT|0.085290|-6.36|14.16|-7.46|15410515|2.34|
|AKE_USDT|0.019993|-5.35|-35.69|-6.45|6342466|0.50|
|ENA_USDT|0.205950|-3.20|8.46|-4.30|67922851|0.48|
|INJ_USDT|7.937000|-3.11|-7.70|-4.21|24371357|1.26|
|SILVER_USDT|53.840000|-1.46|-7.09|-2.56|227031756|1.86|
|DASH_USDT|53.780000|-0.71|7.68|-1.81|15776944|1.86|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.019993|0.019671|0.020037|0.73|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.085290|0.084080|0.085550|0.88|N|Y/Y|N/N|N|N|
|DASH_USDT|53.780000|53.550000|53.700000|8.16|N|Y/Y|N/N|N|N|
|ENA_USDT|0.205950|0.204750|0.206740|4.04|N|Y/Y|N/N|N|N|
|INJ_USDT|7.937000|7.895000|7.956000|0.53|N|Y/Y|N/N|N|N|
|Q_USDT|0.057530|0.055820|0.058150|0.47|N|Y/Y|Y/Y|N|N|
|SILVER_USDT|53.840000|53.750000|53.860000|0.25|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T11:02:08+00:00, last15m_closed_end=2026-10-28T11:00+00:00, prior8high=0.021104, depth_time=2026-10-28T11:03:09+00:00, book20_bid_proxy_usdt=10138, book20_ask_proxy_usdt=6127, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.35%, turnover=6342466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T11:02:07+00:00, last15m_closed_end=2026-10-28T11:00+00:00, prior8high=0.105500, depth_time=2026-10-28T11:02:55+00:00, book20_bid_proxy_usdt=7908, book20_ask_proxy_usdt=20097, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.36%, turnover=15410515. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T11:02:08+00:00, last15m_closed_end=2026-10-28T11:00+00:00, prior8high=54.320000, depth_time=2026-10-28T11:04:12+00:00, book20_bid_proxy_usdt=900676, book20_ask_proxy_usdt=608227, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.71%, turnover=15776944. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T11:02:07+00:00, last15m_closed_end=2026-10-28T11:00+00:00, prior8high=0.210410, depth_time=2026-10-28T11:03:15+00:00, book20_bid_proxy_usdt=179755, book20_ask_proxy_usdt=167296, funding_indicative=0.000047, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.20%, turnover=67922851. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T11:02:08+00:00, last15m_closed_end=2026-10-28T11:00+00:00, prior8high=7.998000, depth_time=2026-10-28T11:03:19+00:00, book20_bid_proxy_usdt=290085, book20_ask_proxy_usdt=254093, funding_indicative=0.000241, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=24371357. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T11:02:07+00:00, last15m_closed_end=2026-10-28T11:00+00:00, prior8high=0.060270, depth_time=2026-10-28T11:02:48+00:00, book20_bid_proxy_usdt=18060, book20_ask_proxy_usdt=24926, funding_indicative=-0.000320, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.52%, turnover=20313466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-28T11:02:07+00:00, last15m_closed_end=2026-10-28T11:00+00:00, prior8high=54.230000, depth_time=2026-10-28T11:03:24+00:00, book20_bid_proxy_usdt=44078410, book20_ask_proxy_usdt=41714001, funding_indicative=0.000009, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.46%, turnover=227031756. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
