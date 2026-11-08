# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T05:30:19Z**
- feed_generated_utc: 2026-11-08T05:30:21+00:00
- source_sha256: `9d82ade85f7bf2ea4ad9e17ec449e8b7e72b1f24b99d75b9988e887ff3a3bfdd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T05:30+00:00, close=75847.8, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T05:00+00:00, close=75830.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001962|-3.65|67.12|-3.81|26369489|0.51|
|ENA_USDT|0.154500|-2.32|-20.36|-2.48|28300748|0.65|
|TIA_USDT|0.433800|-1.76|-11.48|-1.92|7358580|4.61|
|QNT_USDT|195.720000|-1.57|-2.65|-1.73|45872675|0.51|
|ONDO_USDT|0.359100|-1.10|-12.92|-1.26|8742391|2.79|
|WLD_USDT|0.332300|-0.98|-17.82|-1.14|23726842|3.01|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ENA_USDT|0.154500|0.153230|0.154500|0.66|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359100|0.357400|0.359100|1.69|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001962|0.001804|0.001962|1.65|N|Y/Y|N/N|Y|N|
|QNT_USDT|195.720000|193.760000|195.720000|0.50|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.433800|0.432800|0.433700|0.57|N|Y/Y|Y/N|Y|N|
|WLD_USDT|0.332300|0.329900|0.332200|0.49|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ENA_USDT: quote_utc=2026-11-08T05:29:59+00:00, last15m_closed_end=2026-11-08T05:30+00:00, prior8high=0.155380, depth_time=2026-11-08T05:30:07+00:00, book20_bid_proxy_usdt=182344, book20_ask_proxy_usdt=194793, funding_indicative=0.000042, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.32%, turnover=28300748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T05:29:59+00:00, last15m_closed_end=2026-11-08T05:30+00:00, prior8high=0.361900, depth_time=2026-11-08T05:30:15+00:00, book20_bid_proxy_usdt=1488859, book20_ask_proxy_usdt=2382786, funding_indicative=0.000005, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.10%, turnover=8742391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T05:29:59+00:00, last15m_closed_end=2026-11-08T05:30+00:00, prior8high=0.001943, depth_time=2026-11-08T05:30:07+00:00, book20_bid_proxy_usdt=16019, book20_ask_proxy_usdt=13374, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.65%, turnover=26369489. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T05:29:59+00:00, last15m_closed_end=2026-11-08T05:30+00:00, prior8high=195.650000, depth_time=2026-11-08T05:30:12+00:00, book20_bid_proxy_usdt=63625, book20_ask_proxy_usdt=66741, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.57%, turnover=45872675. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T05:29:59+00:00, last15m_closed_end=2026-11-08T05:30+00:00, prior8high=0.438300, depth_time=2026-11-08T05:30:10+00:00, book20_bid_proxy_usdt=309098, book20_ask_proxy_usdt=302512, funding_indicative=0.000003, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.76%, turnover=7358580. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T05:29:59+00:00, last15m_closed_end=2026-11-08T05:30+00:00, prior8high=0.332300, depth_time=2026-11-08T05:30:18+00:00, book20_bid_proxy_usdt=4059531, book20_ask_proxy_usdt=3107629, funding_indicative=-0.000143, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=23726842. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
