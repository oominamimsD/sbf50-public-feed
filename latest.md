# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T07:45:32Z**
- feed_generated_utc: 2026-10-25T07:45:35+00:00
- source_sha256: `04d0bf45b5dac6bb57313e2aaafafaada4fff515788330dad935ddb167e7f6d9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1180; contracts: 1172; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T07:45+00:00, close=80670.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-25T07:00+00:00, close=80457.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T04:00+00:00, close=80826.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.051280|-23.91|65.68|-25.04|13869413|1.95|
|IRYS_USDT|0.036770|-20.15|188.16|-21.28|34304988|5.43|
|BIRB_USDT|0.077990|-20.14|60.73|-21.27|6475537|2.56|
|BTW_USDT|1.690500|-2.91|-25.50|-4.04|11636745|1.77|
|DOT_USDT|1.031100|-0.76|-7.72|-1.89|12081902|0.97|
|SUI_USDT|0.920400|-0.49|-6.25|-1.62|67661784|1.09|
|AKE_USDT|0.029100|-0.44|0.47|-1.57|6581050|1.38|
|STRK_USDT|0.046550|-0.38|-29.62|-1.51|8717810|2.15|
|SEI_USDT|0.052880|0.00|-14.72|-1.13|9717368|1.89|
|APT_USDT|0.702700|0.11|-11.88|-1.02|6192906|1.42|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.029100|0.028767|0.029100|0.46|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.702700|0.697500|0.702700|1.37|N|Y/Y|Y/Y|Y|N|
|BIRB_USDT|0.077990|0.080220|0.077980|1.42|Y|Y/Y|Y/Y|Y|Y|
|BTW_USDT|1.690500|1.590000|1.690500|1.29|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.031100|1.017100|1.031100|2.25|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.036770|0.038170|0.036770|0.93|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.051280|0.054410|0.051270|2.04|Y|Y/N|N/N|Y|N|
|SEI_USDT|0.052880|0.052650|0.052880|0.50|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.046550|0.045690|0.046550|0.82|N|Y/Y|Y/Y|Y|N|
|SUI_USDT|0.920400|0.911400|0.920400|1.28|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-25T07:45:00+00:00, last15m_closed_end=2026-10-25T07:45+00:00, prior8high=0.030326, depth_time=2026-10-25T07:45:24+00:00, book20_bid_proxy_usdt=8884, book20_ask_proxy_usdt=12506, funding_indicative=0.000050, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.44%, turnover=6581050. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-25T07:45:00+00:00, last15m_closed_end=2026-10-25T07:45+00:00, prior8high=0.713400, depth_time=2026-10-25T07:45:31+00:00, book20_bid_proxy_usdt=128939, book20_ask_proxy_usdt=139145, funding_indicative=-0.000017, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.11%, turnover=6192906. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BIRB_USDT: quote_utc=2026-10-25T07:45:00+00:00, last15m_closed_end=2026-10-25T07:45+00:00, prior8high=0.085440, depth_time=2026-10-25T07:45:14+00:00, book20_bid_proxy_usdt=16810, book20_ask_proxy_usdt=11703, funding_indicative=-0.011326, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-20.14%, turnover=6475537. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-25T07:45:00+00:00, last15m_closed_end=2026-10-25T07:45+00:00, prior8high=1.915400, depth_time=2026-10-25T07:45:16+00:00, book20_bid_proxy_usdt=9977, book20_ask_proxy_usdt=10500, funding_indicative=-0.007063, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.91%, turnover=11636745. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-25T07:45:00+00:00, last15m_closed_end=2026-10-25T07:45+00:00, prior8high=1.042400, depth_time=2026-10-25T07:45:19+00:00, book20_bid_proxy_usdt=464962, book20_ask_proxy_usdt=292061, funding_indicative=-0.000045, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.76%, turnover=12081902. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T07:45:00+00:00, last15m_closed_end=2026-10-25T07:45+00:00, prior8high=0.044650, depth_time=2026-10-25T07:45:12+00:00, book20_bid_proxy_usdt=45157, book20_ask_proxy_usdt=46218, funding_indicative=-0.002545, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=1, 24h_change=-20.15%, turnover=34304988. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T07:44:59+00:00, last15m_closed_end=2026-10-25T07:45+00:00, prior8high=0.057990, depth_time=2026-10-25T07:45:09+00:00, book20_bid_proxy_usdt=112315, book20_ask_proxy_usdt=90465, funding_indicative=-0.001060, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=1, 24h_change=-23.91%, turnover=13869413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-25T07:45:00+00:00, last15m_closed_end=2026-10-25T07:45+00:00, prior8high=0.053530, depth_time=2026-10-25T07:45:29+00:00, book20_bid_proxy_usdt=166709, book20_ask_proxy_usdt=429937, funding_indicative=-0.000065, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=0.00%, turnover=9717368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-25T07:45:00+00:00, last15m_closed_end=2026-10-25T07:45+00:00, prior8high=0.046880, depth_time=2026-10-25T07:45:26+00:00, book20_bid_proxy_usdt=693879, book20_ask_proxy_usdt=726864, funding_indicative=0.000036, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.38%, turnover=8717810. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T07:45:00+00:00, last15m_closed_end=2026-10-25T07:45+00:00, prior8high=0.928100, depth_time=2026-10-25T07:45:21+00:00, book20_bid_proxy_usdt=1643103, book20_ask_proxy_usdt=1148652, funding_indicative=0.000035, next_funding_utc=2026-10-25T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.49%, turnover=67661784. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
