# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T09:15:25Z**
- feed_generated_utc: 2026-10-23T09:15:27+00:00
- source_sha256: `c651212c1610d7e7fa3dda868f86116c7fd766f0c52ad21463e40b2f8ea0a38c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T09:15+00:00, close=81755.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-23T09:00+00:00, close=81725, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004174|-9.41|110.27|-9.54|7862390|9.58|
|LIT_USDT|3.401300|-5.89|10.02|-6.02|9437225|0.29|
|STRK_USDT|0.052260|-3.86|-45.76|-3.99|11933081|1.92|
|TIA_USDT|0.552500|-2.79|-8.29|-2.92|24619089|3.62|
|QNT_USDT|186.580000|-2.16|-10.25|-2.29|47192760|1.61|
|SILVER_USDT|54.070000|-2.15|-5.37|-2.28|334274815|1.85|
|PUMPFUN_USDT|0.004619|-1.28|2.05|-1.41|35869192|2.17|
|OP_USDT|0.118740|-0.92|-14.49|-1.05|6173214|0.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|JCT_USDT|0.004174|0.004166|0.004180|2.35|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.401300|3.399900|3.401300|0.29|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.118740|0.118470|0.118740|1.35|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004619|0.004580|0.004619|2.52|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|186.580000|186.600000|186.580000|1.57|Y|Y/Y|Y/Y|Y|Y|
|SILVER_USDT|54.070000|53.870000|54.070000|0.89|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.052260|0.051860|0.052260|4.69|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.552500|0.551500|0.552200|1.27|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- JCT_USDT: quote_utc=2026-10-23T09:15:00+00:00, last15m_closed_end=2026-10-23T09:15+00:00, prior8high=0.004289, depth_time=2026-10-23T09:15:05+00:00, book20_bid_proxy_usdt=61597, book20_ask_proxy_usdt=52005, funding_indicative=0.000125, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.41%, turnover=7862390. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T09:15:00+00:00, last15m_closed_end=2026-10-23T09:15+00:00, prior8high=3.450000, depth_time=2026-10-23T09:15:05+00:00, book20_bid_proxy_usdt=27170, book20_ask_proxy_usdt=27400, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.89%, turnover=9437225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T09:15:00+00:00, last15m_closed_end=2026-10-23T09:15+00:00, prior8high=0.120310, depth_time=2026-10-23T09:15:24+00:00, book20_bid_proxy_usdt=148405, book20_ask_proxy_usdt=139633, funding_indicative=-0.000023, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.92%, turnover=6173214. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-23T09:15:00+00:00, last15m_closed_end=2026-10-23T09:15+00:00, prior8high=0.004665, depth_time=2026-10-23T09:15:20+00:00, book20_bid_proxy_usdt=2571868, book20_ask_proxy_usdt=1358750, funding_indicative=0.000011, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.28%, turnover=35869192. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T09:15:00+00:00, last15m_closed_end=2026-10-23T09:15+00:00, prior8high=189.690000, depth_time=2026-10-23T09:15:16+00:00, book20_bid_proxy_usdt=89087, book20_ask_proxy_usdt=90958, funding_indicative=-0.000157, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=47192760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T09:15:00+00:00, last15m_closed_end=2026-10-23T09:15+00:00, prior8high=54.160000, depth_time=2026-10-23T09:15:19+00:00, book20_bid_proxy_usdt=33680917, book20_ask_proxy_usdt=39516929, funding_indicative=0.000141, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.15%, turnover=334274815. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T09:15:00+00:00, last15m_closed_end=2026-10-23T09:15+00:00, prior8high=0.053510, depth_time=2026-10-23T09:15:12+00:00, book20_bid_proxy_usdt=478320, book20_ask_proxy_usdt=798273, funding_indicative=-0.000012, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.86%, turnover=11933081. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T09:15:00+00:00, last15m_closed_end=2026-10-23T09:15+00:00, prior8high=0.562000, depth_time=2026-10-23T09:15:14+00:00, book20_bid_proxy_usdt=381476, book20_ask_proxy_usdt=458394, funding_indicative=-0.000016, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.79%, turnover=24619089. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
