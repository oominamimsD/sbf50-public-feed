# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T02:45:19Z**
- feed_generated_utc: 2026-10-25T02:45:21+00:00
- source_sha256: `cc88a998987c18a045b38d3e4c23dd34906a9b1771f1f8d2b0feacb5fbec0e94`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1188; contracts: 1180; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T02:45+00:00, close=80918.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T02:00+00:00, close=80872.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-25T00:00+00:00, close=80845, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BIRB_USDT|0.073650|-24.58|51.79|-26.02|9593159|2.72|
|ORDER_USDT|0.052260|-22.46|68.85|-23.90|13418297|1.92|
|IRYS_USDT|0.036450|-20.84|185.65|-22.28|32929776|2.74|
|STRK_USDT|0.046410|-0.68|-29.84|-2.12|8356020|2.15|
|DOT_USDT|1.042200|0.29|-6.72|-1.15|11527694|0.96|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BIRB_USDT|0.073650|0.069260|0.073650|0.81|N|Y/Y|Y/N|Y|N|
|DOT_USDT|1.042200|1.042400|1.042200|0.71|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.036450|0.031610|0.036540|0.94|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.052260|0.050660|0.052260|0.59|N|Y/N|N/N|Y|N|
|STRK_USDT|0.046410|0.046300|0.046410|0.59|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BIRB_USDT: quote_utc=2026-10-25T02:45:01+00:00, last15m_closed_end=2026-10-25T02:45+00:00, prior8high=0.078910, depth_time=2026-10-25T02:45:08+00:00, book20_bid_proxy_usdt=13619, book20_ask_proxy_usdt=12370, funding_indicative=-0.013177, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-24.58%, turnover=9593159. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T02:45:02+00:00, last15m_closed_end=2026-10-25T02:45+00:00, prior8high=1.055300, depth_time=2026-10-25T02:45:17+00:00, book20_bid_proxy_usdt=375841, book20_ask_proxy_usdt=289095, funding_indicative=-0.000109, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.29%, turnover=11527694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T02:45:01+00:00, last15m_closed_end=2026-10-25T02:45+00:00, prior8high=0.037920, depth_time=2026-10-25T02:45:13+00:00, book20_bid_proxy_usdt=28914, book20_ask_proxy_usdt=27870, funding_indicative=0.000012, next_funding_utc=2026-10-25T03:00:00+00:00, funding_cycle_h=1, 24h_change=-20.84%, turnover=32929776. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T02:45:01+00:00, last15m_closed_end=2026-10-25T02:45+00:00, prior8high=0.060610, depth_time=2026-10-25T02:45:10+00:00, book20_bid_proxy_usdt=74642, book20_ask_proxy_usdt=68670, funding_indicative=-0.001126, next_funding_utc=2026-10-25T03:00:00+00:00, funding_cycle_h=1, 24h_change=-22.46%, turnover=13418297. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T02:45:02+00:00, last15m_closed_end=2026-10-25T02:45+00:00, prior8high=0.047560, depth_time=2026-10-25T02:45:15+00:00, book20_bid_proxy_usdt=1141000, book20_ask_proxy_usdt=616579, funding_indicative=0.000050, next_funding_utc=2026-10-25T04:00:00+00:00, funding_cycle_h=4, 24h_change=-0.68%, turnover=8356020. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
