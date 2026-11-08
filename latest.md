# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T01:00:18Z**
- feed_generated_utc: 2026-11-08T01:00:19+00:00
- source_sha256: `685963e73f2582554d34e2cb2f6ab63582a8be33fa93978ac68714439bbeb235`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T01:00+00:00, close=75774, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T01:00+00:00, close=75774, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|QNT_USDT|195.540000|-1.79|-2.74|-1.61|41676370|0.51|
|ENA_USDT|0.157430|-1.75|-18.85|-1.57|27222460|1.91|
|PUMPFUN_USDT|0.003680|-1.65|-12.00|-1.47|17055908|2.72|
|PEPE_USDT|0.000005|-1.64|-2.72|-1.46|38769373|0.21|
|WLD_USDT|0.331200|-1.54|-18.10|-1.36|25751383|3.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.157430|0.157160|0.157410|0.25|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.67|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003680|0.003680|0.003680|0.26|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|195.540000|194.800000|195.540000|0.66|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.331200|0.331700|0.331200|1.61|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-08T01:00:00+00:00, last15m_closed_end=2026-11-08T01:00+00:00, prior8high=0.159120, depth_time=2026-11-08T01:00:09+00:00, book20_bid_proxy_usdt=272824, book20_ask_proxy_usdt=334839, funding_indicative=0.000017, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.75%, turnover=27222460. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-08T01:00:00+00:00, last15m_closed_end=2026-11-08T01:00+00:00, prior8high=0.000005, depth_time=2026-11-08T01:00:14+00:00, book20_bid_proxy_usdt=53443, book20_ask_proxy_usdt=35579, funding_indicative=0.000092, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=38769373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-08T01:00:00+00:00, last15m_closed_end=2026-11-08T01:00+00:00, prior8high=0.003722, depth_time=2026-11-08T01:00:09+00:00, book20_bid_proxy_usdt=2329069, book20_ask_proxy_usdt=2203745, funding_indicative=-0.000108, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.65%, turnover=17055908. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T01:00:00+00:00, last15m_closed_end=2026-11-08T01:00+00:00, prior8high=196.770000, depth_time=2026-11-08T01:00:06+00:00, book20_bid_proxy_usdt=86216, book20_ask_proxy_usdt=76698, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=41676370. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T01:00:00+00:00, last15m_closed_end=2026-11-08T01:00+00:00, prior8high=0.335400, depth_time=2026-11-08T01:00:13+00:00, book20_bid_proxy_usdt=3557600, book20_ask_proxy_usdt=3447577, funding_indicative=-0.000080, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=25751383. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
