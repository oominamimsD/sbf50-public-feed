# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T23:30:37Z**
- feed_generated_utc: 2026-10-31T23:30:40+00:00
- source_sha256: `7705d4d53bf505b0cb167f5504d06d26fe206bf7fc06e5a1c61bad7ad24fbd0d`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T23:30+00:00, close=77480.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-31T23:00+00:00, close=77498.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T20:00+00:00, close=77539.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.246700|-16.70|46.91|-16.60|28647825|0.41|
|BLESS_USDT|0.009365|-11.34|15.43|-11.24|7883031|4.27|
|INJ_USDT|7.199000|-3.83|-4.19|-3.73|20614284|1.39|
|TRX_USDT|0.301240|-3.55|-8.41|-3.45|10271756|0.66|
|ENA_USDT|0.188600|-2.78|0.96|-2.68|46121755|0.53|
|ZEC_USDT|1251.310000|-2.58|9.26|-2.48|1064005231|0.08|
|FET_USDT|0.159500|-2.32|-7.42|-2.22|5821566|6.27|
|BTW_USDT|1.097000|-2.21|-37.00|-2.11|5473871|3.65|
|IDOL_USDT|0.017138|-2.18|116.93|-2.08|6159089|0.58|
|AKE_USDT|0.010932|-1.84|-62.60|-1.74|11884392|1.83|
|Q_USDT|0.031530|-1.71|-60.05|-1.61|10587582|3.17|
|WLD_USDT|0.398000|-1.58|-13.85|-1.48|34712415|2.51|
|FARTCOIN_USDT|0.120070|-1.57|-1.56|-1.47|6599238|0.83|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.010932|0.010970|0.010932|0.44|N|Y/Y|Y/Y|Y|N|
|BLESS_USDT|0.009365|0.009300|0.009365|1.46|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.097000|1.086300|1.097000|0.57|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188600|0.187820|0.188600|0.63|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.120070|0.119850|0.120070|1.40|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.159500|0.159600|0.159500|1.88|Y|Y/Y|Y/Y|Y|Y|
|IDOL_USDT|0.017138|0.016473|0.017138|0.51|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.199000|7.198000|7.199000|0.87|N|Y/N|Y/Y|Y|N|
|LSK_USDT|0.246700|0.237060|0.246980|1.20|N|Y/Y|N/N|Y|N|
|Q_USDT|0.031530|0.031320|0.031530|0.71|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.301240|0.300760|0.301240|0.16|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.398000|0.396100|0.398000|0.60|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1251.310000|1245.000000|1251.440000|2.01|N|Y/Y|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T23:30:00+00:00, last15m_closed_end=2026-10-31T23:30+00:00, prior8high=0.011405, depth_time=2026-10-31T23:30:30+00:00, book20_bid_proxy_usdt=18227, book20_ask_proxy_usdt=17219, funding_indicative=-0.000400, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=11884392. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T23:30:00+00:00, last15m_closed_end=2026-10-31T23:30+00:00, prior8high=0.009629, depth_time=2026-10-31T23:30:09+00:00, book20_bid_proxy_usdt=10377, book20_ask_proxy_usdt=13925, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-11.34%, turnover=7883031. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T23:30:00+00:00, last15m_closed_end=2026-10-31T23:30+00:00, prior8high=1.118300, depth_time=2026-10-31T23:30:23+00:00, book20_bid_proxy_usdt=25429, book20_ask_proxy_usdt=10874, funding_indicative=-0.000101, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.21%, turnover=5473871. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-31T23:30:00+00:00, last15m_closed_end=2026-10-31T23:30+00:00, prior8high=0.191470, depth_time=2026-10-31T23:30:17+00:00, book20_bid_proxy_usdt=219744, book20_ask_proxy_usdt=125488, funding_indicative=-0.000024, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.78%, turnover=46121755. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-31T23:30:01+00:00, last15m_closed_end=2026-10-31T23:30+00:00, prior8high=0.121480, depth_time=2026-10-31T23:30:36+00:00, book20_bid_proxy_usdt=92378, book20_ask_proxy_usdt=79392, funding_indicative=0.000050, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.57%, turnover=6599238. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T23:30:00+00:00, last15m_closed_end=2026-10-31T23:30+00:00, prior8high=0.161300, depth_time=2026-10-31T23:30:21+00:00, book20_bid_proxy_usdt=1210490, book20_ask_proxy_usdt=760987, funding_indicative=-0.000217, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=5821566. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T23:30:00+00:00, last15m_closed_end=2026-10-31T23:30+00:00, prior8high=0.017256, depth_time=2026-10-31T23:30:26+00:00, book20_bid_proxy_usdt=15424, book20_ask_proxy_usdt=3828, funding_indicative=0.000095, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.18%, turnover=6159089. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-31T23:30:00+00:00, last15m_closed_end=2026-10-31T23:30+00:00, prior8high=7.312000, depth_time=2026-10-31T23:30:12+00:00, book20_bid_proxy_usdt=600980, book20_ask_proxy_usdt=299629, funding_indicative=0.000092, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.83%, turnover=20614284. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-10-31T23:30:00+00:00, last15m_closed_end=2026-10-31T23:30+00:00, prior8high=0.248800, depth_time=2026-10-31T23:30:08+00:00, book20_bid_proxy_usdt=14175, book20_ask_proxy_usdt=11664, funding_indicative=-0.001116, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=4, 24h_change=-16.70%, turnover=28647825. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T23:30:00+00:00, last15m_closed_end=2026-10-31T23:30+00:00, prior8high=0.032570, depth_time=2026-10-31T23:30:32+00:00, book20_bid_proxy_usdt=58078, book20_ask_proxy_usdt=52595, funding_indicative=-0.001221, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=1, 24h_change=-1.71%, turnover=10587582. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T23:30:00+00:00, last15m_closed_end=2026-10-31T23:30+00:00, prior8high=0.305440, depth_time=2026-10-31T23:30:11+00:00, book20_bid_proxy_usdt=301906, book20_ask_proxy_usdt=171153, funding_indicative=-0.001243, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.55%, turnover=10271756. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T23:30:00+00:00, last15m_closed_end=2026-10-31T23:30+00:00, prior8high=0.400500, depth_time=2026-10-31T23:30:32+00:00, book20_bid_proxy_usdt=3469287, book20_ask_proxy_usdt=3206268, funding_indicative=0.000076, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=34712415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-10-31T23:30:00+00:00, last15m_closed_end=2026-10-31T23:30+00:00, prior8high=1284.960000, depth_time=2026-10-31T23:30:20+00:00, book20_bid_proxy_usdt=245638, book20_ask_proxy_usdt=555868, funding_indicative=-0.000033, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.58%, turnover=1064005231. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
