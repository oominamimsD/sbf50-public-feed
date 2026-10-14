# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T07:15:21Z**
- feed_generated_utc: 2026-10-14T07:15:22+00:00
- source_sha256: `e19022fbf22602dea3cb1749063c1d55d99e694fd15e7197aa783666b62d4675`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T07:15+00:00, close=83471.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T07:00+00:00, close=83400, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGIC_USDT|0.110690|-6.70|62.49|-6.79|5362934|3.61|
|STRK_USDT|0.081850|-5.84|56.83|-5.93|30659218|1.22|
|W_USDT|0.016172|-3.75|11.43|-3.84|6846610|3.71|
|TIA_USDT|0.557300|-3.46|17.00|-3.55|42340573|1.79|
|UNI_USDT|7.379000|-2.54|-14.84|-2.63|19373097|1.35|
|SILVER_USDT|58.730000|-1.11|-4.30|-1.20|245022583|1.70|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.110690|0.111300|0.110690|1.50|Y|Y/Y|Y/N|N|N|
|SILVER_USDT|58.730000|58.510000|58.730000|0.93|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.081850|0.080270|0.081850|1.06|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.557300|0.547400|0.557300|0.85|N|Y/Y|N/N|N|N|
|UNI_USDT|7.379000|7.259000|7.379000|0.98|N|Y/Y|Y/N|N|N|
|W_USDT|0.016172|0.015869|0.016174|1.30|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T07:15:00+00:00, last15m_closed_end=2026-10-14T07:15+00:00, prior8high=0.115400, depth_time=2026-10-14T07:15:08+00:00, book20_bid_proxy_usdt=175746, book20_ask_proxy_usdt=180606, funding_indicative=-0.000012, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.70%, turnover=5362934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T07:15:00+00:00, last15m_closed_end=2026-10-14T07:15+00:00, prior8high=59.440000, depth_time=2026-10-14T07:15:20+00:00, book20_bid_proxy_usdt=55971031, book20_ask_proxy_usdt=41610890, funding_indicative=0.000070, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.11%, turnover=245022583. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T07:15:00+00:00, last15m_closed_end=2026-10-14T07:15+00:00, prior8high=0.085100, depth_time=2026-10-14T07:15:10+00:00, book20_bid_proxy_usdt=169134, book20_ask_proxy_usdt=159588, funding_indicative=0.000050, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.84%, turnover=30659218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T07:15:00+00:00, last15m_closed_end=2026-10-14T07:15+00:00, prior8high=0.579000, depth_time=2026-10-14T07:15:14+00:00, book20_bid_proxy_usdt=132725, book20_ask_proxy_usdt=205246, funding_indicative=0.000004, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.46%, turnover=42340573. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T07:15:00+00:00, last15m_closed_end=2026-10-14T07:15+00:00, prior8high=7.480000, depth_time=2026-10-14T07:15:17+00:00, book20_bid_proxy_usdt=1605240, book20_ask_proxy_usdt=1285980, funding_indicative=0.000100, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=19373097. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T07:15:00+00:00, last15m_closed_end=2026-10-14T07:15+00:00, prior8high=0.016644, depth_time=2026-10-14T07:15:12+00:00, book20_bid_proxy_usdt=43668, book20_ask_proxy_usdt=34105, funding_indicative=-0.000196, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.75%, turnover=6846610. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
