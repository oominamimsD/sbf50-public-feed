# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T15:45:20Z**
- feed_generated_utc: 2026-10-26T15:45:24+00:00
- source_sha256: `0cfab874cc119d563082ff3eb043846dc53409b85ad72fadec3ddfbcadd86767`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1186; contracts: 1178; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T15:45+00:00, close=80670.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T15:00+00:00, close=80385.4, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.027680|-27.99|126.88|-28.07|10939579|3.61|
|BTW_USDT|1.258900|-24.11|-45.39|-24.19|14932515|0.79|
|APR_USDT|0.032570|-21.15|19.56|-21.23|5632729|3.07|
|BRL_USDT|0.184800|-7.69|-6.09|-7.77|5679146|5.41|
|XMR_USDT|592.170000|-2.48|1.66|-2.56|5241385|0.84|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.032570|0.031420|0.032570|0.61|N|Y/Y|N/N|Y|N|
|BRL_USDT|0.184800|0.179700|0.184800|0.40|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.258900|1.032300|1.280500|4.32|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.027680|0.027330|0.027680|1.11|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|592.170000|591.300000|592.210000|0.49|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T15:45:04+00:00, last15m_closed_end=2026-10-26T15:45+00:00, prior8high=0.033120, depth_time=2026-10-26T15:45:14+00:00, book20_bid_proxy_usdt=45872, book20_ask_proxy_usdt=38552, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.15%, turnover=5632729. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BRL_USDT: quote_utc=2026-10-26T15:45:01+00:00, last15m_closed_end=2026-10-26T15:45+00:00, prior8high=0.186000, depth_time=2026-10-26T15:45:14+00:00, book20_bid_proxy_usdt=397631, book20_ask_proxy_usdt=434520, funding_indicative=-0.000116, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.69%, turnover=5679146. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T15:45:04+00:00, last15m_closed_end=2026-10-26T15:45+00:00, prior8high=1.634800, depth_time=2026-10-26T15:45:12+00:00, book20_bid_proxy_usdt=10065, book20_ask_proxy_usdt=11830, funding_indicative=-0.020000, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-24.11%, turnover=14932515. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T15:45:04+00:00, last15m_closed_end=2026-10-26T15:45+00:00, prior8high=0.028120, depth_time=2026-10-26T15:45:09+00:00, book20_bid_proxy_usdt=88004, book20_ask_proxy_usdt=95107, funding_indicative=-0.000710, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=1, 24h_change=-27.99%, turnover=10939579. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T15:45:05+00:00, last15m_closed_end=2026-10-26T15:45+00:00, prior8high=594.690000, depth_time=2026-10-26T15:45:20+00:00, book20_bid_proxy_usdt=19152, book20_ask_proxy_usdt=16767, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=5241385. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
