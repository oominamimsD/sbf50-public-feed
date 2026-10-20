# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T07:15:27Z**
- feed_generated_utc: 2026-10-20T07:15:29+00:00
- source_sha256: `089c6e5000467dc40d6d049e7246799d6c51414cae4d9902982d24df1997abb8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T07:15+00:00, close=81723, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T07:00+00:00, close=81779.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.117969|-6.36|283.12|-6.13|7729084|1.53|
|CT_USDT|0.310430|-5.96|-9.26|-5.73|5473682|1.29|
|BTW_USDT|1.682200|-3.98|-4.19|-3.75|30266559|1.78|
|SAND_USDT|0.056870|-3.83|-8.40|-3.60|7605582|1.76|
|NEAR_USDT|4.780000|-2.52|-13.85|-2.29|168355968|2.09|
|ZRO_USDT|1.856000|-2.41|-17.91|-2.18|7573398|0.54|
|ATOM_USDT|1.742000|-1.91|-4.70|-1.68|5259163|5.74|
|UNI_USDT|7.187000|-1.38|-3.11|-1.15|10048426|1.39|
|TAO_USDT|264.950000|-1.24|-7.45|-1.01|53875930|1.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ATOM_USDT|1.742000|1.745000|1.742000|1.90|Y|N/N|N/N|Y|N|
|BTW_USDT|1.682200|1.671800|1.684900|2.19|N|Y/Y|Y/Y|Y|N|
|CT_USDT|0.310430|0.301550|0.310430|0.62|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.780000|4.749000|4.779000|0.37|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.117969|0.110142|0.118041|1.47|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.056870|0.056650|0.056860|0.48|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|264.950000|263.780000|264.960000|0.75|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.187000|7.119000|7.187000|0.33|N|Y/Y|N/N|Y|N|
|ZRO_USDT|1.856000|1.826700|1.856000|2.18|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ATOM_USDT: quote_utc=2026-10-20T07:15:01+00:00, last15m_closed_end=2026-10-20T07:15+00:00, prior8high=1.769000, depth_time=2026-10-20T07:15:19+00:00, book20_bid_proxy_usdt=1496964, book20_ask_proxy_usdt=1192183, funding_indicative=0.000088, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=5259163. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T07:15:01+00:00, last15m_closed_end=2026-10-20T07:15+00:00, prior8high=1.808400, depth_time=2026-10-20T07:15:12+00:00, book20_bid_proxy_usdt=14133, book20_ask_proxy_usdt=7246, funding_indicative=-0.004081, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.98%, turnover=30266559. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-20T07:15:01+00:00, last15m_closed_end=2026-10-20T07:15+00:00, prior8high=0.310430, depth_time=2026-10-20T07:15:10+00:00, book20_bid_proxy_usdt=12608, book20_ask_proxy_usdt=9394, funding_indicative=-0.002426, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.96%, turnover=5473682. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T07:15:01+00:00, last15m_closed_end=2026-10-20T07:15+00:00, prior8high=4.830000, depth_time=2026-10-20T07:15:15+00:00, book20_bid_proxy_usdt=4078018, book20_ask_proxy_usdt=2656554, funding_indicative=-0.000009, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.52%, turnover=168355968. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T07:15:01+00:00, last15m_closed_end=2026-10-20T07:15+00:00, prior8high=0.133766, depth_time=2026-10-20T07:15:07+00:00, book20_bid_proxy_usdt=15597, book20_ask_proxy_usdt=15524, funding_indicative=-0.000086, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.36%, turnover=7729084. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T07:15:01+00:00, last15m_closed_end=2026-10-20T07:15+00:00, prior8high=0.057320, depth_time=2026-10-20T07:15:12+00:00, book20_bid_proxy_usdt=755737, book20_ask_proxy_usdt=836830, funding_indicative=-0.001524, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.83%, turnover=7605582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T07:15:01+00:00, last15m_closed_end=2026-10-20T07:15+00:00, prior8high=267.240000, depth_time=2026-10-20T07:15:26+00:00, book20_bid_proxy_usdt=107601, book20_ask_proxy_usdt=121729, funding_indicative=0.000044, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=53875930. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T07:15:01+00:00, last15m_closed_end=2026-10-20T07:15+00:00, prior8high=7.297000, depth_time=2026-10-20T07:15:24+00:00, book20_bid_proxy_usdt=1656594, book20_ask_proxy_usdt=2118854, funding_indicative=0.000025, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.38%, turnover=10048426. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T07:15:01+00:00, last15m_closed_end=2026-10-20T07:15+00:00, prior8high=1.882200, depth_time=2026-10-20T07:15:19+00:00, book20_bid_proxy_usdt=32255, book20_ask_proxy_usdt=50121, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.41%, turnover=7573398. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
