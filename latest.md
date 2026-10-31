# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T10:00:40Z**
- feed_generated_utc: 2026-10-31T10:00:42+00:00
- source_sha256: `e0f3558bfb57d8df85150a36a6885410d1305b26c03f921f1ed32acdc09c8692`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T10:00+00:00, close=77434.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T10:00+00:00, close=77434.3, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.010531|-45.22|-69.90|-45.03|10109821|4.76|
|Q_USDT|0.031620|-33.09|-73.27|-32.90|14231810|3.17|
|BLESS_USDT|0.010327|-23.53|26.54|-23.34|13269364|3.87|
|BTW_USDT|1.135400|-6.72|-33.30|-6.53|8980743|1.76|
|IDOL_USDT|0.019049|-5.89|140.51|-5.70|15801620|6.30|
|HYPE_USDT|87.288000|-5.88|11.33|-5.69|102626880|0.12|
|TRX_USDT|0.317620|-5.58|-3.55|-5.39|7039418|0.32|
|WLD_USDT|0.396600|-3.71|-25.50|-3.52|47326304|2.52|
|PEPE_USDT|0.000005|-3.21|2.40|-3.02|126230431|0.20|
|FET_USDT|0.161900|-2.82|-13.56|-2.63|5685145|6.18|
|DASH_USDT|47.790000|-2.80|-11.25|-2.61|12978450|2.09|
|LTC_USDT|54.930000|-1.41|-6.02|-1.22|6266770|3.64|
|ARB_USDT|0.161340|-1.35|-10.33|-1.16|18674824|0.62|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010531|0.009146|0.010531|0.63|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.161340|0.160660|0.161340|0.97|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.010327|0.009860|0.010327|1.83|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.135400|1.124400|1.135400|0.56|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|47.790000|47.590000|47.790000|0.33|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161900|0.161500|0.161800|0.84|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.288000|86.343000|87.288000|1.70|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.019049|0.018443|0.018968|1.10|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.930000|54.520000|54.940000|3.70|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|1.25|N|N/N|N/N|Y|N|
|Q_USDT|0.031620|0.031230|0.031620|1.12|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.317620|0.316930|0.317620|2.43|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396600|0.394600|0.396700|0.80|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T10:00:01+00:00, last15m_closed_end=2026-10-31T10:00+00:00, prior8high=0.011333, depth_time=2026-10-31T10:00:09+00:00, book20_bid_proxy_usdt=6719, book20_ask_proxy_usdt=8163, funding_indicative=-0.000755, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-45.22%, turnover=10109821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-31T10:00:01+00:00, last15m_closed_end=2026-10-31T10:00+00:00, prior8high=0.162180, depth_time=2026-10-31T10:00:37+00:00, book20_bid_proxy_usdt=85003, book20_ask_proxy_usdt=58465, funding_indicative=0.000053, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=18674824. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T10:00:01+00:00, last15m_closed_end=2026-10-31T10:00+00:00, prior8high=0.010343, depth_time=2026-10-31T10:00:12+00:00, book20_bid_proxy_usdt=22754, book20_ask_proxy_usdt=14338, funding_indicative=0.000100, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-23.53%, turnover=13269364. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T10:00:01+00:00, last15m_closed_end=2026-10-31T10:00+00:00, prior8high=1.181700, depth_time=2026-10-31T10:00:16+00:00, book20_bid_proxy_usdt=19776, book20_ask_proxy_usdt=16628, funding_indicative=-0.000141, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-6.72%, turnover=8980743. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T10:00:02+00:00, last15m_closed_end=2026-10-31T10:00+00:00, prior8high=47.940000, depth_time=2026-10-31T10:00:32+00:00, book20_bid_proxy_usdt=840499, book20_ask_proxy_usdt=664830, funding_indicative=-0.000082, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.80%, turnover=12978450. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T10:00:01+00:00, last15m_closed_end=2026-10-31T10:00+00:00, prior8high=0.162400, depth_time=2026-10-31T10:00:32+00:00, book20_bid_proxy_usdt=1476998, book20_ask_proxy_usdt=983179, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=5685145. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T10:00:01+00:00, last15m_closed_end=2026-10-31T10:00+00:00, prior8high=88.263000, depth_time=2026-10-31T10:00:22+00:00, book20_bid_proxy_usdt=162679, book20_ask_proxy_usdt=155742, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.88%, turnover=102626880. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T10:00:01+00:00, last15m_closed_end=2026-10-31T10:00+00:00, prior8high=0.023044, depth_time=2026-10-31T10:00:19+00:00, book20_bid_proxy_usdt=10331, book20_ask_proxy_usdt=11099, funding_indicative=0.000292, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.89%, turnover=15801620. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T10:00:01+00:00, last15m_closed_end=2026-10-31T10:00+00:00, prior8high=54.990000, depth_time=2026-10-31T10:00:32+00:00, book20_bid_proxy_usdt=1346883, book20_ask_proxy_usdt=1188158, funding_indicative=-0.000010, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=6266770. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T10:00:01+00:00, last15m_closed_end=2026-10-31T10:00+00:00, prior8high=0.000005, depth_time=2026-10-31T10:00:29+00:00, book20_bid_proxy_usdt=30773, book20_ask_proxy_usdt=28989, funding_indicative=-0.000553, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=126230431. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T10:00:01+00:00, last15m_closed_end=2026-10-31T10:00+00:00, prior8high=0.033810, depth_time=2026-10-31T10:00:11+00:00, book20_bid_proxy_usdt=42484, book20_ask_proxy_usdt=47463, funding_indicative=-0.000613, next_funding_utc=2026-10-31T11:00:00+00:00, funding_cycle_h=1, 24h_change=-33.09%, turnover=14231810. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T10:00:01+00:00, last15m_closed_end=2026-10-31T10:00+00:00, prior8high=0.322380, depth_time=2026-10-31T10:00:24+00:00, book20_bid_proxy_usdt=144992, book20_ask_proxy_usdt=78409, funding_indicative=-0.000690, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.58%, turnover=7039418. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T10:00:01+00:00, last15m_closed_end=2026-10-31T10:00+00:00, prior8high=0.399000, depth_time=2026-10-31T10:00:26+00:00, book20_bid_proxy_usdt=3241482, book20_ask_proxy_usdt=2623982, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.71%, turnover=47326304. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
