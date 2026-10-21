# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T06:45:22Z**
- feed_generated_utc: 2026-10-21T06:45:26+00:00
- source_sha256: `c97a195fec74c5889e93dd0f55342b799908bfe13b41501f7947685385cc8687`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T06:45+00:00, close=82795, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T06:00+00:00, close=82635.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T04:00+00:00, close=82699, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.042500|-34.24|162.71|-34.49|6860177|5.19|
|BAT_USDT|0.182230|-15.54|2.73|-15.79|10986781|0.55|
|BR_USDT|0.581260|-10.66|34.23|-10.91|33498834|8.95|
|XMR_USDT|578.870000|-6.66|9.65|-6.91|21245664|0.17|
|PHA_USDT|0.056620|-2.07|2.88|-2.32|6803510|1.77|
|SILVER_USDT|57.320000|-1.08|-3.48|-1.33|226371153|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.042500|0.046675|0.042500|18.97|Y|Y/Y|Y/Y|N|Y|
|BAT_USDT|0.182230|0.182340|0.182230|1.46|Y|Y/Y|Y/N|N|N|
|BR_USDT|0.581260|0.580080|0.579950|1.70|Y|Y/Y|N/N|N|N|
|PHA_USDT|0.056620|0.055950|0.056620|0.63|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.320000|57.270000|57.320000|0.46|N|Y/Y|Y/N|N|N|
|XMR_USDT|578.870000|575.320000|578.870000|0.35|N|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T06:45:02+00:00, last15m_closed_end=2026-10-21T06:45+00:00, prior8high=0.062630, depth_time=2026-10-21T06:45:09+00:00, book20_bid_proxy_usdt=15991, book20_ask_proxy_usdt=7871, funding_indicative=0.000047, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-34.24%, turnover=6860177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T06:45:02+00:00, last15m_closed_end=2026-10-21T06:45+00:00, prior8high=0.186710, depth_time=2026-10-21T06:45:11+00:00, book20_bid_proxy_usdt=29804, book20_ask_proxy_usdt=24889, funding_indicative=-0.000128, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-15.54%, turnover=10986781. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T06:45:02+00:00, last15m_closed_end=2026-10-21T06:45+00:00, prior8high=0.595910, depth_time=2026-10-21T06:45:14+00:00, book20_bid_proxy_usdt=3871, book20_ask_proxy_usdt=4480, funding_indicative=0.000038, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.66%, turnover=33498834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PHA_USDT: quote_utc=2026-10-21T06:45:02+00:00, last15m_closed_end=2026-10-21T06:45+00:00, prior8high=0.057320, depth_time=2026-10-21T06:45:16+00:00, book20_bid_proxy_usdt=95800, book20_ask_proxy_usdt=78879, funding_indicative=-0.000031, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.07%, turnover=6803510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T06:45:02+00:00, last15m_closed_end=2026-10-21T06:45+00:00, prior8high=57.780000, depth_time=2026-10-21T06:45:21+00:00, book20_bid_proxy_usdt=37873685, book20_ask_proxy_usdt=35888690, funding_indicative=0.000040, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=226371153. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-21T06:45:02+00:00, last15m_closed_end=2026-10-21T06:45+00:00, prior8high=581.680000, depth_time=2026-10-21T06:45:16+00:00, book20_bid_proxy_usdt=12026, book20_ask_proxy_usdt=10015, funding_indicative=0.000100, next_funding_utc=2026-10-21T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.66%, turnover=21245664. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
