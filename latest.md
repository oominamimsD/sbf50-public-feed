# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T21:30:18Z**
- feed_generated_utc: 2026-10-21T21:30:21+00:00
- source_sha256: `63b16e399dffaff99e1ed9d200130128f4d22bb0f20e57533df2dabe7f79c3f5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T21:30+00:00, close=84765.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T21:00+00:00, close=84645, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BR_USDT|0.491310|-9.27|20.49|-9.58|14927039|1.02|
|AKE_USDT|0.025396|-4.84|-1.87|-5.15|10346399|1.18|
|ZRO_USDT|2.000800|-4.59|5.64|-4.90|7336239|0.50|
|JCT_USDT|0.004093|-3.71|94.81|-4.02|14108737|9.77|
|LDO_USDT|0.411000|-1.01|1.28|-1.32|5010126|2.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.025396|0.025195|0.025407|1.29|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.491310|0.476600|0.491170|1.12|N|Y/Y|Y/Y|N|N|
|JCT_USDT|0.004093|0.004103|0.004096|0.61|N|Y/Y|N/N|N|N|
|LDO_USDT|0.411000|0.409900|0.411000|0.36|N|N/N|N/N|N|N|
|ZRO_USDT|2.000800|1.993500|2.000800|0.32|N|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T21:30:01+00:00, last15m_closed_end=2026-10-21T21:30+00:00, prior8high=0.026307, depth_time=2026-10-21T21:30:10+00:00, book20_bid_proxy_usdt=17364, book20_ask_proxy_usdt=13849, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.84%, turnover=10346399. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T21:30:01+00:00, last15m_closed_end=2026-10-21T21:30+00:00, prior8high=0.505770, depth_time=2026-10-21T21:30:08+00:00, book20_bid_proxy_usdt=5215, book20_ask_proxy_usdt=4976, funding_indicative=-0.000082, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.27%, turnover=14927039. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-21T21:30:01+00:00, last15m_closed_end=2026-10-21T21:30+00:00, prior8high=0.004323, depth_time=2026-10-21T21:30:15+00:00, book20_bid_proxy_usdt=57310, book20_ask_proxy_usdt=28691, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.71%, turnover=14108737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-21T21:30:01+00:00, last15m_closed_end=2026-10-21T21:30+00:00, prior8high=0.413500, depth_time=2026-10-21T21:30:17+00:00, book20_bid_proxy_usdt=452733, book20_ask_proxy_usdt=433954, funding_indicative=0.000022, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.01%, turnover=5010126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-21T21:30:01+00:00, last15m_closed_end=2026-10-21T21:30+00:00, prior8high=2.050700, depth_time=2026-10-21T21:30:12+00:00, book20_bid_proxy_usdt=56616, book20_ask_proxy_usdt=26745, funding_indicative=0.000018, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.59%, turnover=7336239. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
