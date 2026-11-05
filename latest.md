# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T19:15:17Z**
- feed_generated_utc: 2026-11-05T19:15:18+00:00
- source_sha256: `b36ad474b8ec4aab7bd0c1bc74a7e5f5567aa9005bc53cc6b0a953d1f3ede7fb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T19:15+00:00, close=76218.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T19:00+00:00, close=76066.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T16:00+00:00, close=76013.2, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|FLUID_USDT|2.414000|-4.66|16.95|-4.96|8794894|4.13|
|QNT_USDT|189.650000|-1.13|-4.57|-1.43|43543227|1.05|
|BCH_USDT|276.120000|-1.07|-4.21|-1.37|10223209|2.53|
|XMR_USDT|610.400000|-0.79|1.05|-1.09|5046066|0.16|
|XRP_USDT|1.235400|-0.73|-5.65|-1.03|421824165|0.81|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|276.120000|272.300000|276.050000|0.42|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.414000|2.359000|2.414000|0.47|N|Y/Y|N/N|Y|N|
|QNT_USDT|189.650000|188.100000|189.650000|1.28|N|Y/Y|Y/N|Y|N|
|XMR_USDT|610.400000|610.310000|610.400000|1.52|N|Y/Y|Y/N|Y|N|
|XRP_USDT|1.235400|1.228300|1.235200|0.50|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-05T19:15:01+00:00, last15m_closed_end=2026-11-05T19:15+00:00, prior8high=278.080000, depth_time=2026-11-05T19:15:11+00:00, book20_bid_proxy_usdt=72361, book20_ask_proxy_usdt=57812, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.07%, turnover=10223209. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T19:15:01+00:00, last15m_closed_end=2026-11-05T19:15+00:00, prior8high=2.446000, depth_time=2026-11-05T19:15:03+00:00, book20_bid_proxy_usdt=191440, book20_ask_proxy_usdt=223230, funding_indicative=0.000062, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.66%, turnover=8794894. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-05T19:15:01+00:00, last15m_closed_end=2026-11-05T19:15+00:00, prior8high=192.450000, depth_time=2026-11-05T19:15:09+00:00, book20_bid_proxy_usdt=57743, book20_ask_proxy_usdt=78058, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.13%, turnover=43543227. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-11-05T19:15:01+00:00, last15m_closed_end=2026-11-05T19:15+00:00, prior8high=618.110000, depth_time=2026-11-05T19:15:13+00:00, book20_bid_proxy_usdt=48735, book20_ask_proxy_usdt=39661, funding_indicative=0.000771, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.79%, turnover=5046066. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-05T19:15:01+00:00, last15m_closed_end=2026-11-05T19:15+00:00, prior8high=1.244800, depth_time=2026-11-05T19:15:16+00:00, book20_bid_proxy_usdt=2153582, book20_ask_proxy_usdt=2585971, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.73%, turnover=421824165. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
