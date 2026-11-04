# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T16:45:19Z**
- feed_generated_utc: 2026-11-04T16:45:21+00:00
- source_sha256: `3e775f644983259a6eb5819e09a21ccae587089744d08b0a7fc82d39cafd6a02`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T16:45+00:00, close=80640.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002652|-5.62|-86.80|-6.06|17155457|7.54|
|Q_USDT|0.028200|-1.63|-54.71|-2.07|7289629|3.54|
|TRUMPOFFICIAL_USDT|1.402000|-1.54|-17.96|-1.98|16591832|7.14|
|AGT_USDT|0.035350|-1.53|-21.60|-1.97|6311907|2.83|
|WLFI_USDT|0.047080|-1.50|-10.28|-1.94|5727692|4.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.035350|0.033650|0.035350|0.40|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002652|0.002617|0.002652|1.35|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.028200|0.028100|0.028240|0.15|N|N/N|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.402000|1.402000|1.402000|2.43|N|Y/Y|Y/Y|N|N|
|WLFI_USDT|0.047080|0.046860|0.047080|10.61|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T16:45:01+00:00, last15m_closed_end=2026-11-04T16:45+00:00, prior8high=0.036880, depth_time=2026-11-04T16:45:16+00:00, book20_bid_proxy_usdt=17498, book20_ask_proxy_usdt=18649, funding_indicative=0.000053, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=6311907. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T16:45:01+00:00, last15m_closed_end=2026-11-04T16:45+00:00, prior8high=0.003487, depth_time=2026-11-04T16:45:09+00:00, book20_bid_proxy_usdt=76548, book20_ask_proxy_usdt=114646, funding_indicative=-0.000311, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-5.62%, turnover=17155457. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T16:45:01+00:00, last15m_closed_end=2026-11-04T16:45+00:00, prior8high=0.029470, depth_time=2026-11-04T16:45:10+00:00, book20_bid_proxy_usdt=85164, book20_ask_proxy_usdt=63226, funding_indicative=-0.000080, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=7289629. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T16:45:02+00:00, last15m_closed_end=2026-11-04T16:45+00:00, prior8high=1.465000, depth_time=2026-11-04T16:45:13+00:00, book20_bid_proxy_usdt=2180429, book20_ask_proxy_usdt=2576231, funding_indicative=-0.000407, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.54%, turnover=16591832. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLFI_USDT: quote_utc=2026-11-04T16:45:02+00:00, last15m_closed_end=2026-11-04T16:45+00:00, prior8high=0.050060, depth_time=2026-11-04T16:45:17+00:00, book20_bid_proxy_usdt=140772, book20_ask_proxy_usdt=254541, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.50%, turnover=5727692. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
