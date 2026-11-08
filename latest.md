# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T08:30:30Z**
- feed_generated_utc: 2026-11-08T08:30:31+00:00
- source_sha256: `7192709d9d301f8903ce157e1b23049bae643a6660ccae430bffac32016d8638`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T08:30+00:00, close=75860, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T08:00+00:00, close=75939, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TIA_USDT|0.428600|-2.94|-12.54|-3.11|7427576|2.33|
|ENA_USDT|0.153990|-2.64|-20.62|-2.81|29301461|0.65|
|QNT_USDT|194.960000|-1.95|-3.02|-2.12|43816819|2.56|
|WLD_USDT|0.329400|-1.84|-18.54|-2.01|23618254|3.04|
|AAVE_USDT|130.320000|-1.44|-3.82|-1.61|10845197|0.77|
|LINK_USDT|10.720000|-1.14|-7.35|-1.31|66339836|0.93|
|ONDO_USDT|0.359500|-0.99|-12.82|-1.16|8492710|2.78|
|ADA_USDT|0.180000|-0.88|-7.02|-1.05|9771289|5.55|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.320000|129.910000|130.320000|1.59|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.180000|0.179600|0.180000|0.51|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.153990|0.153450|0.153990|0.82|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.720000|10.711000|10.720000|0.76|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.359500|0.357600|0.359500|0.24|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.960000|194.160000|194.970000|0.20|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.428600|0.428600|0.428600|0.68|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.329400|0.328600|0.329400|0.71|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T08:29:59+00:00, last15m_closed_end=2026-11-08T08:30+00:00, prior8high=131.110000, depth_time=2026-11-08T08:30:20+00:00, book20_bid_proxy_usdt=652768, book20_ask_proxy_usdt=311638, funding_indicative=0.000025, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=10845197. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T08:29:59+00:00, last15m_closed_end=2026-11-08T08:30+00:00, prior8high=0.180600, depth_time=2026-11-08T08:30:28+00:00, book20_bid_proxy_usdt=10572404, book20_ask_proxy_usdt=8840155, funding_indicative=0.000004, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=9771289. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T08:29:59+00:00, last15m_closed_end=2026-11-08T08:30+00:00, prior8high=0.155160, depth_time=2026-11-08T08:30:11+00:00, book20_bid_proxy_usdt=346542, book20_ask_proxy_usdt=181555, funding_indicative=0.000035, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.64%, turnover=29301461. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T08:29:59+00:00, last15m_closed_end=2026-11-08T08:30+00:00, prior8high=10.755000, depth_time=2026-11-08T08:30:24+00:00, book20_bid_proxy_usdt=489976, book20_ask_proxy_usdt=434956, funding_indicative=0.000068, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.14%, turnover=66339836. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T08:29:59+00:00, last15m_closed_end=2026-11-08T08:30+00:00, prior8high=0.360500, depth_time=2026-11-08T08:30:20+00:00, book20_bid_proxy_usdt=1412150, book20_ask_proxy_usdt=1747450, funding_indicative=-0.000009, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.99%, turnover=8492710. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T08:29:59+00:00, last15m_closed_end=2026-11-08T08:30+00:00, prior8high=196.230000, depth_time=2026-11-08T08:30:15+00:00, book20_bid_proxy_usdt=86336, book20_ask_proxy_usdt=90826, funding_indicative=0.000100, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=43816819. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T08:29:59+00:00, last15m_closed_end=2026-11-08T08:30+00:00, prior8high=0.434500, depth_time=2026-11-08T08:30:08+00:00, book20_bid_proxy_usdt=416438, book20_ask_proxy_usdt=396002, funding_indicative=0.000050, next_funding_utc=2026-11-08T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.94%, turnover=7427576. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T08:29:59+00:00, last15m_closed_end=2026-11-08T08:30+00:00, prior8high=0.331200, depth_time=2026-11-08T08:30:16+00:00, book20_bid_proxy_usdt=3844832, book20_ask_proxy_usdt=3508347, funding_indicative=-0.000171, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=23618254. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
