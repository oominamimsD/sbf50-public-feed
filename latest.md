# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T07:15:28Z**
- feed_generated_utc: 2026-10-25T07:15:32+00:00
- source_sha256: `b41649ce972063feb666cfd5d6126e99124a3d9a4a1d711fa8d190d22e7b0aa8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T07:15+00:00, close=80592.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T07:00+00:00, close=80457.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.055340|-17.89|78.80|-18.93|13816377|1.80|
|BIRB_USDT|0.081620|-16.42|68.21|-17.46|6442622|6.14|
|IRYS_USDT|0.039440|-14.35|209.09|-15.39|33873184|2.53|
|DOT_USDT|1.022800|-1.56|-8.46|-2.60|11938111|0.98|
|STRK_USDT|0.046300|-0.92|-30.00|-1.96|8482080|2.16|
|SUI_USDT|0.918100|-0.74|-6.48|-1.78|66779109|1.09|
|APT_USDT|0.700700|-0.17|-12.13|-1.21|5960759|1.43|
|SEI_USDT|0.052830|-0.09|-14.80|-1.13|9640641|1.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.700700|0.697500|0.700700|3.53|N|Y/Y|Y/Y|Y|N|
|BIRB_USDT|0.081620|0.081650|0.081620|1.02|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.022800|1.017100|1.022800|1.60|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.039440|0.039230|0.039440|0.59|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.055340|0.054500|0.055100|0.47|N|Y/N|N/N|Y|N|
|SEI_USDT|0.052830|0.052650|0.052830|0.62|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.046300|0.045690|0.046300|1.18|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.918100|0.911400|0.918100|1.12|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-25T07:15:01+00:00, last15m_closed_end=2026-10-25T07:15+00:00, prior8high=0.713600, depth_time=2026-10-25T07:15:24+00:00, book20_bid_proxy_usdt=155649, book20_ask_proxy_usdt=169798, funding_indicative=-0.000021, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.17%, turnover=5960759. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-25T07:15:01+00:00, last15m_closed_end=2026-10-25T07:15+00:00, prior8high=0.086600, depth_time=2026-10-25T07:15:09+00:00, book20_bid_proxy_usdt=17964, book20_ask_proxy_usdt=12392, funding_indicative=-0.012028, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.42%, turnover=6442622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T07:15:01+00:00, last15m_closed_end=2026-10-25T07:15+00:00, prior8high=1.042400, depth_time=2026-10-25T07:15:16+00:00, book20_bid_proxy_usdt=367086, book20_ask_proxy_usdt=407340, funding_indicative=-0.000073, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=11938111. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T07:15:01+00:00, last15m_closed_end=2026-10-25T07:15+00:00, prior8high=0.044650, depth_time=2026-10-25T07:15:14+00:00, book20_bid_proxy_usdt=30337, book20_ask_proxy_usdt=30306, funding_indicative=-0.002531, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=1, 24h_change=-14.35%, turnover=33873184. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T07:15:01+00:00, last15m_closed_end=2026-10-25T07:15+00:00, prior8high=0.063100, depth_time=2026-10-25T07:15:09+00:00, book20_bid_proxy_usdt=68494, book20_ask_proxy_usdt=79273, funding_indicative=-0.001270, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=1, 24h_change=-17.89%, turnover=13816377. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T07:15:02+00:00, last15m_closed_end=2026-10-25T07:15+00:00, prior8high=0.053690, depth_time=2026-10-25T07:15:26+00:00, book20_bid_proxy_usdt=249084, book20_ask_proxy_usdt=392150, funding_indicative=-0.000066, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.09%, turnover=9640641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T07:15:01+00:00, last15m_closed_end=2026-10-25T07:15+00:00, prior8high=0.047110, depth_time=2026-10-25T07:15:18+00:00, book20_bid_proxy_usdt=766528, book20_ask_proxy_usdt=722013, funding_indicative=0.000039, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.92%, turnover=8482080. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T07:15:01+00:00, last15m_closed_end=2026-10-25T07:15+00:00, prior8high=0.932300, depth_time=2026-10-25T07:15:21+00:00, book20_bid_proxy_usdt=1292090, book20_ask_proxy_usdt=1407183, funding_indicative=0.000033, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.74%, turnover=66779109. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
