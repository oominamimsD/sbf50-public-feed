# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T19:30:18Z**
- feed_generated_utc: 2026-10-21T19:30:20+00:00
- source_sha256: `b3dc444c1e3624905600258da9897d4542b56892429269af95e8b884c5082607`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T19:30+00:00, close=84450.6, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-21T19:00+00:00, close=84374.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T16:00+00:00, close=84499, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002412|-15.18|70.09|-15.13|9091177|4.14|
|BR_USDT|0.497750|-8.08|22.07|-8.03|14845368|1.41|
|AKE_USDT|0.025488|-4.50|-1.51|-4.45|10146878|3.14|
|INJ_USDT|8.503000|-2.91|11.31|-2.86|57820627|4.71|
|JCT_USDT|0.004195|-1.31|99.66|-1.26|15231934|2.38|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025488|0.025371|0.025488|0.67|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.497750|0.502290|0.497760|1.09|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002412|0.002138|0.002412|0.18|N|Y/Y|N/N|N|N|
|INJ_USDT|8.503000|8.474000|8.503000|2.73|N|Y/Y|N/N|N|N|
|JCT_USDT|0.004195|0.004098|0.004182|0.47|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T19:30:02+00:00, last15m_closed_end=2026-10-21T19:30+00:00, prior8high=0.026445, depth_time=2026-10-21T19:30:10+00:00, book20_bid_proxy_usdt=10485, book20_ask_proxy_usdt=14265, funding_indicative=0.000050, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.50%, turnover=10146878. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T19:30:02+00:00, last15m_closed_end=2026-10-21T19:30+00:00, prior8high=0.528660, depth_time=2026-10-21T19:30:10+00:00, book20_bid_proxy_usdt=4570, book20_ask_proxy_usdt=6014, funding_indicative=-0.000148, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.08%, turnover=14845368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T19:30:02+00:00, last15m_closed_end=2026-10-21T19:30+00:00, prior8high=0.002442, depth_time=2026-10-21T19:30:08+00:00, book20_bid_proxy_usdt=119761, book20_ask_proxy_usdt=108945, funding_indicative=0.000012, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=1, 24h_change=-15.18%, turnover=9091177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T19:30:02+00:00, last15m_closed_end=2026-10-21T19:30+00:00, prior8high=8.717000, depth_time=2026-10-21T19:30:15+00:00, book20_bid_proxy_usdt=193281, book20_ask_proxy_usdt=273558, funding_indicative=0.000053, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.91%, turnover=57820627. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-21T19:30:02+00:00, last15m_closed_end=2026-10-21T19:30+00:00, prior8high=0.004433, depth_time=2026-10-21T19:30:17+00:00, book20_bid_proxy_usdt=29763, book20_ask_proxy_usdt=62880, funding_indicative=0.000121, next_funding_utc=2026-10-21T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=15231934. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
