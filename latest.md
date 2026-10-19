# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T06:15:17Z**
- feed_generated_utc: 2026-10-19T06:15:19+00:00
- source_sha256: `7690566a99b44cd365762a3134dfef02d28c01017d958b61bfefcbd7e3250bc8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T06:15+00:00, close=82737.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T06:00+00:00, close=82726.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.059890|-2.71|-49.78|-4.68|17377501|3.34|
|ICNT_USDT|0.174800|-2.56|64.90|-4.53|7188955|5.72|
|BTW_USDT|2.251200|-2.35|33.82|-4.32|21536174|0.44|
|HBAR_USDT|0.084180|-1.86|-10.23|-3.83|50649811|1.19|
|TIA_USDT|0.611200|-1.08|3.82|-3.05|57520851|4.91|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.251200|2.183600|2.251200|2.24|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.084180|0.083810|0.084180|1.28|N|Y/Y|Y/Y|N|N|
|ICNT_USDT|0.174800|0.168800|0.174800|0.39|N|Y/Y|N/N|N|N|
|STRK_USDT|0.059890|0.059440|0.059890|0.36|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.611200|0.604400|0.611200|1.24|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T06:15:01+00:00, last15m_closed_end=2026-10-19T06:15+00:00, prior8high=2.328900, depth_time=2026-10-19T06:15:11+00:00, book20_bid_proxy_usdt=10144, book20_ask_proxy_usdt=11733, funding_indicative=-0.000112, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.35%, turnover=21536174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-19T06:15:01+00:00, last15m_closed_end=2026-10-19T06:15+00:00, prior8high=0.084640, depth_time=2026-10-19T06:15:14+00:00, book20_bid_proxy_usdt=648705, book20_ask_proxy_usdt=1020261, funding_indicative=-0.000035, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=50649811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T06:15:01+00:00, last15m_closed_end=2026-10-19T06:15+00:00, prior8high=0.194500, depth_time=2026-10-19T06:15:09+00:00, book20_bid_proxy_usdt=154093, book20_ask_proxy_usdt=103943, funding_indicative=-0.000205, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.56%, turnover=7188955. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T06:15:01+00:00, last15m_closed_end=2026-10-19T06:15+00:00, prior8high=0.060780, depth_time=2026-10-19T06:15:07+00:00, book20_bid_proxy_usdt=741188, book20_ask_proxy_usdt=607491, funding_indicative=0.000050, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.71%, turnover=17377501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T06:15:01+00:00, last15m_closed_end=2026-10-19T06:15+00:00, prior8high=0.617600, depth_time=2026-10-19T06:15:17+00:00, book20_bid_proxy_usdt=212537, book20_ask_proxy_usdt=280852, funding_indicative=-0.000019, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=57520851. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
