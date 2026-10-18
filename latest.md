# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T01:30:34Z**
- feed_generated_utc: 2026-10-18T01:30:36+00:00
- source_sha256: `c8eaae1495f9be95acfd3023fef60849eb63c1b6c4b967ca3b4c475090a7d995`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T01:30+00:00, close=81551.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-18T01:00+00:00, close=81513.3, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T00:00+00:00, close=81455.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.157600|-14.90|59.03|-15.19|14829829|6.35|
|SAND_USDT|0.058410|-7.34|-13.19|-7.63|27352900|1.71|
|DNA_USDT|0.260300|-4.33|UNKNOWN|-4.62|5358351|3.84|
|STRK_USDT|0.063910|-3.38|-31.59|-3.67|15769618|1.56|
|TIA_USDT|0.637300|-3.14|24.23|-3.43|72990946|3.14|
|FILECOIN_USDT|1.061400|-2.39|-5.88|-2.68|20133300|0.94|
|EIGEN_USDT|0.250900|-2.10|6.49|-2.39|10778288|3.98|
|QNT_USDT|196.530000|-1.93|-19.82|-2.22|68758324|0.51|
|PUMPFUN_USDT|0.004351|-1.38|-24.00|-1.67|23653449|2.30|
|ARB_USDT|0.182180|-0.94|-2.40|-1.23|31836263|0.55|
|DOT_USDT|1.107500|-0.88|-11.88|-1.17|16606785|1.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.182180|0.179900|0.182180|3.48|N|Y/Y|Y/Y|Y|N|
|DNA_USDT|0.260300|0.255400|0.260300|2.24|N|N/Y|?|Y|N|
|DOT_USDT|1.107500|1.105300|1.107500|0.66|N|Y/Y|Y/Y|Y|N|
|EIGEN_USDT|0.250900|0.248200|0.250900|0.48|N|Y/Y|Y/N|Y|N|
|FILECOIN_USDT|1.061400|1.057500|1.061400|2.30|N|Y/Y|Y/Y|Y|N|
|ICNT_USDT|0.157600|0.157000|0.157600|0.54|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004351|0.004297|0.004351|1.16|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|196.530000|193.770000|196.530000|1.56|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.058410|0.057980|0.058410|0.34|N|Y/Y|N/N|Y|N|
|STRK_USDT|0.063910|0.063700|0.063910|0.34|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.637300|0.639600|0.637300|1.98|Y|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-18T01:30:01+00:00, last15m_closed_end=2026-10-18T01:30+00:00, prior8high=0.182310, depth_time=2026-10-18T01:30:30+00:00, book20_bid_proxy_usdt=62438, book20_ask_proxy_usdt=91453, funding_indicative=0.000027, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.94%, turnover=31836263. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DNA_USDT: quote_utc=2026-10-18T01:30:01+00:00, last15m_closed_end=2026-10-18T01:30+00:00, prior8high=0.269200, depth_time=2026-10-18T01:30:12+00:00, book20_bid_proxy_usdt=88610, book20_ask_proxy_usdt=86200, funding_indicative=-0.002236, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.33%, turnover=5358351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-18T01:30:01+00:00, last15m_closed_end=2026-10-18T01:30+00:00, prior8high=1.117400, depth_time=2026-10-18T01:30:33+00:00, book20_bid_proxy_usdt=315267, book20_ask_proxy_usdt=295879, funding_indicative=0.000016, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=16606785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EIGEN_USDT: quote_utc=2026-10-18T01:30:01+00:00, last15m_closed_end=2026-10-18T01:30+00:00, prior8high=0.253300, depth_time=2026-10-18T01:30:22+00:00, book20_bid_proxy_usdt=454258, book20_ask_proxy_usdt=314143, funding_indicative=-0.000014, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.10%, turnover=10778288. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-18T01:30:01+00:00, last15m_closed_end=2026-10-18T01:30+00:00, prior8high=1.070300, depth_time=2026-10-18T01:30:19+00:00, book20_bid_proxy_usdt=484242, book20_ask_proxy_usdt=658178, funding_indicative=-0.000034, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.39%, turnover=20133300. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-18T01:30:01+00:00, last15m_closed_end=2026-10-18T01:30+00:00, prior8high=0.174200, depth_time=2026-10-18T01:30:08+00:00, book20_bid_proxy_usdt=290043, book20_ask_proxy_usdt=173865, funding_indicative=-0.000046, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-14.90%, turnover=14829829. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T01:30:01+00:00, last15m_closed_end=2026-10-18T01:30+00:00, prior8high=0.004364, depth_time=2026-10-18T01:30:28+00:00, book20_bid_proxy_usdt=1719736, book20_ask_proxy_usdt=1326246, funding_indicative=0.000039, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.38%, turnover=23653449. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-18T01:30:01+00:00, last15m_closed_end=2026-10-18T01:30+00:00, prior8high=196.890000, depth_time=2026-10-18T01:30:24+00:00, book20_bid_proxy_usdt=81812, book20_ask_proxy_usdt=44617, funding_indicative=-0.000070, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=68758324. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T01:30:01+00:00, last15m_closed_end=2026-10-18T01:30+00:00, prior8high=0.060240, depth_time=2026-10-18T01:30:09+00:00, book20_bid_proxy_usdt=612072, book20_ask_proxy_usdt=1287173, funding_indicative=-0.002944, next_funding_utc=2026-10-18T08:00:00+00:00, funding_cycle_h=8, 24h_change=-7.34%, turnover=27352900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T01:30:01+00:00, last15m_closed_end=2026-10-18T01:30+00:00, prior8high=0.064810, depth_time=2026-10-18T01:30:15+00:00, book20_bid_proxy_usdt=400005, book20_ask_proxy_usdt=412134, funding_indicative=0.000050, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.38%, turnover=15769618. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-18T01:30:01+00:00, last15m_closed_end=2026-10-18T01:30+00:00, prior8high=0.651200, depth_time=2026-10-18T01:30:17+00:00, book20_bid_proxy_usdt=142846, book20_ask_proxy_usdt=316597, funding_indicative=0.000009, next_funding_utc=2026-10-18T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.14%, turnover=72990946. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
