# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T17:30:24Z**
- feed_generated_utc: 2026-11-08T17:30:25+00:00
- source_sha256: `2811999cf0cbda4940010eed6476f33c0914bf02fe18ccd960e66d0ae783a524`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T17:30+00:00, close=75663.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T17:00+00:00, close=75741.7, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T16:00+00:00, close=76037.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001775|-9.36|52.39|-8.87|19060849|0.56|
|NEAR_USDT|3.598000|-2.78|-16.92|-2.29|30693075|2.78|
|AKE_USDT|0.005234|-2.29|-42.86|-1.80|21007567|1.91|
|PUMPFUN_USDT|0.003655|-2.19|-13.34|-1.70|10427761|2.74|
|ZEC_USDT|1244.610000|-2.05|0.54|-1.56|1382606661|0.08|
|INJ_USDT|7.981000|-1.84|10.97|-1.35|18469809|2.51|
|WLD_USDT|0.320300|-1.71|-19.05|-1.22|24480462|3.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.005234|0.005192|0.005232|0.49|N|Y/Y|N/N|Y|N|
|INJ_USDT|7.981000|7.946000|7.982000|2.48|N|Y/Y|N/N|Y|N|
|NEAR_USDT|3.598000|3.586000|3.598000|0.66|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001775|0.001693|0.001774|0.86|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003655|0.003635|0.003655|0.70|N|Y/N|Y/Y|Y|N|
|WLD_USDT|0.320300|0.320300|0.320300|1.64|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1244.610000|1238.600000|1244.610000|1.26|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-08T17:30:01+00:00, last15m_closed_end=2026-11-08T17:30+00:00, prior8high=0.005442, depth_time=2026-11-08T17:30:11+00:00, book20_bid_proxy_usdt=39074, book20_ask_proxy_usdt=84028, funding_indicative=0.000050, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.29%, turnover=21007567. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-08T17:30:01+00:00, last15m_closed_end=2026-11-08T17:30+00:00, prior8high=8.160000, depth_time=2026-11-08T17:30:19+00:00, book20_bid_proxy_usdt=141172, book20_ask_proxy_usdt=331495, funding_indicative=-0.000061, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.84%, turnover=18469809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T17:30:01+00:00, last15m_closed_end=2026-11-08T17:30+00:00, prior8high=3.715000, depth_time=2026-11-08T17:30:08+00:00, book20_bid_proxy_usdt=4013987, book20_ask_proxy_usdt=5829770, funding_indicative=0.000039, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.78%, turnover=30693075. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T17:30:01+00:00, last15m_closed_end=2026-11-08T17:30+00:00, prior8high=0.001987, depth_time=2026-11-08T17:30:07+00:00, book20_bid_proxy_usdt=9410, book20_ask_proxy_usdt=19253, funding_indicative=-0.001377, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.36%, turnover=19060849. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-08T17:30:01+00:00, last15m_closed_end=2026-11-08T17:30+00:00, prior8high=0.003757, depth_time=2026-11-08T17:30:14+00:00, book20_bid_proxy_usdt=1988494, book20_ask_proxy_usdt=1818590, funding_indicative=0.000009, next_funding_utc=2026-11-08T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.19%, turnover=10427761. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T17:30:01+00:00, last15m_closed_end=2026-11-08T17:30+00:00, prior8high=0.327700, depth_time=2026-11-08T17:30:23+00:00, book20_bid_proxy_usdt=4989908, book20_ask_proxy_usdt=4051811, funding_indicative=-0.000166, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=24480462. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T17:30:01+00:00, last15m_closed_end=2026-11-08T17:30+00:00, prior8high=1275.980000, depth_time=2026-11-08T17:30:17+00:00, book20_bid_proxy_usdt=226147, book20_ask_proxy_usdt=331452, funding_indicative=0.000027, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.05%, turnover=1382606661. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
