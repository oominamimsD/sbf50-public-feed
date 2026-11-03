# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T15:15:33Z**
- feed_generated_utc: 2026-11-03T15:15:34+00:00
- source_sha256: `db345839e01a0e53610e4084b0df2d1c520a8746e24d0e5b88c717982a03ea87`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T15:15+00:00, close=77403.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T15:00+00:00, close=77364.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T12:00+00:00, close=77085.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004104|-25.40|-86.66|-25.31|12393166|2.43|
|UAI_USDT|0.102000|-23.13|-59.00|-23.04|9209674|9.77|
|XPL_USDT|0.064220|-7.70|-13.55|-7.61|11135307|1.56|
|BEAT_USDT|0.095670|-4.55|17.64|-4.46|7608596|2.09|
|TIA_USDT|0.436600|-4.44|-18.49|-4.35|13424050|2.29|
|QNT_USDT|194.220000|-4.06|-7.63|-3.97|53897582|1.03|
|NEAR_USDT|3.853000|-3.91|-15.74|-3.82|80372108|2.60|
|ENA_USDT|0.170240|-2.74|-19.07|-2.65|69740876|0.59|
|DASH_USDT|46.050000|-2.43|-11.81|-2.34|8637895|2.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004104|0.003997|0.004104|1.18|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.095670|0.098170|0.095770|2.31|Y|Y/Y|N/N|Y|N|
|DASH_USDT|46.050000|45.970000|46.050000|0.54|N|Y/N|Y/Y|Y|N|
|ENA_USDT|0.170240|0.169280|0.170240|1.88|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|3.853000|3.854000|3.853000|1.53|Y|Y/N|Y/Y|Y|N|
|QNT_USDT|194.220000|194.170000|194.220000|3.23|N|Y/N|Y/Y|Y|N|
|TIA_USDT|0.436600|0.438000|0.436600|1.91|Y|Y/Y|Y/Y|Y|Y|
|UAI_USDT|0.102000|0.096800|0.102000|0.87|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.064220|0.064060|0.064230|1.14|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T15:14:59+00:00, last15m_closed_end=2026-11-03T15:15+00:00, prior8high=0.004354, depth_time=2026-11-03T15:15:08+00:00, book20_bid_proxy_usdt=105805, book20_ask_proxy_usdt=45644, funding_indicative=-0.000306, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-25.40%, turnover=12393166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-03T15:15:00+00:00, last15m_closed_end=2026-11-03T15:15+00:00, prior8high=0.104840, depth_time=2026-11-03T15:15:17+00:00, book20_bid_proxy_usdt=12883, book20_ask_proxy_usdt=19717, funding_indicative=0.000360, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.55%, turnover=7608596. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-03T15:15:00+00:00, last15m_closed_end=2026-11-03T15:15+00:00, prior8high=46.820000, depth_time=2026-11-03T15:15:30+00:00, book20_bid_proxy_usdt=791545, book20_ask_proxy_usdt=733133, funding_indicative=0.000096, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=8637895. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-03T15:14:59+00:00, last15m_closed_end=2026-11-03T15:15+00:00, prior8high=0.174220, depth_time=2026-11-03T15:15:28+00:00, book20_bid_proxy_usdt=147165, book20_ask_proxy_usdt=119585, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.74%, turnover=69740876. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-03T15:14:59+00:00, last15m_closed_end=2026-11-03T15:15+00:00, prior8high=3.945000, depth_time=2026-11-03T15:15:25+00:00, book20_bid_proxy_usdt=3252016, book20_ask_proxy_usdt=533960, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.91%, turnover=80372108. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T15:15:00+00:00, last15m_closed_end=2026-11-03T15:15+00:00, prior8high=200.480000, depth_time=2026-11-03T15:15:22+00:00, book20_bid_proxy_usdt=63768, book20_ask_proxy_usdt=66058, funding_indicative=0.000100, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.06%, turnover=53897582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T15:15:00+00:00, last15m_closed_end=2026-11-03T15:15+00:00, prior8high=0.448700, depth_time=2026-11-03T15:15:20+00:00, book20_bid_proxy_usdt=462764, book20_ask_proxy_usdt=293917, funding_indicative=-0.000031, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.44%, turnover=13424050. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-03T15:14:59+00:00, last15m_closed_end=2026-11-03T15:15+00:00, prior8high=0.172500, depth_time=2026-11-03T15:15:11+00:00, book20_bid_proxy_usdt=232205, book20_ask_proxy_usdt=158669, funding_indicative=-0.000229, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-23.13%, turnover=9209674. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-03T15:15:00+00:00, last15m_closed_end=2026-11-03T15:15+00:00, prior8high=0.065420, depth_time=2026-11-03T15:15:14+00:00, book20_bid_proxy_usdt=306993, book20_ask_proxy_usdt=594404, funding_indicative=0.000050, next_funding_utc=2026-11-03T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.70%, turnover=11135307. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
