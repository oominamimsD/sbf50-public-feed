# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T02:00:22Z**
- feed_generated_utc: 2026-10-26T02:00:25+00:00
- source_sha256: `bcfc40f8d7af81a31eea485875ca219b3584b01bacbd77b25924c387a8f15731`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T02:00+00:00, close=79714.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T02:00+00:00, close=79714.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.005457|-21.72|196.09|-20.63|10256014|7.34|
|APR_USDT|0.033630|-17.41|23.45|-16.32|11952873|2.97|
|T_USDT|0.004947|-8.09|5.21|-7.00|7331931|4.05|
|DASH_USDT|50.890000|-3.99|6.28|-2.90|13686098|1.97|
|BTW_USDT|1.604900|-3.89|-30.38|-2.80|12076296|0.62|
|PEPE_USDT|0.000004|-3.43|10.90|-2.34|72548009|0.23|
|XMR_USDT|590.960000|-2.85|1.45|-1.76|6637763|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.033630|0.033580|0.033630|1.50|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.604900|1.606400|1.604900|1.45|Y|Y/Y|Y/Y|Y|Y|
|DASH_USDT|50.890000|50.550000|50.890000|0.21|N|Y/Y|Y/N|Y|N|
|JCT_USDT|0.005457|0.005381|0.005457|1.39|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|1.40|N|Y/Y|Y/Y|Y|N|
|T_USDT|0.004947|0.004873|0.004947|0.62|N|Y/Y|N/N|Y|N|
|XMR_USDT|590.960000|589.030000|590.960000|1.20|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T02:00:00+00:00, last15m_closed_end=2026-10-26T02:00+00:00, prior8high=0.041460, depth_time=2026-10-26T02:00:10+00:00, book20_bid_proxy_usdt=40229, book20_ask_proxy_usdt=58690, funding_indicative=0.000109, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-17.41%, turnover=11952873. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T02:00:00+00:00, last15m_closed_end=2026-10-26T02:00+00:00, prior8high=1.639900, depth_time=2026-10-26T02:00:17+00:00, book20_bid_proxy_usdt=15553, book20_ask_proxy_usdt=24406, funding_indicative=-0.006826, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.89%, turnover=12076296. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T02:00:01+00:00, last15m_closed_end=2026-10-26T02:00+00:00, prior8high=51.950000, depth_time=2026-10-26T02:00:14+00:00, book20_bid_proxy_usdt=882459, book20_ask_proxy_usdt=533339, funding_indicative=0.000075, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.99%, turnover=13686098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T02:00:00+00:00, last15m_closed_end=2026-10-26T02:00+00:00, prior8high=0.006255, depth_time=2026-10-26T02:00:07+00:00, book20_bid_proxy_usdt=24902, book20_ask_proxy_usdt=29557, funding_indicative=0.000105, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-21.72%, turnover=10256014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T02:00:00+00:00, last15m_closed_end=2026-10-26T02:00+00:00, prior8high=0.000004, depth_time=2026-10-26T02:00:19+00:00, book20_bid_proxy_usdt=72012, book20_ask_proxy_usdt=75831, funding_indicative=0.000078, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.43%, turnover=72548009. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T02:00:00+00:00, last15m_closed_end=2026-10-26T02:00+00:00, prior8high=0.005278, depth_time=2026-10-26T02:00:12+00:00, book20_bid_proxy_usdt=53790, book20_ask_proxy_usdt=67678, funding_indicative=-0.001818, next_funding_utc=2026-10-26T03:00:00+00:00, funding_cycle_h=1, 24h_change=-8.09%, turnover=7331931. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T02:00:00+00:00, last15m_closed_end=2026-10-26T02:00+00:00, prior8high=597.180000, depth_time=2026-10-26T02:00:20+00:00, book20_bid_proxy_usdt=26716, book20_ask_proxy_usdt=15356, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=6637763. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
