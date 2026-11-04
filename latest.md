# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T16:30:19Z**
- feed_generated_utc: 2026-11-04T16:30:21+00:00
- source_sha256: `051e5cab06e6741121b08b7882716827d801c78b194a6c99cdf87ff0a10063e3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T16:30+00:00, close=80560.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-04T16:00+00:00, close=80272.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002680|-4.62|-86.66|-4.96|16809516|3.73|
|WLFI_USDT|0.047000|-1.67|-10.44|-2.01|5526807|2.13|
|AGT_USDT|0.035490|-1.14|-21.29|-1.48|6288091|2.82|
|Q_USDT|0.028390|-0.97|-54.40|-1.31|7281952|3.53|
|TRUMPOFFICIAL_USDT|1.412000|-0.84|-17.37|-1.18|15762243|7.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.035490|0.033650|0.035490|0.37|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.002680|0.002617|0.002681|0.60|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.028390|0.028130|0.028400|0.31|N|N/N|Y/Y|N|N|
|TRUMPOFFICIAL_USDT|1.412000|1.402000|1.412000|0.54|N|Y/Y|Y/Y|N|N|
|WLFI_USDT|0.047000|0.046860|0.047100|1.32|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T16:30:03+00:00, last15m_closed_end=2026-11-04T16:30+00:00, prior8high=0.037650, depth_time=2026-11-04T16:30:13+00:00, book20_bid_proxy_usdt=15069, book20_ask_proxy_usdt=35908, funding_indicative=0.000053, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.14%, turnover=6288091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T16:30:03+00:00, last15m_closed_end=2026-11-04T16:30+00:00, prior8high=0.003487, depth_time=2026-11-04T16:30:08+00:00, book20_bid_proxy_usdt=55584, book20_ask_proxy_usdt=82696, funding_indicative=-0.000291, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.62%, turnover=16809516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-11-04T16:30:03+00:00, last15m_closed_end=2026-11-04T16:30+00:00, prior8high=0.029660, depth_time=2026-11-04T16:30:16+00:00, book20_bid_proxy_usdt=62170, book20_ask_proxy_usdt=68784, funding_indicative=-0.000081, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.97%, turnover=7281952. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T16:30:03+00:00, last15m_closed_end=2026-11-04T16:30+00:00, prior8high=1.465000, depth_time=2026-11-04T16:30:18+00:00, book20_bid_proxy_usdt=1770247, book20_ask_proxy_usdt=3667084, funding_indicative=-0.000404, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=15762243. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLFI_USDT: quote_utc=2026-11-04T16:30:03+00:00, last15m_closed_end=2026-11-04T16:30+00:00, prior8high=0.050060, depth_time=2026-11-04T16:30:11+00:00, book20_bid_proxy_usdt=176196, book20_ask_proxy_usdt=214894, funding_indicative=0.000050, next_funding_utc=2026-11-04T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.67%, turnover=5526807. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
