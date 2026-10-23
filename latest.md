# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-23T11:45:30Z**
- feed_generated_utc: 2026-10-23T11:45:32+00:00
- source_sha256: `f28b3b18eb0fe9aacd12fcdd03fda15c3497e47f04aa8e9a293fec581f7bc5c0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-23T11:45+00:00, close=81676.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-23T11:00+00:00, close=81656.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-23T08:00+00:00, close=81544.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGMA_USDT|0.436490|-13.05|84.60|-13.08|6954689|1.83|
|JCT_USDT|0.004191|-9.04|111.13|-9.07|7761354|2.39|
|LIT_USDT|3.388100|-6.25|9.59|-6.28|9044340|0.29|
|STRK_USDT|0.051730|-4.83|-46.31|-4.86|12207563|1.93|
|QNT_USDT|182.360000|-4.37|-12.28|-4.40|53259043|0.55|
|TIA_USDT|0.546000|-3.94|-9.37|-3.97|25545763|1.83|
|SILVER_USDT|54.060000|-2.17|-5.39|-2.20|332639103|1.85|
|ARB_USDT|0.180290|-1.82|-5.08|-1.85|25183919|0.56|
|OP_USDT|0.117790|-1.71|-15.17|-1.74|6129945|0.85|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.180290|0.179250|0.180290|0.81|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.004191|0.004042|0.004191|0.70|N|Y/Y|N/N|Y|N|
|LIT_USDT|3.388100|3.349800|3.388100|0.55|N|Y/Y|Y/Y|Y|N|
|MAGMA_USDT|0.436490|0.431000|0.436490|1.62|N|Y/Y|N/N|Y|N|
|OP_USDT|0.117790|0.116880|0.117790|0.95|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|182.360000|181.170000|182.360000|1.33|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|54.060000|53.870000|54.060000|0.52|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.051730|0.051150|0.051730|0.72|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.546000|0.546200|0.546000|2.96|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-23T11:44:59+00:00, last15m_closed_end=2026-10-23T11:45+00:00, prior8high=0.181560, depth_time=2026-10-23T11:45:26+00:00, book20_bid_proxy_usdt=157297, book20_ask_proxy_usdt=63447, funding_indicative=-0.000014, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=25183919. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-23T11:44:59+00:00, last15m_closed_end=2026-10-23T11:45+00:00, prior8high=0.004254, depth_time=2026-10-23T11:45:11+00:00, book20_bid_proxy_usdt=48018, book20_ask_proxy_usdt=51376, funding_indicative=0.000098, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.04%, turnover=7761354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-23T11:44:59+00:00, last15m_closed_end=2026-10-23T11:45+00:00, prior8high=3.396100, depth_time=2026-10-23T11:45:13+00:00, book20_bid_proxy_usdt=26607, book20_ask_proxy_usdt=20402, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.25%, turnover=9044340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- MAGMA_USDT: quote_utc=2026-10-23T11:44:59+00:00, last15m_closed_end=2026-10-23T11:45+00:00, prior8high=0.512000, depth_time=2026-10-23T11:45:08+00:00, book20_bid_proxy_usdt=5383, book20_ask_proxy_usdt=12966, funding_indicative=0.000050, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.05%, turnover=6954689. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-23T11:44:59+00:00, last15m_closed_end=2026-10-23T11:45+00:00, prior8high=0.118640, depth_time=2026-10-23T11:45:29+00:00, book20_bid_proxy_usdt=116863, book20_ask_proxy_usdt=101430, funding_indicative=0.000043, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=6129945. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-23T11:44:59+00:00, last15m_closed_end=2026-10-23T11:45+00:00, prior8high=185.800000, depth_time=2026-10-23T11:45:18+00:00, book20_bid_proxy_usdt=72341, book20_ask_proxy_usdt=92425, funding_indicative=-0.000170, next_funding_utc=2026-10-23T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.37%, turnover=53259043. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-23T11:44:59+00:00, last15m_closed_end=2026-10-23T11:45+00:00, prior8high=54.210000, depth_time=2026-10-23T11:45:23+00:00, book20_bid_proxy_usdt=39861116, book20_ask_proxy_usdt=35986238, funding_indicative=0.000008, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.17%, turnover=332639103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-23T11:44:59+00:00, last15m_closed_end=2026-10-23T11:45+00:00, prior8high=0.052000, depth_time=2026-10-23T11:45:16+00:00, book20_bid_proxy_usdt=661523, book20_ask_proxy_usdt=552088, funding_indicative=0.000042, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.83%, turnover=12207563. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-23T11:44:59+00:00, last15m_closed_end=2026-10-23T11:45+00:00, prior8high=0.552300, depth_time=2026-10-23T11:45:21+00:00, book20_bid_proxy_usdt=272056, book20_ask_proxy_usdt=344937, funding_indicative=0.000013, next_funding_utc=2026-10-23T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.94%, turnover=25545763. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
