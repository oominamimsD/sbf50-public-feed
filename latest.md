# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T06:15:40Z**
- feed_generated_utc: 2026-10-20T06:15:42+00:00
- source_sha256: `788b8a2321538f85ddbccc9160243f8872a8fd5ba86e8849358fb005cde82ec1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T06:15+00:00, close=81611.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T06:00+00:00, close=81684.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CT_USDT|0.306380|-7.18|-10.44|-6.82|5427006|2.29|
|Q_USDT|0.121020|-3.94|293.03|-3.58|9396012|3.39|
|SAND_USDT|0.056840|-3.88|-8.45|-3.52|8160717|1.76|
|ZRO_USDT|1.828800|-3.84|-19.11|-3.48|7538916|0.55|
|NEAR_USDT|4.749000|-3.16|-14.41|-2.80|167166469|2.10|
|UNI_USDT|7.124000|-2.25|-3.96|-1.89|10050279|1.40|
|QNT_USDT|191.420000|-2.18|-16.18|-1.82|82084032|0.52|
|PUMPFUN_USDT|0.004370|-1.92|-17.68|-1.56|29843429|2.29|
|BTW_USDT|1.720800|-1.78|-1.99|-1.42|30085253|1.75|
|ATOM_USDT|1.745000|-1.74|-4.54|-1.38|5184164|5.73|
|TAO_USDT|263.900000|-1.63|-7.82|-1.27|53141939|1.14|
|DOT_USDT|1.128500|-1.59|-8.72|-1.23|19176049|0.89|
|SEI_USDT|0.059760|-1.49|-9.95|-1.13|6893143|3.35|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ATOM_USDT|1.745000|1.748000|1.745000|2.86|Y|N/N|N/N|Y|N|
|BTW_USDT|1.720800|1.675200|1.723100|1.41|N|Y/Y|Y/Y|Y|N|
|CT_USDT|0.306380|0.302430|0.306390|0.94|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|1.128500|1.129000|1.128500|0.86|N|Y/N|N/N|Y|N|
|NEAR_USDT|4.749000|4.765000|4.751000|1.07|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004370|0.004375|0.004367|1.54|Y|Y/N|N/N|Y|N|
|QNT_USDT|191.420000|192.190000|191.370000|1.55|Y|Y/Y|N/Y|Y|N|
|Q_USDT|0.121020|0.110142|0.121020|4.08|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.056840|0.056650|0.056840|0.36|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.059760|0.059930|0.059770|2.54|Y|Y/N|Y/Y|Y|N|
|TAO_USDT|263.900000|264.470000|263.930000|2.26|Y|Y/Y|Y/Y|Y|Y|
|UNI_USDT|7.124000|7.199000|7.125000|1.15|N|Y/Y|N/N|Y|N|
|ZRO_USDT|1.828800|1.841400|1.828800|1.07|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ATOM_USDT: quote_utc=2026-10-20T06:15:01+00:00, last15m_closed_end=2026-10-20T06:15+00:00, prior8high=1.774000, depth_time=2026-10-20T06:15:29+00:00, book20_bid_proxy_usdt=1333622, book20_ask_proxy_usdt=1426329, funding_indicative=0.000089, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.74%, turnover=5184164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T06:15:01+00:00, last15m_closed_end=2026-10-20T06:15+00:00, prior8high=1.923700, depth_time=2026-10-20T06:15:29+00:00, book20_bid_proxy_usdt=8449, book20_ask_proxy_usdt=9494, funding_indicative=-0.003683, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=30085253. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CT_USDT: quote_utc=2026-10-20T06:15:01+00:00, last15m_closed_end=2026-10-20T06:15+00:00, prior8high=0.328090, depth_time=2026-10-20T06:15:07+00:00, book20_bid_proxy_usdt=9461, book20_ask_proxy_usdt=11034, funding_indicative=-0.002586, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.18%, turnover=5427006. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-20T06:15:01+00:00, last15m_closed_end=2026-10-20T06:15+00:00, prior8high=1.158300, depth_time=2026-10-20T06:15:36+00:00, book20_bid_proxy_usdt=331770, book20_ask_proxy_usdt=285661, funding_indicative=0.000036, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=19176049. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T06:15:01+00:00, last15m_closed_end=2026-10-20T06:15+00:00, prior8high=4.872000, depth_time=2026-10-20T06:15:19+00:00, book20_bid_proxy_usdt=2424625, book20_ask_proxy_usdt=2884992, funding_indicative=-0.000011, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.16%, turnover=167166469. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-20T06:15:01+00:00, last15m_closed_end=2026-10-20T06:15+00:00, prior8high=0.004489, depth_time=2026-10-20T06:15:26+00:00, book20_bid_proxy_usdt=1144538, book20_ask_proxy_usdt=1466978, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.92%, turnover=29843429. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T06:15:01+00:00, last15m_closed_end=2026-10-20T06:15+00:00, prior8high=198.680000, depth_time=2026-10-20T06:15:22+00:00, book20_bid_proxy_usdt=82736, book20_ask_proxy_usdt=83618, funding_indicative=0.000000, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=82084032. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T06:15:01+00:00, last15m_closed_end=2026-10-20T06:15+00:00, prior8high=0.133766, depth_time=2026-10-20T06:15:11+00:00, book20_bid_proxy_usdt=14516, book20_ask_proxy_usdt=15824, funding_indicative=-0.000238, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.94%, turnover=9396012. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T06:15:01+00:00, last15m_closed_end=2026-10-20T06:15+00:00, prior8high=0.058160, depth_time=2026-10-20T06:15:13+00:00, book20_bid_proxy_usdt=699918, book20_ask_proxy_usdt=998553, funding_indicative=-0.001739, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.88%, turnover=8160717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T06:15:01+00:00, last15m_closed_end=2026-10-20T06:15+00:00, prior8high=0.061300, depth_time=2026-10-20T06:15:38+00:00, book20_bid_proxy_usdt=239462, book20_ask_proxy_usdt=340779, funding_indicative=0.000037, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.49%, turnover=6893143. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T06:15:01+00:00, last15m_closed_end=2026-10-20T06:15+00:00, prior8high=269.040000, depth_time=2026-10-20T06:15:34+00:00, book20_bid_proxy_usdt=88036, book20_ask_proxy_usdt=89288, funding_indicative=0.000035, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.63%, turnover=53141939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T06:15:01+00:00, last15m_closed_end=2026-10-20T06:15+00:00, prior8high=7.340000, depth_time=2026-10-20T06:15:21+00:00, book20_bid_proxy_usdt=1324958, book20_ask_proxy_usdt=2050264, funding_indicative=0.000019, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.25%, turnover=10050279. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T06:15:01+00:00, last15m_closed_end=2026-10-20T06:15+00:00, prior8high=1.880400, depth_time=2026-10-20T06:15:16+00:00, book20_bid_proxy_usdt=47747, book20_ask_proxy_usdt=41803, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.84%, turnover=7538916. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
