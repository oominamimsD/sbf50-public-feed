# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T00:00:19Z**
- feed_generated_utc: 2026-11-08T00:00:20+00:00
- source_sha256: `a6ac41d9f011a3501dad106b23381ca91420fbff20d876762b9b00a449872574`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.124100|-2.12|-60.05|-2.26|8213088|8.05|
|QNT_USDT|196.050000|-1.54|-2.48|-1.68|42048848|0.51|
|PEPE_USDT|0.000005|-0.96|-2.05|-1.10|39095805|0.21|
|ENA_USDT|0.158730|-0.94|-18.18|-1.08|27331260|1.26|
|ZEC_USDT|1260.580000|-0.86|-1.86|-1.00|1826106965|0.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.158730|0.156440|0.158730|0.84|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.28|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|196.050000|194.800000|196.050000|0.61|N|Y/Y|N/N|Y|N|
|UAI_USDT|0.124100|0.119900|0.124100|0.39|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1260.580000|1245.170000|1260.580000|0.60|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-08T00:00:00+00:00, last15m_closed_end=2026-11-08T00:00+00:00, prior8high=0.158870, depth_time=2026-11-08T00:00:16+00:00, book20_bid_proxy_usdt=252619, book20_ask_proxy_usdt=184725, funding_indicative=0.000050, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.94%, turnover=27331260. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-08T00:00:00+00:00, last15m_closed_end=2026-11-08T00:00+00:00, prior8high=0.000005, depth_time=2026-11-08T00:00:13+00:00, book20_bid_proxy_usdt=63367, book20_ask_proxy_usdt=20792, funding_indicative=0.000062, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.96%, turnover=39095805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T00:00:00+00:00, last15m_closed_end=2026-11-08T00:00+00:00, prior8high=196.770000, depth_time=2026-11-08T00:00:10+00:00, book20_bid_proxy_usdt=71028, book20_ask_proxy_usdt=49233, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=42048848. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-08T00:00:00+00:00, last15m_closed_end=2026-11-08T00:00+00:00, prior8high=0.125500, depth_time=2026-11-08T00:00:05+00:00, book20_bid_proxy_usdt=168864, book20_ask_proxy_usdt=173450, funding_indicative=0.000050, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=8213088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T00:00:00+00:00, last15m_closed_end=2026-11-08T00:00+00:00, prior8high=1262.930000, depth_time=2026-11-08T00:00:18+00:00, book20_bid_proxy_usdt=369702, book20_ask_proxy_usdt=356117, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=1826106965. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
