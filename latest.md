# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-11T00:15:22Z**
- feed_generated_utc: 2026-11-11T00:15:24+00:00
- source_sha256: `9c0cc3b6f17e4f5abf0182f9ffd84ebc6eaac6e3644c5e94d0e1495e6d88574c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-11T00:15+00:00, close=73637.2, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-11T00:00+00:00, close=73762.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.206320|-17.78|53.42|-18.39|54889132|0.48|
|PIEVERSE_USDT|1.810500|-10.64|54.03|-11.25|5308307|0.55|
|DASH_USDT|42.940000|-4.87|-6.93|-5.48|14099379|2.33|
|ZEC_USDT|1042.490000|-4.65|-13.40|-5.26|2168266373|0.10|
|JCT_USDT|0.005146|-2.44|23.16|-3.05|18836865|5.84|
|UNI_USDT|6.687000|-2.09|-9.05|-2.70|31849494|1.50|
|ARB_USDT|0.160130|-0.77|0.15|-1.38|33653848|0.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.160130|0.159790|0.160130|0.50|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.940000|42.400000|42.940000|0.41|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.206320|0.183240|0.206320|1.78|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.005146|0.005119|0.005138|2.18|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.810500|1.831300|1.808000|0.70|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.687000|6.611000|6.687000|1.07|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1042.490000|1030.550000|1042.510000|0.77|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-11T00:15:02+00:00, last15m_closed_end=2026-11-11T00:15+00:00, prior8high=0.161710, depth_time=2026-11-11T00:15:21+00:00, book20_bid_proxy_usdt=78750, book20_ask_proxy_usdt=69691, funding_indicative=-0.000176, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-0.77%, turnover=33653848. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-11T00:15:02+00:00, last15m_closed_end=2026-11-11T00:15+00:00, prior8high=43.380000, depth_time=2026-11-11T00:15:12+00:00, book20_bid_proxy_usdt=556564, book20_ask_proxy_usdt=745350, funding_indicative=-0.000166, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.87%, turnover=14099379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-11T00:15:02+00:00, last15m_closed_end=2026-11-11T00:15+00:00, prior8high=0.221030, depth_time=2026-11-11T00:15:07+00:00, book20_bid_proxy_usdt=7518, book20_ask_proxy_usdt=10690, funding_indicative=-0.016003, next_funding_utc=2026-11-11T01:00:00+00:00, funding_cycle_h=1, 24h_change=-17.78%, turnover=54889132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-11T00:15:02+00:00, last15m_closed_end=2026-11-11T00:15+00:00, prior8high=0.005343, depth_time=2026-11-11T00:15:17+00:00, book20_bid_proxy_usdt=46011, book20_ask_proxy_usdt=49888, funding_indicative=0.000456, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.44%, turnover=18836865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-11T00:15:02+00:00, last15m_closed_end=2026-11-11T00:15+00:00, prior8high=1.858500, depth_time=2026-11-11T00:15:10+00:00, book20_bid_proxy_usdt=9767, book20_ask_proxy_usdt=16181, funding_indicative=0.000050, next_funding_utc=2026-11-11T04:00:00+00:00, funding_cycle_h=4, 24h_change=-10.64%, turnover=5308307. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-11T00:15:02+00:00, last15m_closed_end=2026-11-11T00:15+00:00, prior8high=6.769000, depth_time=2026-11-11T00:15:20+00:00, book20_bid_proxy_usdt=2327134, book20_ask_proxy_usdt=3441633, funding_indicative=-0.000007, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.09%, turnover=31849494. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-11T00:15:02+00:00, last15m_closed_end=2026-11-11T00:15+00:00, prior8high=1063.120000, depth_time=2026-11-11T00:15:14+00:00, book20_bid_proxy_usdt=131895, book20_ask_proxy_usdt=325350, funding_indicative=0.000039, next_funding_utc=2026-11-11T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.65%, turnover=2168266373. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
