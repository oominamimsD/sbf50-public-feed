# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T23:15:31Z**
- feed_generated_utc: 2026-11-10T23:15:32+00:00
- source_sha256: `42952a2724831346e917d89aef36079d0d5af0b0edc1e0ba3164354f1d83b5cd`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T23:15+00:00, close=73640.8, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T23:00+00:00, close=73666.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.208010|-17.10|54.67|-17.72|52621406|4.82|
|PIEVERSE_USDT|1.839900|-9.19|56.53|-9.81|5461022|1.09|
|DASH_USDT|42.550000|-5.73|-7.78|-6.35|13950013|2.35|
|ZEC_USDT|1037.490000|-5.10|-13.81|-5.72|2215568763|0.10|
|UNI_USDT|6.625000|-3.00|-9.90|-3.62|31446497|1.51|
|JUP_USDT|0.250200|-1.18|0.44|-1.80|5461604|4.00|
|JCT_USDT|0.005218|-1.08|24.89|-1.70|19137861|1.92|
|HBAR_USDT|0.065340|-0.66|-6.69|-1.28|8825219|1.53|
|ONDO_USDT|0.364200|-0.43|-6.42|-1.05|15862015|2.75|
|DOT_USDT|0.838300|-0.40|-11.06|-1.02|8474603|1.19|
|NEAR_USDT|3.547000|-0.39|-8.08|-1.01|35024135|2.82|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|42.550000|42.610000|42.550000|1.73|Y|Y/Y|Y/Y|Y|Y|
|DOT_USDT|0.838300|0.835600|0.838300|1.19|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065340|0.065540|0.065340|3.67|Y|Y/Y|Y/Y|Y|Y|
|INIT_USDT|0.208010|0.183240|0.208030|1.69|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.005218|0.005119|0.005218|0.79|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.250200|0.249400|0.250200|0.25|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.547000|3.538000|3.547000|3.06|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.364200|0.363800|0.364200|0.72|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.839900|1.798500|1.839900|1.12|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.625000|6.639000|6.625000|1.32|Y|Y/Y|Y/Y|Y|Y|
|ZEC_USDT|1037.490000|1036.710000|1037.490000|1.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-10T23:15:00+00:00, last15m_closed_end=2026-11-10T23:15+00:00, prior8high=43.460000, depth_time=2026-11-10T23:15:09+00:00, book20_bid_proxy_usdt=799929, book20_ask_proxy_usdt=676908, funding_indicative=-0.000177, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.73%, turnover=13950013. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T23:15:00+00:00, last15m_closed_end=2026-11-10T23:15+00:00, prior8high=0.846200, depth_time=2026-11-10T23:15:25+00:00, book20_bid_proxy_usdt=640537, book20_ask_proxy_usdt=594944, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.40%, turnover=8474603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T23:15:00+00:00, last15m_closed_end=2026-11-10T23:15+00:00, prior8high=0.066260, depth_time=2026-11-10T23:15:21+00:00, book20_bid_proxy_usdt=595630, book20_ask_proxy_usdt=840147, funding_indicative=0.000030, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.66%, turnover=8825219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-10T23:14:59+00:00, last15m_closed_end=2026-11-10T23:15+00:00, prior8high=0.233780, depth_time=2026-11-10T23:15:07+00:00, book20_bid_proxy_usdt=12486, book20_ask_proxy_usdt=13473, funding_indicative=-0.018071, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=1, 24h_change=-17.10%, turnover=52621406. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T23:14:59+00:00, last15m_closed_end=2026-11-10T23:15+00:00, prior8high=0.005437, depth_time=2026-11-10T23:15:20+00:00, book20_bid_proxy_usdt=34016, book20_ask_proxy_usdt=42801, funding_indicative=0.000587, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=19137861. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-11-10T23:15:00+00:00, last15m_closed_end=2026-11-10T23:15+00:00, prior8high=0.257600, depth_time=2026-11-10T23:15:18+00:00, book20_bid_proxy_usdt=544871, book20_ask_proxy_usdt=689818, funding_indicative=-0.000023, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.18%, turnover=5461604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-10T23:14:59+00:00, last15m_closed_end=2026-11-10T23:15+00:00, prior8high=3.611000, depth_time=2026-11-10T23:15:27+00:00, book20_bid_proxy_usdt=2557211, book20_ask_proxy_usdt=2419122, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.39%, turnover=35024135. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T23:15:00+00:00, last15m_closed_end=2026-11-10T23:15+00:00, prior8high=0.369500, depth_time=2026-11-10T23:15:23+00:00, book20_bid_proxy_usdt=3052122, book20_ask_proxy_usdt=2888229, funding_indicative=0.000015, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.43%, turnover=15862015. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T23:14:59+00:00, last15m_closed_end=2026-11-10T23:15+00:00, prior8high=1.858500, depth_time=2026-11-10T23:15:08+00:00, book20_bid_proxy_usdt=25768, book20_ask_proxy_usdt=17736, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.19%, turnover=5461022. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T23:15:00+00:00, last15m_closed_end=2026-11-10T23:15+00:00, prior8high=6.769000, depth_time=2026-11-10T23:15:13+00:00, book20_bid_proxy_usdt=1499248, book20_ask_proxy_usdt=3984098, funding_indicative=-0.000020, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=31446497. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T23:14:59+00:00, last15m_closed_end=2026-11-10T23:15+00:00, prior8high=1069.190000, depth_time=2026-11-10T23:15:13+00:00, book20_bid_proxy_usdt=325486, book20_ask_proxy_usdt=126940, funding_indicative=0.000018, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.10%, turnover=2215568763. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
