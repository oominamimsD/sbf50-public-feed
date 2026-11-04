# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-04T04:15:31Z**
- feed_generated_utc: 2026-11-04T04:15:33+00:00
- source_sha256: `36d2ff915a0a78fed41362dd96e8b42921d598b160968ee8d98f31f2a7481564`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-04T04:15+00:00, close=76846.3, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-04T04:00+00:00, close=76468.7, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.038280|-28.86|-19.44|-27.81|11925884|5.22|
|AKE_USDT|0.003544|-14.72|-83.22|-13.67|12139600|2.82|
|HOT_USDT|0.000474|-12.05|37.08|-11.00|8180841|2.11|
|TRUMPOFFICIAL_USDT|1.513000|-5.90|-10.36|-4.85|8141869|6.61|
|STRK_USDT|0.042020|-4.78|-8.88|-3.73|5868862|2.38|
|HYPE_USDT|83.289000|-4.64|4.82|-3.59|74465968|0.12|
|XPL_USDT|0.061690|-3.68|-16.43|-2.63|7071382|1.62|
|XLM_USDT|0.160240|-2.76|-5.30|-1.71|37006027|0.62|
|LINK_USDT|10.879000|-2.46|-4.99|-1.41|191747471|0.92|
|QNT_USDT|191.160000|-2.17|-3.40|-1.12|61560189|0.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.038280|0.036920|0.038280|0.58|N|Y/Y|N/N|Y|N|
|AKE_USDT|0.003544|0.003340|0.003541|0.56|N|Y/Y|Y/Y|Y|N|
|HOT_USDT|0.000474|0.000458|0.000474|0.79|N|Y/Y|N/N|Y|N|
|HYPE_USDT|83.289000|80.647000|83.289000|1.26|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|10.879000|10.623000|10.877000|1.55|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.160000|185.400000|191.160000|1.30|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.042020|0.040980|0.042020|0.65|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.513000|1.475000|1.512000|0.99|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.160240|0.156990|0.160260|1.23|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.061690|0.060070|0.061690|0.79|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-11-04T04:15:03+00:00, last15m_closed_end=2026-11-04T04:15+00:00, prior8high=0.041310, depth_time=2026-11-04T04:15:08+00:00, book20_bid_proxy_usdt=30070, book20_ask_proxy_usdt=23972, funding_indicative=0.000047, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-28.86%, turnover=11925884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-04T04:15:03+00:00, last15m_closed_end=2026-11-04T04:15+00:00, prior8high=0.003794, depth_time=2026-11-04T04:15:10+00:00, book20_bid_proxy_usdt=38908, book20_ask_proxy_usdt=36234, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.72%, turnover=12139600. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HOT_USDT: quote_utc=2026-11-04T04:15:03+00:00, last15m_closed_end=2026-11-04T04:15+00:00, prior8high=0.000487, depth_time=2026-11-04T04:15:12+00:00, book20_bid_proxy_usdt=91223, book20_ask_proxy_usdt=83435, funding_indicative=-0.000432, next_funding_utc=2026-11-04T05:00:00+00:00, funding_cycle_h=1, 24h_change=-12.05%, turnover=8180841. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-04T04:15:03+00:00, last15m_closed_end=2026-11-04T04:15+00:00, prior8high=83.283000, depth_time=2026-11-04T04:15:20+00:00, book20_bid_proxy_usdt=100167, book20_ask_proxy_usdt=368824, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.64%, turnover=74465968. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-04T04:15:03+00:00, last15m_closed_end=2026-11-04T04:15+00:00, prior8high=10.898000, depth_time=2026-11-04T04:15:27+00:00, book20_bid_proxy_usdt=362321, book20_ask_proxy_usdt=366311, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=191747471. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-04T04:15:03+00:00, last15m_closed_end=2026-11-04T04:15+00:00, prior8high=191.200000, depth_time=2026-11-04T04:15:30+00:00, book20_bid_proxy_usdt=80463, book20_ask_proxy_usdt=48491, funding_indicative=-0.000043, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=61560189. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-11-04T04:15:03+00:00, last15m_closed_end=2026-11-04T04:15+00:00, prior8high=0.042030, depth_time=2026-11-04T04:15:16+00:00, book20_bid_proxy_usdt=353851, book20_ask_proxy_usdt=361480, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.78%, turnover=5868862. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-04T04:15:03+00:00, last15m_closed_end=2026-11-04T04:15+00:00, prior8high=1.529000, depth_time=2026-11-04T04:15:10+00:00, book20_bid_proxy_usdt=2327317, book20_ask_proxy_usdt=2599369, funding_indicative=-0.000190, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.90%, turnover=8141869. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-04T04:15:03+00:00, last15m_closed_end=2026-11-04T04:15+00:00, prior8high=0.160590, depth_time=2026-11-04T04:15:25+00:00, book20_bid_proxy_usdt=140760, book20_ask_proxy_usdt=138607, funding_indicative=0.000100, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=37006027. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-04T04:15:03+00:00, last15m_closed_end=2026-11-04T04:15+00:00, prior8high=0.061640, depth_time=2026-11-04T04:15:23+00:00, book20_bid_proxy_usdt=413686, book20_ask_proxy_usdt=453063, funding_indicative=0.000050, next_funding_utc=2026-11-04T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.68%, turnover=7071382. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
