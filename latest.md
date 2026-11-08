# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T11:45:18Z**
- feed_generated_utc: 2026-11-08T11:45:19+00:00
- source_sha256: `3b43bfddcceecd1c53da6b205b79fcd5904a0c7bd0f5443b2478277c15057600`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T11:45+00:00, close=75952.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T11:00+00:00, close=75861.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.028181|-15.36|60.84|-15.65|16565381|8.52|
|ONE_USDT|0.001926|-5.43|64.04|-5.72|25965295|0.52|
|TIA_USDT|0.426200|-3.48|-13.03|-3.77|7345886|2.35|
|ENA_USDT|0.155220|-1.87|-19.99|-2.16|29786651|0.65|
|WLD_USDT|0.329300|-1.87|-18.57|-2.16|23368350|3.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.155220|0.152210|0.155160|2.11|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.028181|0.030631|0.028182|7.67|Y|N/N|N/N|Y|N|
|ONE_USDT|0.001926|0.001872|0.001924|0.78|N|Y/N|N/N|Y|N|
|TIA_USDT|0.426200|0.422800|0.426200|0.72|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.329300|0.326600|0.329300|2.03|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-08T11:45:01+00:00, last15m_closed_end=2026-11-08T11:45+00:00, prior8high=0.155180, depth_time=2026-11-08T11:45:14+00:00, book20_bid_proxy_usdt=246629, book20_ask_proxy_usdt=130789, funding_indicative=0.000045, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.87%, turnover=29786651. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T11:45:01+00:00, last15m_closed_end=2026-11-08T11:45+00:00, prior8high=0.033952, depth_time=2026-11-08T11:45:07+00:00, book20_bid_proxy_usdt=4948, book20_ask_proxy_usdt=6216, funding_indicative=0.000431, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-15.36%, turnover=16565381. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T11:45:01+00:00, last15m_closed_end=2026-11-08T11:45+00:00, prior8high=0.002228, depth_time=2026-11-08T11:45:09+00:00, book20_bid_proxy_usdt=9161, book20_ask_proxy_usdt=10647, funding_indicative=-0.001529, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.43%, turnover=25965295. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T11:45:01+00:00, last15m_closed_end=2026-11-08T11:45+00:00, prior8high=0.427700, depth_time=2026-11-08T11:45:11+00:00, book20_bid_proxy_usdt=272704, book20_ask_proxy_usdt=400772, funding_indicative=-0.000009, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.48%, turnover=7345886. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T11:45:01+00:00, last15m_closed_end=2026-11-08T11:45+00:00, prior8high=0.330100, depth_time=2026-11-08T11:45:16+00:00, book20_bid_proxy_usdt=3665585, book20_ask_proxy_usdt=3434943, funding_indicative=-0.000039, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=23368350. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
