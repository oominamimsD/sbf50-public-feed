# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T19:30:15Z**
- feed_generated_utc: 2026-11-05T19:30:16+00:00
- source_sha256: `f0bf05c41620a282fe76edd66e594f75d38d806d6e8d77ecd9a2608bd8bc909b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T19:30+00:00, close=76008.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T19:00+00:00, close=76066.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T16:00+00:00, close=76013.2, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002375|-7.94|-88.72|-7.93|18460324|4.22|
|FLUID_USDT|2.402000|-5.13|16.37|-5.12|8810873|8.33|
|BCH_USDT|274.550000|-1.63|-4.76|-1.62|10243853|2.55|
|NEAR_USDT|3.664000|-1.10|-21.18|-1.09|68365400|2.73|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002375|0.001878|0.002386|1.64|N|Y/Y|Y/Y|Y|N|
|BCH_USDT|274.550000|272.300000|274.800000|0.17|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.402000|2.359000|2.402000|0.51|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.664000|3.638000|3.664000|0.30|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T19:30:01+00:00, last15m_closed_end=2026-11-05T19:30+00:00, prior8high=0.003109, depth_time=2026-11-05T19:30:06+00:00, book20_bid_proxy_usdt=36564, book20_ask_proxy_usdt=25073, funding_indicative=-0.011029, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-7.94%, turnover=18460324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T19:30:02+00:00, last15m_closed_end=2026-11-05T19:30+00:00, prior8high=276.140000, depth_time=2026-11-05T19:30:12+00:00, book20_bid_proxy_usdt=57227, book20_ask_proxy_usdt=70303, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.63%, turnover=10243853. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T19:30:01+00:00, last15m_closed_end=2026-11-05T19:30+00:00, prior8high=2.446000, depth_time=2026-11-05T19:30:07+00:00, book20_bid_proxy_usdt=200931, book20_ask_proxy_usdt=229907, funding_indicative=0.000059, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.13%, turnover=8810873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-05T19:30:01+00:00, last15m_closed_end=2026-11-05T19:30+00:00, prior8high=3.749000, depth_time=2026-11-05T19:30:13+00:00, book20_bid_proxy_usdt=4009255, book20_ask_proxy_usdt=4555677, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=68365400. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
