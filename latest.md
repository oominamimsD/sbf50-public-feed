# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T00:30:13Z**
- feed_generated_utc: 2026-10-27T00:30:17+00:00
- source_sha256: `7b5f98ae8324db66efab04a9cc979f5d83420523f429070e3aae6e778bf4f135`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T00:30+00:00, close=80241.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.088070|-11.00|28.15|-10.81|5241334|7.88|
|ZRO_USDT|1.633000|-4.34|-14.14|-4.15|5323187|1.84|
|NEAR_USDT|4.500000|-1.59|-8.23|-1.40|111328141|2.22|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CAP_USDT|0.088070|0.098010|0.088070|13.25|Y|N/N|N/N|Y|N|
|NEAR_USDT|4.500000|4.422000|4.500000|1.07|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.633000|1.610100|1.633000|0.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- CAP_USDT: quote_utc=2026-10-27T00:30:00+00:00, last15m_closed_end=2026-10-27T00:30+00:00, prior8high=0.099940, depth_time=2026-10-27T00:30:08+00:00, book20_bid_proxy_usdt=49998, book20_ask_proxy_usdt=56557, funding_indicative=0.001845, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-11.00%, turnover=5241334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T00:30:00+00:00, last15m_closed_end=2026-10-27T00:30+00:00, prior8high=4.536000, depth_time=2026-10-27T00:30:12+00:00, book20_bid_proxy_usdt=3999433, book20_ask_proxy_usdt=4097661, funding_indicative=-0.000131, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=111328141. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T00:30:00+00:00, last15m_closed_end=2026-10-27T00:30+00:00, prior8high=1.643800, depth_time=2026-10-27T00:30:11+00:00, book20_bid_proxy_usdt=36044, book20_ask_proxy_usdt=46002, funding_indicative=-0.000320, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.34%, turnover=5323187. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
