# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T01:15:21Z**
- feed_generated_utc: 2026-10-27T01:15:25+00:00
- source_sha256: `c774bd66b4ec661da8367211990f1ca3c6d6df79b31c06a8513e95ba8862dee6`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T01:15+00:00, close=80300.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T01:00+00:00, close=80194.2, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.619800|-5.11|-14.83|-4.99|5358082|1.24|
|NEAR_USDT|4.489000|-1.83|-8.46|-1.71|109820951|2.23|
|DOT_USDT|1.005700|-1.65|-12.30|-1.53|10509872|0.99|
|BTW_USDT|1.179100|-1.38|-32.69|-1.26|20985001|3.39|
|LINK_USDT|11.382000|-1.26|-4.69|-1.14|102575557|1.76|
|ARB_USDT|0.168070|-1.12|-14.08|-1.00|20142970|1.19|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.168070|0.165690|0.168070|0.79|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.179100|1.171200|1.179100|0.65|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.005700|0.999000|1.005700|1.85|N|Y/Y|Y/Y|Y|N|
|LINK_USDT|11.382000|11.242000|11.382000|1.16|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.489000|4.422000|4.489000|0.59|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.619800|1.610100|1.619800|0.53|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-27T01:15:01+00:00, last15m_closed_end=2026-10-27T01:15+00:00, prior8high=0.169780, depth_time=2026-10-27T01:15:19+00:00, book20_bid_proxy_usdt=111060, book20_ask_proxy_usdt=87074, funding_indicative=-0.000024, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=20142970. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-27T01:15:01+00:00, last15m_closed_end=2026-10-27T01:15+00:00, prior8high=1.229000, depth_time=2026-10-27T01:15:16+00:00, book20_bid_proxy_usdt=19690, book20_ask_proxy_usdt=10097, funding_indicative=-0.000294, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.38%, turnover=20985001. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T01:15:01+00:00, last15m_closed_end=2026-10-27T01:15+00:00, prior8high=1.013800, depth_time=2026-10-27T01:15:13+00:00, book20_bid_proxy_usdt=332100, book20_ask_proxy_usdt=313697, funding_indicative=-0.000092, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=10509872. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T01:15:01+00:00, last15m_closed_end=2026-10-27T01:15+00:00, prior8high=11.421000, depth_time=2026-10-27T01:15:18+00:00, book20_bid_proxy_usdt=489746, book20_ask_proxy_usdt=566832, funding_indicative=0.000076, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=102575557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T01:15:01+00:00, last15m_closed_end=2026-10-27T01:15+00:00, prior8high=4.536000, depth_time=2026-10-27T01:15:10+00:00, book20_bid_proxy_usdt=4691340, book20_ask_proxy_usdt=5217045, funding_indicative=-0.000097, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=109820951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T01:15:01+00:00, last15m_closed_end=2026-10-27T01:15+00:00, prior8high=1.647700, depth_time=2026-10-27T01:15:08+00:00, book20_bid_proxy_usdt=19622, book20_ask_proxy_usdt=28298, funding_indicative=-0.000225, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.11%, turnover=5358082. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
