# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T18:00:18Z**
- feed_generated_utc: 2026-10-30T18:00:20+00:00
- source_sha256: `304e83dc62e0a84a42623f896d6513186e0a6c6678a198520efc9459f9b48a1e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T18:00+00:00, close=77152, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T18:00+00:00, close=77152, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.009239|-6.21|13.20|-5.66|16388103|4.32|
|LIT_USDT|2.736000|-4.46|-17.68|-3.91|12427628|0.37|
|EVAA_USDT|1.237000|-3.51|135.66|-2.96|6573863|2.43|
|Q_USDT|0.046330|-2.42|-60.84|-1.87|24580995|6.48|
|PUMPFUN_USDT|0.004018|-2.16|-11.94|-1.61|25632454|2.49|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009239|0.008535|0.009255|0.87|N|Y/Y|Y/N|Y|N|
|EVAA_USDT|1.237000|1.251000|1.235100|0.79|N|Y/N|N/N|Y|N|
|LIT_USDT|2.736000|2.745900|2.736000|1.12|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004018|0.004019|0.004019|0.76|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.046330|0.046460|0.046330|0.52|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T18:00:04+00:00, last15m_closed_end=2026-10-30T18:00+00:00, prior8high=0.011760, depth_time=2026-10-30T18:00:08+00:00, book20_bid_proxy_usdt=11357, book20_ask_proxy_usdt=10631, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.21%, turnover=16388103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-30T18:00:04+00:00, last15m_closed_end=2026-10-30T18:00+00:00, prior8high=1.335900, depth_time=2026-10-30T18:00:13+00:00, book20_bid_proxy_usdt=3488, book20_ask_proxy_usdt=5316, funding_indicative=0.000225, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.51%, turnover=6573863. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T18:00:04+00:00, last15m_closed_end=2026-10-30T18:00+00:00, prior8high=2.836600, depth_time=2026-10-30T18:00:11+00:00, book20_bid_proxy_usdt=15927, book20_ask_proxy_usdt=30408, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.46%, turnover=12427628. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T18:00:04+00:00, last15m_closed_end=2026-10-30T18:00+00:00, prior8high=0.004120, depth_time=2026-10-30T18:00:18+00:00, book20_bid_proxy_usdt=2203443, book20_ask_proxy_usdt=1317988, funding_indicative=0.000010, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.16%, turnover=25632454. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-30T18:00:04+00:00, last15m_closed_end=2026-10-30T18:00+00:00, prior8high=0.049120, depth_time=2026-10-30T18:00:15+00:00, book20_bid_proxy_usdt=18247, book20_ask_proxy_usdt=34984, funding_indicative=0.000072, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.42%, turnover=24580995. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
