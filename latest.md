# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T22:15:31Z**
- feed_generated_utc: 2026-11-10T22:15:32+00:00
- source_sha256: `645e9081ae4711588f6582a2b85ac8c69ceec7dffaae359cafafbfb121475b0c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 60/60 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 11; crypto_deep: 11
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T22:15+00:00, close=73891.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-10T22:00+00:00, close=73819.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T20:00+00:00, close=73437.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|INIT_USDT|0.201580|-19.67|49.89|-20.64|49967705|7.44|
|PIEVERSE_USDT|1.842700|-9.05|56.77|-10.02|5727693|1.63|
|DASH_USDT|43.340000|-3.98|-6.06|-4.95|14013039|2.31|
|ZEC_USDT|1060.810000|-2.97|-11.87|-3.94|2224678259|0.09|
|JCT_USDT|0.005173|-1.93|23.81|-2.90|19697072|1.93|
|UNI_USDT|6.763000|-0.98|-8.02|-1.95|30575864|1.48|
|JUP_USDT|0.250700|-0.98|0.64|-1.95|5486150|3.99|
|ARB_USDT|0.160560|-0.50|0.42|-1.47|33713665|0.62|
|XAU_USDT|4040.820000|-0.20|2.42|-1.17|511094033|0.03|
|XAUT_USDT|4024.500000|-0.11|2.41|-1.08|113350721|0.07|
|SILVER_USDT|51.600000|-0.05|3.24|-1.02|267900692|1.94|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.160560|0.158120|0.160560|1.15|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|43.340000|42.550000|43.340000|1.10|N|Y/Y|Y/Y|Y|N|
|INIT_USDT|0.201580|0.202000|0.201610|1.61|Y|Y/N|N/N|Y|N|
|JCT_USDT|0.005173|0.005131|0.005173|1.02|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.250700|0.249400|0.250700|0.24|N|Y/N|N/N|Y|N|
|PIEVERSE_USDT|1.842700|1.782100|1.842700|0.36|N|Y/Y|N/N|Y|N|
|SILVER_USDT|51.600000|51.450000|51.600000|0.29|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.763000|6.670000|6.763000|0.69|N|Y/Y|Y/Y|Y|N|
|XAUT_USDT|4024.500000|4016.750000|4024.500000|6.34|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4040.820000|4032.570000|4040.820000|0.66|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1060.810000|1025.100000|1060.810000|0.63|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-10T22:14:59+00:00, last15m_closed_end=2026-11-10T22:15+00:00, prior8high=0.160230, depth_time=2026-11-10T22:15:21+00:00, book20_bid_proxy_usdt=71707, book20_ask_proxy_usdt=32379, funding_indicative=-0.000228, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.50%, turnover=33713665. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T22:15:00+00:00, last15m_closed_end=2026-11-10T22:15+00:00, prior8high=43.460000, depth_time=2026-11-10T22:15:11+00:00, book20_bid_proxy_usdt=754092, book20_ask_proxy_usdt=558976, funding_indicative=-0.000194, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.98%, turnover=14013039. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INIT_USDT: quote_utc=2026-11-10T22:14:59+00:00, last15m_closed_end=2026-11-10T22:15+00:00, prior8high=0.278610, depth_time=2026-11-10T22:15:07+00:00, book20_bid_proxy_usdt=10927, book20_ask_proxy_usdt=8257, funding_indicative=-0.020000, next_funding_utc=2026-11-10T23:00:00+00:00, funding_cycle_h=1, 24h_change=-19.67%, turnover=49967705. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T22:14:59+00:00, last15m_closed_end=2026-11-10T22:15+00:00, prior8high=0.005437, depth_time=2026-11-10T22:15:15+00:00, book20_bid_proxy_usdt=57031, book20_ask_proxy_usdt=50726, funding_indicative=0.000503, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.93%, turnover=19697072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-11-10T22:15:00+00:00, last15m_closed_end=2026-11-10T22:15+00:00, prior8high=0.257600, depth_time=2026-11-10T22:15:14+00:00, book20_bid_proxy_usdt=541413, book20_ask_proxy_usdt=436558, funding_indicative=-0.000044, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.98%, turnover=5486150. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T22:14:59+00:00, last15m_closed_end=2026-11-10T22:15+00:00, prior8high=1.851100, depth_time=2026-11-10T22:15:09+00:00, book20_bid_proxy_usdt=23935, book20_ask_proxy_usdt=18802, funding_indicative=0.000115, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-9.05%, turnover=5727693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-11-10T22:14:59+00:00, last15m_closed_end=2026-11-10T22:15+00:00, prior8high=51.720000, depth_time=2026-11-10T22:15:28+00:00, book20_bid_proxy_usdt=20973678, book20_ask_proxy_usdt=17883815, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.05%, turnover=267900692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T22:14:59+00:00, last15m_closed_end=2026-11-10T22:15+00:00, prior8high=6.774000, depth_time=2026-11-10T22:15:17+00:00, book20_bid_proxy_usdt=3033291, book20_ask_proxy_usdt=2448237, funding_indicative=-0.000023, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.98%, turnover=30575864. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-11-10T22:14:59+00:00, last15m_closed_end=2026-11-10T22:15+00:00, prior8high=4026.090000, depth_time=2026-11-10T22:15:27+00:00, book20_bid_proxy_usdt=161730, book20_ask_proxy_usdt=190905, funding_indicative=0.000079, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.11%, turnover=113350721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-11-10T22:14:59+00:00, last15m_closed_end=2026-11-10T22:15+00:00, prior8high=4043.650000, depth_time=2026-11-10T22:15:24+00:00, book20_bid_proxy_usdt=538341, book20_ask_proxy_usdt=1457231, funding_indicative=0.000094, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.20%, turnover=511094033. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T22:14:59+00:00, last15m_closed_end=2026-11-10T22:15+00:00, prior8high=1069.190000, depth_time=2026-11-10T22:15:13+00:00, book20_bid_proxy_usdt=76737, book20_ask_proxy_usdt=278190, funding_indicative=0.000008, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=2224678259. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
