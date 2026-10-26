# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T02:30:25Z**
- feed_generated_utc: 2026-10-26T02:30:28+00:00
- source_sha256: `eaaf3db47c3c09c2fccd6875cf755705c317e921d2931ba578bdc16b3b493778`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T02:30+00:00, close=79564.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-26T02:00+00:00, close=79714.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-26T00:00+00:00, close=80114.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|JCT_USDT|0.004192|-39.87|127.45|-38.58|10727167|4.76|
|APR_USDT|0.032600|-21.08|19.67|-19.79|12107728|3.06|
|T_USDT|0.004924|-8.52|4.72|-7.23|7347481|2.03|
|DASH_USDT|50.830000|-3.01|6.16|-1.72|13707128|1.97|
|PEPE_USDT|0.000004|-2.92|10.70|-1.63|73562673|0.94|
|PUMPFUN_USDT|0.004163|-2.84|-0.76|-1.55|17195196|2.40|
|XMR_USDT|590.590000|-2.74|1.38|-1.45|6734911|0.68|
|WLD_USDT|0.445100|-2.51|-6.55|-1.22|73338035|2.25|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.032600|0.033080|0.032600|1.44|Y|Y/Y|N/N|Y|N|
|DASH_USDT|50.830000|50.550000|50.830000|0.11|N|Y/Y|Y/N|Y|N|
|JCT_USDT|0.004192|0.004915|0.004213|5.01|Y|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.72|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004163|0.004164|0.004163|2.72|Y|Y/Y|Y/Y|Y|Y|
|T_USDT|0.004924|0.004873|0.004924|0.31|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.445100|0.442200|0.445200|0.22|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|590.590000|588.410000|590.610000|0.27|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T02:30:01+00:00, last15m_closed_end=2026-10-26T02:30+00:00, prior8high=0.040390, depth_time=2026-10-26T02:30:10+00:00, book20_bid_proxy_usdt=100281, book20_ask_proxy_usdt=62522, funding_indicative=0.000076, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-21.08%, turnover=12107728. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-26T02:30:01+00:00, last15m_closed_end=2026-10-26T02:30+00:00, prior8high=51.950000, depth_time=2026-10-26T02:30:14+00:00, book20_bid_proxy_usdt=939953, book20_ask_proxy_usdt=585405, funding_indicative=0.000064, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.01%, turnover=13707128. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-10-26T02:30:01+00:00, last15m_closed_end=2026-10-26T02:30+00:00, prior8high=0.006255, depth_time=2026-10-26T02:30:07+00:00, book20_bid_proxy_usdt=31748, book20_ask_proxy_usdt=33662, funding_indicative=0.000050, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-39.87%, turnover=10727167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-26T02:30:01+00:00, last15m_closed_end=2026-10-26T02:30+00:00, prior8high=0.000004, depth_time=2026-10-26T02:30:17+00:00, book20_bid_proxy_usdt=38208, book20_ask_proxy_usdt=83594, funding_indicative=0.000043, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.92%, turnover=73562673. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-26T02:30:01+00:00, last15m_closed_end=2026-10-26T02:30+00:00, prior8high=0.004272, depth_time=2026-10-26T02:30:19+00:00, book20_bid_proxy_usdt=2460018, book20_ask_proxy_usdt=2031636, funding_indicative=0.000034, next_funding_utc=2026-10-26T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=17195196. target_RR/account_short_permission/settled_funding=UNKNOWN.
- T_USDT: quote_utc=2026-10-26T02:30:01+00:00, last15m_closed_end=2026-10-26T02:30+00:00, prior8high=0.005030, depth_time=2026-10-26T02:30:13+00:00, book20_bid_proxy_usdt=58423, book20_ask_proxy_usdt=73196, funding_indicative=-0.001871, next_funding_utc=2026-10-26T03:00:00+00:00, funding_cycle_h=1, 24h_change=-8.52%, turnover=7347481. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T02:30:01+00:00, last15m_closed_end=2026-10-26T02:30+00:00, prior8high=0.452600, depth_time=2026-10-26T02:30:25+00:00, book20_bid_proxy_usdt=1918253, book20_ask_proxy_usdt=2687067, funding_indicative=0.000098, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=73338035. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T02:30:01+00:00, last15m_closed_end=2026-10-26T02:30+00:00, prior8high=597.180000, depth_time=2026-10-26T02:30:19+00:00, book20_bid_proxy_usdt=20840, book20_ask_proxy_usdt=22013, funding_indicative=0.000100, next_funding_utc=2026-10-26T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.74%, turnover=6734911. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
