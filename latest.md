# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T21:30:41Z**
- feed_generated_utc: 2026-11-10T21:30:42+00:00
- source_sha256: `758b57dbc3b194acc78f197fe5bdf47a2e153f5c40b2abb6150254312f550744`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T21:30+00:00, close=73943.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T21:00+00:00, close=73756.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.207130|-17.45|54.02|-18.49|48241923|5.31|
|PIEVERSE_USDT|1.837800|-9.29|56.35|-10.33|6136665|2.18|
|DASH_USDT|42.900000|-4.96|-7.02|-6.00|13690606|2.33|
|AKE_USDT|0.002825|-3.05|-32.02|-4.09|15773133|3.55|
|ZEC_USDT|1061.010000|-2.95|-11.86|-3.99|2265334414|0.09|
|UNI_USDT|6.685000|-2.12|-9.08|-3.16|30113338|1.50|
|ARB_USDT|0.158370|-1.86|-0.94|-2.90|34453061|0.63|
|ANTHROPIC_USDT|1300.160000|-1.31|-22.33|-2.35|8260374|1.85|
|DOT_USDT|0.836600|-0.60|-11.24|-1.64|8973741|2.39|
|WLD_USDT|0.306500|-0.51|-17.62|-1.55|29504866|3.26|
|TIA_USDT|0.422900|-0.44|-2.96|-1.48|9496067|2.36|
|NEAR_USDT|3.547000|-0.39|-8.08|-1.43|35350387|2.82|
|XAU_USDT|4035.460000|-0.34|2.29|-1.38|516873991|0.03|
|ENA_USDT|0.148780|-0.27|-13.59|-1.31|31971487|0.67|
|XAUT_USDT|4018.870000|-0.25|2.26|-1.29|113449904|0.07|
|ONDO_USDT|0.365300|-0.13|-6.14|-1.17|15111015|2.74|
|SILVER_USDT|51.580000|-0.09|3.20|-1.13|269835397|1.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002825|0.002773|0.002825|0.61|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1300.160000|1292.100000|1300.160000|0.32|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.158370|0.158120|0.158370|1.21|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.900000|42.550000|42.900000|1.49|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.836600|0.831500|0.836700|1.11|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.148780|0.147450|0.148780|0.63|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.207130|0.202000|0.207130|1.24|N|Y/N|N/N|Y|N|
|NEAR_USDT|3.547000|3.545000|3.547000|0.97|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.837800|1.782100|1.837800|0.84|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.422900|0.418400|0.423000|1.47|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.685000|6.649000|6.685000|0.51|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.306500|0.304400|0.306500|0.58|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4018.870000|4015.640000|4018.870000|0.04|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4035.460000|4031.330000|4035.460000|0.47|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1061.010000|1020.790000|1061.010000|0.75|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=0.002911, depth_time=2026-11-10T21:30:12+00:00, book20_bid_proxy_usdt=39176, book20_ask_proxy_usdt=42011, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=15773133. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=1308.680000, depth_time=2026-11-10T21:30:23+00:00, book20_bid_proxy_usdt=13346, book20_ask_proxy_usdt=21335, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.31%, turnover=8260374. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=0.160720, depth_time=2026-11-10T21:30:21+00:00, book20_bid_proxy_usdt=90501, book20_ask_proxy_usdt=86268, funding_indicative=-0.000224, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=34453061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=43.290000, depth_time=2026-11-10T21:30:11+00:00, book20_bid_proxy_usdt=800576, book20_ask_proxy_usdt=754476, funding_indicative=-0.000203, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-4.96%, turnover=13690606. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=0.842400, depth_time=2026-11-10T21:30:25+00:00, book20_bid_proxy_usdt=802811, book20_ask_proxy_usdt=453671, funding_indicative=0.000068, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.60%, turnover=8973741. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=0.149840, depth_time=2026-11-10T21:30:37+00:00, book20_bid_proxy_usdt=409787, book20_ask_proxy_usdt=281383, funding_indicative=0.000032, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.27%, turnover=31971487. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=0.285840, depth_time=2026-11-10T21:30:07+00:00, book20_bid_proxy_usdt=18380, book20_ask_proxy_usdt=25711, funding_indicative=-0.020000, next_funding_utc=2026-11-10T22:00:00+00:00, funding_cycle_h=1, 24h_change=-17.45%, turnover=48241923. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=3.600000, depth_time=2026-11-10T21:30:32+00:00, book20_bid_proxy_usdt=2984670, book20_ask_proxy_usdt=2664294, funding_indicative=0.000100, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.39%, turnover=35350387. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=1.854900, depth_time=2026-11-10T21:30:09+00:00, book20_bid_proxy_usdt=30746, book20_ask_proxy_usdt=20246, funding_indicative=0.000183, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.29%, turnover=6136665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=0.429600, depth_time=2026-11-10T21:30:30+00:00, book20_bid_proxy_usdt=426470, book20_ask_proxy_usdt=451440, funding_indicative=0.000002, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.44%, turnover=9496067. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=6.774000, depth_time=2026-11-10T21:30:18+00:00, book20_bid_proxy_usdt=2589466, book20_ask_proxy_usdt=2970136, funding_indicative=-0.000027, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.12%, turnover=30113338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=0.310100, depth_time=2026-11-10T21:30:26+00:00, book20_bid_proxy_usdt=5407060, book20_ask_proxy_usdt=5370419, funding_indicative=-0.000027, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.51%, turnover=29504866. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=4026.090000, depth_time=2026-11-10T21:30:37+00:00, book20_bid_proxy_usdt=104356, book20_ask_proxy_usdt=137621, funding_indicative=0.000080, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.25%, turnover=113449904. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=4043.650000, depth_time=2026-11-10T21:30:33+00:00, book20_bid_proxy_usdt=1065810, book20_ask_proxy_usdt=189399, funding_indicative=0.000103, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.34%, turnover=516873991. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T21:30:00+00:00, last15m_closed_end=2026-11-10T21:30+00:00, prior8high=1058.990000, depth_time=2026-11-10T21:30:16+00:00, book20_bid_proxy_usdt=287799, book20_ask_proxy_usdt=277526, funding_indicative=0.000011, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.95%, turnover=2265334414. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
