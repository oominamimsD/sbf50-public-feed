# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T23:30:24Z**
- feed_generated_utc: 2026-11-10T23:30:26+00:00
- source_sha256: `7e3a1b8879dde617d5ea95c7e451133c7cd866fccc51acb54fd1e8ea83bfd74a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T23:30+00:00, close=73647.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T23:00+00:00, close=73666.5, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.216310|-13.80|60.84|-14.43|52938915|2.31|
|PIEVERSE_USDT|1.848800|-8.75|57.29|-9.38|5483337|0.54|
|DASH_USDT|42.640000|-5.53|-7.58|-6.16|14068879|2.35|
|ZEC_USDT|1041.680000|-4.72|-13.46|-5.35|2232882156|0.19|
|UNI_USDT|6.661000|-2.47|-9.41|-3.10|31691782|1.50|
|JCT_USDT|0.005194|-1.53|24.31|-2.16|19151543|1.92|
|JUP_USDT|0.251100|-0.82|0.80|-1.45|5471301|3.98|
|HBAR_USDT|0.065280|-0.76|-6.78|-1.39|8911732|1.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DASH_USDT|42.640000|42.400000|42.640000|0.88|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.065280|0.065190|0.065280|1.93|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.216310|0.183240|0.216310|0.42|N|Y/Y|N/N|Y|N|
|JCT_USDT|0.005194|0.005119|0.005194|0.28|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.251100|0.249200|0.251100|0.95|N|Y/Y|N/N|Y|N|
|PIEVERSE_USDT|1.848800|1.828700|1.848800|0.66|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.661000|6.611000|6.661000|0.96|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1041.680000|1030.550000|1041.590000|0.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- DASH_USDT: quote_utc=2026-11-10T23:29:59+00:00, last15m_closed_end=2026-11-10T23:30+00:00, prior8high=43.460000, depth_time=2026-11-10T23:30:11+00:00, book20_bid_proxy_usdt=805152, book20_ask_proxy_usdt=779149, funding_indicative=-0.000172, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.53%, turnover=14068879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T23:29:59+00:00, last15m_closed_end=2026-11-10T23:30+00:00, prior8high=0.066260, depth_time=2026-11-10T23:30:23+00:00, book20_bid_proxy_usdt=572630, book20_ask_proxy_usdt=736592, funding_indicative=0.000038, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.76%, turnover=8911732. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-10T23:29:59+00:00, last15m_closed_end=2026-11-10T23:30+00:00, prior8high=0.233780, depth_time=2026-11-10T23:30:07+00:00, book20_bid_proxy_usdt=14109, book20_ask_proxy_usdt=16149, funding_indicative=-0.018531, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=1, 24h_change=-13.80%, turnover=52938915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T23:29:59+00:00, last15m_closed_end=2026-11-10T23:30+00:00, prior8high=0.005437, depth_time=2026-11-10T23:30:19+00:00, book20_bid_proxy_usdt=57355, book20_ask_proxy_usdt=58327, funding_indicative=0.000548, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=19151543. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-11-10T23:29:59+00:00, last15m_closed_end=2026-11-10T23:30+00:00, prior8high=0.256900, depth_time=2026-11-10T23:30:21+00:00, book20_bid_proxy_usdt=613705, book20_ask_proxy_usdt=564826, funding_indicative=-0.000017, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.82%, turnover=5471301. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T23:29:59+00:00, last15m_closed_end=2026-11-10T23:30+00:00, prior8high=1.858500, depth_time=2026-11-10T23:30:06+00:00, book20_bid_proxy_usdt=17637, book20_ask_proxy_usdt=15547, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.75%, turnover=5483337. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T23:29:59+00:00, last15m_closed_end=2026-11-10T23:30+00:00, prior8high=6.769000, depth_time=2026-11-10T23:30:13+00:00, book20_bid_proxy_usdt=2483513, book20_ask_proxy_usdt=3000351, funding_indicative=-0.000015, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=31691782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T23:29:59+00:00, last15m_closed_end=2026-11-10T23:30+00:00, prior8high=1069.190000, depth_time=2026-11-10T23:30:14+00:00, book20_bid_proxy_usdt=150324, book20_ask_proxy_usdt=262658, funding_indicative=0.000018, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.72%, turnover=2232882156. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
