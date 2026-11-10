# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T20:30:32Z**
- feed_generated_utc: 2026-11-10T20:30:33+00:00
- source_sha256: `eea04d22e437ee66351e30c01f9945f15fb05d9eb08bc7e43c704b45ff0238c2`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T20:30+00:00, close=73642.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.805900|-10.86|53.64|-11.49|6999330|3.32|
|ZEC_USDT|1037.840000|-5.07|-13.78|-5.70|2303304278|0.10|
|DASH_USDT|42.880000|-5.00|-7.06|-5.63|13508930|2.33|
|JCT_USDT|0.005164|-2.10|23.59|-2.73|20789053|3.87|
|UNI_USDT|6.720000|-1.61|-8.60|-2.24|29421982|1.49|
|ANTHROPIC_USDT|1300.900000|-1.26|-22.28|-1.89|8125304|0.85|
|ARB_USDT|0.159370|-1.24|-0.31|-1.87|34311655|0.63|
|AKE_USDT|0.002886|-0.96|-30.55|-1.59|15868047|3.47|
|DOT_USDT|0.834400|-0.86|-11.47|-1.49|8762809|1.20|
|ENA_USDT|0.148620|-0.38|-13.68|-1.01|30521550|0.67|
|ONDO_USDT|0.364400|-0.38|-6.37|-1.01|14777069|2.74|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002886|0.002801|0.002886|0.30|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1300.900000|1285.250000|1300.950000|1.66|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.159370|0.156260|0.159370|2.20|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.880000|42.600000|42.880000|0.66|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.834400|0.832700|0.834400|0.62|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.148620|0.147450|0.148620|0.98|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.005164|0.005022|0.005164|0.34|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.364400|0.358400|0.364600|0.56|N|Y/Y|Y/Y|Y|N|
|PIEVERSE_USDT|1.805900|1.804700|1.805900|1.02|N|Y/Y|N/N|Y|N|
|UNI_USDT|6.720000|6.649000|6.720000|0.58|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1037.840000|1020.790000|1037.880000|0.75|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T20:29:59+00:00, last15m_closed_end=2026-11-10T20:30+00:00, prior8high=0.002942, depth_time=2026-11-10T20:30:23+00:00, book20_bid_proxy_usdt=42301, book20_ask_proxy_usdt=52169, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=15868047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T20:29:59+00:00, last15m_closed_end=2026-11-10T20:30+00:00, prior8high=1301.800000, depth_time=2026-11-10T20:30:19+00:00, book20_bid_proxy_usdt=8762, book20_ask_proxy_usdt=6542, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.26%, turnover=8125304. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T20:29:59+00:00, last15m_closed_end=2026-11-10T20:30+00:00, prior8high=0.160720, depth_time=2026-11-10T20:30:20+00:00, book20_bid_proxy_usdt=79562, book20_ask_proxy_usdt=75626, funding_indicative=-0.000191, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.24%, turnover=34311655. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T20:29:59+00:00, last15m_closed_end=2026-11-10T20:30+00:00, prior8high=43.620000, depth_time=2026-11-10T20:30:08+00:00, book20_bid_proxy_usdt=656574, book20_ask_proxy_usdt=717048, funding_indicative=-0.000170, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.00%, turnover=13508930. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T20:29:59+00:00, last15m_closed_end=2026-11-10T20:30+00:00, prior8high=0.845000, depth_time=2026-11-10T20:30:25+00:00, book20_bid_proxy_usdt=552645, book20_ask_proxy_usdt=545594, funding_indicative=-0.000020, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=8762809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-10T20:29:59+00:00, last15m_closed_end=2026-11-10T20:30+00:00, prior8high=0.150710, depth_time=2026-11-10T20:30:28+00:00, book20_bid_proxy_usdt=174868, book20_ask_proxy_usdt=184268, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.38%, turnover=30521550. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T20:29:59+00:00, last15m_closed_end=2026-11-10T20:30+00:00, prior8high=0.005277, depth_time=2026-11-10T20:30:14+00:00, book20_bid_proxy_usdt=63180, book20_ask_proxy_usdt=34403, funding_indicative=0.000171, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.10%, turnover=20789053. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T20:29:59+00:00, last15m_closed_end=2026-11-10T20:30+00:00, prior8high=0.364800, depth_time=2026-11-10T20:30:31+00:00, book20_bid_proxy_usdt=2786158, book20_ask_proxy_usdt=2869339, funding_indicative=-0.000006, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.38%, turnover=14777069. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T20:29:59+00:00, last15m_closed_end=2026-11-10T20:30+00:00, prior8high=1.873800, depth_time=2026-11-10T20:30:07+00:00, book20_bid_proxy_usdt=15325, book20_ask_proxy_usdt=12976, funding_indicative=0.000169, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-10.86%, turnover=6999330. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T20:29:59+00:00, last15m_closed_end=2026-11-10T20:30+00:00, prior8high=6.745000, depth_time=2026-11-10T20:30:16+00:00, book20_bid_proxy_usdt=2701158, book20_ask_proxy_usdt=1597190, funding_indicative=-0.000005, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.61%, turnover=29421982. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T20:29:59+00:00, last15m_closed_end=2026-11-10T20:30+00:00, prior8high=1044.410000, depth_time=2026-11-10T20:30:09+00:00, book20_bid_proxy_usdt=119804, book20_ask_proxy_usdt=111148, funding_indicative=0.000014, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.07%, turnover=2303304278. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
