# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T17:30:18Z**
- feed_generated_utc: 2026-10-30T17:30:20+00:00
- source_sha256: `da9fbf7643545a5f939c9dfafe01ec23d63fb8259bb54ce254f08a70c5ef69e5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T17:30+00:00, close=77312, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T17:00+00:00, close=77318.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T16:00+00:00, close=77579.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BLESS_USDT|0.008741|-11.26|7.10|-10.92|18067862|1.14|
|BTW_USDT|1.127300|-6.01|-33.78|-5.67|9778632|1.78|
|LIT_USDT|2.759800|-2.28|-16.97|-1.94|12888144|0.36|
|PUMPFUN_USDT|0.004042|-1.58|-11.41|-1.24|26693040|2.47|
|HYPE_USDT|90.911000|-1.55|15.95|-1.21|233785662|0.11|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.008741|0.008535|0.008741|0.92|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.127300|1.125100|1.126900|0.88|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|90.911000|90.714000|90.914000|1.05|N|N/N|N/N|Y|N|
|LIT_USDT|2.759800|2.757900|2.759800|0.91|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004042|0.004028|0.004044|0.35|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-30T17:30:00+00:00, last15m_closed_end=2026-10-30T17:30+00:00, prior8high=0.012854, depth_time=2026-10-30T17:30:07+00:00, book20_bid_proxy_usdt=14327, book20_ask_proxy_usdt=10517, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-11.26%, turnover=18067862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T17:30:00+00:00, last15m_closed_end=2026-10-30T17:30+00:00, prior8high=1.223800, depth_time=2026-10-30T17:30:09+00:00, book20_bid_proxy_usdt=14519, book20_ask_proxy_usdt=12967, funding_indicative=-0.000088, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.01%, turnover=9778632. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-30T17:30:00+00:00, last15m_closed_end=2026-10-30T17:30+00:00, prior8high=94.022000, depth_time=2026-10-30T17:30:18+00:00, book20_bid_proxy_usdt=173501, book20_ask_proxy_usdt=38228, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.55%, turnover=233785662. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T17:30:00+00:00, last15m_closed_end=2026-10-30T17:30+00:00, prior8high=2.938300, depth_time=2026-10-30T17:30:11+00:00, book20_bid_proxy_usdt=26549, book20_ask_proxy_usdt=25153, funding_indicative=0.000050, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=12888144. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T17:30:00+00:00, last15m_closed_end=2026-10-30T17:30+00:00, prior8high=0.004201, depth_time=2026-10-30T17:30:15+00:00, book20_bid_proxy_usdt=1529858, book20_ask_proxy_usdt=1231823, funding_indicative=0.000019, next_funding_utc=2026-10-30T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.58%, turnover=26693040. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
