# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T11:45:37Z**
- feed_generated_utc: 2026-10-31T11:45:39+00:00
- source_sha256: `b209ab5e0fb751d4063d7e84272eca7ad2202f8ef9b9fcc3b91cf57abec8bb76`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T11:45+00:00, close=77556.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T11:00+00:00, close=77376.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T08:00+00:00, close=77316.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011370|-39.90|-67.51|-39.88|10908441|2.63|
|Q_USDT|0.031550|-33.55|-73.33|-33.53|13216096|3.17|
|TRX_USDT|0.320330|-4.52|-2.73|-4.50|7131742|0.94|
|HYPE_USDT|88.240000|-4.44|12.54|-4.42|98394654|0.11|
|BTW_USDT|1.146400|-4.42|-32.65|-4.40|8967491|2.62|
|IDOL_USDT|0.019369|-4.31|144.55|-4.29|16132798|5.17|
|WLD_USDT|0.394800|-4.15|-25.84|-4.13|45984946|2.53|
|BEAT_USDT|0.101330|-3.63|39.59|-3.61|8082310|2.96|
|FET_USDT|0.161300|-3.18|-13.88|-3.16|5883195|6.20|
|DASH_USDT|48.090000|-1.93|-10.69|-1.91|11756716|2.08|
|LTC_USDT|54.890000|-1.48|-6.09|-1.46|6099819|3.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011370|0.010360|0.011370|1.30|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.101330|0.099720|0.101410|0.90|N|N/N|N/N|Y|N|
|BTW_USDT|1.146400|1.118100|1.146400|1.00|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|48.090000|47.700000|48.090000|2.33|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161300|0.160800|0.161300|0.75|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.240000|86.889000|88.287000|1.65|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.019369|0.017952|0.019370|0.55|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.890000|54.750000|54.890000|0.24|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.031550|0.031080|0.031550|1.24|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.320330|0.315970|0.320330|0.57|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.394800|0.394500|0.394800|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T11:45:01+00:00, last15m_closed_end=2026-10-31T11:45+00:00, prior8high=0.011711, depth_time=2026-10-31T11:45:09+00:00, book20_bid_proxy_usdt=12238, book20_ask_proxy_usdt=13359, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-39.90%, turnover=10908441. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T11:45:01+00:00, last15m_closed_end=2026-10-31T11:45+00:00, prior8high=0.104340, depth_time=2026-10-31T11:45:27+00:00, book20_bid_proxy_usdt=10221, book20_ask_proxy_usdt=10240, funding_indicative=0.000252, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.63%, turnover=8082310. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T11:45:01+00:00, last15m_closed_end=2026-10-31T11:45+00:00, prior8high=1.155200, depth_time=2026-10-31T11:45:20+00:00, book20_bid_proxy_usdt=16132, book20_ask_proxy_usdt=12265, funding_indicative=-0.000360, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.42%, turnover=8967491. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T11:45:01+00:00, last15m_closed_end=2026-10-31T11:45+00:00, prior8high=48.060000, depth_time=2026-10-31T11:45:32+00:00, book20_bid_proxy_usdt=720605, book20_ask_proxy_usdt=639413, funding_indicative=-0.000131, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=11756716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T11:45:01+00:00, last15m_closed_end=2026-10-31T11:45+00:00, prior8high=0.162200, depth_time=2026-10-31T11:45:27+00:00, book20_bid_proxy_usdt=1236170, book20_ask_proxy_usdt=957847, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.18%, turnover=5883195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T11:45:01+00:00, last15m_closed_end=2026-10-31T11:45+00:00, prior8high=88.220000, depth_time=2026-10-31T11:45:17+00:00, book20_bid_proxy_usdt=81480, book20_ask_proxy_usdt=96304, funding_indicative=0.000050, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.44%, turnover=98394654. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T11:45:01+00:00, last15m_closed_end=2026-10-31T11:45+00:00, prior8high=0.019922, depth_time=2026-10-31T11:45:22+00:00, book20_bid_proxy_usdt=6612, book20_ask_proxy_usdt=6369, funding_indicative=0.000273, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.31%, turnover=16132798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T11:45:01+00:00, last15m_closed_end=2026-10-31T11:45+00:00, prior8high=55.070000, depth_time=2026-10-31T11:45:34+00:00, book20_bid_proxy_usdt=1383700, book20_ask_proxy_usdt=1400450, funding_indicative=-0.000057, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=6099819. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T11:45:01+00:00, last15m_closed_end=2026-10-31T11:45+00:00, prior8high=0.033470, depth_time=2026-10-31T11:45:12+00:00, book20_bid_proxy_usdt=55360, book20_ask_proxy_usdt=46685, funding_indicative=-0.000600, next_funding_utc=2026-10-31T12:00:00+00:00, funding_cycle_h=1, 24h_change=-33.55%, turnover=13216096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T11:45:01+00:00, last15m_closed_end=2026-10-31T11:45+00:00, prior8high=0.320970, depth_time=2026-10-31T11:45:13+00:00, book20_bid_proxy_usdt=52292, book20_ask_proxy_usdt=100810, funding_indicative=-0.001089, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.52%, turnover=7131742. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T11:45:01+00:00, last15m_closed_end=2026-10-31T11:45+00:00, prior8high=0.398300, depth_time=2026-10-31T11:45:25+00:00, book20_bid_proxy_usdt=2766783, book20_ask_proxy_usdt=3547106, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.15%, turnover=45984946. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
