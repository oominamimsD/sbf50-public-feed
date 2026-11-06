# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-06T08:15:18Z**
- feed_generated_utc: 2026-11-06T08:15:19+00:00
- source_sha256: `7f4be43e24f72e37ecfcfb4e7122941961597c60b311b6370074090bf5f99284`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-06T08:15+00:00, close=75633.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-06T08:00+00:00, close=75573.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BCH_USDT|264.550000|-5.21|-8.23|-4.72|7631600|2.27|
|FLUID_USDT|2.407000|-4.93|16.61|-4.44|5026483|4.15|
|XRP_USDT|1.189700|-4.41|-9.14|-3.92|465417013|0.84|
|ELSA_USDT|0.078070|-3.79|4.51|-3.30|5166596|2.56|
|XPL_USDT|0.057510|-1.82|-27.13|-1.33|12160174|1.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BCH_USDT|264.550000|261.500000|264.550000|1.12|N|Y/Y|Y/Y|Y|N|
|ELSA_USDT|0.078070|0.076440|0.078070|1.88|N|Y/Y|Y/Y|Y|N|
|FLUID_USDT|2.407000|2.384000|2.407000|15.85|N|Y/Y|N/N|Y|N|
|XPL_USDT|0.057510|0.056460|0.057510|1.39|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.189700|1.177100|1.189700|1.26|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BCH_USDT: quote_utc=2026-11-06T08:15:00+00:00, last15m_closed_end=2026-11-06T08:15+00:00, prior8high=277.780000, depth_time=2026-11-06T08:15:07+00:00, book20_bid_proxy_usdt=45628, book20_ask_proxy_usdt=96441, funding_indicative=0.000017, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.21%, turnover=7631600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ELSA_USDT: quote_utc=2026-11-06T08:15:00+00:00, last15m_closed_end=2026-11-06T08:15+00:00, prior8high=0.078360, depth_time=2026-11-06T08:15:15+00:00, book20_bid_proxy_usdt=24694, book20_ask_proxy_usdt=15032, funding_indicative=0.000105, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.79%, turnover=5166596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-06T08:15:00+00:00, last15m_closed_end=2026-11-06T08:15+00:00, prior8high=2.459000, depth_time=2026-11-06T08:15:06+00:00, book20_bid_proxy_usdt=206340, book20_ask_proxy_usdt=206076, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=5026483. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-06T08:15:00+00:00, last15m_closed_end=2026-11-06T08:15+00:00, prior8high=0.057590, depth_time=2026-11-06T08:15:17+00:00, book20_bid_proxy_usdt=442889, book20_ask_proxy_usdt=469202, funding_indicative=0.000050, next_funding_utc=2026-11-06T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=12160174. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-06T08:15:00+00:00, last15m_closed_end=2026-11-06T08:15+00:00, prior8high=1.199400, depth_time=2026-11-06T08:15:12+00:00, book20_bid_proxy_usdt=3724894, book20_ask_proxy_usdt=3570292, funding_indicative=0.000100, next_funding_utc=2026-11-06T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.41%, turnover=465417013. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
