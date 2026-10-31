# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T12:00:33Z**
- feed_generated_utc: 2026-10-31T12:00:36+00:00
- source_sha256: `ca4eb866533dc9ad1baa6a598c71155b897e99588862438111d28a767a5e7450`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T12:00+00:00, close=77577.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011594|-39.69|-66.87|-39.69|10881767|6.06|
|Q_USDT|0.031950|-32.70|-73.00|-32.70|12659951|6.26|
|HYPE_USDT|87.545000|-5.19|11.65|-5.19|93104121|0.11|
|TRX_USDT|0.320190|-4.82|-2.77|-4.82|6789848|0.31|
|BEAT_USDT|0.100610|-4.31|38.60|-4.31|7313549|2.98|
|FET_USDT|0.160900|-2.54|-14.09|-2.54|5585023|6.22|
|WLD_USDT|0.395500|-1.98|-25.71|-1.98|44273809|2.53|
|DASH_USDT|48.100000|-1.91|-10.67|-1.91|9596452|2.08|
|DOT_USDT|0.953500|-1.61|-15.37|-1.61|8650990|1.05|
|ARB_USDT|0.160950|-1.59|-10.54|-1.59|17533963|0.62|
|LTC_USDT|54.850000|-1.56|-6.15|-1.56|5961110|3.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011594|0.010360|0.011594|0.62|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.160950|0.160560|0.160950|0.39|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.100610|0.100240|0.100530|0.56|N|Y/N|N/N|Y|N|
|DASH_USDT|48.100000|47.700000|48.090000|0.28|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.953500|0.954000|0.953800|0.85|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.160900|0.160800|0.160900|1.24|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|87.545000|86.889000|87.557000|2.27|N|Y/Y|N/N|Y|N|
|LTC_USDT|54.850000|54.750000|54.840000|0.14|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.031950|0.031080|0.032030|1.00|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.320190|0.315970|0.320190|0.31|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.395500|0.394200|0.395500|0.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T12:00:03+00:00, last15m_closed_end=2026-10-31T12:00+00:00, prior8high=0.011724, depth_time=2026-10-31T12:00:08+00:00, book20_bid_proxy_usdt=5192, book20_ask_proxy_usdt=9064, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-39.69%, turnover=10881767. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-10-31T12:00:03+00:00, last15m_closed_end=2026-10-31T12:00+00:00, prior8high=0.161910, depth_time=2026-10-31T12:00:30+00:00, book20_bid_proxy_usdt=86404, book20_ask_proxy_usdt=64850, funding_indicative=0.000030, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=17533963. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T12:00:03+00:00, last15m_closed_end=2026-10-31T12:00+00:00, prior8high=0.104340, depth_time=2026-10-31T12:00:18+00:00, book20_bid_proxy_usdt=11525, book20_ask_proxy_usdt=9448, funding_indicative=0.000239, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.31%, turnover=7313549. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-31T12:00:03+00:00, last15m_closed_end=2026-10-31T12:00+00:00, prior8high=48.130000, depth_time=2026-10-31T12:00:25+00:00, book20_bid_proxy_usdt=670226, book20_ask_proxy_usdt=697365, funding_indicative=-0.000136, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.91%, turnover=9596452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-31T12:00:03+00:00, last15m_closed_end=2026-10-31T12:00+00:00, prior8high=0.959100, depth_time=2026-10-31T12:00:27+00:00, book20_bid_proxy_usdt=493907, book20_ask_proxy_usdt=419532, funding_indicative=-0.000028, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.61%, turnover=8650990. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-31T12:00:03+00:00, last15m_closed_end=2026-10-31T12:00+00:00, prior8high=0.162000, depth_time=2026-10-31T12:00:20+00:00, book20_bid_proxy_usdt=1309692, book20_ask_proxy_usdt=1117434, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.54%, turnover=5585023. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T12:00:03+00:00, last15m_closed_end=2026-10-31T12:00+00:00, prior8high=88.591000, depth_time=2026-10-31T12:00:13+00:00, book20_bid_proxy_usdt=82782, book20_ask_proxy_usdt=60781, funding_indicative=0.000050, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.19%, turnover=93104121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-31T12:00:03+00:00, last15m_closed_end=2026-10-31T12:00+00:00, prior8high=55.070000, depth_time=2026-10-31T12:00:32+00:00, book20_bid_proxy_usdt=1278699, book20_ask_proxy_usdt=1208979, funding_indicative=-0.000061, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=5961110. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T12:00:03+00:00, last15m_closed_end=2026-10-31T12:00+00:00, prior8high=0.033250, depth_time=2026-10-31T12:00:11+00:00, book20_bid_proxy_usdt=44434, book20_ask_proxy_usdt=71785, funding_indicative=-0.000587, next_funding_utc=2026-10-31T13:00:00+00:00, funding_cycle_h=1, 24h_change=-32.70%, turnover=12659951. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T12:00:03+00:00, last15m_closed_end=2026-10-31T12:00+00:00, prior8high=0.320970, depth_time=2026-10-31T12:00:16+00:00, book20_bid_proxy_usdt=71990, book20_ask_proxy_usdt=49536, funding_indicative=-0.001049, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.82%, turnover=6789848. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-31T12:00:03+00:00, last15m_closed_end=2026-10-31T12:00+00:00, prior8high=0.397700, depth_time=2026-10-31T12:00:23+00:00, book20_bid_proxy_usdt=3345912, book20_ask_proxy_usdt=2508553, funding_indicative=0.000100, next_funding_utc=2026-10-31T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.98%, turnover=44273809. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
