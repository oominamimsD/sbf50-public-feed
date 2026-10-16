# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T12:15:15Z**
- feed_generated_utc: 2026-10-16T12:15:17+00:00
- source_sha256: `13d31ec34b8cee4954e192bddcd15717a8eddb7004577a0f4ef3e7e86c2267b0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T12:15+00:00, close=82200, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.076840|-20.25|27.72|-20.04|39907529|3.90|
|BTW_USDT|1.683800|-11.72|21.28|-11.51|21797759|3.57|
|AKE_USDT|0.029561|-6.46|1.85|-6.25|18252540|0.34|
|NIL_USDT|0.082060|-5.54|-5.23|-5.33|5385675|2.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.029561|0.029345|0.029561|0.80|N|Y/Y|N/N|N|N|
|BTW_USDT|1.683800|1.611400|1.683800|1.11|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.082060|0.081930|0.082150|0.74|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.076840|0.075950|0.076920|1.47|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T12:15:00+00:00, last15m_closed_end=2026-10-16T12:15+00:00, prior8high=0.030386, depth_time=2026-10-16T12:15:12+00:00, book20_bid_proxy_usdt=17127, book20_ask_proxy_usdt=14691, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.46%, turnover=18252540. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T12:15:00+00:00, last15m_closed_end=2026-10-16T12:15+00:00, prior8high=1.955200, depth_time=2026-10-16T12:15:10+00:00, book20_bid_proxy_usdt=7740, book20_ask_proxy_usdt=8088, funding_indicative=-0.000690, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.72%, turnover=21797759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T12:15:00+00:00, last15m_closed_end=2026-10-16T12:15+00:00, prior8high=0.084570, depth_time=2026-10-16T12:15:14+00:00, book20_bid_proxy_usdt=28903, book20_ask_proxy_usdt=38418, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.54%, turnover=5385675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T12:15:00+00:00, last15m_closed_end=2026-10-16T12:15+00:00, prior8high=0.080420, depth_time=2026-10-16T12:15:07+00:00, book20_bid_proxy_usdt=185942, book20_ask_proxy_usdt=350045, funding_indicative=-0.000014, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.25%, turnover=39907529. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
