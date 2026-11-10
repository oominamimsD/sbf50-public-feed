# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T18:00:30Z**
- feed_generated_utc: 2026-11-10T18:00:32+00:00
- source_sha256: `3a00458bcfb9bb1d5db4edd7e39851b1fdd2a9a024de8f8855833c940111aa89`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T18:00+00:00, close=73253.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T18:00+00:00, close=73253.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.820000|-10.17|54.84|-10.26|9782717|0.55|
|ZEC_USDT|1037.290000|-5.12|-13.83|-5.21|2410661136|0.10|
|DASH_USDT|43.690000|-3.21|-5.30|-3.30|14192438|2.29|
|ARB_USDT|0.156640|-2.93|-2.02|-3.02|39898714|0.64|
|UNI_USDT|6.667000|-2.38|-9.32|-2.47|27541075|3.00|
|JCT_USDT|0.005153|-2.31|23.33|-2.40|23230203|1.94|
|AKE_USDT|0.002864|-1.71|-31.08|-1.80|15854672|3.49|
|HYPE_USDT|70.914000|-1.19|-18.81|-1.28|42708847|0.14|
|ONDO_USDT|0.362100|-1.01|-6.96|-1.10|15690107|2.76|
|TIA_USDT|0.420500|-1.01|-3.51|-1.10|9870275|9.52|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002864|0.002739|0.002864|0.60|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.156640|0.155570|0.156640|0.34|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.690000|42.350000|43.690000|0.86|N|Y/Y|Y/Y|Y|N|
|HYPE_USDT|70.914000|70.375000|70.914000|0.65|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005153|0.004969|0.005151|0.44|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.362100|0.355900|0.362100|0.57|N|Y/Y|Y/N|Y|N|
|PIEVERSE_USDT|1.820000|1.809600|1.820000|1.08|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.420500|0.412300|0.420500|0.28|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.667000|6.621000|6.667000|1.27|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1037.290000|993.710000|1037.410000|0.83|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T17:59:58+00:00, last15m_closed_end=2026-11-10T18:00+00:00, prior8high=0.003336, depth_time=2026-11-10T18:00:22+00:00, book20_bid_proxy_usdt=20425, book20_ask_proxy_usdt=40142, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.71%, turnover=15854672. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T17:59:58+00:00, last15m_closed_end=2026-11-10T18:00+00:00, prior8high=0.162090, depth_time=2026-11-10T18:00:15+00:00, book20_bid_proxy_usdt=85168, book20_ask_proxy_usdt=51637, funding_indicative=-0.000143, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.93%, turnover=39898714. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T17:59:59+00:00, last15m_closed_end=2026-11-10T18:00+00:00, prior8high=45.460000, depth_time=2026-11-10T18:00:12+00:00, book20_bid_proxy_usdt=887225, book20_ask_proxy_usdt=663517, funding_indicative=-0.000089, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.21%, turnover=14192438. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T17:59:58+00:00, last15m_closed_end=2026-11-10T18:00+00:00, prior8high=72.358000, depth_time=2026-11-10T18:00:23+00:00, book20_bid_proxy_usdt=75400, book20_ask_proxy_usdt=78398, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.19%, turnover=42708847. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T17:59:58+00:00, last15m_closed_end=2026-11-10T18:00+00:00, prior8high=0.005891, depth_time=2026-11-10T18:00:20+00:00, book20_bid_proxy_usdt=44073, book20_ask_proxy_usdt=51385, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.31%, turnover=23230203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T17:59:58+00:00, last15m_closed_end=2026-11-10T18:00+00:00, prior8high=0.370400, depth_time=2026-11-10T18:00:21+00:00, book20_bid_proxy_usdt=3850727, book20_ask_proxy_usdt=1929477, funding_indicative=-0.000011, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.01%, turnover=15690107. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T17:59:58+00:00, last15m_closed_end=2026-11-10T18:00+00:00, prior8high=2.065500, depth_time=2026-11-10T18:00:02+00:00, book20_bid_proxy_usdt=16587, book20_ask_proxy_usdt=26068, funding_indicative=0.000122, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-10.17%, turnover=9782717. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-10T17:59:59+00:00, last15m_closed_end=2026-11-10T18:00+00:00, prior8high=0.427500, depth_time=2026-11-10T18:00:29+00:00, book20_bid_proxy_usdt=530950, book20_ask_proxy_usdt=219624, funding_indicative=0.000029, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.01%, turnover=9870275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T17:59:58+00:00, last15m_closed_end=2026-11-10T18:00+00:00, prior8high=6.882000, depth_time=2026-11-10T18:00:16+00:00, book20_bid_proxy_usdt=2754406, book20_ask_proxy_usdt=2496020, funding_indicative=0.000008, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.38%, turnover=27541075. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T17:59:58+00:00, last15m_closed_end=2026-11-10T18:00+00:00, prior8high=1102.710000, depth_time=2026-11-10T18:00:10+00:00, book20_bid_proxy_usdt=334291, book20_ask_proxy_usdt=441103, funding_indicative=-0.000025, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.12%, turnover=2410661136. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
