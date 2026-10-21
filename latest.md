# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T13:30:20Z**
- feed_generated_utc: 2026-10-21T13:30:22+00:00
- source_sha256: `ec636ceba20330ebd7babdead61784399e39cd107430f8e2a6508d9cc7d7643d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1206; contracts: 1198; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T13:30+00:00, close=83711.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T13:00+00:00, close=83471.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.178610|-17.22|0.69|-18.55|10693116|1.68|
|BTW_USDT|1.576700|-14.75|-19.24|-16.08|25055996|6.35|
|AKE_USDT|0.028612|-7.97|14.14|-9.30|9316223|6.30|
|BR_USDT|0.628330|-3.43|45.10|-4.76|19957031|3.02|
|TIA_USDT|0.619000|-0.59|7.22|-1.92|43829669|1.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.028612|0.026106|0.028644|1.28|N|Y/Y|Y/N|N|N|
|BAT_USDT|0.178610|0.179180|0.178610|2.41|Y|Y/Y|Y/Y|N|Y|
|BR_USDT|0.628330|0.572580|0.628700|3.03|N|N/Y|N/N|N|N|
|BTW_USDT|1.576700|1.546500|1.576700|2.54|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.619000|0.615000|0.619000|1.36|N|N/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-21T13:30:02+00:00, last15m_closed_end=2026-10-21T13:30+00:00, prior8high=0.036142, depth_time=2026-10-21T13:30:14+00:00, book20_bid_proxy_usdt=7678, book20_ask_proxy_usdt=11824, funding_indicative=0.000050, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.97%, turnover=9316223. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T13:30:02+00:00, last15m_closed_end=2026-10-21T13:30+00:00, prior8high=0.182410, depth_time=2026-10-21T13:30:09+00:00, book20_bid_proxy_usdt=22463, book20_ask_proxy_usdt=23430, funding_indicative=-0.000195, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-17.22%, turnover=10693116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T13:30:02+00:00, last15m_closed_end=2026-10-21T13:30+00:00, prior8high=0.623940, depth_time=2026-10-21T13:30:17+00:00, book20_bid_proxy_usdt=4281, book20_ask_proxy_usdt=2503, funding_indicative=0.000028, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.43%, turnover=19957031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T13:30:02+00:00, last15m_closed_end=2026-10-21T13:30+00:00, prior8high=1.738100, depth_time=2026-10-21T13:30:12+00:00, book20_bid_proxy_usdt=7447, book20_ask_proxy_usdt=11111, funding_indicative=-0.005559, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.75%, turnover=25055996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T13:30:02+00:00, last15m_closed_end=2026-10-21T13:30+00:00, prior8high=0.626700, depth_time=2026-10-21T13:30:19+00:00, book20_bid_proxy_usdt=137610, book20_ask_proxy_usdt=146378, funding_indicative=-0.000084, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.59%, turnover=43829669. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
