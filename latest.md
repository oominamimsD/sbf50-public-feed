# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T09:45:34Z**
- feed_generated_utc: 2026-10-20T09:45:37+00:00
- source_sha256: `3e7b24f20594d419fad9a34b9cbe0f16b9365926fc5b50cc4a9e6ebadec52d4b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T09:45+00:00, close=81379.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T09:00+00:00, close=81498.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.068959|-20.77|313.86|-20.10|9838368|1.01|
|BTW_USDT|1.624600|-7.27|-7.47|-6.60|33885178|1.23|
|SAND_USDT|0.056400|-4.63|-9.16|-3.96|5856669|1.77|
|NEAR_USDT|4.705000|-4.05|-15.20|-3.38|170582641|2.12|
|ATOM_USDT|1.714000|-3.49|-6.23|-2.82|5205558|5.83|
|ARB_USDT|0.189350|-3.21|0.46|-2.54|96096868|0.53|
|Q_USDT|0.122490|-2.77|297.81|-2.10|6566451|4.08|
|UNI_USDT|7.111000|-2.42|-4.13|-1.75|10307447|1.41|
|TAO_USDT|262.270000|-2.24|-8.39|-1.57|59204132|1.14|
|QNT_USDT|192.230000|-1.77|-15.82|-1.10|81036996|0.52|
|SEI_USDT|0.059620|-1.73|-10.17|-1.06|6751645|1.68|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.068959|0.066550|0.068951|2.30|N|Y/Y|N/N|Y|N|
|ARB_USDT|0.189350|0.188850|0.189350|0.27|N|Y/Y|N/N|Y|N|
|ATOM_USDT|1.714000|1.717000|1.714000|0.84|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.624600|1.486000|1.624000|1.70|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.705000|4.708000|4.706000|8.93|Y|Y/Y|Y/Y|Y|Y|
|QNT_USDT|192.230000|189.730000|192.230000|0.63|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.122490|0.118441|0.122450|2.32|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.056400|0.056360|0.056400|1.23|N|Y/Y|Y/Y|Y|N|
|SEI_USDT|0.059620|0.059530|0.059620|0.75|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|262.270000|261.940000|262.300000|0.88|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.111000|7.099000|7.111000|0.49|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-20T09:45:01+00:00, last15m_closed_end=2026-10-20T09:45+00:00, prior8high=0.078229, depth_time=2026-10-20T09:45:08+00:00, book20_bid_proxy_usdt=9519, book20_ask_proxy_usdt=11164, funding_indicative=0.000047, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-20.77%, turnover=9838368. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-20T09:45:01+00:00, last15m_closed_end=2026-10-20T09:45+00:00, prior8high=0.194000, depth_time=2026-10-20T09:45:20+00:00, book20_bid_proxy_usdt=83184, book20_ask_proxy_usdt=124558, funding_indicative=0.000078, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=96096868. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ATOM_USDT: quote_utc=2026-10-20T09:45:02+00:00, last15m_closed_end=2026-10-20T09:45+00:00, prior8high=1.743000, depth_time=2026-10-20T09:45:17+00:00, book20_bid_proxy_usdt=1544916, book20_ask_proxy_usdt=1387422, funding_indicative=0.000088, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.49%, turnover=5205558. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T09:45:01+00:00, last15m_closed_end=2026-10-20T09:45+00:00, prior8high=1.673600, depth_time=2026-10-20T09:45:11+00:00, book20_bid_proxy_usdt=15531, book20_ask_proxy_usdt=9722, funding_indicative=-0.004197, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.27%, turnover=33885178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T09:45:01+00:00, last15m_closed_end=2026-10-20T09:45+00:00, prior8high=4.799000, depth_time=2026-10-20T09:45:15+00:00, book20_bid_proxy_usdt=4912150, book20_ask_proxy_usdt=3579397, funding_indicative=0.000047, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.05%, turnover=170582641. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T09:45:01+00:00, last15m_closed_end=2026-10-20T09:45+00:00, prior8high=192.610000, depth_time=2026-10-20T09:45:31+00:00, book20_bid_proxy_usdt=110271, book20_ask_proxy_usdt=81047, funding_indicative=0.000049, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=81036996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T09:45:01+00:00, last15m_closed_end=2026-10-20T09:45+00:00, prior8high=0.126849, depth_time=2026-10-20T09:45:22+00:00, book20_bid_proxy_usdt=14589, book20_ask_proxy_usdt=25057, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.77%, turnover=6566451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T09:45:02+00:00, last15m_closed_end=2026-10-20T09:45+00:00, prior8high=0.056910, depth_time=2026-10-20T09:45:12+00:00, book20_bid_proxy_usdt=706104, book20_ask_proxy_usdt=967483, funding_indicative=-0.001534, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.63%, turnover=5856669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-10-20T09:45:02+00:00, last15m_closed_end=2026-10-20T09:45+00:00, prior8high=0.060250, depth_time=2026-10-20T09:45:29+00:00, book20_bid_proxy_usdt=518026, book20_ask_proxy_usdt=221650, funding_indicative=0.000008, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.73%, turnover=6751645. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T09:45:01+00:00, last15m_closed_end=2026-10-20T09:45+00:00, prior8high=264.550000, depth_time=2026-10-20T09:45:28+00:00, book20_bid_proxy_usdt=125116, book20_ask_proxy_usdt=176769, funding_indicative=0.000043, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.24%, turnover=59204132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T09:45:01+00:00, last15m_closed_end=2026-10-20T09:45+00:00, prior8high=7.196000, depth_time=2026-10-20T09:45:25+00:00, book20_bid_proxy_usdt=1979118, book20_ask_proxy_usdt=1994407, funding_indicative=0.000078, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.42%, turnover=10307447. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
