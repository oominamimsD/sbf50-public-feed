# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T22:45:13Z**
- feed_generated_utc: 2026-11-07T22:45:14+00:00
- source_sha256: `c055d5e595dc258c44c75357e8b692ce7ec5b12e0d64455bd974df05c3a43922`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T22:45+00:00, close=75765.8, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T22:00+00:00, close=75715.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T20:00+00:00, close=75772.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.122400|-1.60|-60.60|-1.65|9559485|8.17|
|QNT_USDT|196.390000|-1.23|-2.31|-1.28|42297337|0.51|
|PEPE_USDT|0.000005|-1.00|-2.69|-1.05|42402541|1.03|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|PEPE_USDT|0.000005|0.000005|0.000005|0.61|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|196.390000|195.390000|196.390000|0.80|N|Y/N|N/N|Y|N|
|UAI_USDT|0.122400|0.119900|0.122400|0.13|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- PEPE_USDT: quote_utc=2026-11-07T22:45:01+00:00, last15m_closed_end=2026-11-07T22:45+00:00, prior8high=0.000005, depth_time=2026-11-07T22:45:12+00:00, book20_bid_proxy_usdt=126881, book20_ask_proxy_usdt=66142, funding_indicative=0.000044, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.00%, turnover=42402541. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-07T22:45:01+00:00, last15m_closed_end=2026-11-07T22:45+00:00, prior8high=198.370000, depth_time=2026-11-07T22:45:06+00:00, book20_bid_proxy_usdt=61763, book20_ask_proxy_usdt=44454, funding_indicative=0.000100, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=42297337. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T22:45:01+00:00, last15m_closed_end=2026-11-07T22:45+00:00, prior8high=0.124500, depth_time=2026-11-07T22:45:05+00:00, book20_bid_proxy_usdt=158067, book20_ask_proxy_usdt=178022, funding_indicative=0.000050, next_funding_utc=2026-11-08T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.60%, turnover=9559485. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
