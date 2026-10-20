# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T15:15:19Z**
- feed_generated_utc: 2026-10-20T15:15:21+00:00
- source_sha256: `84fff7b4e635825b734b987bc1425cec895c42b5622dcd11119bfa7c4602dbe8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T15:15+00:00, close=82391.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T15:00+00:00, close=83242.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-20T12:00+00:00, close=81467.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.066298|-23.83|297.89|-24.41|8199480|6.03|
|ARB_USDT|0.190710|-2.51|1.18|-3.09|102617278|0.52|
|AKE_USDT|0.030360|-1.31|28.97|-1.89|6682136|2.63|
|STRK_USDT|0.055940|-1.13|-38.30|-1.71|17681467|1.79|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.066298|0.063242|0.066298|2.39|N|Y/Y|Y/N|Y|N|
|AKE_USDT|0.030360|0.029930|0.030360|0.49|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.190710|0.187280|0.190900|4.46|N|N/Y|Y/N|Y|N|
|STRK_USDT|0.055940|0.055710|0.055940|5.18|N|N/N|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T15:15:00+00:00, last15m_closed_end=2026-10-20T15:15+00:00, prior8high=0.069150, depth_time=2026-10-20T15:15:09+00:00, book20_bid_proxy_usdt=110097, book20_ask_proxy_usdt=7072, funding_indicative=0.000070, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.83%, turnover=8199480. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-20T15:15:00+00:00, last15m_closed_end=2026-10-20T15:15+00:00, prior8high=0.030823, depth_time=2026-10-20T15:15:15+00:00, book20_bid_proxy_usdt=8423, book20_ask_proxy_usdt=11644, funding_indicative=0.000063, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.31%, turnover=6682136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T15:15:00+00:00, last15m_closed_end=2026-10-20T15:15+00:00, prior8high=0.198770, depth_time=2026-10-20T15:15:12+00:00, book20_bid_proxy_usdt=49495, book20_ask_proxy_usdt=66462, funding_indicative=-0.000012, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=102617278. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T15:15:00+00:00, last15m_closed_end=2026-10-20T15:15+00:00, prior8high=0.059770, depth_time=2026-10-20T15:15:18+00:00, book20_bid_proxy_usdt=473231, book20_ask_proxy_usdt=381422, funding_indicative=0.000004, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.13%, turnover=17681467. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
