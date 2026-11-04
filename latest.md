# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T12:30:17Z**
- feed_generated_utc: 2026-11-04T12:30:18+00:00
- source_sha256: `535431c9b0d7b68bd3f8481c65c96fab22ea24154782688e99d609268dfdaa82`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T12:30+00:00, close=78265.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T12:00+00:00, close=78453.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.032640|-39.34|-31.31|-40.11|10535268|6.12|
|AKE_USDT|0.002869|-30.96|-86.41|-31.73|13472750|6.97|
|TRUMPOFFICIAL_USDT|1.442000|-10.32|-14.57|-11.09|11545023|6.93|
|HOT_USDT|0.000490|-8.93|41.95|-9.70|7326668|2.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.032640|0.032190|0.032640|0.70|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002869|0.002804|0.002869|0.94|N|Y/Y|Y/Y|N|N|
|HOT_USDT|0.000490|0.000487|0.000490|0.71|N|Y/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.442000|1.445000|1.442000|3.37|Y|Y/Y|Y/Y|N|Y|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T12:29:59+00:00, last15m_closed_end=2026-11-04T12:30+00:00, prior8high=0.033970, depth_time=2026-11-04T12:30:08+00:00, book20_bid_proxy_usdt=41964, book20_ask_proxy_usdt=23951, funding_indicative=0.000053, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-39.34%, turnover=10535268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T12:29:59+00:00, last15m_closed_end=2026-11-04T12:30+00:00, prior8high=0.003000, depth_time=2026-11-04T12:30:10+00:00, book20_bid_proxy_usdt=88843, book20_ask_proxy_usdt=44577, funding_indicative=0.000050, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-30.96%, turnover=13472750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T12:29:59+00:00, last15m_closed_end=2026-11-04T12:30+00:00, prior8high=0.000532, depth_time=2026-11-04T12:30:15+00:00, book20_bid_proxy_usdt=61793, book20_ask_proxy_usdt=77779, funding_indicative=-0.000079, next_funding_utc=2026-11-04T13:00:00+00:00, funding_cycle_h=1, 24h_change=-8.93%, turnover=7326668. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T12:30:00+00:00, last15m_closed_end=2026-11-04T12:30+00:00, prior8high=1.490000, depth_time=2026-11-04T12:30:13+00:00, book20_bid_proxy_usdt=2170500, book20_ask_proxy_usdt=2249369, funding_indicative=-0.000302, next_funding_utc=2026-11-04T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.32%, turnover=11545023. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
