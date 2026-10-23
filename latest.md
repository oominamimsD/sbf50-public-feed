# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T08:45:20Z**
- feed_generated_utc: 2026-10-23T08:45:22+00:00
- source_sha256: `9c8e626a1f31a3737b1fa693c33cef0f904347430df49e8d03955369a1a2eccd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T08:45+00:00, close=81811.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004230|-8.20|113.09|-8.39|8071166|4.73|
|LIT_USDT|3.435800|-4.93|11.14|-5.12|9773732|0.29|
|STRK_USDT|0.052820|-2.83|-45.18|-3.02|11314167|1.89|
|TIA_USDT|0.554300|-2.48|-8.00|-2.67|24905503|1.80|
|SILVER_USDT|54.100000|-2.09|-5.32|-2.28|345051324|1.85|
|QNT_USDT|187.940000|-1.45|-9.60|-1.64|48839557|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004230|0.004176|0.004231|0.43|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.435800|3.399900|3.435800|0.64|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|187.940000|187.480000|187.940000|2.23|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.100000|53.870000|54.100000|0.65|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052820|0.052400|0.052820|8.93|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.554300|0.552400|0.554300|1.19|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T08:45:00+00:00, last15m_closed_end=2026-10-23T08:45+00:00, prior8high=0.004316, depth_time=2026-10-23T08:45:06+00:00, book20_bid_proxy_usdt=63416, book20_ask_proxy_usdt=52396, funding_indicative=0.000141, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.20%, turnover=8071166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T08:45:01+00:00, last15m_closed_end=2026-10-23T08:45+00:00, prior8high=3.450000, depth_time=2026-10-23T08:45:08+00:00, book20_bid_proxy_usdt=25961, book20_ask_proxy_usdt=22433, funding_indicative=0.000048, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.93%, turnover=9773732. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T08:45:01+00:00, last15m_closed_end=2026-10-23T08:45+00:00, prior8high=190.170000, depth_time=2026-10-23T08:45:18+00:00, book20_bid_proxy_usdt=68802, book20_ask_proxy_usdt=112858, funding_indicative=-0.000143, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.45%, turnover=48839557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T08:45:00+00:00, last15m_closed_end=2026-10-23T08:45+00:00, prior8high=54.280000, depth_time=2026-10-23T08:45:15+00:00, book20_bid_proxy_usdt=31203189, book20_ask_proxy_usdt=31441505, funding_indicative=0.000155, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.09%, turnover=345051324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T08:45:01+00:00, last15m_closed_end=2026-10-23T08:45+00:00, prior8high=0.053510, depth_time=2026-10-23T08:45:12+00:00, book20_bid_proxy_usdt=742925, book20_ask_proxy_usdt=665132, funding_indicative=-0.000026, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.83%, turnover=11314167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T08:45:01+00:00, last15m_closed_end=2026-10-23T08:45+00:00, prior8high=0.562000, depth_time=2026-10-23T08:45:14+00:00, book20_bid_proxy_usdt=315852, book20_ask_proxy_usdt=358719, funding_indicative=-0.000003, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.48%, turnover=24905503. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
