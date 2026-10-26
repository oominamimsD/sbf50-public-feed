# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T15:00:23Z**
- feed_generated_utc: 2026-10-26T15:00:27+00:00
- source_sha256: `0bbd73c6e2b1aa9f63b3f08eae2fb04abdffb9f4432d4db091eacd28193a6b52`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1186; contracts: 1178; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T15:00+00:00, close=80385.4, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T15:00+00:00, close=80385.4, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.193000|-28.08|-48.25|-27.80|12533058|7.54|
|IRYS_USDT|0.027880|-20.84|128.52|-20.56|10667424|3.59|
|APR_USDT|0.032290|-20.70|18.53|-20.42|5558175|3.10|
|BRL_USDT|0.183400|-8.16|-6.80|-7.88|5503617|5.45|
|XMR_USDT|593.670000|-2.40|1.91|-2.12|5149450|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.032290|0.031070|0.032290|1.75|N|Y/Y|N/N|Y|N|
|BRL_USDT|0.183400|0.179700|0.183400|2.06|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.193000|1.241500|1.206900|7.46|Y|Y/Y|Y/Y|Y|Y|
|IRYS_USDT|0.027880|0.027330|0.027880|0.70|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|593.670000|590.710000|593.670000|1.12|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T15:00:01+00:00, last15m_closed_end=2026-10-26T15:00+00:00, prior8high=0.037130, depth_time=2026-10-26T15:00:14+00:00, book20_bid_proxy_usdt=40256, book20_ask_proxy_usdt=82162, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.70%, turnover=5558175. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BRL_USDT: quote_utc=2026-10-26T15:00:02+00:00, last15m_closed_end=2026-10-26T15:00+00:00, prior8high=0.183400, depth_time=2026-10-26T15:00:18+00:00, book20_bid_proxy_usdt=395707, book20_ask_proxy_usdt=398690, funding_indicative=-0.000116, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.16%, turnover=5503617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T15:00:01+00:00, last15m_closed_end=2026-10-26T15:00+00:00, prior8high=1.462300, depth_time=2026-10-26T15:00:10+00:00, book20_bid_proxy_usdt=6951, book20_ask_proxy_usdt=10746, funding_indicative=-0.020000, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-28.08%, turnover=12533058. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T15:00:01+00:00, last15m_closed_end=2026-10-26T15:00+00:00, prior8high=0.029430, depth_time=2026-10-26T15:00:13+00:00, book20_bid_proxy_usdt=68870, book20_ask_proxy_usdt=68237, funding_indicative=-0.000806, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=1, 24h_change=-20.84%, turnover=10667424. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T15:00:01+00:00, last15m_closed_end=2026-10-26T15:00+00:00, prior8high=594.690000, depth_time=2026-10-26T15:00:21+00:00, book20_bid_proxy_usdt=8354, book20_ask_proxy_usdt=5614, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.40%, turnover=5149450. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
