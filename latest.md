# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T19:15:13Z**
- feed_generated_utc: 2026-11-03T19:15:15+00:00
- source_sha256: `b5a5d3963a2065b425b905edb928758c34619375076ad590b16c5688d2a64aaa`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T19:15+00:00, close=77504.8, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T19:00+00:00, close=77569.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T16:00+00:00, close=77664.3, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003964|-4.61|-81.23|-4.41|13303962|2.52|
|QNT_USDT|191.540000|-1.98|-3.20|-1.78|55685422|0.52|
|XPL_USDT|0.063170|-1.37|-14.42|-1.17|9690235|3.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003964|0.003757|0.003964|1.08|N|Y/Y|Y/Y|N|N|
|QNT_USDT|191.540000|191.500000|191.540000|1.12|N|Y/Y|Y/Y|N|N|
|XPL_USDT|0.063170|0.063250|0.063170|2.00|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T19:15:00+00:00, last15m_closed_end=2026-11-03T19:15+00:00, prior8high=0.004095, depth_time=2026-11-03T19:15:08+00:00, book20_bid_proxy_usdt=29364, book20_ask_proxy_usdt=42784, funding_indicative=-0.000569, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.61%, turnover=13303962. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T19:15:00+00:00, last15m_closed_end=2026-11-03T19:15+00:00, prior8high=195.800000, depth_time=2026-11-03T19:15:10+00:00, book20_bid_proxy_usdt=100618, book20_ask_proxy_usdt=105153, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=55685422. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T19:15:00+00:00, last15m_closed_end=2026-11-03T19:15+00:00, prior8high=0.064190, depth_time=2026-11-03T19:15:12+00:00, book20_bid_proxy_usdt=517947, book20_ask_proxy_usdt=440466, funding_indicative=0.000050, next_funding_utc=2026-11-03T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.37%, turnover=9690235. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
