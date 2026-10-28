# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-28T09:45:18Z**
- feed_generated_utc: 2026-10-28T09:45:21+00:00
- source_sha256: `a402b0e34842539ea7067b95865c1e655f4f8a1c2b49ca56d82ac486b223cebe`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-28T09:45+00:00, close=81485.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-28T09:00+00:00, close=81450, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-28T08:00+00:00, close=81049, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.058670|-7.72|-52.20|-8.91|26191326|1.70|
|BEAT_USDT|0.088070|-3.31|17.88|-4.50|14895346|2.27|
|INJ_USDT|7.929000|-3.21|-7.80|-4.40|25067479|1.26|
|AKE_USDT|0.020982|-0.67|-32.51|-1.86|6039842|6.20|
|DASH_USDT|54.220000|0.09|8.57|-1.10|16205300|1.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.020982|0.020071|0.020982|1.61|N|Y/Y|Y/Y|N|N|
|BEAT_USDT|0.088070|0.090650|0.088070|2.97|Y|N/N|N/N|N|N|
|DASH_USDT|54.220000|53.960000|54.220000|0.13|N|Y/Y|N/N|N|N|
|INJ_USDT|7.929000|7.895000|7.929000|0.83|N|Y/Y|N/N|N|N|
|Q_USDT|0.058670|0.056930|0.058670|0.30|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-28T09:45:04+00:00, last15m_closed_end=2026-10-28T09:45+00:00, prior8high=0.021005, depth_time=2026-10-28T09:45:14+00:00, book20_bid_proxy_usdt=7033, book20_ask_proxy_usdt=8171, funding_indicative=0.000050, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.67%, turnover=6039842. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-28T09:45:04+00:00, last15m_closed_end=2026-10-28T09:45+00:00, prior8high=0.108740, depth_time=2026-10-28T09:45:10+00:00, book20_bid_proxy_usdt=5706, book20_ask_proxy_usdt=7077, funding_indicative=0.000079, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.31%, turnover=14895346. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-28T09:45:04+00:00, last15m_closed_end=2026-10-28T09:45+00:00, prior8high=54.730000, depth_time=2026-10-28T09:45:16+00:00, book20_bid_proxy_usdt=953572, book20_ask_proxy_usdt=590873, funding_indicative=0.000100, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.09%, turnover=16205300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-28T09:45:04+00:00, last15m_closed_end=2026-10-28T09:45+00:00, prior8high=8.006000, depth_time=2026-10-28T09:45:12+00:00, book20_bid_proxy_usdt=290878, book20_ask_proxy_usdt=104886, funding_indicative=0.000248, next_funding_utc=2026-10-28T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=25067479. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-28T09:45:03+00:00, last15m_closed_end=2026-10-28T09:45+00:00, prior8high=0.061020, depth_time=2026-10-28T09:45:07+00:00, book20_bid_proxy_usdt=16281, book20_ask_proxy_usdt=15978, funding_indicative=-0.000518, next_funding_utc=2026-10-28T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.72%, turnover=26191326. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
