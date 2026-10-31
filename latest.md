# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T19:45:20Z**
- feed_generated_utc: 2026-10-31T19:45:22+00:00
- source_sha256: `f5c8ff2f4562821ae096575bb3d8c743f834899b93ba45155d0cb0df59fd0d4d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T19:45+00:00, close=77569.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T19:00+00:00, close=77582.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRX_USDT|0.306620|-1.82|-6.78|-1.83|8681926|0.33|
|WLD_USDT|0.397100|-1.80|-14.04|-1.81|36753036|2.52|
|DASH_USDT|47.920000|-1.43|-3.19|-1.44|5125917|2.09|
|BTW_USDT|1.107000|-1.32|-36.42|-1.33|6968095|4.51|
|FET_USDT|0.161200|-1.28|-6.44|-1.29|5321497|6.20|
|APT_USDT|0.633900|-1.07|-9.68|-1.08|5174274|1.58|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.633900|0.634500|0.633900|2.53|Y|Y/Y|Y/Y|Y|Y|
|BTW_USDT|1.107000|1.100400|1.107000|0.72|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.920000|47.990000|47.920000|1.16|N|Y/N|Y/Y|Y|N|
|FET_USDT|0.161200|0.160900|0.161200|0.28|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.306620|0.305290|0.306620|0.24|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.397100|0.397200|0.397100|0.64|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-31T19:44:59+00:00, last15m_closed_end=2026-10-31T19:45+00:00, prior8high=0.638000, depth_time=2026-10-31T19:45:18+00:00, book20_bid_proxy_usdt=151664, book20_ask_proxy_usdt=135140, funding_indicative=0.000036, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=5174274. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T19:44:59+00:00, last15m_closed_end=2026-10-31T19:45+00:00, prior8high=1.134700, depth_time=2026-10-31T19:45:15+00:00, book20_bid_proxy_usdt=22352, book20_ask_proxy_usdt=17632, funding_indicative=-0.000212, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.32%, turnover=6968095. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T19:45:00+00:00, last15m_closed_end=2026-10-31T19:45+00:00, prior8high=48.340000, depth_time=2026-10-31T19:45:09+00:00, book20_bid_proxy_usdt=1019281, book20_ask_proxy_usdt=725858, funding_indicative=-0.000024, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.43%, turnover=5125917. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T19:45:00+00:00, last15m_closed_end=2026-10-31T19:45+00:00, prior8high=0.162200, depth_time=2026-10-31T19:45:11+00:00, book20_bid_proxy_usdt=1213627, book20_ask_proxy_usdt=867529, funding_indicative=-0.000119, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=5321497. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T19:44:59+00:00, last15m_closed_end=2026-10-31T19:45+00:00, prior8high=0.310250, depth_time=2026-10-31T19:45:04+00:00, book20_bid_proxy_usdt=86238, book20_ask_proxy_usdt=78868, funding_indicative=-0.000398, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=8681926. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T19:44:59+00:00, last15m_closed_end=2026-10-31T19:45+00:00, prior8high=0.400400, depth_time=2026-10-31T19:45:10+00:00, book20_bid_proxy_usdt=3259164, book20_ask_proxy_usdt=2813192, funding_indicative=-0.000068, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=36753036. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
