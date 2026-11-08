# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T18:45:15Z**
- feed_generated_utc: 2026-11-08T18:45:16+00:00
- source_sha256: `b69d7cea3678e3b61e3fbf06eddc4681e648d2266757c7a7b497167d3d24ac48`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T18:45+00:00, close=75900, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T18:00+00:00, close=75716, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001796|-8.27|54.22|-8.09|17627315|0.56|
|AKE_USDT|0.005175|-3.39|-43.50|-3.21|19341116|7.73|
|NEAR_USDT|3.644000|-1.54|-15.86|-1.36|31928408|2.74|
|IDOL_USDT|0.030493|-1.18|54.99|-1.00|7568428|3.28|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005175|0.005175|0.005174|0.77|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.030493|0.029412|0.030493|0.34|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.644000|3.586000|3.644000|0.60|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001796|0.001693|0.001794|0.60|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T18:44:59+00:00, last15m_closed_end=2026-11-08T18:45+00:00, prior8high=0.005344, depth_time=2026-11-08T18:45:09+00:00, book20_bid_proxy_usdt=102450, book20_ask_proxy_usdt=46803, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.39%, turnover=19341116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T18:44:59+00:00, last15m_closed_end=2026-11-08T18:45+00:00, prior8high=0.031558, depth_time=2026-11-08T18:45:14+00:00, book20_bid_proxy_usdt=4380, book20_ask_proxy_usdt=4034, funding_indicative=0.000895, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.18%, turnover=7568428. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T18:44:59+00:00, last15m_closed_end=2026-11-08T18:45+00:00, prior8high=3.695000, depth_time=2026-11-08T18:45:12+00:00, book20_bid_proxy_usdt=3591950, book20_ask_proxy_usdt=3976438, funding_indicative=0.000098, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=31928408. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T18:44:59+00:00, last15m_closed_end=2026-11-08T18:45+00:00, prior8high=0.001938, depth_time=2026-11-08T18:45:07+00:00, book20_bid_proxy_usdt=11464, book20_ask_proxy_usdt=12424, funding_indicative=-0.001016, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.27%, turnover=17627315. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
