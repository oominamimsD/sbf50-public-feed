# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T18:15:18Z**
- feed_generated_utc: 2026-11-08T18:15:19+00:00
- source_sha256: `b752275d40617b362bc9bfe575face3823933431087a379d3858d8961fee0294`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T18:15+00:00, close=75859.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T18:00+00:00, close=75716, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001821|-7.00|56.35|-6.77|17514032|0.55|
|NEAR_USDT|3.609000|-2.48|-16.67|-2.25|30691215|2.77|
|AKE_USDT|0.005240|-2.18|-42.79|-1.95|19191885|3.82|
|IDOL_USDT|0.030203|-2.12|53.51|-1.89|7555501|4.29|
|ZEC_USDT|1254.370000|-1.28|1.32|-1.05|1405144359|0.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005240|0.005192|0.005240|0.89|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.030203|0.029412|0.030203|0.98|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.609000|3.586000|3.608000|0.99|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001821|0.001693|0.001821|0.38|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1254.370000|1238.290000|1254.300000|0.99|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T18:14:59+00:00, last15m_closed_end=2026-11-08T18:15+00:00, prior8high=0.005391, depth_time=2026-11-08T18:15:11+00:00, book20_bid_proxy_usdt=50702, book20_ask_proxy_usdt=39999, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.18%, turnover=19191885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T18:14:59+00:00, last15m_closed_end=2026-11-08T18:15+00:00, prior8high=0.031558, depth_time=2026-11-08T18:15:15+00:00, book20_bid_proxy_usdt=5097, book20_ask_proxy_usdt=3240, funding_indicative=0.000899, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=7555501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T18:14:59+00:00, last15m_closed_end=2026-11-08T18:15+00:00, prior8high=3.711000, depth_time=2026-11-08T18:15:08+00:00, book20_bid_proxy_usdt=4453259, book20_ask_proxy_usdt=3627566, funding_indicative=0.000059, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=30691215. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T18:14:59+00:00, last15m_closed_end=2026-11-08T18:15+00:00, prior8high=0.001970, depth_time=2026-11-08T18:15:07+00:00, book20_bid_proxy_usdt=15631, book20_ask_proxy_usdt=6298, funding_indicative=-0.001155, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.00%, turnover=17514032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T18:14:59+00:00, last15m_closed_end=2026-11-08T18:15+00:00, prior8high=1275.830000, depth_time=2026-11-08T18:15:17+00:00, book20_bid_proxy_usdt=318070, book20_ask_proxy_usdt=211613, funding_indicative=0.000032, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=1405144359. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
