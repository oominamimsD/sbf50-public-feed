# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T00:15:17Z**
- feed_generated_utc: 2026-11-10T00:15:18+00:00
- source_sha256: `cb9ec234a087c2f3b1569bbc993b3f0dfa457fc5a6813b9eaed1b81cf8f33b30`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T00:15+00:00, close=75264, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002448|-50.01|-55.50|-49.70|11069510|8.17|
|ZEC_USDT|1166.220000|-4.85|-7.00|-4.54|2413482248|0.09|
|DOT_USDT|0.856000|-3.91|-8.36|-3.60|10731500|1.17|
|HBAR_USDT|0.066510|-2.86|-5.61|-2.55|8437717|1.50|
|QNT_USDT|194.570000|-2.73|-3.89|-2.42|40153823|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002448|0.002859|0.002448|11.18|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|0.856000|0.853200|0.856000|1.88|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.066510|0.066670|0.066510|2.54|Y|Y/Y|Y/N|Y|N|
|QNT_USDT|194.570000|193.880000|194.570000|1.04|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1166.220000|1152.430000|1166.210000|1.08|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T00:14:59+00:00, last15m_closed_end=2026-11-10T00:15+00:00, prior8high=0.005150, depth_time=2026-11-10T00:15:07+00:00, book20_bid_proxy_usdt=37583, book20_ask_proxy_usdt=178789, funding_indicative=-0.001077, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-50.01%, turnover=11069510. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T00:14:59+00:00, last15m_closed_end=2026-11-10T00:15+00:00, prior8high=0.864400, depth_time=2026-11-10T00:15:11+00:00, book20_bid_proxy_usdt=693294, book20_ask_proxy_usdt=656940, funding_indicative=0.000066, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.91%, turnover=10731500. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T00:14:59+00:00, last15m_closed_end=2026-11-10T00:15+00:00, prior8high=0.067330, depth_time=2026-11-10T00:15:12+00:00, book20_bid_proxy_usdt=710752, book20_ask_proxy_usdt=869280, funding_indicative=0.000088, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.86%, turnover=8437717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T00:14:59+00:00, last15m_closed_end=2026-11-10T00:15+00:00, prior8high=197.070000, depth_time=2026-11-10T00:15:15+00:00, book20_bid_proxy_usdt=80039, book20_ask_proxy_usdt=62423, funding_indicative=0.000100, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.73%, turnover=40153823. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T00:14:59+00:00, last15m_closed_end=2026-11-10T00:15+00:00, prior8high=1184.660000, depth_time=2026-11-10T00:15:09+00:00, book20_bid_proxy_usdt=170718, book20_ask_proxy_usdt=267729, funding_indicative=0.000094, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.85%, turnover=2413482248. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
