# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T09:30:20Z**
- feed_generated_utc: 2026-10-26T09:30:24+00:00
- source_sha256: `5cc7d36681b2b702e90a1312d077fddd6cf7232e944572c47a5bc58ae32b492e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T09:30+00:00, close=80496.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T09:00+00:00, close=80203.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.029220|-23.98|139.50|-23.85|12877792|3.42|
|CAP_USDT|0.084150|-21.70|26.54|-21.57|7292889|4.75|
|BTW_USDT|1.527500|-7.92|-33.74|-7.79|10985715|2.62|
|XMR_USDT|588.950000|-3.01|1.10|-2.88|5996458|0.17|
|WLD_USDT|0.443200|-2.93|-6.94|-2.80|65895459|2.26|
|LIT_USDT|3.098500|-2.51|5.73|-2.38|5690824|0.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.527500|1.440500|1.527500|1.28|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.084150|0.074320|0.084310|2.78|N|Y/Y|N/N|Y|N|
|IRYS_USDT|0.029220|0.028610|0.029220|0.58|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.098500|3.052200|3.098500|0.51|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.443200|0.434300|0.443600|3.23|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|588.950000|583.530000|588.950000|0.82|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-26T09:30:02+00:00, last15m_closed_end=2026-10-26T09:30+00:00, prior8high=1.617300, depth_time=2026-10-26T09:30:12+00:00, book20_bid_proxy_usdt=14463, book20_ask_proxy_usdt=13262, funding_indicative=-0.008651, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.92%, turnover=10985715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T09:30:01+00:00, last15m_closed_end=2026-10-26T09:30+00:00, prior8high=0.097940, depth_time=2026-10-26T09:30:10+00:00, book20_bid_proxy_usdt=60563, book20_ask_proxy_usdt=97831, funding_indicative=0.000101, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-21.70%, turnover=7292889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T09:30:01+00:00, last15m_closed_end=2026-10-26T09:30+00:00, prior8high=0.031910, depth_time=2026-10-26T09:30:08+00:00, book20_bid_proxy_usdt=146909, book20_ask_proxy_usdt=70485, funding_indicative=-0.000279, next_funding_utc=2026-10-26T10:00:00+00:00, funding_cycle_h=1, 24h_change=-23.98%, turnover=12877792. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T09:30:02+00:00, last15m_closed_end=2026-10-26T09:30+00:00, prior8high=3.121700, depth_time=2026-10-26T09:30:20+00:00, book20_bid_proxy_usdt=18744, book20_ask_proxy_usdt=19721, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.51%, turnover=5690824. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T09:30:01+00:00, last15m_closed_end=2026-10-26T09:30+00:00, prior8high=0.444800, depth_time=2026-10-26T09:30:17+00:00, book20_bid_proxy_usdt=2201918, book20_ask_proxy_usdt=2512362, funding_indicative=-0.000104, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.93%, turnover=65895459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T09:30:02+00:00, last15m_closed_end=2026-10-26T09:30+00:00, prior8high=592.000000, depth_time=2026-10-26T09:30:14+00:00, book20_bid_proxy_usdt=34621, book20_ask_proxy_usdt=12505, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.01%, turnover=5996458. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
