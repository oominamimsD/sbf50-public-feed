# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T20:45:19Z**
- feed_generated_utc: 2026-11-06T20:45:21+00:00
- source_sha256: `9898d01973a81b352dc5d5d07971cf2a2cadb7d8fb87efabc32d298bbd74750c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T20:45+00:00, close=75873.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T20:00+00:00, close=75863.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.135800|-28.52|-48.87|-28.56|30768744|7.37|
|ANTHROPIC_USDT|1336.610000|-6.61|-20.26|-6.65|6419892|0.22|
|LIT_USDT|3.318500|-2.17|17.50|-2.21|11117132|0.30|
|AKE_USDT|0.003718|-1.24|-80.34|-1.28|53201069|5.38|
|XRP_USDT|1.174400|-1.09|-6.38|-1.13|373670154|0.85|
|UNI_USDT|6.879000|-1.06|-0.97|-1.10|32820544|1.45|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003718|0.003497|0.003720|0.35|N|Y/Y|Y/N|Y|N|
|ANTHROPIC_USDT|1336.610000|1316.030000|1336.610000|0.62|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.318500|3.268700|3.318500|0.64|N|Y/Y|Y/N|Y|N|
|UAI_USDT|0.135800|0.105200|0.135800|1.82|N|Y/Y|Y/N|Y|N|
|UNI_USDT|6.879000|6.859000|6.879000|0.53|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.174400|1.174000|1.174400|1.10|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-06T20:44:59+00:00, last15m_closed_end=2026-11-06T20:45+00:00, prior8high=0.004135, depth_time=2026-11-06T20:45:14+00:00, book20_bid_proxy_usdt=62975, book20_ask_proxy_usdt=25390, funding_indicative=-0.000876, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=53201069. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-06T20:44:59+00:00, last15m_closed_end=2026-11-06T20:45+00:00, prior8high=1358.890000, depth_time=2026-11-06T20:45:09+00:00, book20_bid_proxy_usdt=21903, book20_ask_proxy_usdt=18048, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-6.61%, turnover=6419892. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-06T20:44:59+00:00, last15m_closed_end=2026-11-06T20:45+00:00, prior8high=3.370000, depth_time=2026-11-06T20:45:11+00:00, book20_bid_proxy_usdt=21045, book20_ask_proxy_usdt=28176, funding_indicative=0.000050, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=11117132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-06T20:44:59+00:00, last15m_closed_end=2026-11-06T20:45+00:00, prior8high=0.207700, depth_time=2026-11-06T20:45:06+00:00, book20_bid_proxy_usdt=142516, book20_ask_proxy_usdt=266009, funding_indicative=0.000026, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=4, 24h_change=-28.52%, turnover=30768744. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-06T20:44:59+00:00, last15m_closed_end=2026-11-06T20:45+00:00, prior8high=6.946000, depth_time=2026-11-06T20:45:16+00:00, book20_bid_proxy_usdt=1964852, book20_ask_proxy_usdt=2914536, funding_indicative=0.000090, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.06%, turnover=32820544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T20:44:59+00:00, last15m_closed_end=2026-11-06T20:45+00:00, prior8high=1.189800, depth_time=2026-11-06T20:45:16+00:00, book20_bid_proxy_usdt=2634825, book20_ask_proxy_usdt=3159930, funding_indicative=0.000044, next_funding_utc=2026-11-07T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.09%, turnover=373670154. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
