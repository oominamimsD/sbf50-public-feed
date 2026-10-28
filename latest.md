# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T11:45:25Z**
- feed_generated_utc: 2026-10-28T11:45:32+00:00
- source_sha256: `95f5bc24045b3fa650da6e706b219fdc2fa3537eb5d4ec5a25c71c0fd6cbe200`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.12 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T11:45+00:00, close=81345.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T11:00+00:00, close=81460.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.054750|-13.89|-55.39|-14.90|20732097|5.47|
|BEAT_USDT|0.080370|-11.76|7.57|-12.77|16154574|4.97|
|AKE_USDT|0.019958|-5.52|-35.80|-6.53|6467345|2.00|
|ENA_USDT|0.203490|-4.36|7.16|-5.37|74288481|0.49|
|INJ_USDT|7.953000|-2.91|-7.52|-3.92|24655600|1.26|
|DASH_USDT|53.590000|-1.07|7.30|-2.08|16198985|1.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.019958|0.019671|0.019958|1.09|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.080370|0.074400|0.080420|0.72|N|Y/Y|N/N|N|N|
|DASH_USDT|53.590000|53.440000|53.590000|0.67|N|Y/Y|N/N|N|N|
|ENA_USDT|0.203490|0.202410|0.203490|4.01|N|Y/Y|N/N|N|N|
|INJ_USDT|7.953000|7.897000|7.953000|0.87|N|Y/Y|N/N|N|N|
|Q_USDT|0.054750|0.054670|0.054750|0.68|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T11:45:02+00:00, last15m_closed_end=2026-10-28T11:45+00:00, prior8high=0.021104, depth_time=2026-10-28T11:45:13+00:00, book20_bid_proxy_usdt=10686, book20_ask_proxy_usdt=4651, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.52%, turnover=6467345. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T11:45:02+00:00, last15m_closed_end=2026-10-28T11:45+00:00, prior8high=0.091680, depth_time=2026-10-28T11:45:11+00:00, book20_bid_proxy_usdt=5937, book20_ask_proxy_usdt=7696, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.76%, turnover=16154574. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T11:45:02+00:00, last15m_closed_end=2026-10-28T11:45+00:00, prior8high=54.240000, depth_time=2026-10-28T11:45:25+00:00, book20_bid_proxy_usdt=969948, book20_ask_proxy_usdt=733787, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=16198985. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-28T11:45:02+00:00, last15m_closed_end=2026-10-28T11:45+00:00, prior8high=0.208060, depth_time=2026-10-28T11:45:16+00:00, book20_bid_proxy_usdt=196364, book20_ask_proxy_usdt=187718, funding_indicative=0.000025, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.36%, turnover=74288481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T11:45:02+00:00, last15m_closed_end=2026-10-28T11:45+00:00, prior8high=7.998000, depth_time=2026-10-28T11:45:21+00:00, book20_bid_proxy_usdt=236743, book20_ask_proxy_usdt=250348, funding_indicative=0.000234, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=24655600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T11:45:02+00:00, last15m_closed_end=2026-10-28T11:45+00:00, prior8high=0.059890, depth_time=2026-10-28T11:45:08+00:00, book20_bid_proxy_usdt=17746, book20_ask_proxy_usdt=23167, funding_indicative=-0.000354, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.89%, turnover=20732097. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
