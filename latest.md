# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T15:00:31Z**
- feed_generated_utc: 2026-10-21T15:00:34+00:00
- source_sha256: `38f1f5afdec564e7475f5881983943304a1727d0bdfbf40a74355057cfa6a4cb`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1206; contracts: 1198; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T15:00+00:00, close=84530, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T15:00+00:00, close=84530, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T12:00+00:00, close=83464, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.046150|-28.59|185.28|-31.02|6130748|4.12|
|BAT_USDT|0.179910|-16.61|1.42|-19.04|9180336|0.56|
|BTW_USDT|1.597600|-13.62|-18.17|-16.05|26234534|1.25|
|AKE_USDT|0.027252|-12.34|8.71|-14.77|9563082|3.67|
|BR_USDT|0.579380|-10.95|33.80|-13.38|18896947|1.90|
|INJ_USDT|8.750000|-1.75|11.64|-4.18|61279352|3.43|
|OP_USDT|0.130360|-0.70|-8.29|-3.13|6262172|0.77|
|SILVER_USDT|57.610000|-0.58|-2.99|-3.01|163545042|1.74|
|QNT_USDT|195.860000|0.35|-4.21|-2.08|68419437|0.51|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.046150|0.044473|0.046163|1.05|N|Y/Y|Y/Y|N|N|
|AKE_USDT|0.027252|0.026106|0.027330|0.45|N|Y/Y|Y/N|N|N|
|BAT_USDT|0.179910|0.177360|0.179960|1.70|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.579380|0.575600|0.579200|1.10|N|Y/Y|N/N|N|N|
|BTW_USDT|1.597600|1.471900|1.596000|1.18|N|Y/Y|Y/Y|N|N|
|INJ_USDT|8.750000|8.633000|8.750000|1.06|N|Y/Y|N/N|N|N|
|OP_USDT|0.130360|0.127930|0.130300|2.12|N|N/Y|N/N|N|N|
|QNT_USDT|195.860000|192.220000|195.890000|1.24|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.610000|57.440000|57.630000|0.98|N|N/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T15:00:04+00:00, last15m_closed_end=2026-10-21T15:00+00:00, prior8high=0.046298, depth_time=2026-10-21T15:00:09+00:00, book20_bid_proxy_usdt=21494, book20_ask_proxy_usdt=6618, funding_indicative=0.000168, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-28.59%, turnover=6130748. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T15:00:04+00:00, last15m_closed_end=2026-10-21T15:00+00:00, prior8high=0.029869, depth_time=2026-10-21T15:00:17+00:00, book20_bid_proxy_usdt=11795, book20_ask_proxy_usdt=15411, funding_indicative=0.000050, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.34%, turnover=9563082. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T15:00:04+00:00, last15m_closed_end=2026-10-21T15:00+00:00, prior8high=0.181260, depth_time=2026-10-21T15:00:12+00:00, book20_bid_proxy_usdt=22117, book20_ask_proxy_usdt=23714, funding_indicative=-0.000234, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-16.61%, turnover=9180336. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T15:00:04+00:00, last15m_closed_end=2026-10-21T15:00+00:00, prior8high=0.634300, depth_time=2026-10-21T15:00:19+00:00, book20_bid_proxy_usdt=5822, book20_ask_proxy_usdt=5161, funding_indicative=0.000047, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.95%, turnover=18896947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T15:00:04+00:00, last15m_closed_end=2026-10-21T15:00+00:00, prior8high=1.641600, depth_time=2026-10-21T15:00:15+00:00, book20_bid_proxy_usdt=17054, book20_ask_proxy_usdt=11976, funding_indicative=-0.005035, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.62%, turnover=26234534. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T15:00:04+00:00, last15m_closed_end=2026-10-21T15:00+00:00, prior8high=8.803000, depth_time=2026-10-21T15:00:22+00:00, book20_bid_proxy_usdt=120979, book20_ask_proxy_usdt=208137, funding_indicative=0.000048, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.75%, turnover=61279352. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-21T15:00:04+00:00, last15m_closed_end=2026-10-21T15:00+00:00, prior8high=0.131020, depth_time=2026-10-21T15:00:24+00:00, book20_bid_proxy_usdt=60243, book20_ask_proxy_usdt=54995, funding_indicative=0.000044, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.70%, turnover=6262172. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-21T15:00:04+00:00, last15m_closed_end=2026-10-21T15:00+00:00, prior8high=199.400000, depth_time=2026-10-21T15:00:30+00:00, book20_bid_proxy_usdt=68934, book20_ask_proxy_usdt=56074, funding_indicative=-0.000043, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=0.35%, turnover=68419437. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T15:00:04+00:00, last15m_closed_end=2026-10-21T15:00+00:00, prior8high=57.950000, depth_time=2026-10-21T15:00:25+00:00, book20_bid_proxy_usdt=45479887, book20_ask_proxy_usdt=41962892, funding_indicative=0.000039, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.58%, turnover=163545042. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
