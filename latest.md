# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T12:45:34Z**
- feed_generated_utc: 2026-10-31T12:45:37+00:00
- source_sha256: `fec51926a5421cbec4b2d7ce88f2505fe5e3d0d1324d77169ebc1a30e645cb99`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T12:45+00:00, close=77535.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011537|-39.02|-67.03|-38.96|11374939|4.34|
|Q_USDT|0.031690|-33.25|-73.22|-33.19|12768958|3.15|
|BTW_USDT|1.096300|-8.60|-35.60|-8.54|8768690|2.73|
|IDOL_USDT|0.019113|-5.57|141.32|-5.51|16128637|0.52|
|BEAT_USDT|0.099740|-5.14|37.40|-5.08|7464812|3.01|
|TRX_USDT|0.318950|-4.93|-3.15|-4.87|6997815|0.31|
|HYPE_USDT|88.409000|-4.26|12.76|-4.20|95714272|0.11|
|WLD_USDT|0.396800|-3.66|-25.46|-3.60|45207104|2.52|
|FET_USDT|0.161000|-3.36|-14.04|-3.30|5989388|6.22|
|DASH_USDT|47.970000|-2.18|-10.91|-2.12|9655615|2.08|
|LTC_USDT|55.040000|-1.22|-5.83|-1.16|6029029|3.63|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011537|0.010466|0.011540|1.43|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.099740|0.100290|0.099880|1.02|N|Y/N|N/N|Y|N|
|BTW_USDT|1.096300|1.120000|1.091700|3.71|Y|N/Y|Y/Y|Y|N|
|DASH_USDT|47.970000|47.700000|47.970000|0.54|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.161000|0.160400|0.161000|13.69|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|88.409000|87.134000|88.404000|1.48|N|Y/Y|N/N|Y|N|
|IDOL_USDT|0.019113|0.018410|0.019113|0.43|N|Y/Y|N/N|Y|N|
|LTC_USDT|55.040000|54.780000|55.060000|1.52|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.031690|0.031390|0.031690|0.75|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.318950|0.316120|0.318710|0.26|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.396800|0.394200|0.396800|1.66|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T12:45:03+00:00, last15m_closed_end=2026-10-31T12:45+00:00, prior8high=0.012080, depth_time=2026-10-31T12:45:08+00:00, book20_bid_proxy_usdt=7568, book20_ask_proxy_usdt=10400, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-39.02%, turnover=11374939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T12:45:04+00:00, last15m_closed_end=2026-10-31T12:45+00:00, prior8high=0.104340, depth_time=2026-10-31T12:45:19+00:00, book20_bid_proxy_usdt=17696, book20_ask_proxy_usdt=15534, funding_indicative=0.000232, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.14%, turnover=7464812. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T12:45:04+00:00, last15m_closed_end=2026-10-31T12:45+00:00, prior8high=1.204600, depth_time=2026-10-31T12:45:13+00:00, book20_bid_proxy_usdt=17353, book20_ask_proxy_usdt=7929, funding_indicative=-0.000255, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.60%, turnover=8768690. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T12:45:04+00:00, last15m_closed_end=2026-10-31T12:45+00:00, prior8high=48.200000, depth_time=2026-10-31T12:45:30+00:00, book20_bid_proxy_usdt=695969, book20_ask_proxy_usdt=571318, funding_indicative=-0.000103, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.18%, turnover=9655615. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T12:45:04+00:00, last15m_closed_end=2026-10-31T12:45+00:00, prior8high=0.162000, depth_time=2026-10-31T12:45:28+00:00, book20_bid_proxy_usdt=1290390, book20_ask_proxy_usdt=972863, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.36%, turnover=5989388. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T12:45:03+00:00, last15m_closed_end=2026-10-31T12:45+00:00, prior8high=88.782000, depth_time=2026-10-31T12:45:23+00:00, book20_bid_proxy_usdt=185283, book20_ask_proxy_usdt=70691, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.26%, turnover=95714272. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T12:45:03+00:00, last15m_closed_end=2026-10-31T12:45+00:00, prior8high=0.019922, depth_time=2026-10-31T12:45:16+00:00, book20_bid_proxy_usdt=7428, book20_ask_proxy_usdt=5298, funding_indicative=0.000259, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.57%, turnover=16128637. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T12:45:04+00:00, last15m_closed_end=2026-10-31T12:45+00:00, prior8high=55.070000, depth_time=2026-10-31T12:45:33+00:00, book20_bid_proxy_usdt=1356217, book20_ask_proxy_usdt=1384281, funding_indicative=-0.000067, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.22%, turnover=6029029. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T12:45:03+00:00, last15m_closed_end=2026-10-31T12:45+00:00, prior8high=0.033250, depth_time=2026-10-31T12:45:11+00:00, book20_bid_proxy_usdt=53931, book20_ask_proxy_usdt=45372, funding_indicative=-0.000510, next_funding_utc=2026-10-31T13:00:00+00:00, funding_cycle_h=1, 24h_change=-33.25%, turnover=12768958. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T12:45:04+00:00, last15m_closed_end=2026-10-31T12:45+00:00, prior8high=0.320970, depth_time=2026-10-31T12:45:21+00:00, book20_bid_proxy_usdt=67294, book20_ask_proxy_usdt=63212, funding_indicative=-0.001002, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.93%, turnover=6997815. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T12:45:04+00:00, last15m_closed_end=2026-10-31T12:45+00:00, prior8high=0.397200, depth_time=2026-10-31T12:45:25+00:00, book20_bid_proxy_usdt=3646121, book20_ask_proxy_usdt=3179467, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.66%, turnover=45207104. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
