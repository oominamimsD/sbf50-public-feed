# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T14:00:25Z**
- feed_generated_utc: 2026-10-26T14:00:28+00:00
- source_sha256: `77ae45785d1fe4d08a9f0be7bdf4df29e7eb5d9e62ca2b08ed3612e8b45c891f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1186; contracts: 1178; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T14:00+00:00, close=79668.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T14:00+00:00, close=79668.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.027450|-22.06|125.00|-20.91|11618592|3.64|
|APR_USDT|0.032580|-19.99|19.60|-18.84|5907929|3.06|
|BTW_USDT|1.393400|-16.56|-39.55|-15.41|10922412|5.03|
|WLD_USDT|0.437200|-4.24|-8.20|-3.09|60318143|2.29|
|LIT_USDT|3.050400|-3.72|4.09|-2.57|5009172|0.33|
|XMR_USDT|592.720000|-2.56|1.75|-1.41|5486069|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.032580|0.031070|0.032580|0.69|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.393400|1.395000|1.393400|2.63|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.027450|0.027440|0.027450|1.23|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.050400|3.046800|3.050400|2.39|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.437200|0.435800|0.437700|1.63|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|592.720000|588.980000|592.720000|1.13|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T14:00:01+00:00, last15m_closed_end=2026-10-26T14:00+00:00, prior8high=0.037130, depth_time=2026-10-26T14:00:12+00:00, book20_bid_proxy_usdt=62773, book20_ask_proxy_usdt=34113, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-19.99%, turnover=5907929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T14:00:01+00:00, last15m_closed_end=2026-10-26T14:00+00:00, prior8high=1.492700, depth_time=2026-10-26T14:00:16+00:00, book20_bid_proxy_usdt=15991, book20_ask_proxy_usdt=18809, funding_indicative=-0.015672, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.56%, turnover=10922412. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T14:00:01+00:00, last15m_closed_end=2026-10-26T14:00+00:00, prior8high=0.029430, depth_time=2026-10-26T14:00:09+00:00, book20_bid_proxy_usdt=106750, book20_ask_proxy_usdt=126383, funding_indicative=-0.000782, next_funding_utc=2026-10-26T15:00:00+00:00, funding_cycle_h=1, 24h_change=-22.06%, turnover=11618592. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T14:00:02+00:00, last15m_closed_end=2026-10-26T14:00+00:00, prior8high=3.115900, depth_time=2026-10-26T14:00:21+00:00, book20_bid_proxy_usdt=16681, book20_ask_proxy_usdt=22343, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.72%, turnover=5009172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T14:00:01+00:00, last15m_closed_end=2026-10-26T14:00+00:00, prior8high=0.444700, depth_time=2026-10-26T14:00:19+00:00, book20_bid_proxy_usdt=2668374, book20_ask_proxy_usdt=2313341, funding_indicative=-0.000161, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.24%, turnover=60318143. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T14:00:02+00:00, last15m_closed_end=2026-10-26T14:00+00:00, prior8high=594.610000, depth_time=2026-10-26T14:00:23+00:00, book20_bid_proxy_usdt=17440, book20_ask_proxy_usdt=27781, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.56%, turnover=5486069. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
