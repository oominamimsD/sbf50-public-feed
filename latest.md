# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-18T18:00:34Z**
- feed_generated_utc: 2026-10-18T18:00:36+00:00
- source_sha256: `fb707ee61323db013b3c394b5f5d1e054b6b0ed35828817b419a5ebb469cf455`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-18T18:00+00:00, close=81150, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-18T18:00+00:00, close=81150, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-18T16:00+00:00, close=81137.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BAT_USDT|0.171110|-3.98|2.68|-3.99|8712311|0.58|
|BTW_USDT|2.276800|-3.04|35.34|-3.05|25537002|2.19|
|HBAR_USDT|0.084830|-2.82|-9.54|-2.83|41564924|1.18|
|PUMPFUN_USDT|0.004129|-2.54|-28.50|-2.55|29383186|2.42|
|SAND_USDT|0.058830|-2.32|-11.45|-2.33|36072353|1.70|
|AGT_USDT|0.067910|-1.87|283.99|-1.88|10548385|0.88|
|STRK_USDT|0.059730|-1.79|-49.92|-1.80|14932941|1.67|
|XPL_USDT|0.075560|-1.78|-15.33|-1.79|6420120|1.32|
|LTC_USDT|57.970000|-1.46|-10.12|-1.47|9342841|3.45|
|DASH_USDT|47.560000|-1.16|-9.39|-1.17|6643340|2.10|
|WLD_USDT|0.472200|-1.15|-18.47|-1.16|70472953|2.12|
|TRUMPOFFICIAL_USDT|1.680000|-1.00|-12.40|-1.01|5649197|5.95|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.067910|0.065920|0.067910|0.44|N|Y/Y|N/N|Y|N|
|BAT_USDT|0.171110|0.170390|0.171110|0.23|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|2.276800|2.184900|2.276800|1.35|N|Y/Y|N/N|Y|N|
|DASH_USDT|47.560000|47.560000|47.560000|0.90|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.084830|0.084290|0.084830|1.16|N|Y/Y|N/N|Y|N|
|LTC_USDT|57.970000|57.920000|57.970000|1.69|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004129|0.004107|0.004129|1.33|N|Y/Y|Y/Y|Y|N|
|SAND_USDT|0.058830|0.058120|0.058830|0.32|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.059730|0.059590|0.059730|0.80|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.680000|1.675000|1.680000|0.27|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.472200|0.472800|0.472200|0.74|N|Y/Y|Y/Y|Y|N|
|XPL_USDT|0.075560|0.075290|0.075560|0.97|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-18T18:00:00+00:00, last15m_closed_end=2026-10-18T18:00+00:00, prior8high=0.070296, depth_time=2026-10-18T18:00:19+00:00, book20_bid_proxy_usdt=3265, book20_ask_proxy_usdt=1469, funding_indicative=0.000296, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.87%, turnover=10548385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-18T18:00:00+00:00, last15m_closed_end=2026-10-18T18:00+00:00, prior8high=0.177360, depth_time=2026-10-18T18:00:08+00:00, book20_bid_proxy_usdt=24289, book20_ask_proxy_usdt=24426, funding_indicative=0.000007, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.98%, turnover=8712311. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-18T18:00:00+00:00, last15m_closed_end=2026-10-18T18:00+00:00, prior8high=2.354400, depth_time=2026-10-18T18:00:09+00:00, book20_bid_proxy_usdt=10250, book20_ask_proxy_usdt=8892, funding_indicative=-0.000516, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=25537002. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-18T18:00:00+00:00, last15m_closed_end=2026-10-18T18:00+00:00, prior8high=48.170000, depth_time=2026-10-18T18:00:27+00:00, book20_bid_proxy_usdt=796680, book20_ask_proxy_usdt=916046, funding_indicative=0.000029, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.16%, turnover=6643340. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-18T18:00:00+00:00, last15m_closed_end=2026-10-18T18:00+00:00, prior8high=0.086580, depth_time=2026-10-18T18:00:12+00:00, book20_bid_proxy_usdt=497284, book20_ask_proxy_usdt=1007505, funding_indicative=0.000021, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=41564924. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-18T18:00:00+00:00, last15m_closed_end=2026-10-18T18:00+00:00, prior8high=58.430000, depth_time=2026-10-18T18:00:25+00:00, book20_bid_proxy_usdt=1189761, book20_ask_proxy_usdt=1405425, funding_indicative=0.000077, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.46%, turnover=9342841. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-18T18:00:00+00:00, last15m_closed_end=2026-10-18T18:00+00:00, prior8high=0.004208, depth_time=2026-10-18T18:00:14+00:00, book20_bid_proxy_usdt=1388160, book20_ask_proxy_usdt=2852580, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.54%, turnover=29383186. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-18T18:00:00+00:00, last15m_closed_end=2026-10-18T18:00+00:00, prior8high=0.059280, depth_time=2026-10-18T18:00:17+00:00, book20_bid_proxy_usdt=828796, book20_ask_proxy_usdt=601255, funding_indicative=-0.003641, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=36072353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-18T18:00:00+00:00, last15m_closed_end=2026-10-18T18:00+00:00, prior8high=0.062250, depth_time=2026-10-18T18:00:21+00:00, book20_bid_proxy_usdt=479033, book20_ask_proxy_usdt=444766, funding_indicative=0.000050, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.79%, turnover=14932941. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-18T18:00:00+00:00, last15m_closed_end=2026-10-18T18:00+00:00, prior8high=1.694000, depth_time=2026-10-18T18:00:32+00:00, book20_bid_proxy_usdt=1550364, book20_ask_proxy_usdt=1168417, funding_indicative=-0.000084, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.00%, turnover=5649197. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-18T18:00:00+00:00, last15m_closed_end=2026-10-18T18:00+00:00, prior8high=0.480000, depth_time=2026-10-18T18:00:31+00:00, book20_bid_proxy_usdt=2196876, book20_ask_proxy_usdt=1937607, funding_indicative=-0.000184, next_funding_utc=2026-10-19T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.15%, turnover=70472953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-10-18T18:00:00+00:00, last15m_closed_end=2026-10-18T18:00+00:00, prior8high=0.076170, depth_time=2026-10-18T18:00:24+00:00, book20_bid_proxy_usdt=421269, book20_ask_proxy_usdt=566430, funding_indicative=-0.000008, next_funding_utc=2026-10-18T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.78%, turnover=6420120. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
