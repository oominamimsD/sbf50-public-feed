# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T19:00:16Z**
- feed_generated_utc: 2026-11-05T19:00:18+00:00
- source_sha256: `b0591bc9fc78c4678d027185617fc0c5a9c7c8f89e7c3f38a7a59e77d0fd75ae`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T19:00+00:00, close=76066.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T19:00+00:00, close=76066.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T16:00+00:00, close=76013.2, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002385|-7.55|-88.67|-7.62|18077517|8.39|
|FLUID_USDT|2.375000|-6.20|15.06|-6.27|8923756|4.20|
|BCH_USDT|274.780000|-1.55|-4.68|-1.62|10196301|2.91|
|ZEC_USDT|1225.680000|-0.94|-9.70|-1.01|1975087111|0.08|
|HYPE_USDT|77.959000|-0.94|-17.00|-1.01|91794280|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002385|0.001878|0.002385|3.18|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|274.780000|272.300000|274.780000|0.25|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.375000|2.359000|2.375000|0.34|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.959000|77.682000|77.959000|0.45|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1225.680000|1233.000000|1225.830000|0.65|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T18:59:59+00:00, last15m_closed_end=2026-11-05T19:00+00:00, prior8high=0.003465, depth_time=2026-11-05T19:00:07+00:00, book20_bid_proxy_usdt=25514, book20_ask_proxy_usdt=17659, funding_indicative=-0.013751, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.55%, turnover=18077517. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T18:59:59+00:00, last15m_closed_end=2026-11-05T19:00+00:00, prior8high=279.080000, depth_time=2026-11-05T19:00:11+00:00, book20_bid_proxy_usdt=56631, book20_ask_proxy_usdt=83126, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.55%, turnover=10196301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T18:59:59+00:00, last15m_closed_end=2026-11-05T19:00+00:00, prior8high=2.526000, depth_time=2026-11-05T19:00:08+00:00, book20_bid_proxy_usdt=182366, book20_ask_proxy_usdt=208560, funding_indicative=0.000107, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.20%, turnover=8923756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T18:59:59+00:00, last15m_closed_end=2026-11-05T19:00+00:00, prior8high=79.928000, depth_time=2026-11-05T19:00:15+00:00, book20_bid_proxy_usdt=165759, book20_ask_proxy_usdt=169475, funding_indicative=0.000050, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.94%, turnover=91794280. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-05T18:59:59+00:00, last15m_closed_end=2026-11-05T19:00+00:00, prior8high=1264.370000, depth_time=2026-11-05T19:00:13+00:00, book20_bid_proxy_usdt=179158, book20_ask_proxy_usdt=298865, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.94%, turnover=1975087111. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
