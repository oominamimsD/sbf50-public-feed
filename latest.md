# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T08:00:31Z**
- feed_generated_utc: 2026-10-20T08:00:34+00:00
- source_sha256: `6ec0fbfb22d4849365a74eb55681579037473aa9b39a92b2c6cc4077f8fc690a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1196; contracts: 1188; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T08:00+00:00, close=81519.9, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.661500|-5.16|-5.37|-4.25|30431874|6.02|
|SAND_USDT|0.056750|-4.71|-8.60|-3.80|7091241|1.76|
|Q_USDT|0.119394|-3.41|287.75|-2.50|6639471|0.50|
|NEAR_USDT|4.780000|-3.00|-13.85|-2.09|161961760|2.09|
|QNT_USDT|191.790000|-2.90|-16.02|-1.99|79751400|0.52|
|ARB_USDT|0.193090|-2.32|2.45|-1.41|93632492|0.52|
|AVAX_USDT|9.474000|-2.20|-11.30|-1.29|137071197|1.05|
|UNI_USDT|7.180000|-2.17|-3.20|-1.26|9749643|1.39|
|STRK_USDT|0.056020|-2.11|-38.21|-1.20|19459131|1.79|
|TAO_USDT|264.420000|-2.08|-7.63|-1.17|55017701|1.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.193090|0.192360|0.193090|1.01|N|Y/Y|N/N|Y|N|
|AVAX_USDT|9.474000|9.473000|9.474000|0.87|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.661500|1.656400|1.665500|1.21|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.780000|4.749000|4.780000|0.45|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.790000|191.100000|191.790000|0.86|N|Y/Y|Y/Y|Y|N|
|Q_USDT|0.119394|0.110142|0.119394|0.27|N|Y/Y|N/N|Y|N|
|SAND_USDT|0.056750|0.056700|0.056760|8.64|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.056020|0.055880|0.056020|1.65|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|264.420000|263.320000|264.420000|2.51|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|7.180000|7.119000|7.180000|2.86|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-10-20T08:00:01+00:00, last15m_closed_end=2026-10-20T08:00+00:00, prior8high=0.200580, depth_time=2026-10-20T08:00:19+00:00, book20_bid_proxy_usdt=44908, book20_ask_proxy_usdt=52220, funding_indicative=-0.000057, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=93632492. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-20T08:00:01+00:00, last15m_closed_end=2026-10-20T08:00+00:00, prior8high=9.600000, depth_time=2026-10-20T08:00:22+00:00, book20_bid_proxy_usdt=847214, book20_ask_proxy_usdt=997383, funding_indicative=0.000011, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=137071197. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-20T08:00:01+00:00, last15m_closed_end=2026-10-20T08:00+00:00, prior8high=1.799100, depth_time=2026-10-20T08:00:09+00:00, book20_bid_proxy_usdt=10286, book20_ask_proxy_usdt=8975, funding_indicative=-0.004577, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.16%, turnover=30431874. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T08:00:01+00:00, last15m_closed_end=2026-10-20T08:00+00:00, prior8high=4.811000, depth_time=2026-10-20T08:00:15+00:00, book20_bid_proxy_usdt=2459404, book20_ask_proxy_usdt=2335912, funding_indicative=-0.000018, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.00%, turnover=161961760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-20T08:00:01+00:00, last15m_closed_end=2026-10-20T08:00+00:00, prior8high=194.330000, depth_time=2026-10-20T08:00:18+00:00, book20_bid_proxy_usdt=115059, book20_ask_proxy_usdt=50343, funding_indicative=0.000030, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.90%, turnover=79751400. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T08:00:01+00:00, last15m_closed_end=2026-10-20T08:00+00:00, prior8high=0.124246, depth_time=2026-10-20T08:00:11+00:00, book20_bid_proxy_usdt=18469, book20_ask_proxy_usdt=14190, funding_indicative=0.000024, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.41%, turnover=6639471. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T08:00:01+00:00, last15m_closed_end=2026-10-20T08:00+00:00, prior8high=0.057320, depth_time=2026-10-20T08:00:09+00:00, book20_bid_proxy_usdt=566972, book20_ask_proxy_usdt=598912, funding_indicative=-0.001365, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.71%, turnover=7091241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-20T08:00:01+00:00, last15m_closed_end=2026-10-20T08:00+00:00, prior8high=0.056910, depth_time=2026-10-20T08:00:24+00:00, book20_bid_proxy_usdt=534505, book20_ask_proxy_usdt=648674, funding_indicative=0.000038, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.11%, turnover=19459131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-20T08:00:01+00:00, last15m_closed_end=2026-10-20T08:00+00:00, prior8high=266.580000, depth_time=2026-10-20T08:00:30+00:00, book20_bid_proxy_usdt=38716, book20_ask_proxy_usdt=104389, funding_indicative=0.000050, next_funding_utc=2026-10-20T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.08%, turnover=55017701. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-20T08:00:01+00:00, last15m_closed_end=2026-10-20T08:00+00:00, prior8high=7.263000, depth_time=2026-10-20T08:00:24+00:00, book20_bid_proxy_usdt=1726397, book20_ask_proxy_usdt=2339675, funding_indicative=0.000045, next_funding_utc=2026-10-20T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=9749643. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
