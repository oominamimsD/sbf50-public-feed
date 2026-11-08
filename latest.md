# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T07:00:27Z**
- feed_generated_utc: 2026-11-08T07:00:28+00:00
- source_sha256: `45e5f22dcd1f79e28021df8ac714b0841bc1dff8304b08672717e18312440c99`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T07:00+00:00, close=75801.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T07:00+00:00, close=75801.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T04:00+00:00, close=75885, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005160|-13.75|-53.67|-13.85|40733177|1.94|
|ENA_USDT|0.153830|-2.75|-20.71|-2.85|29069070|0.65|
|TIA_USDT|0.430200|-2.58|-12.22|-2.68|7779658|2.32|
|QNT_USDT|194.480000|-2.19|-3.26|-2.29|46520091|1.54|
|WLD_USDT|0.329000|-1.96|-18.64|-2.06|23793436|3.04|
|AAVE_USDT|130.120000|-1.59|-3.97|-1.69|10864909|0.77|
|ONDO_USDT|0.357900|-1.43|-13.21|-1.53|8701551|2.79|
|LINK_USDT|10.719000|-1.15|-7.36|-1.25|68674373|0.93|
|ADA_USDT|0.179800|-0.99|-7.12|-1.09|11626223|5.56|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.120000|129.910000|130.120000|0.50|N|Y/Y|N/N|Y|N|
|ADA_USDT|0.179800|0.179600|0.179800|0.18|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005160|0.005077|0.005160|0.79|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.153830|0.153230|0.153830|1.08|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.719000|10.717000|10.719000|2.15|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.357900|0.357400|0.357900|0.75|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|194.480000|193.910000|194.480000|0.99|N|Y/Y|Y/N|Y|N|
|TIA_USDT|0.430200|0.431000|0.430200|3.32|Y|Y/Y|Y/N|Y|N|
|WLD_USDT|0.329000|0.328600|0.329000|0.61|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T06:59:59+00:00, last15m_closed_end=2026-11-08T07:00+00:00, prior8high=131.110000, depth_time=2026-11-08T07:00:17+00:00, book20_bid_proxy_usdt=486153, book20_ask_proxy_usdt=738848, funding_indicative=0.000015, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=10864909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T06:59:59+00:00, last15m_closed_end=2026-11-08T07:00+00:00, prior8high=0.180600, depth_time=2026-11-08T07:00:25+00:00, book20_bid_proxy_usdt=11159390, book20_ask_proxy_usdt=8815446, funding_indicative=0.000000, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.99%, turnover=11626223. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T06:59:59+00:00, last15m_closed_end=2026-11-08T07:00+00:00, prior8high=0.005418, depth_time=2026-11-08T07:00:06+00:00, book20_bid_proxy_usdt=54057, book20_ask_proxy_usdt=78998, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-13.75%, turnover=40733177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T06:59:59+00:00, last15m_closed_end=2026-11-08T07:00+00:00, prior8high=0.155160, depth_time=2026-11-08T07:00:09+00:00, book20_bid_proxy_usdt=284239, book20_ask_proxy_usdt=244977, funding_indicative=0.000050, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.75%, turnover=29069070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T06:59:59+00:00, last15m_closed_end=2026-11-08T07:00+00:00, prior8high=10.771000, depth_time=2026-11-08T07:00:23+00:00, book20_bid_proxy_usdt=475016, book20_ask_proxy_usdt=361192, funding_indicative=0.000068, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=68674373. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T06:59:59+00:00, last15m_closed_end=2026-11-08T07:00+00:00, prior8high=0.359500, depth_time=2026-11-08T07:00:20+00:00, book20_bid_proxy_usdt=1366258, book20_ask_proxy_usdt=1535332, funding_indicative=-0.000030, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=8701551. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T06:59:59+00:00, last15m_closed_end=2026-11-08T07:00+00:00, prior8high=196.790000, depth_time=2026-11-08T07:00:10+00:00, book20_bid_proxy_usdt=63315, book20_ask_proxy_usdt=73306, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.19%, turnover=46520091. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T06:59:59+00:00, last15m_closed_end=2026-11-08T07:00+00:00, prior8high=0.435000, depth_time=2026-11-08T07:00:11+00:00, book20_bid_proxy_usdt=292224, book20_ask_proxy_usdt=360688, funding_indicative=0.000037, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.58%, turnover=7779658. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T06:59:59+00:00, last15m_closed_end=2026-11-08T07:00+00:00, prior8high=0.332600, depth_time=2026-11-08T07:00:16+00:00, book20_bid_proxy_usdt=4459735, book20_ask_proxy_usdt=3754684, funding_indicative=-0.000166, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=23793436. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
